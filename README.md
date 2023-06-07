# MSc_Thesis_MAE
In the folder "R SCRIPTS" four .Rmd-files are listed: INT_Clean_2023.Rmd, PD_Bleaching_2023.Rmd, PD_Clean_2023.Rmd, and Temp_2022_2023.Rmd. These R scripts were used to analyse raw data of my Thesis Project. In the following paragraphs, the content of each .Rmd-file will be described.

INT_Clean_2023.Rmd-file contains how raw data from the 'intertidal experiment' is analysed. Data selection (row 44-111) was firstly done before cleaning data (row 113-142). At the end of each section, a code is written to download a new excel file to avoid redoing the previous process. Afterwards, the specific growth rate (SGR) was analysed, statistically tested, and plotted per date (row 146-377). In the last section of the script, live coral tissue (survival) from the last date was analysed, statistically tested, and plotted (row 379-650).

PD_Bleaching_2023.Rmd-file started first by preparing the data where data was selected and cleaned. At the end of data preparation, a code is written to download a new excel file containing prepared data before analysing it (row 63-117). Next, data was analysed, statistically tested, and plotted (row 203-250).

PD_Clean_2023.Rmd-file contains the same codings in the same order as the INT_Clean_2023.Rmd-script but raw data from the 'bleaching experiment' is used instead.

Temp_2022_2023.Rmd-file starts first by organising imported data. Data from NOAA was firstly imported, selected, and cleaned (row 43-55). Data from the HOBO loggers was imported, selected and cleaned afterwards (row 57-78). Eventually, data from NOAA and HOBO-loggers were assembled in a new dataset which was downloaded as a new excel-file (row 80-84). To create figure 1, two separate data frames were created (row 86-88). From row 91-154, figure 1 and figure S5 were made and plotted.
