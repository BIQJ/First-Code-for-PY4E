# First-Code-for-PY4E
# try to finish the first test for PY4E in coursera work 
# This code can be used in the last assignment of the section one from Michigan University 's online course on coursera,
# which name Python for everyone.
largest = None
smallest = None
while True:
        num = input('Enter a number:')
        if num == "done":
            break
        try:
            number = int(num)
        except:
            print('Invalid input')
        if largest == None:
            largest = number
        if number > largest:
            largest = number
        if smallest == None:
            smallest = number
        if number < smallest:
            smallest = number
print('Maximum is',largest)
print('Minimum is',smallest)
