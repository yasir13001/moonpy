Install python 3.0 or above

dependencies:
Install dependencies "pip install -r requirements.txt"

Run Script:
cd to the directory where python file resides.
run "python moonPredictor.py"

Program Instructions:
if python script and data directory are in same dir then just enter directory name without inverted commas
Same as above for the outout directory
Date format should be "yy-mm-dd", it will search the date in the given data
Input Islamic Month with upper case, it will write it as it is in the pdf.
Same as above for Islamic year. 
A PDF will pop up in default browser and pdf with the same date you mentioned wth .pdf ext will be saved in output dir 

Program lines:
Input data directory(Drag and drop): moon data
Output file destination(Drag and drop): output
Date (yy-mm-dd): 2023-09-15
Islamic Month(Upper case): RABI-UL-AWWAL
Islamic year: 1445
Restarting...


Data format:
Replace the header with " year  h   cd conj  f wk   mon  day  set   Saz    age  Alt Maz  dz  Mag El  mset  lag   best  cat"
Remove irrelevent text written by publisher from all files
Make sure columns align correctly
Jiwani file is important because its conjuction time and moon age will be written on output file
If you want to add other city just rename it with correct format and place it in moon data directory.

