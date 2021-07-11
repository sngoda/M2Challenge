# Qualifying Loans (M2 Challenge) 

This is a Qualifying Loans application. 

Given a set of available loans from multiple financial instituitions, select the loans that are available to a qualified customer. In a very few easy steps, loan seeker can answer questions about his/her financial status and be provided with available loans from financial instituitions in a file specified by customer while answering questions.

It is as simple as that.

## Technologies

Describe the technologies required to use your project such as programming languages, libraries, frameworks, and operating systems. Be sure to include the specific versions of any critical dependencies that you have used in the stable version of your project.

Python3 is used to build the application. Lists (Lists of Lists), file io and questionary packages are utilized to fulfil the requirements.

## Installation Guide

Download source code
Goto the directory, M2Challenge
Run, python3 app.y for application
Run, python3 tests/test_qualifier.py for unit tests

## Examples

This section should include screenshots, code blocks, or animations showing how your project works.

---
cd M2Challenge
~/m2c/M2Challenge$ python3 app.py 
? Enter a file path to a rate-sheet (.csv): data/daily_rate_sheet.csv
Path is, data/daily_rate_sheet.csv
PWD is, /home/srini/FinTech/Homeworks/Week2/Starter_Code/qualifier
? What's your credit score? 895
? What's your current amount of monthly debt? 5000
? What's your total monthly income? 15000
? What's your desired loan amount? 350000
? What's your home value? 1500000
The monthly debt to income ratio is 0.33
The loan to value ratio is 0.23.
Found 9 qualifying loans
? Enter the csv filename to save with complete path:  data/qualifying_loans.csv
qualifying loans is,
 [['West Central Credit Union - Premier Option', '400000', '0.9', '0.35', '760', '2.7'], ['FHA Fredie Mac - Premier Option', '600000', '0.9', '0.43', '790', '3.6'], ['FHA Fannie Mae - Premier Option', '500000', '0.9', '0.47', '780', '3.6'], ['General MBS Partners - Premier Option', '400000', '0.95', '0.35', '790', '3.0'], ['iBank - Premier Option', '500000', '0.85', '0.46', '780', '3.15'], ['Goldman MBS - Premier Option', '500000', '0.8', '0.4', '770', '3.6'], ['Citi MBS - Premier Option', '400000', '0.9', '0.47', '780', '3.6'], ['Prosper MBS - Premier Option', '400000', '0.85', '0.42', '750', '3.45'], ['Bank of Stodge & Stiff - Premier Option', '500000', '0.9', '0.41', '790', '3.15']]


## Usage

python3 app.py
python3 tests/test_qualifier.py

## Contributors

Team Bootcamp

## License

GPL
