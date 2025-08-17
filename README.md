💳 Loan Apply Utility Bot
📌 Overview

The Loan Apply Utility Bot is an RPA (Robotic Process Automation) project developed in UiPath Studio.
It automates the end-to-end loan application process by:

Reading applicant details from an Excel sheet

Filling a web-based loan application form

Submitting the application

Extracting eligibility and loan interest rate information

Updating the results back into Excel

Renaming the processed file for tracking

This bot eliminates repetitive manual work, reduces human errors, and significantly speeds up loan application processing.

🎯 Objectives

✅ Automate manual loan data entry tasks

✅ Improve accuracy & reduce processing errors

✅ Save time in loan processing lifecycle

✅ Provide an easy-to-use automation solution

📝 Problem Statement

Banks and financial institutions often process hundreds of loan applications daily.
Manual data entry into loan portals is:

Time-consuming ⏳

Error-prone ❌

Costly 💸

The Loan Apply Utility Bot solves this problem by automating the entire workflow with minimal human intervention.

🌍 Scope
🔹 Technical Scope

Reads and writes Excel files (using Workbook activities)

Automates web-based loan application forms

Extracts loan results dynamically

Works with structured input data

🔹 Environmental Scope

Reduces paper usage by digitalizing applications 📑

Minimizes manual labor → more efficient workforce ⚡

Provides scalability for large-scale processing

🏗️ System Development

The bot follows a modular workflow design for clarity and maintainability.

🔹 Architecture Diagram
flowchart TD
    A[Excel File with Applicant Data] --> B[UiPath Bot]
    B --> C[Loan Application Website]
    C --> D[Eligibility & Loan Rate Extraction]
    D --> E[Update Excel File]
    E --> F[Rename Processed File]

🧩 Modules

Input Module – Reads applicant details from Excel

Web Automation Module – Opens loan portal & fills application form

Submission Module – Submits loan application

Extraction Module – Retrieves eligibility and loan interest details

Output Module – Updates and renames the Excel file

🛠️ Requirements

UiPath Studio (Community or Enterprise Edition)

Excel File (Input dataset with applicant details)

Internet Connection (for accessing loan portal)

📂 Sample Input Format:

Name	Age	Income	Loan Amount	Tenure	Eligibility	Interest Rate
John D	28	50000	200000	24		
🚀 Setup & Execution

Clone or download this repository 📥

Open the .xaml file in UiPath Studio

Place the input Excel file in the project folder

Update file paths/selectors if required

Click ▶ Run File to start automation

📊 Expected Output

✅ Processed Excel file updated with Eligibility & Interest Rate

✅ Renamed Excel file for tracking

✅ Log messages in UiPath Output panel

🔮 Future Enhancements

📧 Email applicants their loan results

🗄️ Store records in a central database

🌐 Support multiple loan portals

🔄 Retry mechanism & improved exception handling

📌 Summary

The Loan Apply Utility Bot is a smart automation solution that simplifies loan application workflows. With minimal setup, it:

Reads input data

Automates form filling

Retrieves results

Updates output file

This ensures faster processing, higher accuracy, and greater efficiency for financial institutions.
