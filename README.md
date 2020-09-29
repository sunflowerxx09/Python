print('Hello')

percent = 15
tax_rate = percent/100
print(tax_rate)

first_name = str(input('First Name: '))
last_name = str(input('Last Name: '))
print(last_name,',',  first_name)

pay_rate = float(input('Pay Rate: '))
total_hours = float(input('Hours Worked: '))
# regular hours = total hours if less than 40
# overtime = total hours - 40
regular_pay = 0
while True:
    if total_hours <= float(40):
        print(regular_pay)
        regular_pay = total_hours * pay_rate
    else:
        overtime_pay = ((total_hours - float(40))) * 1.5 * pay_rate
        print(overtime_pay)
