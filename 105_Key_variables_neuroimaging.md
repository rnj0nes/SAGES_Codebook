% Key variables neuroimaging
<body style="margin: auto; max-width: 48em;">
</body>

### Neuroimaging

```
. qsagesmetadata mri

variablefieldname: mrintid
formname: mr_demographics
sectionheader: <b><u> FOLLOW-UP HOSPITAL MEDICAL RECORD FORM <u><b> 
fieldtype: dropdown
fieldlabel: Interviewer ID
choicescalculationsorsliderlabel: 11, Guoquan Xu (11) | 15, Jackie Gallagher (15) | 25, Jennifer Inloes (25) | 32, Sarah Rastegar (32) | 33, Meghan Sh
> anahan | 34, Rejoice Dhliwayo | 35, Gina Michael | 36, Peter Wang | 26, Julianna Liu | 27, Jason Albaum
fieldannotation:  @HIDECHOICE='15,25,32'
variablefieldname_3_99: intid


variablefieldname: mricu01
formname: mr_icu_ccu_stay
sectionheader: ICU/CCU Stay [ICU]
fieldtype: dropdown
fieldlabel: 1. Was the patient ever in the ICU or CCU?
choicescalculationsorsliderlabel: 1, Yes (1) | 2, No (2)
variablefieldname_3_99: icu01


variablefieldname: mricu02
formname: mr_icu_ccu_stay
fieldtype: text
fieldlabel: 2. (If patient was in ICU/CCU) How many times?
fieldnote: 99 - NA
textvalidationtypeorshowslidernu: integer
variablefieldname_3_99: icu02


variablefieldname: mricu03am
formname: mr_icu_ccu_stay
fieldtype: text
fieldlabel: 3a. (If patient was in ICU/CCU) Starting Date
fieldnote: 999999 - NA
textvalidationtypeorshowslidernu: date_mdy
variablefieldname_3_99: icu03am


variablefieldname: mricu03bm
formname: mr_icu_ccu_stay
fieldtype: text
fieldlabel: b. (If patient was in ICU/CCU) Ending Date
fieldnote: 999999 - NA
textvalidationtypeorshowslidernu: date_mdy
variablefieldname_3_99: icu03bm


variablefieldname: mricu04am
formname: mr_icu_ccu_stay
fieldtype: text
fieldlabel: 4a. (If patient was in ICU/CCU) Starting Date (Second Stay)
fieldnote: 999999 - NA
textvalidationtypeorshowslidernu: date_mdy
variablefieldname_3_99: icu04am


variablefieldname: mricu04bm
formname: mr_icu_ccu_stay
fieldtype: text
fieldlabel: b. (If patient was in ICU/CCU) Ending Date (Second Stay)
fieldnote: 999999 - NA
textvalidationtypeorshowslidernu: date_mdy
variablefieldname_3_99: icu04bm


variablefieldname: mrimg01
formname: mr_neuroimaging_data
sectionheader: <u>NEUROIMAGING DATA [IMG] </u><br /><br />  <i>Now, we would like you to review the medical record, including previous office visits, 
> current,  hospitalization, and laboratory records, for ANY NEW brain neuroimaging results (CT, MRI)  after discharge from the index surgery or after
>  the last admission</i>
fieldtype: radio
fieldlabel: 1.  Is there any brain CT data in any part of the medical record?
variablefieldname_3_99: img01


variablefieldname: mrimg03
formname: mr_neuroimaging_data
fieldtype: notes
fieldlabel: 3.  Medical Record brain CT: abnormalities noted in the impression section:
variablefieldname_3_99: img03


variablefieldname: mrimg04
formname: mr_neuroimaging_data
fieldtype: radio
fieldlabel: 4.  Is there any brain MRI/MRA data in any part of the medical record?
variablefieldname_3_99: img04


variablefieldname: mrimg06
formname: mr_neuroimaging_data
fieldtype: notes
fieldlabel: 6.  Medical Record brain MRI/MRA: abnormalities noted in the impression section:
variablefieldname_3_99: img06


variablefieldname: mrimg07
formname: mr_neuroimaging_data
fieldtype: radio
fieldlabel: 7.  Is there any other brain neuroimaging data, not including CT or MRI, (e.g. Standard Angiogram, SPECT. PET, etc.) in any part of the me
> dical record?
variablefieldname_3_99: img07


variablefieldname: mrimg09
formname: mr_neuroimaging_data
fieldtype: notes
fieldlabel: 9.  Other neuroimaging data: abnormalities noted in the impression section:
variablefieldname_3_99: img09


variablefieldname: mrigreymatter
formname: project_3_data
sectionheader: Data collected with Sienax (Alsop Group)
fieldtype: text
fieldlabel: Grey Matter
textvalidationtypeorshowslidernu: number
variablefieldname_3_99: igreymatter


variablefieldname: mriwhitematter
formname: project_3_data
fieldtype: text
fieldlabel: White Matter
textvalidationtypeorshowslidernu: number
variablefieldname_3_99: iwhitematter


variablefieldname: mricsf
formname: project_3_data
fieldtype: text
fieldlabel: Cerebrospinal Fluid
variablefieldname_3_99: icsf


variablefieldname: mriicv_fsman
formname: project_3_data
sectionheader: Data Collected with Freesurfer (Guttmann Group)
fieldtype: text
fieldlabel: Intracranial Cavity Volume- Freesurfer with BET (brain extraction tool) and manual correction
variablefieldname_3_99: iicv_fsman


variablefieldname: mribpv_fs
formname: project_3_data
fieldtype: text
fieldlabel: Brain Parenchymal Volume, Freesurfer automatic
variablefieldname_3_99: ibpv_fs


variablefieldname: mrilefthippo_fs
formname: project_3_data
fieldtype: text
fieldlabel: Left Hippocampus, Freesurfer automatic
variablefieldname_3_99: ilefthippo_fs


variablefieldname: mririghthippo_fs
formname: project_3_data
fieldtype: text
fieldlabel: Right Hippocampus, Freesurfer automatic
variablefieldname_3_99: irighthippo_fs


variablefieldname: mridwmh_fsman
formname: project_3_data
fieldtype: text
fieldlabel: Deep White Matter Hyperintensity, Freesurfer with manual correction
variablefieldname_3_99: idwmh_fsman


variablefieldname: mriguttmanlabcomments
formname: project_3_data
fieldtype: text
fieldlabel: Comments from Guttmann Group 
variablefieldname_3_99: iguttmanlabcomments


variablefieldname: mrifazekas_dwmh
formname: project_3_data
sectionheader: Qualitative Data
fieldtype: dropdown
fieldlabel: Fazekas Score-Deep White Matter Hyperintensity
choicescalculationsorsliderlabel: 0, Absent (0) | 1, Punctate foci (1) | 2, Initial confluence of foci (2) | 3, Large confluent Area (3)
variablefieldname_3_99: ifazekas_dwmh


variablefieldname: mridwmh_if
formname: project_3_data
sectionheader: Data Received October 2014
fieldtype: text
fieldlabel: White Matter Hyperintensity Island Filter
variablefieldname_3_99: idwmh_if


variablefieldname: mri_pbvc
formname: project_3_data
fieldtype: text
fieldlabel: Percentage Brain Volume Change (At follow-up event (1 year) only)
variablefieldname_3_99: i_pbvc


variablefieldname: mrintid
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrintid


variablefieldname: mricu01
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mricu01


variablefieldname: mricu02
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mricu02


variablefieldname: mricu03am
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mricu03am


variablefieldname: mricu03bm
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mricu03bm


variablefieldname: mricu04am
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mricu04am


variablefieldname: mricu04bm
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mricu04bm


variablefieldname: mrimg01
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrimg01


variablefieldname: mrimg03
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrimg03


variablefieldname: mrimg04
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrimg04


variablefieldname: mrimg06
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrimg06


variablefieldname: mrimg07
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrimg07


variablefieldname: mrimg09
formname: SAGES-Rehospitalization-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrimg09


variablefieldname: vdmrilefthippo
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: Left Hippocampal Volume
variablefieldname_3_99: vdmrilefthippo


variablefieldname: vdmririghthippo
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: Right Hippocampal Volume
variablefieldname_3_99: vdmririghthippo


variablefieldname: mri01
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: (pimri01) mri01. eligible mris
variablefieldname_3_99: mri01
choicescalculationssliderlabels: 1,(1) yes | 2,(2) no


variablefieldname: mri02a
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: (pimri02a) mri02a. interest proceed
variablefieldname_3_99: mri02a
choicescalculationssliderlabels: 1,(1) yes | 2,(2) no | 9,(9) na


variablefieldname: mri02bo
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: (pimri02bo) mri02bo. not intereseted
variablefieldname_3_99: mri02bo


variablefieldname: mri02bo2
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: (pimri02bo2) mri02bo2. not intereseted
variablefieldname_3_99: mri02bo2


variablefieldname: mri02bo3
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: (pimri02bo3) mri02bo3. not intereseted
variablefieldname_3_99: mri02bo3


variablefieldname: mri02bo4
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: (pimri02bo4) mri02bo4. not intereseted
variablefieldname_3_99: mri02bo4


variablefieldname: mri02bo5
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: (pimri02bo5) mri02bo5. not intereseted
variablefieldname_3_99: mri02bo5


variablefieldname: mri03
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: (pimri03) mri03. pacemaker
variablefieldname_3_99: mri03
choicescalculationssliderlabels: 1,(1) yes | 2,(2) no | 9,(9) na


variablefieldname: mri04
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: (pimri04) mri04. metal in eye
variablefieldname_3_99: mri04
choicescalculationssliderlabels: 1,(1) yes | 2,(2) no | 9,(9) na


variablefieldname: mri05
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: (pimri05) mri05. had mri
variablefieldname_3_99: mri05
choicescalculationssliderlabels: 1,(1) yes | 2,(2) no | 9,(9) na


variablefieldname: date_mri1
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: date_mri1
variablefieldname_3_99: date_mri1


variablefieldname: study_status_mri
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: study_status_mri
variablefieldname_3_99: study_status_mri


variablefieldname: covidmri1
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: covidmri1


variablefieldname: covidmri2
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: covidmri2


variablefieldname: covidmri3
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: covidmri3


variablefieldname: econsent_mri16
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: econsent_mri16


variablefieldname: econsent_mri17
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: econsent_mri17


variablefieldname: econsent_mri18
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: econsent_mri18


variablefieldname: econsent_mri20
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: econsent_mri20


variablefieldname: mrireconsent3
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrireconsent3


variablefieldname: mrireconsent4
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrireconsent4


variablefieldname: mrireconsent5
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrireconsent5


variablefieldname: mrireconsent1
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrireconsent1


variablefieldname: mrireconsent2
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrireconsent2


variablefieldname: mrireconsent_complete
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrireconsent_complete


variablefieldname: mrintid
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrintid


variablefieldname: omr_sages1mri
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: omr_sages1mri


variablefieldname: mricu01
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mricu01


variablefieldname: mricu02
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mricu02


variablefieldname: mricu03am
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mricu03am


variablefieldname: mricu03bm
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mricu03bm


variablefieldname: mricu04am
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mricu04am


variablefieldname: mricu04bm
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mricu04bm


variablefieldname: mrimg01
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrimg01


variablefieldname: mrimg03
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrimg03


variablefieldname: mrimg04
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrimg04


variablefieldname: mrimg06
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrimg06


variablefieldname: mrimg07
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrimg07


variablefieldname: mrimg09
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mrimg09


variablefieldname: mrigreymatter
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: Grey Matter, from Sienax/Alsop Group
variablefieldname_3_99: mrigreymatter


variablefieldname: mriwhitematter
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: White Matter, from Sienax/Alsop Group
variablefieldname_3_99: mriwhitematter


variablefieldname: mricsf
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: Cerebrospinal Fluid, from Sienax/Alsop Group
variablefieldname_3_99: mricsf


variablefieldname: mriicv_fsman
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: Intracranial Cavity Volume, from Freesurfer with manual edits (cc)
variablefieldname_3_99: mriicv_fsman


variablefieldname: mribpv_fs
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: Parenchymal Volume, from Freesurfer, no manual edits (cc)
variablefieldname_3_99: mribpv_fs


variablefieldname: mrilefthippo_fs
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: Left Hippocampus Volume, from Freesurfer, no manual edits (cc)
variablefieldname_3_99: mrilefthippo_fs


variablefieldname: mririghthippo_fs
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mririghthippo_fs


variablefieldname: mridwmh_fsman
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: Deep White Matter Hyperintensity, from Freesurfer with manual edits (cc)
variablefieldname_3_99: mridwmh_fsman


variablefieldname: mriguttmanlabcomments
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mriguttmanlabcomments


variablefieldname: mrifazekas_dwmh
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: Fazekas Score for Deep White Matter Hyperintensities
variablefieldname_3_99: mrifazekas_dwmh


variablefieldname: mridwmh_if
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mridwmh_if


variablefieldname: mri_pbvc
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
variablefieldname_3_99: mri_pbvc


variablefieldname: vdagemri
formname: SAGES-Subject-Interview-Data-Analysis-File.dta
fieldtype: text
fieldlabel: Age at Baseline MRI
variablefieldname_3_99: vdagemri


```

---
105_Key_variables_neuroimaging.md<br>
2022-12-11<br>
Rich Jones<br>


