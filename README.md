CleanupCode.ipynb File:
Class file_cleanup
Function p_extract_files will accept two parameters
1) Input file path location
2) output files path location

Input files will be unzipped and will be put in the output folder.
Preprocessing function will perform the cleanup activities on the extracted files.
Rows with NULL in Event_type column will be removed as part of preprocess
Categorical variables will be replaced with Numberial labels.
