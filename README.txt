Plugins-
Software: Terminal (.sh files run .ipynb files)

Environment: conda 4.10.1, python 3.8.8



Dependencies-
Python Libraries: pandas 1.2.4, scipy



Programs-


.sh files:

assign2.sh
Top-level script that runs the entire assignment

percent-india.sh
runs Q1_Assgn2.ipynb as
jupyter nbconvert --to notebook --execute Q1_Assgn2.ipynb

gender-india.sh
runs Q2_Assgn2.ipynb as
jupyter nbconvert --to notebook --execute Q2_Assgn2.ipynb

geography-india.sh
runs Q3_Assgn2.ipynb as
jupyter nbconvert --to notebook --execute Q3_Assgn2.ipynb

3-to-2-ratio.sh
runs Q4_3to2_Assgn2.ipynb as
jupyter nbconvert --to notebook --execute Q4_3to2_Assgn2.ipynb

2-to-1-ratio.sh
runs Q4_2to1_Assgn2.ipynb as
jupyter nbconvert --to notebook --execute Q4_2to1_Assgn2.ipynb

age-india.sh
runs Q5_Assgn2.ipynb as
jupyter nbconvert --to notebook --execute Q5_Assgn2.ipynb

literacy-india.sh
runs Q6_Assgn2.ipynb as
jupyter nbconvert --to notebook --execute Q6_Assgn2.ipynb

region-india.sh
runs Q7_Assgn2.ipynb as
jupyter nbconvert --to notebook --execute Q7_Assgn2.ipynb

age-gender.sh
runs Q8_Assgn2.ipynb as
jupyter nbconvert --to notebook --execute Q8_Assgn2.ipynb

literacy-gender.sh
runs Q9_Assgn2.ipynb as
jupyter nbconvert --to notebook --execute Q9_Assgn2.ipynb


Python files:

Q1_Assgn2.ipynb
Input: Population data (DDW_PCA0000_2011_Indiastatedist.xlsx), Language data (DDW-C18-0000.xlsx)
Output: percent-india.csv
Remark: All input files are kept in 'input' directory.

Q2_Assgn2.ipynb
Input: Population data (DDW_PCA0000_2011_Indiastatedist.xlsx), Language data (DDW-C18-0000.xlsx)
Output: gender-india-a.csv, gender-india-b.csv, gender-india-c.csv
Remark: All input files are kept in 'input' directory.

Q3_Assgn2.ipynb
Input: Population data (DDW_PCA0000_2011_Indiastatedist.xlsx), Language data (DDW-C18-0000.xlsx)
Output: geography-india-a.csv, geography-india-b.csv, geography-india-c.csv
Remark: All input files are kept in 'input' directory.

Q4_3to2_Assgn2.ipynb
Input: percent-india.csv (the file generated from Q1)
Output: 3-to-2-ratio.csv
Remark: percent-india.csv input file present outside the 'input' directory.

Q4_2to1_Assgn2.ipynb
Input: percent-india.csv (the file generated from Q1)
Output: 2-to-1-ratio.csv
Remark: percent-india.csv input file present outside the 'input' directory.

Q5_Assgn2.ipynb
Input: Population data with age-group (DDW-0000C-14.xls), Language data with age-group (DDW-C18-0000.xlsx)
Output: age-india.csv
Remark: All input files are kept in 'input' directory.

Q6_Assgn2.ipynb
Input: Population data with literacy-group (DDW-0000C-08.xlsx), Language data with literacy-group (DDW-C19-0000.xlsx)
Output: literacy-india.csv
Remark: All input files are kept in 'input' directory.

Q7_Assgn2.ipynb
Input: Language data statewise (DDW-C17-0000.xlsx to DDW-C17-3500.xlsx)
Output: region-india-a.csv, region-india-b.csv
Remark: All input files are kept in 'input' directory.

Q8_Assgn2.ipynb
Input: Population data with age-group (DDW-0000C-14.xls), Language data with age-group (DDW-C18-0000.xlsx)
Output: age-gender-a.csv, age-gender-b.csv, age-gender-c.csv
Remark: All input files are kept in 'input' directory.

Q9_Assgn2.ipynb
Input: Population data with literacy-group (DDW-0000C-08.xlsx), Language data with literacy-group (DDW-C19-0000.xlsx)
Output: literacy-gender-a.csv, literacy-gender-b.csv, literacy-gender-c.csv
Remark: All input files are kept in 'input' directory.


How to run:
In order to run all the programs sequentially, run below mentioned command from the terminal-
bash assign1.sh
