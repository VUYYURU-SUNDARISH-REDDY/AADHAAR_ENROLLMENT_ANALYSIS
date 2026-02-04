# AADHAAR_ENROLLMENT_ANALYSIS
This project examines the data about UIDAI Aadhaar enrolments to detect the geographic, demographic, and seasonal trends in the data through data analytics and visualization tool. The generated insights contribute to planning in administration that is based on data and enhanced service delivery.

DATASETS : https://drive.google.com/drive/folders/1tLXC9FYcED_KFs1BxeBcguIed_XOm2ig?usp=sharing

Datasets Used:
This discussion is based on the Aadhaar enrolment and update statistics of Unique Identification Authority- India (UIDAI). The data is daily enrolments in Aadhaar in various regions of the country. It encompasses data linked to place, age categories, and time which enable one to familiarize themselves with the difference in Aadhaar enrolment rates by regions and time.
The dataset can be analyzed at various levels including state, district and pincode. It also gives age specific details of enrolment and the data is helpful in the analysis of demographic trends in Aadhaar registration.
Important columns used in the analysis include:
 date — event date
 state — state name
 district — district name
 pincode — geographic pincode
 age_0_5 — enrolment counts for age 0–5
 age_5_17 — enrolment counts for age 5–17
 age_18_greater — enrolment counts for age 18+
 total enrollment — engineered feature equal to age_0_5 + age_5_17 + age_18_greater
 month / year — derived temporal fields for aggregation
