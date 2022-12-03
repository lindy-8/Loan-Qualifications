# Saving Qualifying Loans App

This a python oriented CLI (command line interface) challenge that will enable the respective users with access to view a list of qualified loans. This is completed through the utilization and analysis of data within the 'daily_rate_sheet' that contains information regarding loan criteria requested from loan providers. Then is will then prompt a little questionaire that needs to be filled out to fully evaluate their loan elidgability, which then returns them to a list of loans that they are qualified for. 

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

To use the Saving Qualifying Loans application simply clone the repository and run the **app.py** with:
```git clone
git@github.com:"username"/"repository name".git
```
```python
python app.py
```

Upon launching the app it is required to download and install both programs to properly run the app. Then will be welcomed with the following prompts.

![Screenshot](Evidence_Image.png)

---

## Contributors

Starter code for this app was provided by the DU Fintech Bootcamp program. 

---

## License

MIT License
