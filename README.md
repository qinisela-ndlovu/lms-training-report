# 🧠 LMS Training Tracker & Duplicate Assignment Checker

This python script automates the process of tracking training progress across multiple learning modules exported from LMS and ensures that users are not accidentally assigned training they've already completed or currently busy with. The manual assignment allows duplicates(unfortunately).

The process to clean up learning history(duplicates) is a difficult process. 

## 🚀 What the scipt does
1. Splits - complted and outstanding training data into structured excel reports(from .csv)
2. Organises each module into a seperate sheet
3. Compares both reports against a list of new employee numbers(the ones you are trying to avoid duplicates assignment)
4. Outputs a list of company numbers that do not appear in either of the reports, meaning they are safe to assign.
5. Prevents reassigning training to uers who don't need it. If they forgot something, they can always review the content from LMS no need for ressigning.

## 🧩 Why This Script Exists

 Duplicate training assignments can create cluttered learning histories, user confusion, and administrative headaches — especially in compliance-heavy environments.

In many LMS systems, there is:
- No automatic deduplication
- No easy way to retract assignments once made

## Requirements for this
1. Python 3.*
2. pandas
3. xlswriter

make sure to install:: 
pip install pandas xlswriter

The repo have: report1 and report2(dummies), the script(jupyter), README.md ...

The master_list is the actual users that are about to be assigned training.

## Time Saved
- Manual Excel VLOOKUPs and filtering across 3–5 modules = ~20+ minutes







