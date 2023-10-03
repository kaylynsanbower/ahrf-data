# ahrf-data
This repository contains the code used to take the raw Area Health Resource Files (AHRF) data from the Health Resources and Services Administration (HRSA) and prepare it to be used in subsequent analyses. 

* **data** -- I downloaded the AHRF data from [the HRSA website](https://data.hrsa.gov/data/download). I used the 2019-2020 SAS file. Place that file in "data/input," and create a file "data/intermediate" and "data/output" to house the intermediate files and the final dataset, respectively. 
* **data-code** -- This folder contains the single code file that extracts the CMI and Medicare Record number from the annual files and combines them into a single dataset. 
