# Liver ultrasound dataset  

### Description

Measures of liver health from a liver ultrasound and 2D shear wave elastography (2D-SWE), including measures of viscosity, elasticity, attenuation, and sound speed.

### Introduction

Liver ultrasound was performed using the Supersonic Aixplorer MACH 30 (Hologic, USA).  The Supersonic Imagine Aixplorer is an ultrasound device that is able to measure the liver's stiffness, viscosity, attenuation and sound speed to diagnose and monitor liver conditions such as steatosis, fibrosis and inflammation. The device uses several ultrasound-based measures, including Speed of Sound (SSp.PLUS), Attenuation Index (Att.PLUS), Viscosity (Vi.PLUS) and Elasticity (Two-Dimensional ShareWave Elastography (2D-SWE)) to evaluate the liver and improve diagnosis performance. These measurements have been shown to be correlated to different stages of liver conditions.

Ultrasound-based liver measurements were performed using ShearWave Elastography (2D- SWE.PLUS) for elasticity assessment, sound speed Plane-wave ultrasound and attenuation. Plane-wave ultrasound was measured for assessment of liver steatosis (fatness) and viscosity plane-wave ultrasound for assessment of viscosity as a marker of inflammation. Measurements were performed with a C6-1X convex transducer using the UltraFast software available on the Mach 30 ultrasound system. US images of the liver were also saved.

### Measurement protocol 
<!-- long measurment protocol for the data browser -->
Measurement protocol: All patients were examined in supine position, with the right arm elevated above the head, by an intercostal approach, in the right liver lobe. Acquisitions were performed during neutral respiratory apnea. Initially the Attenuation and Speed of Sound were measured from a homogeneous area of the liver parenchyma free of vessels or other structures. Measurements were performed from 3 different liver regions. 2D-SWE and viscosity were then measured from 3 different locations in an area of relative uniform elasticity, at a depth of 3–5 cm using stability index tool (SI) derived from the spatial and temporal stiffness stability at a stability index >90%. 

![Liver US example](liver_ultrasound_swe_and_vi_image.png)

### Data availability: 
<!-- for the example notebooks -->
The information is stored in 2 parquet files: `liver_ultrasound.parquet`and `liver_ultrasound_aggregated.parquet`

### Summary of available data 
<!-- for the data browser -->
1. Liver ultrasound image DICOM file
2. Liver ultrasound image file
3. Derived measures (e.g. viscosity, elasticity, and attenuation)
4. Auxiliary data (e.g. stability index)

### Relevant links

* Pheno Knowledgebase: https://knowledgebase.pheno.ai/datasets/004-liver_ultrasound.html