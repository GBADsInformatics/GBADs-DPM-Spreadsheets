# GBADs-DPM-Spreadsheets
<img src= "https://github.com/GBADsInformatics/GBADs-DPM-Spreadsheets/blob/main/images/GBADsInformaticsLogo.png" width="150">
This repo contains the spreadsheets that function as an input interface to the parameters for the DPM.  Currently there are only
MSExcel spreadsheets but other types of spreadsheets (such as Google Sheets, LibreOffice Calc, etc.) will hopefully be added in
the future. The spreadsheets are versioned and are in species-specific subdirectories (e.g. cattle).
Currently (August 26, 2025) there are 2 species with working spreadsheets: cattle and small-ruminants.  Other species to be added
in the future include pigs and equids.

## Repository Structure
```
.
├── MSExcel/                # Directory for MSExcel spreadsheets
│   ├── cattle/             # Template spreadsheets and examples for cattle
│       ├── version_1.0/    # Version 1.0
│           ├── cattle_template_version_1.0.xlsm     # Template
│           ├── cattle_example_current.xlsm          # Example of a current scenario
│           ├── cattle_example_ideal.xlsm            # Example of an ideal scenario
│   ├── pigs/               # Template spreadsheets and examples for pigs
│       ├── version_1.0/    # Version 1.0
│           ├── pigs_template_version_1.0.xlsm       # Template (not complete as of August 26, 2025 - do NOT use)
│   ├── small-ruminants/    # Template spreadsheets and examples for small-ruminants
│       ├── version_1.0/    # Version 1.0
│           ├── small-ruminants_template_version_1.0.xlsm     # Template
│           ├── small-ruminants_example_current.xlsm          # Example of a current scenario
├── images/                 # Images for documentation
├── README.md               # Project documentation

