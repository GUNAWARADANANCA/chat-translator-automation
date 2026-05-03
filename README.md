# Chat Translator Automation

## Project Description
This project tests the Singlish to Sinhala translation using automated testing.

## Objective
To validate the accuracy of Singlish to Sinhala translations and identify incorrect or unexpected outputs using automated testing.

## Tools Used
- Python
- Playwright
- OpenPyXL

## Project Structure
chat-translator-automation/
│
├── test_automation/
│   ├── test_automation.py
│   └── Assignment 1 - Test cases.xlsx
│
└── README.md

## How to Run

1. Install dependencies:
```bash
pip install playwright openpyxl
python -m playwright install
```

2. Run the script:
```bash
python test_automation/test_automation.py --excel "test_automation/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"
```

## Test Cases
- Total: 50
- Types: Short (S), Medium (M), Long (L)
- Focus: Negative testing (wrong translations)

## Output
- The script updates the Excel file with:
  - Actual Output
  - Pass/Fail Status
