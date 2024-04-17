"GPS exps.zip" contains all code for section 4 (LapPE vs homomorphism counts in graph transformer) of the report

"GIN_exps" contains all code for section 3 (Spectral learning of homomorphism counts)

In order to run code, one must edit the lines which request a directory path:

  - line 10 of submit.sh in "GPS exps/batch_jobs" requires the user edit in the path to their conda env
  - line 26 of "GPS_exps/main_method.py" requires the user edit in the path to wherever they download the "GPS exps/zinc-data" folder
  - the "Drive setup" cell in "GIN_exps/GIN_Exp.ipynb" requires user to edit in path of "GIN_exps/get_data_edited.py"
  - the "Data" cell in "GIN_exps/GIN_Exp.ipynb" requires user unzip "GPS exps/zinc-data" and then edit in path to the unzipped data
