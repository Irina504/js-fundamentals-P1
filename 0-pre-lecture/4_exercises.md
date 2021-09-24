# Fundamentals: Exercises

_We will correct these exercises in class._

## Exercise 1

```js
// Look at these expressions below and determine whether they evaluate to true or false

1. true || false  (true)
2. false && false (false)
3. 1 < 2 && 2 > 1 (true)
4. 31 < 13 || 1 < 2 && 3 > 1 (true)
5. 400 <= 400 && 399 < 400 && (30 > 31 || 400 > 31) (false)
6. true && false && false || false && true (true)
7. true && false || true || false (true)
8. true && false && false || false && true ? true && false && false || false && true : 1 < 2 && 2 > 1 (true)
```

---

## Exercise 2

Given this data structure:

```js
let data = [0, [], [], [1, 2, 3, [4]]];
```

1. How would you access the value `0`? anArray[0]
2. How would you access the value `3`? anArray[1]
3. How would you access the value `4`? anArray[2]

---

## Exercise 3

- List the number of properties for each object.
- For each property, indicate its key and its value.
- For each property value, indicate its type.

```js
{ label: 'corn', price: 5.3 + '$' };

- List the number of properties for each object: 2
- For each property, indicate its key:(label, price) and its value:('corn',5.3$) 
- For each property value, indicate its type: (string, string)

{ ISBN: 53532, isAvailable: true, author: 'Nakamoto' }; 

- List the number of properties for each object: 3
- For each property, indicate its key:(ISBN,isAvailable,author) and its value:(53532,true,'Nakamoto') 
- For each property value, indicate its type: (number, boolean,string)
```

---

## Exercise 4

```js
// Given
let person = { name: "Bob", age: 23 };
```

What is the value of the following expressions?

1. person.name   ("Bob")
2. person['name'] ("Bob")
3. person[name]  (?)
