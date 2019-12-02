# Applied Data Analytics - TDC Fall 2019 Training Course

Repository for the training program focusing on TANF and employment data.


### Projects

This program is centered around a core data analytics project. The projects in this program focused on return to TANF and combined TANF spells with individuals' employment history from UI wage records.

### Training Program Agenda

- Sept 18 — Program Introduction, Overview, Data Exploration, and Project Formulation
- Sept 19 — Data Exploration, Visualization, and Initial Project Exploration
- Sept 20 - Introduction and Analysis of Machine Learning

- Oct 16 - Project Work, Inference, and Record Linkage
- Oct 17 - Project Discussion and Project Work
- Oct 18 - Disclosure Review, Privacy and Confidentiality, and Project Work

### Datasets

The primary datasets used in the program are all stored in the PostgreSQL database called `appliedda` on the ADRF; the datasets are:

1. TANF receipt data for both Illinois and Indiana:
   - Illinois Department of Human Services (IDHS)—the class had access to case data from IDHS on administering TANF (this also includes SNAP and cash assistance cases) programs. These data are in the `il_dhs` schema.
   Indiana Family and Social Services Adminstration—the `in_fssa` schema has TANF case data from Indiana.
2. Quarlerly Census of Employment and Wages (QCEW)—this is a federally mandated program that is also used in conjunction with the Unemployment Insurance program at the U.S. Census Bureau to produce the Logitudinal Employer Household Dynamics datasets. There are two data tables associated with the QCEW dataset and for this program we have access to both tables for Illinois and Indiana:
   - Business data: The tables are `in_dwd.in_qcew_employers` and `il_des_kcmo.il_qcew_employers`.
   - Job data: The tables are `in_dwd.wage_by_employer` and `il_des_kcmo.il_wage`.
  
  ### Jupyter Kernel
  
  The Python3 kernel used in these notebooks was using the `requirements.txt` file.
