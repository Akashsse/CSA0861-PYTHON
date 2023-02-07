# CSA0861-PYTHON
from datetime import date

def days_between(date1, date2):
    date1 = date(*map(int, date1.split('-')))
    date2 = date(*map(int, date2.split('-')))
    delta = date2 - date1
    return delta.days

date1 = input("Enter a date in YYYY-MM-DD format: ")
date2 = input("Enter a second date in YYYY-MM-DD format: ")

print("There are", days_between(date1, date2), "days between", date1, "and", date2)
