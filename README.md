# algorithms-task

import random

numbers = []

for i in range(0,6):

  n = random.randint(1,30)
  
  numbers.append(n)
  
print("your numbers are",numbers)

bonus = random.randint(1,49)

print("and your bonus ball is", bonus)

