# Loan Qualifier Application

This is a python command-line interface application that allows users to see qualifying loans from lenders quickly and easily. The application works by taking in a `daily_rate_sheet` of loan criteria from various loan providers, asking the user a number of questions to evaluate their loan eligibility, and then returning to them a list of qualifying loans.

---

## Technologies

This project leverages Python 3.7 and the following libraries:

* [Fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [Questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogue.

---

## Installation Guide

Before running the application, first install the following dependancies:
```python
    pip install fire
    pip install questionary
```

---

## Usage
clone the repo by copying the link [here](git@github.com:danporeda/Loan_Qualifier.git), then open terminal, change the directory `cd` to the desired location, then command `git clone git@github.com:danporeda/Loan_Qualifier.git`. Run the app by commanding `python app.py`. You will be prompted with questions regarding your loan, which will then output the fitered results of the loans you qualify for. 

![CLI_input](https://github.com/danporeda/Loan_Qualifier/blob/main/Unsolved/screen_shot_loan_qualifier.png)

---

## Contributors

The project was brought to you by the talented instructors at Denver University Fintech bootcamp, and yours truly, Daniel Poreda.

---

## License

MIT
