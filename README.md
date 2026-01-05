📊 NSE Automation – RPA Framework Project
📌 Overview

NSE Automation is a framework-based RPA solution designed to automatically extract Equity & SME market data from the NSE (National Stock Exchange of India) website and store it in a structured format for analysis and reporting.
The automation follows enterprise RPA framework principles such as:

-> Config-driven execution
-> Modular business flows
-> Robust validation & error handling
-> Scalable and reusable design
This project eliminates manual data collection and ensures accuracy, speed, and consistency in daily market data extraction.

🎯 Business Requirement

The finance/trading team requires daily NSE market data for analysis, but manual extraction is:
-> Time-consuming
-> Error-prone
-> Dependent on human availability

✅ Automation Objectives

The automation automatically:

🌐 Opens the NSE website
📈 Navigates to Equity Market → Equity & SME
📋 Extracts stock market table data
🔄 Handles dynamic web tables & pagination
📊 Saves extracted data into Excel
📩 Sends execution status via email

Main
 ├── Initiate Flow
 │    ├── Read Config File
 │    ├── Kill Process
 │    └── Environment Setup
 │
 ├── Main Business Flow
 │    ├── BSF001 – File & Column Validation
 │    ├── BSF002 – NSE Web Automation
 │    └── BSF003 – Send Mail
 │
 ├── Archive File
 ├── Screenshots Flow
 └── End / Cleanup

🗂️ Archives processed files

📸 Captures screenshots for audit & debugging
