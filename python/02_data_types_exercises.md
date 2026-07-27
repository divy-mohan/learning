# Python Data Types Exercises (Hinglish) 🐍

Is file me aap har Python data type ke liye practice karenge. 
Aapko har type ke saath:
- ek simple example diya jayega
- phir beginner level exercises
- phir intermediate level exercises
- phir advanced level exercises

Is tarah aap apni coding skill ko basic se perfect tak develop kar sakte ho.

---

## 1. Integer (int) – Whole Numbers

### Example
```python
age = 25
print(age)
print(type(age))
```

### Practice Level 1 – Basic
1. Ek variable `num1` banaye aur usme 10 store karein.
2. Ek variable `num2` banaye aur usme 5 store karein.
3. In dono ka sum print karein.

### Practice Level 2 – Easy
1. `a = 15` aur `b = 7` banayein.
2. `a - b`, `a * b`, `a // b` print karein.
3. Check karein ki `a` aur `b` equal hain ya nahi.

### Practice Level 3 – Intermediate
1. Ek variable `marks` lein aur usme 88 store karein.
2. Agar marks 90 se zyada ho toh print karein: `"A Grade"`.
3. Agar marks 70 se zyada ho toh print karein: `"B Grade"`.

### Practice Level 4 – Intermediate + Logic
1. Ek program likhein jo user se `age` input le aur bataye ki wo `adult` hai ya `minor`.
2. `age >= 18` toh `adult`, warna `minor`.

### Practice Level 5 – Advanced
1. Ek simple calculator banayein jo integer values par kaam kare.
2. Add, subtract, multiply, divide aur modulus operator use karein.

---

## 2. Float (float) – Decimal Numbers

### Example
```python
price = 99.99
print(price)
print(type(price))
```

### Practice Level 1 – Basic
1. Ek variable `price` banayein aur usme `45.50` store karein.
2. Usko print karein.

### Practice Level 2 – Easy
1. `tax = 12.5` aur `total = 100.0` banayein.
2. In dono ko add karein.
3. Result print karein.

### Practice Level 3 – Intermediate
1. `discount = 10.25` aur `amount = 250.75` lein.
2. Final amount calculate karein.
3. `final_amount = amount - discount` print karein.

### Practice Level 4 – Intermediate + Input
1. User se `price` aur `quantity` input lein.
2. Total price calculate karein.
3. `total = price * quantity` print karein.

### Practice Level 5 – Advanced
1. Ek program likhein jo `height` aur `weight` le aur BMI calculate karein.
2. Formula: `BMI = weight / (height * height)`

---

## 3. String (str) – Text Data

### Example
```python
name = "Rahul"
print(name)
print(type(name))
```

### Practice Level 1 – Basic
1. Ek variable `name` banayein aur apna naam store karein.
2. Use print karein.

### Practice Level 2 – Easy
1. `greeting = "Hello"` banayein.
2. `name` ko add karke full message banao.
3. Example: `Hello Rahul`

### Practice Level 3 – Intermediate
1. Ek string `message = "Python is fun"` banayein.
2. `message.upper()` aur `message.lower()` use karein.
3. Check karein ki string me `Python` hai ya nahi.

### Practice Level 4 – Intermediate + Slicing
1. `word = "programming"` banayein.
2. First 3 characters print karein.
3. Last 4 characters print karein.
4. Middle part print karein.

### Practice Level 5 – Advanced
1. Ek program likhein jo user ka naam input le aur greeting print kare.
2. Example: `Hello, Rahul!`
3. Phir naam ka length count karein.

---

## 4. Boolean (bool) – True/False

### Example
```python
is_student = True
print(is_student)
print(type(is_student))
```

### Practice Level 1 – Basic
1. Ek variable `is_active` banayein aur `True` assign karein.
2. Use print karein.

### Practice Level 2 – Easy
1. `a = 10` aur `b = 20` banayein.
2. Check karein ki `a < b`.
3. Result print karein.

### Practice Level 3 – Intermediate
1. User se `age` input lein.
2. Check karein ki user adult hai ya nahi.

### Practice Level 4 – Intermediate + Logic
1. Ek program likhein jo bataye ki number even hai ya odd.
2. `number % 2 == 0` use karein.

### Practice Level 5 – Advanced
1. Ek login checker banayein.
2. Agar username aur password correct ho toh `True`, warna `False`.

---

## 5. List (list) – Ordered Collection

### Example
```python
fruits = ["Apple", "Banana", "Mango"]
print(fruits)
print(type(fruits))
```

### Practice Level 1 – Basic
1. Ek list `colors` banayein jisme 3 colors ho.
2. Print karein.

### Practice Level 2 – Easy
1. `numbers = [1, 2, 3, 4]` banayein.
2. Add karein `5` list me.
3. Print list.

### Practice Level 3 – Intermediate
1. `shopping_list = ["milk", "bread"]` banayein.
2. `"eggs"` add karein.
3. `"milk"` remove karein.
4. Final list print karein.

### Practice Level 4 – Intermediate + Loop
1. List ke har item ko loop se print karein.
2. Har item ke saath `-` add karke print karein.

### Practice Level 5 – Advanced
1. Ek list banayein jisme student names ho.
2. `append`, `remove`, `sort`, aur `len()` use karein.
3. Total items count print karein.

---

## 6. Tuple (tuple) – Immutable Collection

### Example
```python
point = (10, 20)
print(point)
print(type(point))
```

### Practice Level 1 – Basic
1. Ek tuple `days` banayein jisme `"Mon", "Tue", "Wed"` ho.
2. Print karein.

### Practice Level 2 – Easy
1. `coordinates = (5, 8)` banayein.
2. First value aur second value ko alag-alag print karein.

### Practice Level 3 – Intermediate
1. `person = ("Rahul", 21, "Delhi")` banayein.
2. Tuple unpacking use karke values print karein.

### Practice Level 4 – Intermediate + Logic
1. Tuple ko loop se iterate karein.
2. Har item ko print karein.

### Practice Level 5 – Advanced
1. Ek tuple banayein jisme 5 numbers ho.
2. Sum aur average calculate karein.

---

## 7. Set (set) – Unique Values

### Example
```python
skills = {"Python", "SQL", "Python"}
print(skills)
```

### Practice Level 1 – Basic
1. Ek set `colors` banayein jisme 3 colors ho.
2. Print karein.

### Practice Level 2 – Easy
1. Ek set me duplicate value add karein.
2. Dekhein ki duplicate automatically remove ho jata hai.

### Practice Level 3 – Intermediate
1. Do sets banayein: `set1` aur `set2`.
2. `union`, `intersection` aur `difference` use karein.

### Practice Level 4 – Intermediate + Logic
1. Ek set me student IDs store karein.
2. Check karein ki koi ID already present hai ya nahi.

### Practice Level 5 – Advanced
1. Ek program likhein jo two lists ko set me convert kare aur duplicate remove kare.

---

## 8. Dictionary (dict) – Key-Value Pairs

### Example
```python
student = {"name": "Rahul", "age": 20}
print(student)
print(type(student))
```

### Practice Level 1 – Basic
1. Ek dictionary `car` banayein jisme `brand` aur `color` ho.
2. Print karein.

### Practice Level 2 – Easy
1. `person = {"name": "Asha", "city": "Delhi"}` banayein.
2. `person["name"]` print karein.

### Practice Level 3 – Intermediate
1. Ek student dictionary banayein.
2. `name`, `age`, `marks` add karein.
3. `marks` update karein.

### Practice Level 4 – Intermediate + Loop
1. Dictionary ke keys aur values ko loop se print karein.
2. Har key-value pair ko alag line me print karein.

### Practice Level 5 – Advanced
1. Ek nested dictionary banayein jisme student ka profile ho.
2. Example: name, age, subjects.
3. Subject list print karein.

---

## 9. None – Empty / No Value

### Example
```python
result = None
print(result)
print(type(result))
```

### Practice Level 1 – Basic
1. Ek variable `data` banayein aur `None` assign karein.
2. Print karein.

### Practice Level 2 – Easy
1. Check karein ki variable `None` hai ya nahi.

### Practice Level 3 – Intermediate
1. Ek function likhein jo kuch return na kare aur `None` return kare.
2. Result print karein.

### Practice Level 4 – Advanced
1. `None` ko kisi condition me use karein.
2. Agar value `None` ho toh message print karein.

---

## 10. Bytes and Bytearray

### Example
```python
b = b"ABC"
print(b)
print(type(b))
```

### Practice Level 1 – Basic
1. Ek bytes object banayein.
2. Print karein.

### Practice Level 2 – Easy
1. `b = b"Hello"` banayein.
2. `len(b)` print karein.

### Practice Level 3 – Intermediate
1. Bytearray banayein.
2. Usme value add karein.
3. Print karein.

### Practice Level 4 – Advanced
1. Bytes ko decode karein aur string me convert karein.
2. Example: `b"Python".decode()`

---

## 11. Memoryview

### Example
```python
mv = memoryview(b"ABC")
print(mv)
print(type(mv))
```

### Practice Level 1 – Basic
1. Ek bytes object banayein.
2. Usko memoryview me convert karein.

### Practice Level 2 – Easy
1. `memoryview` ke values ko list me convert karein.
2. Print karein.

### Practice Level 3 – Advanced
1. Ek `memoryview` create karein.
2. Uske elements ko iterate karein.

---

## 12. Complex – Complex Numbers

### Example
```python
z = 4 + 3j
print(z)
print(type(z))
```

### Practice Level 1 – Basic
1. Ek complex number `z = 2 + 5j` banayein.
2. Print karein.

### Practice Level 2 – Easy
1. Ek aur complex number `y = 1 + 2j` banayein.
2. In dono ko add karein.

### Practice Level 3 – Intermediate
1. Complex numbers ka addition aur multiplication practice karein.

### Practice Level 4 – Advanced
1. Complex numbers ke saath simple math operations kar ke output dekhien.

---

## 🎯 Final Practice Challenge

Ab aapko in sab data types ko use karke ek mini project banana hai:

### Challenge 1 – Student Record System
1. Student ka `name`, `age`, `marks`, `passed` store karein.
2. `marks` integer ho.
3. `passed` boolean ho.
4. `subjects` list ho.
5. Student ka detail dictionary me ho.

### Challenge 2 – Shopping Cart
1. `product_name` string ho.
2. `price` float ho.
3. `quantity` integer ho.
4. `in_stock` boolean ho.
5. Cart list banayein.

### Challenge 3 – Unique Skills Tracker
1. User ke skills set me store karein.
2. Duplicate skills ignore ho.
3. Skills ko dictionary ya list ke saath print karein.

---

## ✅ Tips for Becoming Perfect

- Har exercise ko step-by-step solve karo.
- Har example ko apne words me samjho.
- Ek hi concept ko 5-10 baar practice karo.
- Errors ko dekh kar samjho.
- Small programs likh kar practice karo.
- Jab aap har type ko confidently use kar sakte ho, tab aap “developer” ban sakte ho.

---

## 💡 Bonus Homework

1. Ek program likhein jo user ka naam, age aur city input le.
2. In values ko dictionary me store karein.
3. Phir unhe print karein.
4. Isme `None` bhi use karke ek optional field add karein.

Agar aap chaho toh main is file ke liye next step me:
- answer key
- practice solutions
- quiz questions
- mini projects
bhi add kar sakta hoon.
