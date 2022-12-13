% Analytic files
<body style="margin: auto; max-width: 96em;">
</body>


## Description of SAGES Data Analytic Files 

SAGES 1 data are collected by a variety of modalities: patient interviews, family member interviews, medical chart review, procedures (MRI, serum sampling). Interview and chart review data are entered into a REDCap data base. SAGES Core C prepares analytic files from the REDCap data and integrates some project-specific data (e.g., MRI data, biomarker data) into these data analytic files. The data analytic files are as follows:

|Name of file|Description|Key variables|
|--|--|--|
|SAGES-Subject-Interview-Data-Analysis-File|Contains data from the in-person baseline, and 1,2,6(12)36(12)132+ month follow-up visits|`studyid`<br>`timefr`|
|SAGES-Delirium-Assessments-Analysis-File|Contains delirium assessment data from the index hospitalization|`studyid`<br>`date`|
|SAGES-Telephone-Call-Data-Analysis-File|Contains data from the follow-up telephone calls (month 4, 9, 15, 21, 27)|`studyid`<br>`timefr`|
|SAGES-Proxy-Interview-Data-Analysis-File|Contains data from family member interviews, conducted at baseline and months (6(6)36(12)132+) month follow-up|`studyid`<br>`timefr`|
|SAGES-Medical-Record-Data-Analysis-File|Contains data from the index hospitalization chart review|`studyid`|
|SAGES-Rehospitalization-Data-Analysis-File|Contains medical record review data collected during patient follow-up|`studyid`<br>`redcap_event_name`|

Note: the **Key variables** are variables needed to uniquely identify the records in the data set. `studyid` and `timefr` will match (as appropriate) across data sets. 


Data files are distributed in Stata (.dta) format and SAS format (.sas7bdat).

### N = 560
Additionally, a file exists `n560.dta` (and `n560.csv`) that contains only the variable `studyid`, but can be used to easily restrict analyses to the 560 SAGES surgical participants who were dementia free at baseline. Most of our papers using SAGES data use the N=560 sample. 

### A note on `studyid`

`studyid` is the study identifier number for participants. These are alphanumeric values. The first two columns indicate the source of the participant (BIDMC, BWH, and the non-surgical comparison group [outpatient at BIDMC]) with the following two letter codes: SD, SW, and ND. The remainder portion of the studyid are exactly 6 numerals and reflect the order in which the patient was screened. The total width of the `studyid` field is 8.

Many of the data files include participants from the non-surgical comparison group. Analysts may want to exclude them, and can do so by referring to the first column of the `studyid` variable.

[Codebook Home](https://quantsci.s3.amazonaws.com/Work/SAGES/SAGES1_Online_Codebook_Files/010_Navigation.html)

---
050_Analytic_files.md<br>
Rich Jones<br>
2022-12-10<br>


