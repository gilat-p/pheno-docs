# Diet logging dataset  

### Description

Diet logging using a smartphone app involves collecting data on food and drink consumption through a mobile application. These data include information such as types of food, serving sizes, nutritional information and the times of consumption. The data is used to track dietary habits and can be used in scientific research to gain insights into the dietary habits of a population and to correlate to other temporal measurements and events.

### Introduction

There is a strong relationship between the development of chronic disease and a person’s diet. Adults who eat a healthy diet are more likely to live longer and are less likely to develop chronic disease or become obese. An unhealthy diet is a major risk factor for type 2 diabetes, cardiovascular disease and certain types of cancer. Consuming a nutrient-dense diet was associated with a low risk of all-cause mortality.

Nutritional epidemiology is a sub-discipline of epidemiology that provides data about the relationship between diet and disease. The data collected is used to define diet–disease associations that are converted into the practice of prevention by public-health nutrition practitioners. To study the associations between diet and disease, there is a need to accurately characterize the dietary habits of individuals. One approach is to use a food diary, which is a daily log of what an individual eats and drinks. Such diaries are used to characterize eating habits in large and small epidemiological studies. Owing to recent technological advancements and the vast availability of smartphones, nutrition-related apps are commonly used to track dietary behavior.

### Measurement protocol 
<!-- long measurment protocol for the data browser -->
Participants in the Human Phenotype Project are asked to log their food for a period of at least two weeks following each visit to the assessment center or a followup call. The figure below shows the process of logging a food item through the diet logging app.

![image alt](diet_logging_eng.png)

Participants are asked to download the app and start logging data one day before the visit to the assessment center. Participants are asked to log everything they eat and drink and to include as one “meal” all the items they have consumed within a 30 minute interval. While participants are asked to log their meals for at least 14 days after each visit, the logging app is open for the whole study period and participants are encouraged to document their diets beyond this time. 


### Data availability:  
<!-- for the example notebooks -->
The information is stored in 3 parquet files: `diet_logging.parquet`, `diet_logging_events.parquet`,  `raw_diet_logging_events.parquet `which contains summary information, processed diet logging data and raw diet logging data respectively.

### Summary of available data 
<!-- for the data browser -->
1. Clean Diet Logging Data: A DataFrame with individual-level diet logging records, post-basic preprocessing and filtering.
2. Raw Diet Logging Data: A DataFrame containing the raw, unprocessed individual-level diet logging records.
3. Nutrients: Nutritional information corresponding to the diet logging records.
4. Summary Table: Contains summary statistics of the diet logging data, aggregated per participant per research stage.


### Relevant links

* Pheno Knowledgebase: https://knowledgebase.pheno.ai/datasets/005-diet_logging.html
