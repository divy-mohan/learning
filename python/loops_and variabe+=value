# Python Code Explanation (Hinglish)

## Original Code

``` python
def lcm(number):
    for divisor in range(2, number + 1):
        while number % divisor == 0:
            print(f"{divisor} | {number}")
            number = int(number / divisor)
    print("    1")
    print("LCM ka result upar likha hua hai")

x = int(input("LCM nikalne ke liye number daalo: "))
lcm(x)
```

> **Important Note:** Ye function asal mein **LCM (Least Common
> Multiple)** nahi nikal raha. Ye **Prime Factorization** dikhata hai.
> Function ka naam `prime_factorization` hona zyada sahi hota.

------------------------------------------------------------------------

# Line by Line Explanation

## `def lcm(number):`

-   `def` ka matlab **define** hota hai.
-   Is line se Python ko bataya ja raha hai ki hum ek function bana rahe
    hain.
-   `number` ek parameter hai.
-   Jab function call hoga tab jo value doge wahi `number` ban jayegi.

Example:

``` python
lcm(60)
```

toh function ke andar

``` python
number = 60
```

------------------------------------------------------------------------

## `for divisor in range(2, number + 1):`

Ye loop 2 se lekar `number` tak chalega.

Agar number = 12 hai

``` python
range(2,13)
```

banega

    2
    3
    4
    5
    6
    7
    8
    9
    10
    11
    12

Har baar ek naya divisor milega.

------------------------------------------------------------------------

## `while number % divisor == 0:`

Yeh sabse important line hai.

`%` remainder (shesh) operator hai.

Example:

    12 % 2 = 0

Matlab 12 completely divide ho gaya.

    12 % 5 = 2

Matlab divide nahi hua.

Isliye jab tak remainder 0 hai tab tak repeatedly divide karte rahenge.

Example:

    72
    ↓ ÷2
    36
    ↓ ÷2
    18
    ↓ ÷2
    9

Teen baar 2 divide hua.

Agar yahan `if` use karte to sirf ek baar divide hota.

------------------------------------------------------------------------

## `print(f"{divisor} | {number}")`

Ye sirf display ke liye hai.

Example:

    2 | 72
    2 | 36
    2 | 18

f-string ke andar variables automatically print hote hain.

------------------------------------------------------------------------

# Sabse Important Line

``` python
number = int(number / divisor)
```

Is line ko bahut dhyan se samjho.

Suppose

    number = 72
    divisor = 2

Python pehle right side calculate karta hai.

    72 / 2

Result

    36.0

Dhyan do ki `/` operator **float** return karta hai.

Isliye

    72 / 2

banta hai

    36.0

Ab

``` python
int(36.0)
```

ban gaya

    36

Fir

    number = 36

Ab purani value **replace** ho gayi.

Pehle

    number = 72

tha.

Ab

    number = 36

hai.

Isi ko assignment kehte hain.

Iska matlab

> Right side calculate karo, phir result left side wale variable me
> store kar do.

------------------------------------------------------------------------

## Memory View

Pehle

    number
     ↓
    72

After assignment

    number
     ↓
    36

72 memory se delete nahi hota turant, bas variable usko point karna band
kar deta hai.

------------------------------------------------------------------------

## Agar ye line na hoti

Suppose code hota

``` python
while number % divisor == 0:
    print(number)
```

Toh

    number

kabhi change hi nahi hota.

72 hamesha 72 hi rehta.

Condition

    72 % 2 == 0

hamesha True rehti.

Infinite loop ban jata.

Isi liye andar

``` python
number = int(number/divisor)
```

likhna zaroori hai.

------------------------------------------------------------------------

# Ye line loop ke ANDAR hi kyun hai?

Galat:

``` python
while number % divisor == 0:
    print(number)

number = int(number/divisor)
```

Yahan problem:

Loop kabhi khatam hi nahi hoga.

Kyunki number change hi nahi hua.

Sahi:

``` python
while number % divisor == 0:
    print(number)
    number = int(number/divisor)
```

Har iteration ke baad number chhota hota ja raha hai.

Example

    72
    ↓
    36
    ↓
    18
    ↓
    9

Ab

    9 % 2 = 1

Condition False.

Loop ruk gaya.

------------------------------------------------------------------------

# Why `while` is inside `for`?

`for` ka kaam:

Har possible divisor check karna.

    2
    3
    4
    5
    6...

`while` ka kaam:

Ek hi divisor se jitni baar divide ho sakta hai utni baar divide karna.

Example

60

For divisor = 2

    60
    ↓
    30
    ↓
    15

Ab 15 divisible nahi.

Then for loop next divisor 3 pe chala jayega.

    15
    ↓
    5

Fir divisor 5

    5
    ↓
    1

------------------------------------------------------------------------

# Last Lines

``` python
print("    1")
```

Prime factorization complete hone ke baad last me 1 print karte hain.

``` python
print("LCM ka result upar likha hua hai")
```

Ye sirf message print kar raha hai.

Actually result prime factors ke form me upar print hua hota hai.

------------------------------------------------------------------------

# Complete Dry Run (Input = 60)

Start

    number = 60

divisor = 2

    60 →30 →15

divisor = 3

    15 →5

divisor = 5

    5 →1

Output

    2 | 60
    2 | 30
    3 | 15
    5 | 5
        1

Prime factors:

    60 = 2 × 2 × 3 × 5

------------------------------------------------------------------------

# Summary

-   `for` → har divisor check karta hai.
-   `while` → ek divisor ko baar-baar use karta hai.
-   `%` → divisibility check karta hai.
-   `number = int(number/divisor)` → number ki purani value ko naye
    divided value se replace karta hai.
-   Ye line loop ke andar isliye hai taaki number continuously chhota
    hota rahe aur loop kabhi infinite na ho.
-   Function ka naam `lcm()` hai, lekin ye actually **prime
    factorization** karta hai.
