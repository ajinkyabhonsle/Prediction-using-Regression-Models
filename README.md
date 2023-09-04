# Prediction-using-Regression-Models
**Context:**
Hospital management is a vital area that gained a lot of attention during the COVID-19 pandemic. Inefficient distribution of resources like beds, ventilators might lead to a lot of complications. However, this can be mitigated by predicting the length of stay (LOS) of a patient before getting admitted. Once this is determined, the hospital can plan a suitable treatment, resources, and staff to reduce the LOS and increase the chances of recovery. The rooms and bed can also be planned in accordance with that.
HealthPlus hospital has been incurring a lot of losses in revenue and life due to its inefficient management system. They have been unsuccessful in allocating pieces of equipment, beds, and hospital staff fairly. A system that could estimate the length of stay (LOS) of a patient can solve this problem to a great extent.


**Objective:**
Find out what factors affect the length of stay (LOS) the most, and come up with a machine learning model which can predict the LOS of a patient using the data available during admission and after running a few tests. Also, bring about useful insights and policies from the data, which can help the hospital to improve their health care infrastructure and revenue.

**Data Dictionary:**
The data contains various information recorded during the time of admission of the patient. It only contains records of patients who were admitted to the hospital. The detailed data dictionary is given below:
patientid: Patient ID
Age: Range of age of the patient
gender: Gender of the patient
Type of Admission: Trauma, emergency or urgent
Severity of Illness: Extreme, moderate, or minor
health_conditions: Any previous health conditions suffered by the patient
Visitors with Patient: The number of patients who accompany the patient
Insurance: Does the patient have health insurance or not?
Admission_Deposit: The deposit paid by the patient during admission
Stay (in days): The number of days that the patient has stayed in the hospital. This is the target variable
Available Extra Rooms in Hospital: The number of rooms available during admission
Department: The department which will be treating the patient
Ward_Facility_Code: The code of the ward facility in which the patient will be admitted
doctor_name: The doctor who will be treating the patient
staff_available: The number of staff who are not occupied at the moment in the ward
