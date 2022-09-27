# Python For Loop
# What is FOR LOOP?
In computer programming, a loop is a sequence of instructions that is continuously repeated until a certain condition is reached. Typically, a certain process is done.
In python FOR loop is used to iterate over a sequence data type like list, tuple, dictionary, set and string until last item. 
```
for x in "LOOPBREAK":
	print(x)

van = ["suv", "nano", "bolero"]
for item in van:
	print(item)
  ```
 # Python Statement
 ### break
### pass
### continue
  ## Python For Loop Syntax
  ```
for item in object:
    LOOP Body
```
```
for value in sequence:
    LOOP Body
```
## Python For Loop Break Statement

```
van = ["suv", "nano", "bolero", "Bus"]

for x in van:
	if x == "Bus":
		break
	print(x)
```

## Python For Loop Pass Statement
```
#Pass Statement

van = ["suv", "nano", "bolero", "Bus"]
for x in van:
	pass
```
## Python For Loop Continue Statement
```
van = ["suv", "nano", "bolero", "Bus"]
for x in van:
	if x == "nano":
		continue
	print(x)
```
## Python For Loop With Range
```
# Range Function Syntax
range function
range(stop)
range(start, stop, step)
```
### with one argument
```
for x in range(11):
	print(x)
```
### with two arguments
```
for x in range(1, 11):
	print(x)
```
### 3 arguments
```
for x in range(2, 21, 2):
	print(x)
for x in range(3, 31, 3):
 	print(x)
```

## Python For Loop With Else
### Python For Loop With Else Syntax
```
for item in object:
    LOOP Body
else:
	ELSE Body
```
```
for value in sequence:
    LOOP Body
else:
	ELSE Body

```
### for loop with else 
```
for x in "LOOP":
	print(x)
else:
	print("Finally loop breaked")
```
```
my_fruit_basket = ["Mango", "Orange", "Banana"]
for fruit in my_fruit_basket:
	print(fruit)
else:
	print("Basket is empty now")
```
## Python Nested For Loop
### Python Nested For Loop Syntax
```
for items in object:
	for item in items:
    	LOOP Body
else:
	ELSE Body
```
```
for values in sequence:
	for value in values:
		LOOP Body
else:
	ELSE Body
```
### Nested For Loop
```
van = ["Maruti", "nano", "Suzuki"]
for x in van:
	print(x)
	for y in x:
		print(y)
else:
	print("Loop stopped")
```
```
for x in "LOOP":
	print(x)
	for y in x:
		print(y)
else:
	print("Loop stopped")
```

```
for x in ["Maruti", "nano", "Suzuki"]:
	print(x)
	for y in x:
		print(y)
else:
	print("Loop stopped")
```
