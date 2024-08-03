# Pandas Merge Left Join

This repository demonstrates how to perform a left join on two CSV files using pandas in Python.

## Files
**annotated.csv**: Contains columns `chr`, `start`, and `alt`.
<img width="197" alt="Screenshot 2023-05-05 at 15 21 11" src="https://user-images.githubusercontent.com/13205577/236468837-5b4ef85b-f5da-4cb2-a622-e5e572523f5e.png">
**class.csv**: Contains columns `chr`, `start`, `alt`, and `class`.
<img width="260" alt="Screenshot 2023-05-05 at 15 22 05" src="https://user-images.githubusercontent.com/13205577/236469089-5448ef06-d939-4323-abb0-d716d5f1ed35.png">

## Objective

Append the `class` column from `class.csv` to `annotated.csv` where the `chr`, `start`, and `alt` columns match.
