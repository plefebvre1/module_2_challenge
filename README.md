# Loan Qualifier Application

This is a python command-line interface application that allows users to see qualifying loans from lenders quickly and easily. The application works by taking in a `daily_rate_sheet` of loan criteria from various loan providers, asking the user a number of questions to evaluate their loan eligibility, and then returning to them a list of qualifying loans.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs
---

## Installation Guide

The application uses fire and questionary dictionaries. Please install them before running the application.

```python
  pip install fire
  pip install questionary
```

---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```

Upon launching the loan qualifier application you will be greeted with the following prompts.

![Loan Qualifier App](images/Qualifying_Loans_SS.png)
---

## Contributors

Starter code for this app was provided by the GWU Fintech Bootcamp program. Updates to that code to fulfill the given user story were done by Peter Lefebvre (peter.c.lefebvre@gmail.com)

---

## License

MIT License
