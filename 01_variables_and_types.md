# Lesson 01: Variables & Data Types

## 🎯 Aaj Hum Kya Seekhenge?

1. **Variable kya hota hai?**
2. **Data Type kya hota hai?**
3. **`type()` function kya karta hai?**
4. **Type Casting kya hoti hai?**

---

## 📦 1. Variables

**Variable ek naam wala box hota hai.** Hum is box me koi bhi value rakh sakte hain.

### Example:
```python
Name = "Divy Mohan"
Age = 22
```

```
[ Name Box ]  --->  "Divy Mohan"
[ Age Box  ]  --->  22
```

### Syntax:
```python
variable_name = value
```

### Example:
```python
name = "Rahul"
age = 20
```

> [!NOTE]
> **Kab use karte hain?**  
> Jab kisi value ko future me dobara use karna ho.

---

## 🗂️ 2. Data Types

**Har value ka ek type hota hai.** Python ko pata hona chahiye ki value Text hai, Number hai, ya True/False (Boolean) hai.

### Common Data Types:

| Data Type | Description | Example |
| :--- | :--- | :--- |
| **`str`** | Text (String) | `"Hello"`, `"Divy"` |
| **`int`** | Whole Number (Integer) | `100`, `-5` |
| **`float`** | Decimal Number | `99.5`, `3.14` |
| **`bool`** | True / False (Boolean) | `True`, `False` |

---

## 🔍 3. `type()` Function

**`type()` function batata hai ki variable kis type ka hai.**

### Syntax:
```python
type(variable)
```

### Example:
```python
age = 12
print("The Value of Age is", age)
print(type(age))
```

**Output:**
```python
The Value of Age is 12
<class 'int'>
```

---

## 🔄 4. Type Casting

Kabhi-kabhi hume ek data type ko dusre data type me badalna padta hai. **Isi ko Type Casting kehte hain.**

### Common Functions:

*   **`int()`** $\rightarrow$ String ya Float ko Integer banata hai.
*   **`float()`** $\rightarrow$ Integer ya String ko Float banata hai.
*   **`str()`** $\rightarrow$ Kisi bhi value ko String banata hai.
*   **`bool()`** $\rightarrow$ Value ko `True` ya `False` me convert karta hai.

### Examples:
```python
marks = 22.35

print("Marks = ", marks)
print("Data type of", marks, "is", type(marks))

# Float to Integer conversion
whole_marks = int(marks)
print("The complete marks of Pooja are : ", whole_marks)
print("Data type of", whole_marks, "is", type(whole_marks))
```

> [!TIP]
> **Example Conversion:**  
> String `"100"` $\rightarrow$ `int("100")` $\rightarrow$ Integer `100`

---

## ⚡ Quick Recap

*   **Variable** = Value store karne ka box.
*   **`str`** = Text.
*   **`int`** = Whole Number.
*   **`float`** = Decimal Number.
*   **`bool`** = True / False.
*   **`type()`** = Type check karta hai.
*   **`int()`, `str()`, `float()`, `bool()`** = Type change karte hain.

---

## 📝 Practice Questions

### 🟢 Level 1 (Easy)

#### Q1. Ek variable `name` banao aur usme apna naam store karo.
**Expected Output:**
```
My Name is Pooja
```

#### Q2. Ek variable `age` banao aur usme apni age store karo.
**Expected Output:**
```
I am 22 years old.
```

#### Q3. Ek variable `city` banao aur usme apne city ka naam store karo.
**Expected Output:**
```
I live in Sitapur.
```

#### Q4. Ek variable `college` banao aur usme apne college ka naam store karo.
**Expected Output:**
```
I study at IIT Madras.
```

#### Q5. Ek variable `pi` banao aur usme value `3.14` store karo aur uska Data Type print karo.

---

### 🟡 Level 2 (Data Types)

#### Q6. Neeche diye gaye values ka Data Type print karo:
*   `100`
*   `25.75`
*   `"Python"`
*   `True`
*(Hint: Use `type()`)*

#### Q7. Ek variable `salary` me value `45000` store karo aur uska Data Type print karo.

#### Q8. Ek variable `temperature` me value `36.7` store karo aur uska Data Type print karo.

#### Q9. Ek variable `is_student` banao aur usme `True` store karo aur uska Data Type print karo.

---

### 🟠 Level 3 (Type Casting)

#### Q10. String `"500"` ko Integer me convert karo aur uska Data Type print karo.

#### Q11. Float `99.99` ko Integer me convert karo. Output kya hoga?

#### Q12. Integer `25` ko String me convert karo aur uska Data Type print karo.

#### Q13. String `"45.67"` ko Float me convert karo. Output aur Data Type print karo.

---

### 🔵 Level 4 (Input)

#### Q14. User se Name input lo aur print karo.
**Example:**
```
Enter Your Name : Rahul
Welcome Rahul
```

#### Q15. User se Age input lo aur print karo.
**Example:**
```
Enter Age : 20
Your Age is 20
```

#### Q16. User se Number input lo aur uska Square print karo.
**Example:**
```
Enter Number : 8
Square is 64
```

---

### 🔴 Level 5 (Think & Solve)

#### Q17. Ek variable `a = 10` aur `b = 20` banao aur dono ko print karo.

#### Q18. Teen variables banao (`name`, `age`, `city`) aur niche diya gaya output print karo:
```
My name is Rahul.
I am 20 years old.
I live in Delhi.
```

#### Q19. Ek Float value store karo, usse Integer me convert karo, aur original aur converted value dono print karo.

#### Q20. User se ek Number input lo, uska Data Type print karo, uske baad usse Integer me convert karke fir se Data Type print karo.

---

## 🏆 Challenge Questions

### Challenge 1
User se apna Name aur Age lo aur is format me output do:
```
Hello Rahul!
You are 20 years old.
```

### Challenge 2
Ek variable me apna Favourite Programming Language store karo aur uska Data Type print karo.

### Challenge 3
Ek variable me Decimal Number store karo, usko Integer me convert karo, aur fir dono values compare karo.

### Challenge 4
User se Decimal Number input lo aur usko Integer me convert karke print karo.

### Challenge 5 ⭐
Ek hi program me ye sab variables banao:
*   Name
*   Age
*   Height
*   Is Student

Sabki Value aur Data Type ek saath print karo.
