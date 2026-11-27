# Data Dictionary

## Dataset: Learners

This document describes the fields included in the initial synthetic learner dataset.

| Field | Data Type | Description |
|---|---|---|
| Learner_ID | Text | Unique identifier assigned to each fictional learner |
| Registration_Date | Date | Date the fictional learner registered |
| Province | Text | South African province |
| Age_Band | Text | Learner age category |
| Education_Level | Text | Highest education level category |
| Institution_Type | Text | Category of educational institution |
| Learning_Pathway | Text | Selected digital learning pathway |

## Data Quality Rules

1. Learner_ID must be unique.
2. Registration_Date must contain valid dates.
3. Province must match an approved category.
4. Learning_Pathway must match the pathway reference list.
5. Missing values should be identified and investigated.

## Data Limitations

All records are synthetic. These fields are provisional and must be compared with Ikamva Digital's official learner profile options before being treated as representative of its platform.
