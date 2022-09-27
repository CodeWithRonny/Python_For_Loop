# Python For Loop
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
  ## Python For Loop Statement
  ```


van = ["suv", "nano", "bolero", "Bus"]
for x in van:
	if x == "nano":
		continue
	print(x)
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

## for loop with else
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
## Nested For Loop
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
