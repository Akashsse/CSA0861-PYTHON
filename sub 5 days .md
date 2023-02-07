# CSA0861-PYTHON
import datetime

current_date = datetime.datetime.now().date()
five_days_ago = current_date - datetime.timedelta(days=5)

print("Current date:", current_date)
print("Five days ago:", five_days_ago)
