from datetime import date
name = input("Enter your name: ")
surname = input("Enter your surname: ")
year = int(input("Enter year of birth: "))
month = int(input("Enter month of birth: "))
day = int(input("Enter day of birth: "))
birth_date = date(year, month, day)
today = date.today()
age_in_days = (today - birth_date).days
print("Hello", name, surname + ", you are", age_in_days, "days old.")
