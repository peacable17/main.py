# main.py
#Week 3 Sales Tax Homework

user_amt = input()
tax_state = float(user_amt) * 0.05
tax_county = float(user_amt) * 0.025
tax_total = tax_state + tax_county
sale_total = float(user_amt) + float(tax_total)

print('Your purchase amount:',user_amt)
print('State sales tax:',tax_state)
print('County sales tax:',tax_county)
print('Total tax:',tax_total)
print('Total cost:',sale_total)
