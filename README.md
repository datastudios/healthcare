# Introduction

### Home Healthcare Industry

Home health is a nursing specialty in which nurses provide multidimensional home care to patients of all ages. Home health care is a cost efficient way to deliver quality care in the convenience of the client's home. 
 Home health nurses create care plans to achieve goals based on the client's diagnosis. These plans can include preventive, therapeutic, and rehabilitative actions. Home health nurses also supervise certified nursing assistants. The professional nursing organization for home health nurses is the Home Healthcare Nurses Association (HHNA). Home health care is intended for clients that are well enough to be discharged home, but still require skilled nursing personnel to assess, initiate and oversee nursing interventions.

From Wikipedia: [Home Health Nursing](https://en.wikipedia.org/wiki/Home_health_nursing)

### Business Challenge

The primary focus of the home healthcare provider is to keep their patients healthy and out of the hospital.  Home healthcare nurses make at-home visits, monitor a patients health, and take measures to proactively address health issues that might require a patient's hospitalization.  Beyond individual patient health, there are financial incentives from insurers for home healhcare organization that maintain the patient population under their care healthy and outside of the hospital.

### Data Description

During at-home visits by home healthcare nurses, patient health statistics were collected on a recurring basis with the frequency varying across the patient population.  

The following datasets and corresponding data-points were collected: 
<br/><br/>

- **Patients**
  - Age
  - Gender  
* **Visits**
  * Date of Visit (i.e., year, month, week number, date)
  * Total Visits - Cumulative number of visits to-date.
  * Total Hospitalizations for Week - Cumulative number of hospitalizations on a particular week if any.
  * Total Hospitalizations - Cumulative number of hospitalizations to-date if any.

* **Health Statistics**
  * 150+ Health statistics including blood pressure, pulse, weight and medications taken by a particular patient.

### Analysis and Model Deployment Goals

In order to proactively identify, monitor and predict the likelihood of a patient requiring hospitalization a classification machine learning model was developed.  

The primary goals for development were to:


1. Develop a machine learning model that can aid in identifying patients at highest risk of hospitalizaiton on a weekly basis.
2. Understand the risk factors that contribute to a high risk of hospitalization.
3. Deploy the model and refresh with patient visit, health statistic, and hospitalization risk data on an on-going basis.
