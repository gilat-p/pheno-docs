# Medical symptoms dataset

### Description 

Medical symptoms data captures detailed information about an individual's current health status by recording physical and mental symptoms they experience. This data includes subjective descriptions such as pain levels, fatigue, and other discomforts, along with observed signs like fever or swelling. Tracking symptoms over time helps in identifying potential health issues, understanding disease onset and progression, and supporting diagnosis. It provides valuable real-time insights into patient well-being and is crucial for personalized healthcare management and treatment planning.

### Introduction

The Human Phenotype Project study collects medical data through online surveys, where participants self-report their experiences with various medical symptoms. This method depends on individuals accurately conveying their own health experiences. Obtaining detailed and thorough information about the symptoms people experience is essential to understand their actual impact on individual health.

### Measurement protocol 
<!-- long measurment protocol for the data browser -->
In the initial phase of the study, during registration, participants are asked to provide information about any medical symptoms they have experienced in the Initial Medical Survey. Additional data is then collected in the Follow-up UKBB Survey during subsequent visits, allowing for ongoing tracking of these symptoms

An additional survey is asked to participants focusing on Irritable Bowel Syndrome (IBS) and digestive health. This digestive health survey is an adaptation of the UK Biobank online gastro-intestinal health self-assessment questionnaire. Many of the questions in the UK Biobank gut health (IBS) questionnaire were adopted from the World Gastroenterology Association questionnaire (2009). Questions asked are related to the participant’s bowel habits, characterization of abdominal pain patterns, accompanying symptoms, and history of IBS in the family.

### Data availability 
<!-- for the example notebooks -->
The information is stored in 3 parquest files: `initial_medical.parquet`, `follow_up_ukbb.parquet` and `digestve_health.parquet` 

### Summary of available data 
<!-- for the data browser -->
1. Initial Medical Survey: A DataFrame containing tabular features representing responses related to medical symptoms from the initial medical survey.
2. Lifestyle Survey: A DataFrame containing tabular features representing responses related to medical symptoms, from the lifestyle survey.
3. Digestive Health: A DataFrame containing tabular features focused on reported medical symptoms specifically related to digestive health, such as abdominal pain, bloating, and bowel habits.

### Relevant links

* Pheno Knowledgebase: https://knowledgebase.pheno.ai/datasets/049-medical_symptoms
