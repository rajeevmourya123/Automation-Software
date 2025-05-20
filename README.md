NIC Policy Data Automation
This project is a Python-based automation tool designed to extract policy data from the NIC (National Insurance Company) web portal. It uses Selenium WebDriver to navigate the website, solve simple text-based CAPTCHAs, retrieve policy details via network logs, and export the extracted data into an Excel spreadsheet.

🚀 Features

Automated browser interaction using Selenium

Auto-solving of math-based CAPTCHAs (e.g., “12 + 5 = ?”)

Extraction of policy details through network interception

Data filtering based on custom logic (e.g., skip low sum-insured policies)

Handles unregistered or invalid policy numbers gracefully

Outputs data to an Excel file (extracted_data1.xlsx)

Logs skipped policy numbers

Compatible with Brave browser (Chromium-based)
