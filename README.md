# SAR ship images
Dataset in `json` format from [Sarmaps](http://sarmaps.gitlab.io/index.html) repository.
For working with Google Colaboratory notebooks:)

`Synthetic Aperture Radar (SAR)` is a monitoring solution which is especially well fitted to maritime surveillance. 
The large swath widths, time-independent, weather resistant observations can be very useful for the detection of ships typically invisible to other forms of monitoring. 
A dataset contains 43 `Sentinel-1 Extended Wide Swath` images and 3 `RADARSAT-2 ScanSAR Narrow` images between the 6th October 2014 to the 22 July 2015. 
These images cover a large percentage of the South African Exclusive Economic Zone using multiple polarisations and three different resolutions. 

A detailed description of the dataset is [given](http://sarmaps.gitlab.io/data/dataset_paper.pdf) including: 
* the entire generation process from the original compressed data to the geocoded images; 
* the dataset organisational structure tailored to each step of the ship detection process; 
* ship referencing and attribute extraction procedures; 
* supplementary `Automatic Identification System (AIS)` transponder information and matching; 
* ship reference and `AIS` matched ship attribute analysis. 

A number of novel components are introduced, including a three-class discrimination dataset component which helps provide a more granular approach to ship discrimination performance analysis. 
The aim of the dataset is to introduce a single `SAR` dataset which covers a wide range of possible requirements for scientific ship detection method analysis using the newest `SAR` imagery available. 
