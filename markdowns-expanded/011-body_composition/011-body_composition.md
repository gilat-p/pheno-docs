# Body composition (DXA) dataset  

### Description 

Body composition was profiled based on DXA (dual-energy x-ray absorptiometry) imaging, and includes measurements of fat and lean mass for the legs, arms, trunk, gynoid, and android, as well as measurements of total scan visceral adipose tissue (VAT) and subcutaneous adipose tissue (SAT) area, mass and volume are included.

### Introduction

DXA (dual-energy x-ray absorptiometry) is a medical imaging technique that is used to measure body composition, specifically the amounts of bone, fat, and lean muscle tissue in the body. A DXA scan uses a low dose of ionizing radiation to produce a detailed image of the body, which is then analyzed by a software to determine the body composition. This method is considered to be one of the most accurate methods for measuring body composition, as it is able to distinguish between different types of tissue and provide detailed information about the distribution of fat and muscle in the body. DXA imaging is commonly used for assessing bone density and for monitoring changes in body composition over time, such as during weight loss, muscle building programs or for assessment of sarcopenia.

### Measurement protocol 
<!-- long measurment protocol for the data browser -->
Dual-energy X-ray Absorptiometry (DXA) was performed with the GE Lunar Prodigy Advance device (GE Healthcare, USA) and the GE CoreScan software application. Before the scan, participants were asked to remove all metal items, heavy clothing and shoes. Each participant performed a total body scan in a supine position to determine percent body fat, fat mass, lean body mass, and bone mineral density. The total body composition is calculated for various regions (arms, legs, trunk, android, gynoid and total). The CoreScan also estimates the Visceral Adipose Tissue (VAT) and Subcutaneous Adipose Tissue (SAT) content within the android region. Bone mineral density was measured from the Femur necks, bilaterally and from the spine vertebra L1-L4. 

![DXA](dxa_machine.jpeg)

### Data availability 
<!-- for the example notebooks -->
The information is stored in 1 parquet file: `body_composition.parquet`

### Summary of available data 
<!-- for the data browser -->
1. Measurements of fat and lean mass for the legs, arms, trunk, gynoid, and android.
2. Measurements of total scan visceral adipose tissue (VAT) and subcutaneous adipose tissue (SAT) area, mass and volume.
3. DXA image files (e.g., total body composition - %fat).
4. DXA image DICOM files.

### Relevant links

* Pheno Knowledgebase: https://knowledgebase.pheno.ai/datasets/011-body_composition.html
