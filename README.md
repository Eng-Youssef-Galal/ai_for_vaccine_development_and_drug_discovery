# ai_for_vaccine_development_and_drug_discovery
## The Fluprint Dataset
The FluPRINT is the name of a unified database for a large-scale study exploring novel cellular and molecular underpinnings of successful immunity to influenza vaccines. It contains information on more than 3,000 parameters measured using mass cytometry, flow cytometry, phosphorylation-specific cytometry (phospho-flow), multiplex ELISA, clinical lab tests (hormones and complete blood count), serological profiling with hemagglutination inhibition assay, and virological tests.
The dataset represents fully integrated and normalized immunology measurements from 747 individuals from eight clinical studies conducted between 2007 to 2015 at the Human Immune Monitoring Center of Stanford University. The dataset represents a unique source in terms of value and scale, which will broaden our understanding of influenza immunity.
FluPRINT, facilitates the application of machine learning algorithms for data mining. The data are publicly available and represent a resource to uncover new markers and mechanisms that are important for influenza vaccine immunogenicity

![FEATURES](https://github.com/Eng-Youssef-Galal/ai_for_vaccine_development_and_drug_discovery/assets/138930263/44ec41bf-75d4-469c-893f-0b7a34547d91)


## Fluprint Usage
Recent advances in computational biology and the development of novel machine learning algorithms, especially deep learning, make it possible to extract knowledge and identify patterns  in  an  unbiased  manner  from  large  clinical  datasets.  Application  of  machine learning  algorithms  to  clinical  datasets  can  reveal biomarkers  for  different  diseases, therapies36, including vaccinations8,9,12. The data from the FluPRINT study can be used to identify cellular and molecular baseline biomarkers that govern successful antibody response to influenza vaccines (IIV and LAIV) across different influenza seasons and a broad age population. The HAI antibody response to influenza vaccines is considered as an  alternative  way to  compare immunogenicity  of  the  vaccines in  susceptible groups where placebocontrolled clinical efficacy study cannot be performed. Since FluPRINT dataset is provided as a database, this facilitates further analysis. Queries can be easily performed  to  obtain  a  single  CSV  file.  For  example,  researchers  interested in understanding which immune cells and chemokines can differentiate between high and low responders that received inactivated influenza vaccine could search the FluPRINT database. In the database, they can find all donors for which flow cytometry or mass cytometry  were  performed  together with  Luminex  assays,  for  which  donors the  HAI response was measured, and all the donors who received inactivated influenza vaccine. The resulting CSV file can then easily be used for downstream analysis.
Major advantages of this dataset are the mapping of the vaccine outcome, classifying individuals as high or low responders, standardization of the data from different clinical studies,  and  from  different  assays.  This  data  harmonization  process  allows  for  direct comparison  of  immune  cell  frequency,  phenotype,  and  functionality  and  quantity  of chemokines  and  cytokines  shared  between  individuals  before  or  after  influenza vaccinations. By releasing the FluPRINT database and the source code, we provide users with the ability to continue building upon this resource and to update the database with their data and other databases.

![1](https://github.com/Eng-Youssef-Galal/ai_for_vaccine_development_and_drug_discovery/assets/138930263/7b106173-1f6e-41d1-bbdc-6b13cac0a707)


## The VAERS Dataset
Established in 1990, the Vaccine Adverse Event Reporting System (VAERS) is a national early warning system to detect possible safety problems in U.S.-licensed vaccines. VAERS is co-managed by the Centers for Disease Control and Prevention (CDC) and the U.S. Food and Drug Administration (FDA). VAERS accepts and analyzes reports of adverse events (possible side effects) after a person has received a vaccination. Anyone can report an adverse event to VAERS. Healthcare professionals are required to report certain adverse events and vaccine manufacturers are required to report all adverse events that come to their attention.  VAERS is a passive reporting system, meaning it relies on individuals to send in reports of their experiences to CDC and FDA. VAERS is not designed to determine if a vaccine caused  a health  problem  but  is  especially  useful  for  detecting  unusual  or  unexpected patterns of adverse event reporting that might indicate a possible safety problem with a vaccine. This way, VAERS can provide CDC and FDA with valuable information that additional work and evaluation is necessary to further assess a possible safety concern.

## VAERS Platform
It  was  created  by the Food  and  Drug  Administration  (FDA) and Centers  for  Disease Control  and  Prevention  (CDC)  to  receive  reports  about  adverse  events  that  may  be associated with vaccines. No prescription drug or biological product, such as a vaccine, is completely free from side effects. Vaccines protect many people from dangerous illnesses, but vaccines, like drugs, can cause side effects, a small percentage of which may be serious.   
VAERS is used to continually monitor reports to determine whether any vaccine or vaccine lot has a higher-than-expected rate of events. Doctors and other vaccine providers are encouraged to report adverse events, even if they are not certain that the vaccination was the cause. Since   it is difficult to distinguish a coincidental event from one truly caused by a vaccine, the VAERS database will contain events of both types.

![Capture](https://github.com/Eng-Youssef-Galal/ai_for_vaccine_development_and_drug_discovery/assets/138930263/42982a0a-1b15-4139-9687-6786ac169621)



## VAERS Usage
#### The primary objectives of VAERS are to:
#### Detect new, unusual, or rare vaccine adverse events.
#### Monitor increases in known adverse events.
#### Identify potential patient risk factors for particular types of adverse events.
#### Assess the safety of newly licensed vaccines.
#### Determine and address possible reporting clusters.
#### Recognize persistent safe-use problems and administration errors.
#### Provide a national safety monitoring system that extends to the entire general population for response to public health emergencies, such as a large-scale pandemic influenza vaccination program.
But also, according to research it contains a features that can help us to predict the suitable candidates for covid vaccine to decrease number of deaths

## VAERS Feature Desription

#### VAERS_ID VAERS: Identification Number
#### SYMPTOM1: Adverse Event MedDRA Term 1
#### SYMPTOMVERSION: MedDRA dictionary version number 1
#### SYMPTOM2: Adverse Event MedDRA Term 1
#### SYMPTOMVERSION2: MedDRA dictionary version number 2
#### SYMPTOM3: Adverse Event MedDRA Term 3
#### SYMPTOMVERSION3: MedDRA dictionary version number 3
#### SYMPTOM4: Adverse Event MedDRA Term 4
#### SYMPTOMVERSION4: MedDRA dictionary version number 4
#### SYMPTOM5: Adverse Event MedDRA Term 5
#### SYMPTOMVERSION5: MedDRA dictionary version number 5
#### VAX_TYPE: Administered Vaccine Type
#### VAX_MANU: Vaccine Manufacturer
#### VAX_LOT: Manufacturer's Vaccine Lot
#### VAX_DOSE_SERIES: Number of doses administered
#### VAX_ROUTE: Vaccination Route
#### VAX_SITE: Vaccination Site
#### VAX_NAME: Vaccination Name
#### RECVDATE: Date report was received
#### STATE: State
#### AGE_YRS: Age in Years
#### CAGE_YR: Calculated age of patient in years
#### CAGE_MO: Calculated age of patient in months
#### SEX: Sex
#### RPT_DATE: Date Form Completed
#### SYMPTOM_TEXT: Reported symptom text
#### DIED: Died
#### DATEDIED: Date of Death
#### L_THREAT: Life-Threatening Illness
#### ER_VISIT: Emergency Room or Doctor Visit
#### HOSPITA: Hospitalized
#### HOSPDAYS: Number of days Hospitalized
#### X_STAY: Prolongation of Existing Hospitalization
#### DISABLE: Disability
#### RECOVD: Recovered
#### VAX_DATE: Vaccination Date
#### ONSET_DATE: Adverse Event Onset Date
#### NUMDAYS: Number of days (Onset date - Vax. Date)
#### LAB_DATA: Diagnostic laboratory data
#### V_ADMINBY: Type of facility where vaccine was administered
#### V_FUNDBY: Type of funds used to purchase vaccines
#### OTHER_MEDS: Other Medications
#### CUR_ILL: Illnesses at time of vaccination
#### HISTORY: Chronic or long-standing health conditions
#### PRIOR_VAX: Prior Vaccination Event information
#### SPLTTYPE: Manufacturer/Immunization Project Report Number
#### FORM_VERS: VAERS form version 1 or 2
#### TODAYS_DATE: Form Completed
#### BIRTH_DEFECT: Congenital anomaly or birth defect
#### OFC_VISIT: Doctor or other healthcare provider office/clinic visit
#### ER_ED_VISIT: Emergency room/department or urgent care
#### ALLERGIES: Allergies to medications,food, or other products
