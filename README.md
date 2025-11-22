# 19CS565-14-Capstone-Project

## Title: CGPA Calculation Automation

### Objective: 
To calculate a student's Cumulative CGPA by automating the following steps on the MyCamu portal:
1. Securely log in and navigate to the results page.

2. Download the result PDF for every semester, starting with the oldest.

3. Read and extract grades and credits from the PDFs.

4. Calculate the final CGPA and email the result to the student.

### Applications to be used:

1. UiPath Studio: The main development environment.
   
2. Web Browser (Edge): Used for navigating the MyCamu portal.
   
3. UiPath Orchestrator: Used to securely store the students credential as assets.
   
4. GMail: To mail the students their results back.

### Phase 01  - Navigation & Access: 
Navigate to MyCamu by using the credential asset stored, and accessing the student account.

https://github.com/user-attachments/assets/f6819ae1-1e59-4990-a67e-5f2b75a4b234

##### status: completed

### Phase 02 - Data Retrieval & Storage: 
Dynamically download the PDF for each semester.

##### status: on progress

### Phase 03 - To perform Mathematical Calculations:
Calculate the CGPA from the Student Scorex

##### status: on progress

### Future Scope: 
Release as a reusable module.
