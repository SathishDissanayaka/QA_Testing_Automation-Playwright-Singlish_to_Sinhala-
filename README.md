📌 Overview

This project implements an automated functional testing framework for the Singlish-to-Sinhala transliteration system available on Swift Translator.
It is developed to evaluate translation accuracy, system behavior, and UI functionality through structured test automation.

The solution uses Playwright with Node.js and follows industry-standard QA practices, covering positive, negative, and UI test scenarios. Test cases are data-driven and executed automatically to ensure consistency, reliability, and repeatability.

⚙️ Key Features

📊 Data-driven testing using Excel

🧪 Automated execution of functional, negative, and UI test cases

🔄 Real-time input submission and output capture

✅ Automatic comparison of expected vs actual results

📝 Test results written back to an Excel report

🚀 Fast, repeatable, and scalable test execution using Playwright

🗂️ Structure
QA Test Automation/
 ├── SinhalaAutomation/        # Playwright test scripts and configuration
 ├── Test_Cases.xlsx           # Input Excel file containing test cases
 ├── Testing_results.xlsx      # Auto-generated Excel file with test results
 └── README.md                 # Project documentation

🧩 How the Automation Works

Reads test cases from Test_Cases.xlsx

Automatically inputs Singlish text into the Swift Translator UI

Captures the generated Sinhala output in real time

Compares actual output against expected output

Records pass/fail status and remarks in Testing_results.xlsx

🛠️ Prerequisites

Ensure the following are installed on your system:

Node.js (version 18 or higher)

npm (version 9 or higher)

Playwright testing framework

📥 Installation & Setup
1️⃣ Clone the Repository
git clone <your-g
