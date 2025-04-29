This folder contains example of cleaning scripts.
Currently it contains a cleaning dofile, used in a data collection project, which does the following:

- Setup of common variables (globals) to be used in the script
- Setup pahts
- Import raw data
- Drop ineligible surveys
- Corrections from data collection notes
- Variable type conversion
- Drop numeric variables with all missing observations
- Clean multiple choice variables
- Label categorical variables with loops
- Export Personal Identifiable Information to Anonymize the dataset into a secure location
- Merge pweights for analysis
- Save anonymized dataset
