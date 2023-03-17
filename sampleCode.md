# Sample Code

This is a python script that I used for the **List and Loops challenge** in my IT1000 class
```
values = [6, 5, 3, 8, 4, 2, 5, 4, 11, 43, 1, 17, 27, 90, 77, 62, 51, 47, 82, 86, 20]

amount_of_nums = len(values)
print(f"The list has {amount_of_nums} numbers\n")

values_sum = sum(values)
print(f"The sum of the values in the list is {values_sum}\n")

average = values_sum / amount_of_nums
print(f"The average of the values in the list is {average}\n")

print("Printing every value in the list with it's index")

index = 0
count = -1
item = -1
while index < amount_of_nums:
    count += 1
    item += 1
    print(f"Item {item}: {values[count]}")
    index += 1

print("\nPrinting every other value in the list with it's index")

for x in range(0, 21, 2):
    print(f"Item {x}: {values[x]}")
   
print("\nBonus: finding whether the number is even or odd")

item = -1
for i in values:
    if (i % 2) == 0:
        print(f"{i} is even")
    else:
        print(f"{i} is odd")
        
```

[<-Back](./README.md)
