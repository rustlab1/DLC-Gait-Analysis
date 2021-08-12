# DLC Analysis for stroke
## DeepLabCut based analysis for behavioral profiling of rodent stroke recovery 

![Fig. 1: Graphical overview](https://user-images.githubusercontent.com/58003304/128338257-0d5d6ca8-c62c-422d-938a-e02ec4f37e55.jpg)


### (1) BEFORE YOU START

-  Download the entire data set including the raw files, and the R script. The script was tested on Windows and Mac under the R Version 3.8  

- Do not change the order structure or rename the files, this may cause errors in the script.

- Note that the .csv files represent the output from DeepLabCut. We have randomly selected representative videos from baseline and 3 days post injury to give you an example of the data processing. Due to the random selection the output files do not necessarily show the exact same values as described in the manuscript. If your set-up is different you may need to adapt the script. You are welcome to contact ruslan.rust@irem.uzh.ch for further help / collaboration. 

- You can choose between a) "Runway_Analysis.Rmd" and b) "Ladder_Rung_Analysis.Rmd". 
a) The runway analysis provides key calculations and codes described in the paper that covers reliability calculations, analysis from the down side (e..g synchronization, step definition, speed, stance and swing time etc), analysis from lateral side (heights, lengths, angles etc.) 

b) The ladder rung analysis provides key calculations to identify missteps during a ladder rung test including reliability calculations, step identification and error step calculations. 


### (2) INITIAL USAGE
- Update your R and RStudio packages 

- Open the .Rmd file you like to test in R Studio

- Please make sure that first all packages are correctly installed. If packages are not correctly installed, please manually install and load your packages. You can find further information here: http://derekogle.com/IFAR/supplements/installations/InstallPackagesRStudio.html 

- Run the entire code. You may receive few warnings but you should not receive any errors when running the code. If you receive an error try to resolve the error or contact me for further help.

- You can check the "Html Files" and the Output packages for confirmation 

### (3) REGULAR USE

- Please let us know if you identify errors or you made improvements to the script, we will continuously update the code 

- We are also happy to receive updates regarding your projects that are based on this script.

- Please send all inquiries to ruslan.rust@irem.uzh.ch 






