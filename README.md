# -Ms.C.-Thesis-project-Lag-time-analysis-between-two-data-sets-.mat-from-spectrometers-at-5-and-10-Hz

- 👋 Hi, I’m Shahid from Rome and currently working on my master's thesis project at LF University in Innsbruck, AUT. My research field from both bachelor and master backgrounds is Atmospheric Physics and in particular Biogeochemistry and Micrometeorology.
-   Currently I'm working on solving a lag-time issue emerging from two data sets of two spectrometers (Los Gatos and AERIS, 10Hz and 5Hz) using MATLAB language.
-   Both spectrometers are built to give at .100 and .200 s values of methane, ethane, CO2, water, pressure and temperature as we are interested in measuring methane and ethane fluxes through eddy covariance method in the alpine city of Innsbruck.
-   The ultimate goal is to create a full source apportionment map of the methane emission characteristics of Innsbruck city.
-   I'll try to upload what I've achieved until now here to find some help, as I'm experiencing more problems than anticipating.
-   Hope to find some nice people eager to understand the topic I'm working on and help solve this cold case. 
- 👀 I’m interested in learnig and masterize problem solving skills, advance coding language proficiency and ability as they are and will be the key to success for me now and for the tasks of the future.
- 🌱 I’m currently learning how to treat the lag-time issue, specially in the programming aspect as it is one of the arguments that is not present in literature and forums as I was expecting to be.
-   At the moment, it takes a lot of elbow grease

- So I'm working on creating a MATLAB script for the lag-time correction of several .mat files with the second set taken as reference. The .mat files come from two spectrometers that sample at 10 (LGR) and 5 (AERIS) Hz and each .mat file corresponds to a day from 00:00:00.000 to 23:59:59.900. In total for both instruments and file folders I have 54 files corresponding to 54 days. For simplicity I've downsampled the LGR data values to match the number of data of AERIS, since LGR has double their numbers. AERIS samples at every instant with a lag compared to LGR and this lag accumulates as we keep both instruments running. The goal here is to create a script that corrects the lag


