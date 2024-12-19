# About

- Coding Language: [R]
- Version: [4.2.1]
- Required Packages: 
	- [dplyr]
    - [ggplot2]
    - [ggpubr]
    - [rstatix]
    - [readxl]
    - [table1]
    - [lme4]
    - [multcomp]
    - [lmerTest]
    - [interactions]
    - [corrplot]
    - [car]
    - [patchwork]
    - [moments]
    - [tidyr]

- Related Publication: [Melville, M. A., Stark, J., Hiersche, K. J., Esterman, M., & Hayes, S. M. (2024, August 25). Examining the Impact of Light and Vigorous Acute Aerobic Exercise on Pattern Separation and Sustained Attention in Young Adults. https://doi.org/10.31219/osf.io/9aenu]

# Usage

Goal: [This code was used to perform statistical analyses for the "Related Publication" mentioned above.]
Original Usage: 
[The input data should be downloaded from Zenodo to the file paths "GitHub_Export/Data/All_Processed.csv" and "GitHub_Export/Data/IPAQ_SF.csv". These files contain demographic and IPAQ-SF information, exercise or rest bouts, and cognitive tasks data. Output includes the .html knitted file ("GitHub_Export/R/MAE_Data_Analysis.html") and various figures ("GitHub_Export/Output/").]
How to Use: 
- [Create a folder titled "Github_Export" on your computer and ensure it contains the following subfolders: "Data", "Documentation", "Output", and "R". Download all input files to the correct folders ("GitHub_Export/Data/All_Processed.csv") and (GitHub_Export/Data/IPAQ_SF.csv). Do not rename or change the format of the "GitHub_Export" folder, its subfolders, or any of the files it contains, as changes to file or folder names might cause the script to crash. Prior to running the .Rmd file, set your current working directory to a parent directory of "GitHub_Export". This is necessary because the .Rmd file contains a custom function to automatically locate the "GitHub_Export" folder. If all these requirements are met, the script should execute correctly without errors.] 

# Further Reading
[NA]

