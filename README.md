# Pandas Merge Left Join
There are two CSV files.

File 1 = annotated.csv

<img width="197" alt="Screenshot 2023-05-05 at 15 21 11" src="https://user-images.githubusercontent.com/13205577/236468837-5b4ef85b-f5da-4cb2-a622-e5e572523f5e.png">

File 2 = class.csv

<img width="260" alt="Screenshot 2023-05-05 at 15 22 05" src="https://user-images.githubusercontent.com/13205577/236469089-5448ef06-d939-4323-abb0-d716d5f1ed35.png">


annotated.csv has three columns: chr, start, alt and class.csv has four column: chr, start, alt, class.

Whenever chr, start and alt in annotated.csv matches chr, start and alt in class.csv file, then take the class column value and append it to annotated.csv file.
