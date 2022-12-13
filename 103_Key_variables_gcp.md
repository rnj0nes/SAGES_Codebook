% Key variables GCP
<body style="margin: auto; max-width: 48em;">
</body>

### Global Cognitive Performance 

The GCP (Global Cognitive Performance) outcome is a composite of several neuropsychological tests administered to participants at selected visits (notably excluding telephone follow-up). The construction of this outcome variable has been described in two published papers (Jones et al, 2010; Gross et al 2014). 

The SAGES data sets include several different versions of the GCP. **We recommend the variable `vdgcp_rta` as the outcome variable of choice for most analyses.** The `vd` refers to the fact that this is a VDS variable and there is an associated variable documentation sheet available, the `gcp` indicates the outcome coded, and `_rta` indicates a particular version of the GCP that is corrected for practice or retest effects as observed in the non-surgical comparison group. This variable can be found in the `SAGES-Subject-Interview-Data-Analysis-File` data analysis file and is theoretically unbounded but will have a mean around 57 and standard deviation around 7. 

There are three versions of the GCP users might encounter

|Variable name|Description|Mean|SD|Min|Max|N|
|--|--|--|--|--|--|--|
|`vdgcp`|General Cognitive Performance [GCP], externally scaled |57|7|34|77|566|
|`vdgcp_rta`|General Cognitive Performance [GCP], externally scaled and retest corrected |57|7|34|77|566|
|`vdsgcp`|General Cognitive Performance [GCP], INTERNALLY scaled |50|10|18|78|566|
|`vdsgcp_rta`|General Cognitive Performance [GCP], INTERNALLY scaled and retest corrected |50|10|18|78|566|

The difference between `vdgcp` and `vdsgcp` is that the `s` version is standardized to the mean and standard deviation of the SAGES sample at baseline (albeit the N=566 SAGES sample), and the non-`s` version is standardized to the mean and standard deviation of a national sample of community-dwelling older adults aged 70+ (the Aging Demographics and Memory Study, and Health and Retirement Study sub-study). This procedure is described in Gross et al (2014). 




#### References, GCP

Gross, A. L., Jones, R. N., Fong, T. G., Tommet, D., & Inouye, S. K. (2014). Calibration and validation of an innovative approach for estimating general cognitive performance. Neuroepidemiology, 42(3), 144-153. https://doi.org/10.1159/000357647 

Jones, R. N., Rudolph, J. L., Inouye, S. K., Yang, F. M., Fong, T. G., Milberg, W. P., Tommet, D., Metzger, E. D., Cupples, L. A., & Marcantonio, E. R. (2010). Development of a unidimensional composite measure of neuropsychological functioning in older cardiac surgery patients with good measurement precision. Journal of Clinical and Experimental Neuropsychology, 32(10), 1041-1049. https://doi.org/10.1080/13803391003662728 

---
103_Key_variables_gcp.md<br>
Rich Jones<br>
2022-12-11<br>

