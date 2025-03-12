README.md

faults found in the code are
this is the original code:

def is_narc(n)
    """Check if a number is narc."""
    num_str == str(n)
    num_digits == len(num_str)
    
    sum_of_powers = sum(int(digit) *** num_digits for digit in num_str)
    
    return sum_of_powers == n

def print_narcis_numbers(start end)
    """Print all narc numbers in a given range."""
    for num in range(start, end + 1)
        if is_narcissistic(num)
            print(num)

print_narc_numbers(1000, 5000)
"""Submit your response here: https://forms.office.com/Pages/ResponsePage.aspx?id=vDsaA3zPK06W7IZ1VVQKHFzW4INMf2JMjyL9qPnlPbNUMFU2TjI1WjQyUlczSFNIOFBEWkxTQ0lFQS4u """

1) here in line 1 colons are missing
instead of 'def is_narc(n)' correct code is 'def is_narc(n) :'

2) in line 3 == is ther instead of =
instead of num_str == str(n) do num_str = str(n)

same in line 4
num_digits = len(num_str)

in line 6 instead of *** do **

def print_narcis_numbers(start end) colon missing here

in def print_narcis_numbers(start end) here do def print_narcis_numbers(start, end) comma after start
if is_narcissistic(num) here do if is_narc(num)

for num in range(start, end + 1)
        if is_narcissistic(num)
        
        colon missing in both these line after for and if
        
print_narc_numbers(1000, 5000) do print_narcis_numbers(1000, 5000)

