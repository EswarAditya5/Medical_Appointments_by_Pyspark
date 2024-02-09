# Medical_Appointments_by_Pyspark

## Overview
This repository contains a dataset related to medical appointments, sourced from Kaggle. The dataset encompasses information about patients and their scheduled medical appointments, aiming to facilitate exploratory data analysis and predictive modeling in the healthcare domain. Understanding patterns in this data can aid in improving appointment attendance rates and overall healthcare management.

## Dataset Information:
Source: Data from [Kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

File_Format: CSV (Comma-Separated Values)

## Data Description
The dataset comprises the following key features:
| Name | Description |
|--|--|
| PatientID| Unique identifier for each patient|
| AppointmentID| Unique identifier for each appointment|
| Gender| Patient's gender (Male/Female)|
| ScheduledDay| Date and time when the appointment was scheduled|
| AppointmentDay| Date of the actual appointment|
| Age| Patient's age|
| Neighborhood| The neighborhood in which the healthcare center is located|
| Scholarship| Indicates whether the patient is enrolled in the Bolsa Família welfare program|
| Hipertension| Indicates whether the patient has hypertension|
| Diabetes| Indicates whether the patient has diabetes|
| Alcoholism| Indicates whether the patient is diagnosed with alcoholism|
| Handcap| Indicates the level of handicap (0 to 4)|
| SMS_received| Indicates whether the patient received an SMS reminder for the appointment|
| No-show| Target variable, indicating whether the patient showed up for the appointment (Yes/No)|


## Usage

### Exploratory Data Analysis (EDA):
Utilize the provided Jupyter Notebook (medical_appointment_eda.ipynb) for an in-depth exploration of the dataset.
### Predictive Modeling:
Explore the modeling directory for scripts and notebooks related to predictive modeling of appointment no-shows.
### Data Visualization:
Visualize key insights using the visualization directory, which includes scripts for creating informative plots and graphs.

### Acknowledgments:
We appreciate Kaggle and the original data contributors for making this dataset available for research and analysis.

### License:
This dataset is provided under the terms specified by Kaggle. Refer to Kaggle's licensing information for details.

### Technology used:
<div align ='left'>
<img src ='https://technology.amis.nl/wp-content/uploads/2020/11/image_thumb-27.png', height = "50" alt = 'Jupyter'/><img width='12'/> 
<img src = 'https://cdn.dribbble.com/users/6569/screenshots/16471177/media/8bbfe7fd594073dc6271d5d852c7381a.png', height = "50" alt = 'Vs code'/><img width = '12'/>
<img src = 'https://thomasjpfan.github.io/data-umbrella-2020-streamlit-slides/images/streamlit.png', height = "50" alt = 'Streamlit'/><img width = '12'/>
<img src = 'https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png', height = "50" alt = 'Github'/><img width = '12'/>
</div>
