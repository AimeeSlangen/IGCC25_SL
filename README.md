This repository contains the data and python notebook script to process and plot the sea-level observation time series for the IGCC 26. 
For any questions, please contact: aimee.slangen [at] nioz.nl. 
This python notebook is written by Aimée Slangen (NIOZ, UU) and Matthew Palmer (Met Office, Uni Bristol). 

This repository contains the AR6 sea level reconstruction data (in the folder AR6), new altimetry series (in the folder altimetry) and new TG series (in the folder TG). The notebook IGCC_2026_SL-replace-SAT.ipynb first loads all the data, then merges the AR6 tide gauge reconstruction with the new altimetry data, and finally computes rates over various periods.

The csv files that are output by the python notebook are also included for reference. These files represent a) the updated satellite altimetry ensemble; b) the updated invididual altimetry annual time series; c) the updated sea level reconstruction from 1901 to 2025. 

Please note that in this version of the python notebook the addition of the Mu et al tide gauge reconstruction (https://essd.copernicus.org/articles/17/5507/2025/essd-17-5507-2025.pdf) to figure 1a is commented out, because the dataset is too large to store here. This dataset can be downloaded at https://doi.org/10.5281/zenodo.15385035. 

A thank you to Sonke Dangendorf, Jinping Wang and John Church, and Dapeng Mu for sharing their tide gauge reconstructions. Also thanks to AVISO, Ben Hamlington (NASA JPL) and Steve Nerem (Univ Colorado) for updating and sharing the satellite altimetry data. 


