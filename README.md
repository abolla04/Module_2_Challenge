# Loan Qualifier Application

This is a python application that quickly allows a user to determine their loan eligibility based on a series of qualiers.  The application references a 'daily_rate_sheet' to return a list of the applicable loans.  The user then has the option to save the output file to a designated location.

---

## Technologies

*[csv] - (https://docs.python.org/3/library/csv.html) used to create output file
*[sys] - (https://github.com/golang/sys) - used to exit after command
*[fire] - (https://github.com/google/python-fire) - used for generating CLIs from Python 
*[questionary] - (https://github.com/search?l=Python&q=questionary&type=Repositories) - used for *interactive user responses
*[pytest] - (https://docs.pytest.org/en/6.2.x/) - used to test file saving, calculators and fileio

---

## Installation Guide

To run this application, the following will need to be installed:

'''python
    pip install fire
    pip install questionary
    pip install pytest
    pip install mkdocs

---

## Examples

This section should include screenshots, code blocks, or animations showing how your project works.

---

## Usage

This loan qualifier application can be used by cloning the repository and running the **app.py** with
'''python
python app.py
'''
When the application runs, there will be a series of user prompts.
![Loan Qualifier Prompts](loan_qualifier_no_loans.png)
![Loan Qualifier Prompts](loan_qualifier_19_loans.png)

---

## Contributors

This application was brought to you by ABOLoans

---

## License

MIT
