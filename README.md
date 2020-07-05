Why is this tool now? :
==
1)  ~95% of Oracle database's Performance and Tuning (PT) DBA's primary role is to review AWR reports.

2)  ~50% of time, in live monitoring, we rely on ASH and AWR reports.

3)  Easy to convey to your clients during root cause analysis and critical performance issues.

4)  AWR reports are huge in size and ~99%, DBA has to read numbers in the reports and infer the analysis based on it. Most of the information in the AWR report are not really needed for analysis; due to its size and reading numbers in the report, these are things can happen

         a)  specialized DBA skillset is needed
     
         b)  Lots of chances for human errors or oversight
     
         c)  Skilled DBA has to spend lots of time.
     
This tool is developed using Python language. This tool prompts for entering AWR report to be analyzed and visualized. These are steps to follow to make use of this tool and it has to be developed further adding all important sections of the AWR report to excel sheet,
Let's start!!!

--------------------------------------------------------------------------
Prerequisites:
==
Basic programming knowledge on Python language.

Basic understanding of OOPS concepts.

Basic understanding of pandas library

--------------------------------------------------------------------------

Step 1:
==

Use this link to download and install Python 3.7.6 version on Windows 10, 64bit OS.

https://www.python.org/downloads/

--------------------------------------------------------------------------

Step 2:
==
Install these libraries. I used 'pip' command to install. 
Example: Follow this to install pandas library.

start program --> command prompt --> pip install pandas

matplotlib

BeautifulSoup

pandas 

xlsxwriter

openpyxl

--------------------------------------------------------------------------
Step 3:
==
Copy and paste the repository python script files in a location and keet it ready

--------------------------------------------------------------------------

Step 4:
==

Execution Method: 

prvoide full path+awr report name

C:\Users\cthangavelu\Desktop\Delete\Python>python main.py

Enter the AWR report file name to be analyzed: AWR_RPT_PMIF28_20191122-12353-12354.html

Extracting DB, Host and Snap details

Extracting ADDM and Foreground wait event details

Extracting IO Profile details

Extracting SQL Order By CPU details

Extracting SQL Order By Elapsed Time details

Extracting SQL Order By USER IO details

Extracting SQL Order By Gets details

Extracting SQL Order By Physical Reads details

Extracting SGA Advisory Target  details

--------------------------------------------------------------------------

Let me know your feedback to enhance this in a better way
