# Fundamentals: Exercises

_We will correct these exercises in class._

## Exercise 1

```js
// Look at these expressions below and determine whether they evaluate to true or false

1. true || false 
    A. true
2. false && false
    A. false
3. 1 < 2 && 2 > 1
    A. true
4. 31 < 13 || 1 < 2 && 3 > 1
    A. true  
5. 400 <= 400 && 399 < 400 && (30 > 31 || 400 > 31)
    A. true 
6. true && false && false || false && true
    A. false
7. true && false || true || false
    A. true
8. true && false && false || false && true ? true && false && false || false && true : 1 < 2 && 2 > 1
    A. true
```

---

## Exercise 2

Given this data structure:

```js
let data = [0, [], [], [1, 2, 3, [4]]];
```

1. How would you access the value `0`?
`data[0]`
2. How would you access the value `3`?
`data[3][2]`
3. How would you access the value `4`?
`data[3][3][0]`

---

## Exercise 3

- List the number of properties for each object.
- For each property, indicate its key and its value.
- For each property value, indicate its type.

```js
{ label: 'corn', price: 5.3 + '$' };
This object has 2 properties:
-It has a property with name `label` and value of `'corn'` of type string.;
-It has a property with name `price` and value of `'5.3$'` of type string.
{ ISBN: 53532, isAvailable: true, author: 'Nakamoto' };
This object has 3 properties:
-It has a property with name `ISBN` and value of `53532` of type number.;
-It has a property with name `isAvailable` and value of `true` of type boolean.;
-It has a property with name `author` and value of `'Nakamoto'` of type string.;
```

---

## Exercise 4

```js
// Given
let person = { name: 'Bob', age: 23 };
let name = 'John';
```

What is the value of the following expressions?

1. person.name is 'Bob'
2. person['name'] is 'Bob'
3. person[name] is unidentified

---

## Exercise 5

```js
// Given
let person = { name: 'Bob', age: 23 };
let key = 'name';
```

What is the value of the following expressions:

1. person.key is unidentified
2. person['key'] is unidentified
3. person[key] is 'Bob'
