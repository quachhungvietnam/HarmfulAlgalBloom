# HarmfulAlgalBloom
 
Folders in the Capstone Code: 
- Remote_sensing: Process Sentinel-3 remote sensing data. 
- In situ: Process DBHydro Data for calibrating Sentinel-3 data
- Nutrient_Model: Construct and optimize nutrient models using LOBO data. 

Python Scripts/Files in Capstone Code folder: 
- Calibration curve 2: Construct calibration curve from Sentinel-3 remote sensing data and DBHydro in situ data. The result of this script is linearreg.sav file (a linear calibration curve). This file is used for "Chlorophyll estimation visualization.ipynb" script in remote_sensing folder. 
- Data files summarized from other script: "coordinate.csv" (coordinates of stations in DBHydro), "RS_and_insitu.csv" (remote sensing signal at different wavelengths for a given station and its true chlorophyll concentration (from DBHydro).  
