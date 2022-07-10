# calculate Charlson Comorbidty Index and Ischemic Stroke Comorbity Index in Python
## This repository contains codes for calculating Charlson Comorbidty Index and Ischemic Stroke Comorbity Index


It is programmed to account for hierarchical calcualtion of the scores, from reference paper:

" Calculation of the maximum score is based on a hierarchy where diabetes with complications supersedes diabetes without complications; moderate or severe liver disease supersedes mild liver disease; and metastatic solid tumor supersedes any malignancy"

The file is based on ICD-10-CM codes, but works with ICD-10 as well

Functions are reapting saving values so you can change comorbidity wieghts  and claculate your own index
For ISchaemic Stroke comorbidity weights I used following paper (Table 2): 
https://bmchealthservres.biomedcentral.com/articles/10.1186/s12913-019-4720-y


The scores have been validated with clinicians to ensure the accuracy

