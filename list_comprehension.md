# list comprehension
## how this works is instead of:
### new_num = []
### for i in range (1,5):
###   new_num = i * 2 
## output will be: [2,4,6,8]
# we can do this called as list comprehension
## new_num = [i*2 for i in range(1,5)], this single line of code will give us the same o/p and we don't have to write many lines of code.
## ex2: 
name = "King"
name_in_single_letters = [n for n in name]
this will give output as 'K' 'i' 'n' 'g'