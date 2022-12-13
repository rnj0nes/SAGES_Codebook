% Table all variables
<body style="margin: auto; max-width: 48em;">
</body>

## Table: All Variables (SAGES variables metadata)

We have prepared a dataset (distributed as comma delimited CSV) that is formatted as a REDCap codebook and contains variable name, label, value label, and administration information. This data set contains information for every variable in the REDCap data dictionary, and every variable in each of the six data analytic files generated from the REDCap data dictionary.

<https://quantsci.s3.amazonaws.com/Work/SAGES/SAGES_metadata.csv>

This metadata data set could be useful for quickly reviewing:

- How data analytic files variable labels compare to REDCap data dictionary labels (which are question text).
- Identify missing value labels in data analytic files by reviewing value labels in REDCap data dictionary.
- Understanding skip patterns as detailed in the REDCap data dictionary.

We have prepared tools the query this metadata data file for Stata [(click to download qsagesmetadata.ado)](https://www.dropbox.com/s/5yz77eo9e2rj3zx/qsagesmetadata.ado?dl=1) and R [(Click to download NOTFINISHEDYET.R)](#Notfinished), as described below.

**WARNING**: The data analytic files and REDCap data dictionary -- in many cases -- use different variable names. Often the difference is in the first two characters of the variable name. 

---

**`qsagesmetadata`** use example

```
. qsagesmetadata studyid
variablefieldname: studyid
formname: ti_startadl
fieldtype: text
fieldlabel: Study ID
variablefieldname_3_99: udyid


variablefieldname: studyid
formname: SAGES-Delirium-Assessments-Analysis-File.dta
sectionheader: Stata Data Analysis File
fieldtype: text
variablefieldname_3_99: studyid


variablefieldname: studyid
formname: SAGES-Medical-Record-Data-Analysis-File.dta
sectionheader: Stata Data Analysis File
fieldtype: text
variablefieldname_3_99: studyid


variablefieldname: studyid
formname: SAGES-Proxy-Interview-Data-Analysis-File.dta
sectionheader: Stata Data Analysis File
fieldtype: text
fieldlabel: STUDYID. STUDYID
variablefieldname_3_99: studyid


variablefieldname: studyid
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
sectionheader: Stata Data Analysis File
fieldtype: text
variablefieldname_3_99: studyid


variablefieldname: studyid
formname: SAGES-Telephone-Call-Data-Analysis-File.dta
sectionheader: Stata Data Analysis File
fieldtype: text
variablefieldname_3_99: studyid


variablefieldname: studyid
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
sectionheader: Stata Data Analysis File
fieldtype: text
fieldlabel: studyid
variablefieldname_3_99: studyid
```

[Codebook Home](https://quantsci.s3.amazonaws.com/Work/SAGES/SAGES1_Online_Codebook_Files/010_Navigation.html)

---
300_Table_all_variables.md<br>
Rich Jones<br>
12-11-2022<br>



