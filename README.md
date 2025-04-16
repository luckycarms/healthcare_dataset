# Synthetic Healthcare Dataset from Kaggle

## The Data
The dataset used in this project can be found from the following website:

[Healthcare Dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)

Due to nature of sensitivity with healthcare data this is directly from website as well:

" About Dataset
Context:
This synthetic healthcare dataset has been created to serve as a valuable resource for data science, machine learning, and data analysis enthusiasts. It is designed to mimic real-world healthcare data, enabling users to practice, develop, and showcase their data manipulation and analysis skills in the context of the healthcare industry.

Inspiration:
The inspiration behind this dataset is rooted in the need for practical and diverse healthcare data for educational and research purposes. Healthcare data is often sensitive and subject to privacy regulations, making it challenging to access for learning and experimentation. To address this gap, I have leveraged Python's Faker library to generate a dataset that mirrors the structure and attributes commonly found in healthcare records. By providing this synthetic data, I hope to foster innovation, learning, and knowledge sharing in the healthcare analytics domain.

Dataset Information:
Each column provides specific information about the patient, their admission, and the healthcare services provided, making this dataset suitable for various data analysis and modeling tasks in the healthcare domain. Here's a brief explanation of each column in the dataset -

Name: This column represents the name of the patient associated with the healthcare record.
Age: The age of the patient at the time of admission, expressed in years.
Gender: Indicates the gender of the patient, either "Male" or "Female."
Blood Type: The patient's blood type, which can be one of the common blood types (e.g., "A+", "O-", etc.).
Medical Condition: This column specifies the primary medical condition or diagnosis associated with the patient, such as "Diabetes," "Hypertension," "Asthma," and more.
Date of Admission: The date on which the patient was admitted to the healthcare facility.
Doctor: The name of the doctor responsible for the patient's care during their admission.
Hospital: Identifies the healthcare facility or hospital where the patient was admitted.
Insurance Provider: This column indicates the patient's insurance provider, which can be one of several options, including "Aetna," "Blue Cross," "Cigna," "UnitedHealthcare," and "Medicare."
Billing Amount: The amount of money billed for the patient's healthcare services during their admission. This is expressed as a floating-point number.
Room Number: The room number where the patient was accommodated during their admission.
Admission Type: Specifies the type of admission, which can be "Emergency," "Elective," or "Urgent," reflecting the circumstances of the admission.
Discharge Date: The date on which the patient was discharged from the healthcare facility, based on the admission date and a random number of days within a realistic range.
Medication: Identifies a medication prescribed or administered to the patient during their admission. Examples include "Aspirin," "Ibuprofen," "Penicillin," "Paracetamol," and "Lipitor."
Test Results: Describes the results of a medical test conducted during the patient's admission. Possible values include "Normal," "Abnormal," or "Inconclusive," indicating the outcome of the test.
Usage Scenarios:
This dataset can be utilized for a wide range of purposes, including:

Developing and testing healthcare predictive models.
Practicing data cleaning, transformation, and analysis techniques.
Creating data visualizations to gain insights into healthcare trends.
Learning and teaching data science and machine learning concepts in a healthcare context.
You can treat it as a Multi-Class Classification Problem and solve it for Test Results which contains 3 categories(Normal, Abnormal, and Inconclusive).
Acknowledgments:
I acknowledge the importance of healthcare data privacy and security and emphasize that this dataset is entirely synthetic. It does not contain any real patient information or violate any privacy regulations.
I hope that this dataset contributes to the advancement of data science and healthcare analytics and inspires new ideas. Feel free to explore, analyze, and share your findings with the Kaggle community."

Patil, P. (2024, May 8). Healthcare dataset. Kaggle. https://www.kaggle.com/datasets/prasad22/healthcare-dataset 

## Project Overview

This project will look at synthetic healthcare data for the purposes of cleaning and creating plots to see what the data shows.

## Project Structure

1. Data exploration: Jupyter Notebook
2. Analysis: Using Python with Pandas Package to clean and organize the data
3. Visualization: Using Matplotlib and Seaborn to plot the data

## Features Utilized

| Feature | Description |
| ------- | ----------- |
| Read in dataset with API | Read in dataset using Kagglehub API |
| Cleaned dataset | In jupyter notebook, cleaned the dataset by removing columns not needed |
| Visualization | Made Line Graphs to display findings |
| Utilized Virtual Environment | Made a venv for this project |
| Notate code | In jupyter notebook, notated code within code cells as well as made notes in markdown cells |

## Getting Started

1. Clone the repository: [git clone](https://github.com/luckycarms/healthcare_dataset)
2. Create a virtual environment (follow commands below)
3. Install the necessary requirements: pip install -r requirements.txt
4. Explore the jupyter notebook (you may need to install kernel if using vs code)

## Dependencies

- Used Python with Pandas
- Review requirements text
- used a Mac OS Sequoia 15.3.1

## Virtual Environment

### Instructions
- After you have cloned the repo to your machine, navigate to the project folder in GitBash/Terminal.
- Create a virtual environment in the project folder.
- Activate the virtual environment.
- Install the required packages.
- When you are done working on your repo, deactivate the virtual environment.


### Command

| Command  | Linux/Mac | PC - GitBash |
|--------- | --------- | ------------ | 
| Create   | python3 -m venv venv | python -m venv venv|
| Activate | source venv/bin/activate | source venv/Scripts/activate |
| Install | pip install -r requirements.txt or pip install packages | pip install -r requirements.txt or pip install packages |
| Deactivate | deactivate | deactivate|

