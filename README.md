# STRING and NUMBERS

### What is a Method in JavaScript?
+ A method is a block of code which only runs when
it is called. You can pass data, known as
parameters, into a method. Methods are used to
perform certain actions, and they are also known
as functions.

### How many tyoe of string we have in JavaScript
1.  Double quotes
```javaSript
"Hello world!"
```
2.  Single quotes
```javaSript
'Hello world!'
```
3.  Backticks
```javaSript
 'hello ${hi}'
```



### string methods in JavaScript
1. charAt()
2. at()
3. concat()
4. trim()
5. includes()
6. indexOf()
7. replace(), replaceAll()
8. repeat()
9. slice()
10. substring()
11. split()
12. toString()
13. toLowerCase()
14. toUpperCase()

```javascript
let str = "Hello, World!";
```
```javascript
let slicedStr = str.slice(0, 5);
```
```javascript
let substringStr = str.substring(7, 12);
```
```javascript
let substrStr = str.substr(7, 5);
```
```javascript
  let replacedStr = str.replace("World", "JavaScript");
```
```javascript
let replaceAllStr = "Hello, World! World!".replaceAll("World", "JavaScript");
```
```javascript
let upperStr = str.toUpperCase();
```
```javascript
lowerStr = str.toLowerCase();
```
```javascript
let concatStr = str.concat(" How are you?");
```
```javascript
let trimmedStr = "   Hello, World!   ".trim()
```
+ The charAt() method returns the character at a specified index (position) in a string.
The index of the first character is 0, the second 1, ...
The index of the last character is string length - 1 .

+ The at() method takes an integer value and returns a new String.
This method allows for positive and negative integers. Negative
integers count back from the last string character.

+ The concat() method joins two or more strings.
The concat() method returns a new string.
The concat() method does not change the original string.

+ The concat() method joins two or more strings.
The concat() method returns a new string.
The concat() method does not change the original string.

+ The replaceAll() method returns a new string with all matches of a pattern replaced by
a replacement.

+ The split() method splits a string into an array of substrings. The split() method
returns the new array. The split() method does not change the original string. If (" ") is
used as separator, the string is split between words. 

+ The substring() method extracts characters, between two indices (positions), from a string, and
returns the substring.
The substring() method extracts characters from start to end (exclusive).
The substring() method does not change the original string.
If start is greater than end, arguments are swapped: (4, 1) = (1, 4).
Start or end values less than 0, are treated as 0.

+ The slice() method returns a shallow copy of a portion of an array and string into a new array object
selected from start to end ( end not included) where start and end represent the index of items in
that array.

### number method in JavScript
+ JavaScript provides several methods to work with numbers. Here are some of the most commonly used number methods:

toString():
+ Converts a number to a string.
toExponential(fractionDigits):
+ Converts a number to exponential notation.
toFixed(digits): 
Formats a number using fixed-point notation.
toPrecision(precision):
+ Formats a number to a specified length.
valueOf(): 
+ Returns the primitive value of a number.
Number.isInteger(value):
+ Checks if a value is an integer.
Number.isNaN(value):
+ Checks if a value is NaN (Not-a-Number).
Number.parseFloat(string): 
+ Parses a string and returns a floating-point number.
Number.parseInt(string, radix):
+ Parses a string and returns an integer of the specified radix (base).
Number.isFinite(value): 
Checks if a value is a finite number.


```javascript
let num = 123.456;


let strNum = num.toString();


let expNum = num.toExponential(2); 


let fixedNum = num.toFixed(2); 


let precisionNum = num.toPrecision(5); 


let valueNum = num.valueOf();


let isInteger = Number.isInteger(num); /


let isNaN = Number.isNaN(NaN);


let floatNum = Number.parseFloat("123.456"); 


let intNum = Number.parseInt("123", 10); 


let isFiniteNum = Number.isFinite(num); 
```



