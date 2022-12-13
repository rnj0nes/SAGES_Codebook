% All VDS variables
<body style="margin: auto; max-width: 48em;">
</body>

### All Variable Definition Sheet (VDS) variables

In conducting a data analysis using the SAGES data we need to generate analytic variables from the collected data. Our operating rule has been to generate VDSs for any created variable that we anticipate needing in more than one data analysis project. As of 10 Dec 2022, we have defined about 300 VDS variables for the SAGES data. We are constantly adding to our collection of VDSs. 

In this section, I provide tables that list the VDSs that have been generated, the analytic data file in which they are distributed, and a short variable description (variable label). VDSs that are considered important are listed first and bolded.

**Hyperlinks to subtables**:<a name="vdstoc" /><br>

[Delirium-related VDSs](#delirium)<br>
[Cognition-related VDSs](#cognition)<br>
[Neuropsychological test performance and derived variables VDSs](#npb)<br>
[Functional descriptors and outcomes VDSs](#function)<br>
[Clinical descriptors and outcomes VDSs](#clinical)<br>
[Activity & frailty components, descriptors,  and outcomes VDSs](#frailty)<br>
[Sociodemographic and socio-economic VDSs](#socio)<br>
[Health Behaviors VDSs](#health-behaviors)<br>
[Health-related quality of life components, descriptors, and outcomes VDSs](#hrqol)<br>
[Biomarkers (Project 2)](#biomarkers)<br>
[Brain MRI VDSs](#mri)<br>
[Brain reserve project related VDSs](#reserve)<br>
[Uncertain use or meaning](#uncertain)


#### Delirium-related VDSs <a name="delirium" />

|Variable|Form|Description|
|--|--|--|
|**vdsagesdeliriumever**|**SAGES-Delirium-Assessments-Analysis-File.dta**|**Ever Delirious in Hospital by Interview OR Chart**|
|**vdcamseverity_sum**|**SAGES-Subject-Interview-Data-Analysis-File.dta**|**Sum of all CAM-S Scores**|
|**vdcamseverity_peak**|**SAGES-Subject-Interview-Data-Analysis-File.dta**|**Peak CAM-S**|
|vdcamdelirium|SAGES-Delirium-Assessments-Analysis-File.dta|CAM Delirium|
|vdcamdelirium|SAGES-Subject-Interview-Data-Analysis-File.dta|CAM Delirium|
|vdcamicudelirium|SAGES-Delirium-Assessments-Analysis-File.dta|Delirium by CAM-ICU|
|vdcamnegativeclass|SAGES-Delirium-Assessments-Analysis-File.dta|CAM delirium negative subtype|
|vdcamnegativeclass|SAGES-Subject-Interview-Data-Analysis-File.dta|CAM delirium negative subtype|
|vdcampositiveclass|SAGES-Delirium-Assessments-Analysis-File.dta|CAM delirium positive subtype|
|vdcampositiveclass|SAGES-Subject-Interview-Data-Analysis-File.dta|CAM delirium positive subtype|
|vdcamseverity_peak|SAGES-Delirium-Assessments-Analysis-File.dta|Peak CAM-S|
|vdcamseverity_sum|SAGES-Delirium-Assessments-Analysis-File.dta|Sum of all CAM-S Scores|
|vdcamseveritylf|SAGES-Delirium-Assessments-Analysis-File.dta|CAM Severity Score (Long form)|
|vdcamseveritylf|SAGES-Subject-Interview-Data-Analysis-File.dta|CAM Severity Score (Long form)|
|vdcamseveritysf|SAGES-Delirium-Assessments-Analysis-File.dta|CAM Severity Score (Short form)|
|vdcamseveritysf|SAGES-Subject-Interview-Data-Analysis-File.dta|CAM Severity Score (Short form)|
|vdcamsubsyndromal|SAGES-Delirium-Assessments-Analysis-File.dta|Subsyndromal CAM Delirium|
|vdcamsubsyndromal|SAGES-Subject-Interview-Data-Analysis-File.dta|Subsyndromal CAM Delirium|
|vdcamsubsyndromal|SAGES-Telephone-Call-Data-Analysis-File.dta|Subsyndromal CAM Delirium|
|vdcamsubsyndromalever|SAGES-Delirium-Assessments-Analysis-File.dta|Subsyndromal CAM Delirium - Ever|
|vdcamsubsyndromalever|SAGES-Subject-Interview-Data-Analysis-File.dta|Subsyndromal CAM Delirium - Ever|
|vdcamsubsyndromalever|SAGES-Telephone-Call-Data-Analysis-File.dta|Subsyndromal CAM Delirium - Ever|
|vdcamsubtype|SAGES-Delirium-Assessments-Analysis-File.dta|CAM delirium subtype (positive, negative symptoms)|
|vdchartdelirium|SAGES-Medical-Record-Data-Analysis-File.dta|Delirium by Chart|
|vdcomadelirium|SAGES-Delirium-Assessments-Analysis-File.dta|Delirium-Stupor or Coma, defined by RASS, CAM-LOC, or Interviewer Procedure Code|
|vdcomadelirium|SAGES-Subject-Interview-Data-Analysis-File.dta|Delirium-Stupor or Coma, defined by RASS, CAM-LOC, or Interviewer Procedure Code|
|vdcomadelirium|SAGES-Telephone-Call-Data-Analysis-File.dta|Delirium-Stupor or Coma, defined by RASS, CAM-LOC, or Interviewer Procedure Code|
|vdhidelirium_days|SAGES-Delirium-Assessments-Analysis-File.dta|Duration of Delirium by Interview Episodes|
|vdhidelirium|SAGES-Delirium-Assessments-Analysis-File.dta|Delirium by Interview (CAM, CAM-ICU or RASS (if available), Noted Stupor/Coma)|
|vdhidelirium|SAGES-Subject-Interview-Data-Analysis-File.dta|Delirium by Interview (CAM, CAM-ICU or RASS (if available), Noted Stupor/Coma)|
|vdhidelirium|SAGES-Telephone-Call-Data-Analysis-File.dta|Delirium by Interview (CAM, CAM-ICU or RASS (if available), Noted Stupor/Coma)|
|vdhideliriumever|SAGES-Delirium-Assessments-Analysis-File.dta|Ever Delirious in Hospital by Interview|
|vdmdas|SAGES-Delirium-Assessments-Analysis-File.dta|MDAS Score|
|vdmdas|SAGES-Subject-Interview-Data-Analysis-File.dta|MDAS Score|
|vdscog16|SAGES-Subject-Interview-Data-Analysis-File.dta|SCOG: 16-Item|
|vdscog18|SAGES-Subject-Interview-Data-Analysis-File.dta|SCOG: 18-Item|

[back to VDS table of contents](#vdstoc)


#### Cognition-related VDSs <a name="cognition" />

|Variable|Form|Description|
|--|--|--|
|**vd3ms**|**SAGES-Subject-Interview-Data-Analysis-File.dta**|**3MS Score**|
|vd3ms_iflag|SAGES-Subject-Interview-Data-Analysis-File.dta|Imputation flag for 3MS Score|
|vdiqc|SAGES-Subject-Interview-Data-Analysis-File.dta|IQCODE, Self Report|
|vdmmse|SAGES-Subject-Interview-Data-Analysis-File.dta|MMSE Score- Derived from 3MS|
|vdscog_db01|SAGES-Delirium-Assessments-Analysis-File.dta|Scog Digits Backward Correct Response 742|
|vdscog_db01|SAGES-Subject-Interview-Data-Analysis-File.dta|Scog Digits Backward Correct Response 742|
|vdscog_db01|SAGES-Telephone-Call-Data-Analysis-File.dta|Scog Digits Backward Correct Response 742|
|vdscog_db02|SAGES-Delirium-Assessments-Analysis-File.dta|Scog Digits Backward Correct Response 5384|
|vdscog_db02|SAGES-Subject-Interview-Data-Analysis-File.dta|Scog Digits Backward Correct Response 5384|
|vdscog_db02|SAGES-Telephone-Call-Data-Analysis-File.dta|Scog Digits Backward Correct Response 5384|
|vdscog_df01|SAGES-Delirium-Assessments-Analysis-File.dta|Scog Digits Forward Correct Response 291|
|vdscog_df01|SAGES-Subject-Interview-Data-Analysis-File.dta|Scog Digits Forward Correct Response 291|
|vdscog_df01|SAGES-Telephone-Call-Data-Analysis-File.dta|Scog Digits Forward Correct Response 291|
|vdscog_df02|SAGES-Delirium-Assessments-Analysis-File.dta|Scog Digits Forward Correct Response 3574|
|vdscog_df02|SAGES-Subject-Interview-Data-Analysis-File.dta|Scog Digits Forward Correct Response 3574|
|vdscog_df02|SAGES-Telephone-Call-Data-Analysis-File.dta|Scog Digits Forward Correct Response 3574|
|vdscog_df03|SAGES-Delirium-Assessments-Analysis-File.dta|Scog Digits Forward Correct Response 61927|
|vdscog_df03|SAGES-Subject-Interview-Data-Analysis-File.dta|Scog Digits Forward Correct Response 61927|
|vdscog_df03|SAGES-Telephone-Call-Data-Analysis-File.dta|Scog Digits Forward Correct Response 61927|
|vdscog_rec01|SAGES-Delirium-Assessments-Analysis-File.dta|Scog Recall Correct Response Car|
|vdscog_rec01|SAGES-Subject-Interview-Data-Analysis-File.dta|Scog Recall Correct Response Car|
|vdscog_rec01|SAGES-Telephone-Call-Data-Analysis-File.dta|Scog Recall Correct Response Car|
|vdscog_rec02|SAGES-Delirium-Assessments-Analysis-File.dta|Scog Recall Correct Response Mountain|
|vdscog_rec02|SAGES-Subject-Interview-Data-Analysis-File.dta|Scog Recall Correct Response Mountain|
|vdscog_rec02|SAGES-Telephone-Call-Data-Analysis-File.dta|Scog Recall Correct Response Mountain|
|vdscog_rec03|SAGES-Delirium-Assessments-Analysis-File.dta|Scog Recall Correct Response Window|
|vdscog_rec03|SAGES-Subject-Interview-Data-Analysis-File.dta|Scog Recall Correct Response Window|
|vdscog_rec03|SAGES-Telephone-Call-Data-Analysis-File.dta|Scog Recall Correct Response Window|
|vdscog_reg01|SAGES-Delirium-Assessments-Analysis-File.dta|Scog Registration Correct Response Car|
|vdscog_reg01|SAGES-Subject-Interview-Data-Analysis-File.dta|Scog Registration Correct Response Car|
|vdscog_reg01|SAGES-Telephone-Call-Data-Analysis-File.dta|Scog Registration Correct Response Car|
|vdscog_reg02|SAGES-Delirium-Assessments-Analysis-File.dta|Scog Registration Correct Response Mountain|
|vdscog_reg02|SAGES-Subject-Interview-Data-Analysis-File.dta|Scog Registration Correct Response Mountain|
|vdscog_reg02|SAGES-Telephone-Call-Data-Analysis-File.dta|Scog Registration Correct Response Mountain|
|vdscog_reg03|SAGES-Delirium-Assessments-Analysis-File.dta|Scog Registration Correct Response Window|
|vdscog_reg03|SAGES-Subject-Interview-Data-Analysis-File.dta|Scog Registration Correct Response Window|
|vdscog_reg03|SAGES-Telephone-Call-Data-Analysis-File.dta|Scog Registration Correct Response Window|
|vdscog16_baseline|SAGES-Subject-Interview-Data-Analysis-File.dta|Baseline SCOG Score (16 Point)- Derived from 3MS|
|vdscog16|SAGES-Delirium-Assessments-Analysis-File.dta|SCOG: 16-Item|
|vdscog16|SAGES-Telephone-Call-Data-Analysis-File.dta|SCOG: 16-Item|
|vdscog18|SAGES-Delirium-Assessments-Analysis-File.dta|SCOG: 18-Item|
|vdscog18|SAGES-Telephone-Call-Data-Analysis-File.dta|SCOG: 18-Item|

[back to VDS table of contents](#vdstoc)


#### Neuropsychological test performance and derived variables VDSs <a name="npb" />

|Variable|Form|Description|
|--|--|--|
|**vdgcp_rta**|**SAGES-Subject-Interview-Data-Analysis-File.dta**|**GCP, externally scaled, corrected for retest effect**|
|**vdgcp_slope48**|**SAGES-Subject-Interview-Data-Analysis-File.dta**|**Estimated slope, 2-48 months**|
|**vdgcp_slope36m**|**SAGES-Subject-Interview-Data-Analysis-File.dta**|**Estimated instantaneous slope, 36 months**|
|**vdgcp_change36m**|**SAGES-Subject-Interview-Data-Analysis-File.dta**|**Estimated change from baseline, 36 months**|
|vdawords|SAGES-Subject-Interview-Data-Analysis-File.dta|FAS fluency - A words|
|vdbnttot_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|Boston Naming Test total flag|
|vdbnttot_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|Boston Namimg Test total percentile rank|
|vdbnttot_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|Boston Naming Test, corrected for retest effect|
|vdbnttot_z|SAGES-Subject-Interview-Data-Analysis-File.dta|Boston Naming Test total z-score|
|vdbnttot|SAGES-Subject-Interview-Data-Analysis-File.dta|Boston Naming Test - Total|
|vdcat_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|Category fluency flag|
|vdcat_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|Category fluency percentile rank|
|vdcat_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|Category fluency, corrected for retest effect|
|vdcat_z|SAGES-Subject-Interview-Data-Analysis-File.dta|Category fluency z-score|
|vdcat|SAGES-Subject-Interview-Data-Analysis-File.dta|Category fluency|
|vdcola|SAGES-Subject-Interview-Data-Analysis-File.dta|Boston Naming Test - Col A|
|vdcolb|SAGES-Subject-Interview-Data-Analysis-File.dta|Boston Naming Test - Col B|
|vdcowat_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|COWAT flag|
|vdcowat_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|COWAT percentile rank|
|vdcowat_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|COWAT, corrected for retest effect|
|vdcowat_z|SAGES-Subject-Interview-Data-Analysis-File.dta|COWAT z-score|
|vdcowat|SAGES-Subject-Interview-Data-Analysis-File.dta|FAS fluency - Total words|
|vddsb_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span backwards flag|
|vddsb_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span backwards percentile rank|
|vddsb_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span backward, corrected for retest effect|
|vddsb_s|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit Span - Backward (Longest span)|
|vddsb_sscore|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span backwards standard score|
|vddsb_z|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span backwards z score|
|vddsb|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit Span - Backward|
|vddsf_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span forward flag|
|vddsf_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span forward percentile rank|
|vddsf_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span forward, corrected for retest effect|
|vddsf_s|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit Span - Forward (Longest span)|
|vddsf_sscore|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span forward standard score|
|vddsf_z|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span forward z score|
|vddsf|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit Span - Forward|
|vddstotal_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span total flag|
|vddstotal_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span total percentile rank|
|vddstotal_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span total, corrected for retest effect|
|vddstotal_sscore|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span total standard score|
|vddstotal_z|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit span total z score|
|vddstotal|SAGES-Subject-Interview-Data-Analysis-File.dta|Digit Span - Total|
|vdfwords|SAGES-Subject-Interview-Data-Analysis-File.dta|FAS fluency - F words|
|vdgcp_se|SAGES-Subject-Interview-Data-Analysis-File.dta|Standard Error of Measurement of GCP, externally scaled|
|vdgcp|SAGES-Subject-Interview-Data-Analysis-File.dta|General Cognitive Performance [GCP], externally scaled|
|vdhvdel_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT delayed recall flag|
|vdhvdel_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT delayed recall percentile rank|
|vdhvdel_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT delayed recall, corrected for retest effect|
|vdhvdel_tscore|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT delayed recall t-score|
|vdhvdel_zscore|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT delayed recall z-score|
|vdhvdel|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLTR - delayed recall|
|vdhvdelquot|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLTR - delayed recall percent|
|vdhvlt_dis_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT discrimination flag|
|vdhvlt_dis_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT discrimination percentile rank|
|vdhvlt_dis_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT discrimination trial, corrected for retest effect|
|vdhvlt_dis_tscore|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT discrimination t score|
|vdhvlt_dis_zscore|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT discrimination z-score|
|vdhvlt_dis|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLTR - discrimination|
|vdhvlt_fc_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT forced choice, corrected for retest effect|
|vdhvlt_fc|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLTR - forced choice|
|vdhvlt_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT learning flag|
|vdhvlt_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT learning percentile rank|
|vdhvlt_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT sum of learning, corrected for retest effect|
|vdhvlt_tscore|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT learning t-score|
|vdhvlt_zscore|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT learning z-score|
|vdhvlt|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLTR - total score|
|vdhvlt1|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLTR - trial 1|
|vdhvlt2|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLTR - trial 2|
|vdhvlt3|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLTR - trial 3|
|vdhvltretp_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT retention percent flag|
|vdhvltretp_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT retention percent percentile rank|
|vdhvltretp_tscore|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT retention percent t score|
|vdhvltretp_zcore|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLT retention percent z-score|
|vdhvltretp|SAGES-Subject-Interview-Data-Analysis-File.dta|HVLTR Retention Pergentage|
|vdrbans_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|RBANS flag|
|vdrbans_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|RBANS percentile rank|
|vdrbans_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|RBANS, corrected for retest effect|
|vdrbans_z|SAGES-Subject-Interview-Data-Analysis-File.dta|RBANS z score|
|vdrbans|SAGES-Subject-Interview-Data-Analysis-File.dta|RBANS Digit Symbol Substitution|
|vdsgcp_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|GCP, internally scaled, corrected for retest effect|
|vdsgcp_se|SAGES-Subject-Interview-Data-Analysis-File.dta|Standard Error of Measurement of GCP, internally scaled|
|vdsgcp|SAGES-Subject-Interview-Data-Analysis-File.dta|General Cognitive Performance [GCP], internally scaled|
|vdswords|SAGES-Subject-Interview-Data-Analysis-File.dta|FAS fluency - S words|
|vdtraila_err|SAGES-Subject-Interview-Data-Analysis-File.dta|Trail A (errors)|
|vdtraila_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|Trails A flag|
|vdtraila_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|Trails A percentile rank|
|vdtraila_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|Trails A time, corrected for retest effect|
|vdtraila|SAGES-Subject-Interview-Data-Analysis-File.dta|Trail A (sec)|
|vdtrailb_err|SAGES-Subject-Interview-Data-Analysis-File.dta|Trail B (errors)|
|vdtrailb_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|Trails B flag|
|vdtrailb_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|Trails B percentile rank|
|vdtrailb_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|Trails B time, corrected for retest effect|
|vdtrailb|SAGES-Subject-Interview-Data-Analysis-File.dta|Trail B (sec)|
|vdvsat_flag|SAGES-Subject-Interview-Data-Analysis-File.dta|VSAT flag|
|vdvsat_prank|SAGES-Subject-Interview-Data-Analysis-File.dta|VSAT percentile rank|
|vdvsat_rta|SAGES-Subject-Interview-Data-Analysis-File.dta|VSAT, corrected for retest effect|
|vdvsat_z|SAGES-Subject-Interview-Data-Analysis-File.dta|VSAT z score|
|vdvsat|SAGES-Subject-Interview-Data-Analysis-File.dta|VSAT|

[back to VDS table of contents](#vdstoc)


#### Functional descriptors and outcomes VDSs <a name="function" />

|Variable|Form|Description|
|--|--|--|
|**vdfxncomp**|**SAGES-Subject-Interview-Data-Analysis-File.dta**|**Physical function composite, PROMIS-scaled**|
|vdadlany|SAGES-Proxy-Interview-Data-Analysis-File.dta|Any ADL impairment|
|vdadlany|SAGES-Subject-Interview-Data-Analysis-File.dta|Any ADL impairment|
|vdadlany|SAGES-Telephone-Call-Data-Analysis-File.dta|Any ADL impairment|
|vdadldif|SAGES-Proxy-Interview-Data-Analysis-File.dta|ADL difficulties and dependency [0-21] (higher worse)|
|vdadldif|SAGES-Subject-Interview-Data-Analysis-File.dta|ADL difficulties and dependency [0-21] (higher worse)|
|vdadldif|SAGES-Telephone-Call-Data-Analysis-File.dta|ADL difficulties and dependency [0-21] (higher worse)|
|vdadlt|SAGES-Proxy-Interview-Data-Analysis-File.dta|ADL dependency [0-14] (higher worse)|
|vdadlt|SAGES-Subject-Interview-Data-Analysis-File.dta|ADL dependency [0-14] (higher worse)|
|vdadlt|SAGES-Telephone-Call-Data-Analysis-File.dta|ADL dependency [0-14] (higher worse)|
|vdcamdelirium|SAGES-Telephone-Call-Data-Analysis-File.dta|CAM Delirium|
|vdcamf|SAGES-Proxy-Interview-Data-Analysis-File.dta|FAM-CAM (Confusion Assessment Method for Proxies)|
|vdcamseveritysf|SAGES-Telephone-Call-Data-Analysis-File.dta|CAM Severity Score (Short form)|
|vdiadlany|SAGES-Proxy-Interview-Data-Analysis-File.dta|Any IADL impairment|
|vdiadlany|SAGES-Subject-Interview-Data-Analysis-File.dta|Any IADL impairment|
|vdiadlany|SAGES-Telephone-Call-Data-Analysis-File.dta|Any IADL impairment|
|vdiadlanyc|SAGES-Proxy-Interview-Data-Analysis-File.dta|Any cognitive IADL impairment|
|vdiadlanyc|SAGES-Subject-Interview-Data-Analysis-File.dta|Any cognitive IADL impairment|
|vdiadlanyc|SAGES-Telephone-Call-Data-Analysis-File.dta|Any cognitive IADL impairment|
|vdiadlt|SAGES-Proxy-Interview-Data-Analysis-File.dta|Total IADL impairment (higher values are more impaired)|
|vdiadlt|SAGES-Subject-Interview-Data-Analysis-File.dta|Total IADL impairment (higher values are more impaired)|
|vdiadlt|SAGES-Telephone-Call-Data-Analysis-File.dta|Total IADL impairment (higher values are more impaired)|
|vdiadltc|SAGES-Proxy-Interview-Data-Analysis-File.dta|Total cognitive IADL impairment (higher values are more impaired)|
|vdiadltc|SAGES-Subject-Interview-Data-Analysis-File.dta|Total cognitive IADL impairment (higher values are more impaired)|
|vdiadltc|SAGES-Telephone-Call-Data-Analysis-File.dta|Total cognitive IADL impairment (higher values are more impaired)|
|vdiqc|SAGES-Proxy-Interview-Data-Analysis-File.dta|IQCODE, Proxy Report|

[back to VDS table of contents](#vdstoc)


#### Clinical descriptors and outcomes VDSs <a name="clinical" />

|Variable|Form|Description|
|--|--|--|
|vdanesth|SAGES-Medical-Record-Data-Analysis-File.dta|Anesthesia type|
|vdapache_aps|SAGES-Medical-Record-Data-Analysis-File.dta|Postoperative Acute Physiology Score (APS)|
|vdapache|SAGES-Medical-Record-Data-Analysis-File.dta|Postoperative APACHE II Score|
|vdbmi1|SAGES-Subject-Interview-Data-Analysis-File.dta|Subject's BMI: Self Reported Weight and Height|
|vdbmi2|SAGES-Subject-Interview-Data-Analysis-File.dta|Subject's BMI: Self Reported Weight, Chart Reported Height|
|vdbmi3|SAGES-Subject-Interview-Data-Analysis-File.dta|Subject's BMI: Chart-Reported Weight/Height (Baseline Only)|
|vdcci_cat|SAGES-Medical-Record-Data-Analysis-File.dta|Charlson Comorbidity Index-Categorized|
|vdcci|SAGES-Medical-Record-Data-Analysis-File.dta|Charlson Comorbidity Index|
|vdctd|SAGES-Medical-Record-Data-Analysis-File.dta|Connective Tissue Disease|
|vddrisk93_1|SAGES-Subject-Interview-Data-Analysis-File.dta|Visual Impairment (over 20/70 after correction) (Inouye '93 Factor 1)|
|vddrisk93_2|SAGES-Subject-Interview-Data-Analysis-File.dta|Cognitive Impairment (MMSE below 24) (Inouye '93 Factor 2)|
|vddrisk93_3|SAGES-Subject-Interview-Data-Analysis-File.dta|Severe Illness (Apache II above 16) (Inouye '93 Factor 3)|
|vddrisk93_4|SAGES-Subject-Interview-Data-Analysis-File.dta|BUN/Creatinine 18+ (Inouye '93 Factor 4)|
|vddriskgroup|SAGES-Subject-Interview-Data-Analysis-File.dta|Delirium Risk Group (from Inouye 1993)|
|vdfacilitydc|SAGES-Medical-Record-Data-Analysis-File.dta|Post-acute Facility Discharge|
|vdgds15|SAGES-Subject-Interview-Data-Analysis-File.dta|Geriatric Depression Scale Score  (/15 Points)|
|vdhearingimp|SAGES-Subject-Interview-Data-Analysis-File.dta|Hearing Impairment|
|vdheight1|SAGES-Subject-Interview-Data-Analysis-File.dta|Subject's Self-Reported Height (cm)|
|vdheight2|SAGES-Subject-Interview-Data-Analysis-File.dta|Subject's Height from Chart (cm), Baseline Only|
|vdiculos|SAGES-Medical-Record-Data-Analysis-File.dta|ICU Length of Stay (days)|
|vdlos|SAGES-Medical-Record-Data-Analysis-File.dta|Total Length of Stay (days)|
|vdmajorcomp|SAGES-Medical-Record-Data-Analysis-File.dta|Total Postoperative Complications|
|vdnh_1m|SAGES-Subject-Interview-Data-Analysis-File.dta|New or Continued Nursing Home Residence|
|vdpod|SAGES-Delirium-Assessments-Analysis-File.dta|Post - operative day|
|vdsurg|SAGES-Subject-Interview-Data-Analysis-File.dta|Surgery Type|
|vdsurglos|SAGES-Medical-Record-Data-Analysis-File.dta|Postoperative Length of Stay (days)|
|vdvascom|SAGES-Medical-Record-Data-Analysis-File.dta|Vascular comorbidity|
|vdweight1|SAGES-Subject-Interview-Data-Analysis-File.dta|Subject's Self-Reported Weight (kg)|
|vdweight2|SAGES-Subject-Interview-Data-Analysis-File.dta|Subject's Weight from Chart (kg), Baseline Only|

[back to VDS table of contents](#vdstoc)


#### Sociodemographic and socio-economic VDSs <a name="socio" />

|Variable|Form|Description|
|--|--|--|
|vdadi|SAGES-Subject-Interview-Data-Analysis-File.dta|Area Deprivation Index, 1 to 100 higher values indicating greater socioeconomic|
|vdage|SAGES-Subject-Interview-Data-Analysis-File.dta|Age at This Visit|
|vdagebaseline|SAGES-Subject-Interview-Data-Analysis-File.dta|Age at Baseline Assessment|
|vdagemri|SAGES-Subject-Interview-Data-Analysis-File.dta|Age at Baseline MRI|
|vdagesurg|SAGES-Subject-Interview-Data-Analysis-File.dta|Age at Index Surgery|
|vdcountry|SAGES-Subject-Interview-Data-Analysis-File.dta|Country of origin|
|vdeduc_f_cat|SAGES-Subject-Interview-Data-Analysis-File.dta|Father's Education, Categorized|
|vdeduc_f_iflag|SAGES-Subject-Interview-Data-Analysis-File.dta|Imputation flag for Father's education|
|vdeduc_f|SAGES-Subject-Interview-Data-Analysis-File.dta|Father's Education, Years|
|vdeduc_m_cat|SAGES-Subject-Interview-Data-Analysis-File.dta|Mother's Education, Categorized|
|vdeduc_m_iflag|SAGES-Subject-Interview-Data-Analysis-File.dta|Imputation flag for Mother's education|
|vdeduc_m|SAGES-Subject-Interview-Data-Analysis-File.dta|Mother's Education, Years|
|vdeduc_r_cat|SAGES-Subject-Interview-Data-Analysis-File.dta|Respondent's Education, Categorized|
|vdeduc_r_iflag|SAGES-Subject-Interview-Data-Analysis-File.dta|Imputation flag for Respondent's education|
|vdeduc_r|SAGES-Subject-Interview-Data-Analysis-File.dta|Respondent's Education, Years|
|vdesl|SAGES-Subject-Interview-Data-Analysis-File.dta|English as a Second Language (ESL)|
|vdfemale|SAGES-Subject-Interview-Data-Analysis-File.dta|Female Sex|
|vdlivesalone|SAGES-Subject-Interview-Data-Analysis-File.dta|Lives Alone|
|vdlivesatnh|SAGES-Subject-Interview-Data-Analysis-File.dta|Lives in a Nursing Home|
|vdmarried|SAGES-Subject-Interview-Data-Analysis-File.dta|Currently Married/Living with Partner|
|vdnonwhite|SAGES-Subject-Interview-Data-Analysis-File.dta|Non-White or Hispanic|


[back to VDS table of contents](#vdstoc)


#### Health Behaviors VDSs <a name="health-behaviors" />

|Variable|Form|Description|
|--|--|--|
|vdalcohol|SAGES-Subject-Interview-Data-Analysis-File.dta|Current Alcohol Consumption (Frequency)|
|vdobesity|SAGES-Subject-Interview-Data-Analysis-File.dta|Obesity (BMI greater than or equal to 30)|
|vdsmokingstatus|SAGES-Subject-Interview-Data-Analysis-File.dta|Subject's Smoking Status|

[back to VDS table of contents](#vdstoc)


#### Brain MRI VDSs <a name="mri" />

|Variable|Form|Description|
|--|--|--|
|vdbpv|SAGES-Subject-Interview-Data-Analysis-File.dta|Brain Parenchymal Volume (BPV)|
|vdicv|SAGES-Subject-Interview-Data-Analysis-File.dta|Intracranial Cavity Volume|
|vdmrilefthippo|SAGES-Subject-Interview-Data-Analysis-File.dta|Left Hippocampal Volume|
|vdmririghthippo|SAGES-Subject-Interview-Data-Analysis-File.dta|Right Hippocampal Volume|
|vdwmh|SAGES-Subject-Interview-Data-Analysis-File.dta|White Matter Hyperintensity Volume|

[back to VDS table of contents](#vdstoc)


#### Biomarkers (Project 2) <a name="biomarkers" />

|Variable|Form|Description|
|--|--|--|
|vdcrp_pod2|SAGES-Subject-Interview-Data-Analysis-File.dta|POD2 CRP|
|vdcrp_preop|SAGES-Subject-Interview-Data-Analysis-File.dta|PREOP CRP|

[back to VDS table of contents](#vdstoc)


#### Activity & frailty components, descriptors,  and outcomes VDSs <a name="frailty" />

|Variable|Form|Description|
|--|--|--|
|**vdfriedfrail_index**|**SAGES-Subject-Interview-Data-Analysis-File.dta**|**Fried Frailty Index (from Fried et. al 2001)**|
|vdfriedfrail_count|SAGES-Subject-Interview-Data-Analysis-File.dta|Count of Triggered Phenotypic Indicators for Frailty (/5)|
|vdfriedfrail1|SAGES-Subject-Interview-Data-Analysis-File.dta|Fried Frailty Indicator: Weight Loss|
|vdfriedfrail2|SAGES-Subject-Interview-Data-Analysis-File.dta|Fried Frailty Indicator: Exhaustion|
|vdfriedfrail3|SAGES-Subject-Interview-Data-Analysis-File.dta|Fried Frailty Indicator: Low Physical Activity|
|vdfriedfrail4|SAGES-Subject-Interview-Data-Analysis-File.dta|Fried Frailty Indicator: Low Grip Strength|
|vdfriedfrail5|SAGES-Subject-Interview-Data-Analysis-File.dta|Fried Frailty Indicator: Low Gait Speed|
|vdgs_max|SAGES-Subject-Interview-Data-Analysis-File.dta|Max Grip Strength (Two Trials)|
|vdgs_mean|SAGES-Subject-Interview-Data-Analysis-File.dta|Mean Grip Strength (Two Trials)|
|vdgs_min|SAGES-Subject-Interview-Data-Analysis-File.dta|Min Grip Strength (Two Trials)|
|vdmlta_kcal|SAGES-Subject-Interview-Data-Analysis-File.dta|Kilocalories expended per week from MLTA|
|vdmlta_metmins|SAGES-Subject-Interview-Data-Analysis-File.dta|Metabolic Equivalent Times (minutes) expended per week from  MLTA|
|vdtw_max|SAGES-Subject-Interview-Data-Analysis-File.dta|Max Timed Walk (Two Trials)|
|vdtw_mean|SAGES-Subject-Interview-Data-Analysis-File.dta|Mean Timed Walk (Two Trials)|
|vdtw_min|SAGES-Subject-Interview-Data-Analysis-File.dta|Min Timed Walk (Two Trials)|

[back to VDS table of contents](#vdstoc)


#### Health-related quality of life components, descriptors, and outcomes VDSs <a name="hrqol" />

|Variable|Form|Description|
|--|--|--|
|**vdsf12pcs**|**SAGES-Subject-Interview-Data-Analysis-File.dta**|**SF12 physical composite T-score**|
|**vdsf12mcs**|**SAGES-Subject-Interview-Data-Analysis-File.dta**|**SF12 mental composite T-score**|
|vdsf12bp|SAGES-Subject-Interview-Data-Analysis-File.dta|SF12 Bodily Pain|
|vdsf12gh|SAGES-Subject-Interview-Data-Analysis-File.dta|SF12 General Health|
|vdsf12mcs_ob|SAGES-Subject-Interview-Data-Analysis-File.dta|SF12 mental composite, oblique rotation|
|vdsf12mh|SAGES-Subject-Interview-Data-Analysis-File.dta|SF12 Mental Health|
|vdsf12pcs_ob|SAGES-Subject-Interview-Data-Analysis-File.dta|SF12 physical composite, oblique rotation|
|vdsf12pf|SAGES-Subject-Interview-Data-Analysis-File.dta|SF12 Physical Functioning|
|vdsf12re|SAGES-Subject-Interview-Data-Analysis-File.dta|SF12 Role Emotional|
|vdsf12rp|SAGES-Subject-Interview-Data-Analysis-File.dta|SF12 Role Physical|
|vdsf12sf|SAGES-Subject-Interview-Data-Analysis-File.dta|SF12 Social Functioning|
|vdsf12vt|SAGES-Subject-Interview-Data-Analysis-File.dta|SF12 Vitality|

[back to VDS table of contents](#vdstoc)


#### Brain reserve project related VDSs <a name="reserve" />
|Variable|Form|Description|
|--|--|--|
|vdcas12|SAGES-Subject-Interview-Data-Analysis-File.dta|Cognitive Activities Scale Score, 12 (T-Scale)|
|vdcas18|SAGES-Subject-Interview-Data-Analysis-File.dta|Cognitive Activities Scale Score, 18 (T-Scale)|
|vdcas40|SAGES-Subject-Interview-Data-Analysis-File.dta|Cognitive Activities Scale Score, 40 (T-Scale)|
|vdcas70|SAGES-Subject-Interview-Data-Analysis-File.dta|Cognitive Activities Scale Score, 70 (T-Scale)|
|vdcasall|SAGES-Subject-Interview-Data-Analysis-File.dta|Cognitive Activities Scale Score, All Ages (T-Scale)|
|vdhcm|SAGES-Subject-Interview-Data-Analysis-File.dta|Head Circumference (cm)|
|vdp4occf1|SAGES-Subject-Interview-Data-Analysis-File.dta|Factor 1: 'Artistic'|
|vdp4occf2|SAGES-Subject-Interview-Data-Analysis-File.dta|Factor 2: 'Strength'|
|vdp4occf3|SAGES-Subject-Interview-Data-Analysis-File.dta|Factor 3: 'Intelligence'|
|vdp4occf4|SAGES-Subject-Interview-Data-Analysis-File.dta|Factor 4: 'Repetitive'|

[back to VDS table of contents](#vdstoc)


#### Uncertain use or meaning <a name="uncertain" />

|Variable|Form|Description|
|--|--|--|
|vdhos01m_sr|SAGES-Subject-Interview-Data-Analysis-File.dta|RECODE of hos01a|
|vds|SAGES-Delirium-Assessments-Analysis-File.dta|(hivds) vds. vds|

[back to VDS table of contents](#vdstoc)

[Codebook Home](https://quantsci.s3.amazonaws.com/Work/SAGES/SAGES1_Online_Codebook_Files/010_Navigation.html)


---
200_All_vds_variables.md<br>
Rich Jones<br>
2022-12-10<br>
