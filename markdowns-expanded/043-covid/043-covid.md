 # COVID-19 dataset

### Description 

 Information about Covid is collected in a standalone Covid survey and in the Follow-up Medical Survey in the Human Phenotype Project study.

### Introduction 

 This Covid survey presents the participants with questions regarding their Covid-19 vaccinations and diagnosis status. It is asked in-person, in every visit to the clinical testing center. Questions asked are related to the participant’s vaccination status, number of vaccine doses and boosters, were participants diagnosed with Covid-19 in the past and were they hospitalized following diagnosis. 

### Measurement protocol 
<!-- long measurment protocol for the data browser -->
Participants are asked the COVID survey questions during the visit to the clinical testing center (CTC) both at baseline and on follow up visits. It is asked in person, and answers are filled into the system by study coordinators.
 
### Data availability 
<!-- for the example notebooks -->
The information is stored in 1 parquet file: `covid.parquet`. The 'data source' column indicates which survey the infromation comes from either the initial Covid survey or the Follow-up Medical Survey.

### Summary of available data 
<!-- for the data browser -->
The processed data is saved as a pandas DataFrame.
Each question is stored in a single column. All question answers are coded as integers, according to the question code that can be found in the Covid survey data dictionary.
Each single instance of a survey filled by a participant is saved in multiple rows (indicated with an array_index) to accommodate for multiple choice questions as single integer values.

### Relevant links

* Pheno Knowledgebase: https://knowledgebase.pheno.ai/datasets/043-covid.html
