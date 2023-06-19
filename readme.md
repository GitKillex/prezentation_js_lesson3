<h1 align = 'center'>METHOD</h1>

## Method - is a  block of code which only runs when it called. You can pass data known as parameters, into a method. Methods are used to perform certain actions and they are also known as functions 

___

<h1 align = 'center'>CREATING OF STRING</h1>

### There're 3 methods of creating string!

1. "Double Quotes"
2. 'Single Quotes'
3. `Backticks`

___

<h1 align = 'center'>STRING - METHODS</h1>

## The `charAt()` method returns the character at a specified index (position) in a string. The index of the first character is 0, the second 1.

1. `.charAt()`
```javascript
    let str = 'Hello world!'
    console.log(str.charAt(0)) // H
```

## The `concat()` method joins two or more strings.The `concat()` method does not change the existing strings. The `concat()` method returns a new string.
2. `.concat()`
```javascript
    let str1 = 'Hello'
    let str2 = 'world!'
    console.log(str.concat(' ',str2)) // Hello world!
```

## The `replace()` method searches a string for a value or a regular expression. The `replace()` method returns a new string with the value(s) replaced. The `replace()` method does not change the original string.
3. `.replace()`
```javascript
    let str = 'Visit Microsoft!'
    console.log(str.replace('Microsoft','Soft Club')) // Visit Soft Club!
```

## The `replaceAll()` method returns a new string with all matches of a pattern replaced by a replacement.
4. `.replaceAll()`
```javascript
    let str = 'the one of the days were one of one'
    console.log(str.replaceAll('one','two')) // the two of the days were two of two
```

## The `split()` method splits a string into an array of substrings. The `split()` method returns the new array. The `split()` method does not change the original string. `If (" ") `is used as separator, the string is split between words.
5. `.split()`
```javascript
    let str = 'How are you doing today?'
    console.log(str.split(' ')) // ['How', 'are', 'you', 'doing', 'today?']
```

## The `substring()` method extracts characters, between two indices (positions), from a string, and returns the substring.
## The `substring()` method extracts characters from start to end (exclusive).
## The `substring()` method does not change the original string.
## If start is greater than end, arguments are swapped: (4, 1) = (1, 4). Start or end values less than 0, are treated as 0.
6. `.substring()`
```javascript
    let str = 'Hello world!'
    console.log(str.substring(3)) // lo world!
```

## The `slice()` method returns a shallow copy of a portion of an array into a new array object selected from start to end ( end not included) where start and end represent the index of items in that array.
7. `.slice()`
```javascript
    let str = 'Hello world!'
    console.log(str.slice(3,7)) // lo w
```

## The `toLowerCase()` method converts a string to lowercase letters. The `toLowerCase()` method does not change the original string.
8. `.toLowerCase()`
```javascript
    let str = 'HELLO WORLD!'
    console.log(str.toLowerCase()) // hello world!
```

## The `toUpperCase()` method converts a string to uppercase letters, using current locale. The `toUpperCase()` method does not change the original string.
9. `.toUpperCase()`
```javascript
    let str = 'hello world!'
    console.log(str.toUpperCase()) // HELLO WORLD!
```

## Method `trim()` removes whitespace from both sides of a string. The `trim()` method does not change the original string.
10. `.trim()`
```javascript
    let str = '      hello world!      '
    console.log(str.trim()) // hello world!
```

## The `includes()` method returns true if a string contains a specified string. Otherwise it returns false. The `includes()` method is case sensitive.
11. `.includes()`
```javascript
    let str = 'hello world my hola umeco!'
    console.log(str.includes('hola')) // true
    console.log(str.includes('hola',6)) // false
```

## The `toString()` method returns a string representing the object. By default `toString()` takes no parameters.
12. `.toString()`
```javascript
    let str = 55
    console.log(typeof(str.toString('hola'))) // string
```

## The `indexOf()` method returns the position of the first occurrence of a value in a string. The `indexOf()` method returns -1 if the value is not found.
## The `indexOf()` method is case sensitive.
13. `.indexOf()`
```javascript
    let str = 'hello world my hola umeco!'
    console.log(str.indexOf('hola')) // 15
```

## The `repeat()` method creates a new string by repeating the given string a specified number of times and returns it.
14. `.repeat()`
```javascript
    let str = 'hello'
    console.log(str.repeat(3)) // hellohellohello
```

## The `at()` method takes an integer value and returns a new String.
## This method allows for positive and negative integers. Negative integers count back from the last string character.
15. `.at()`
```javascript
    let str = 'hello'
    console.log(str.at(-1)) // o
    console.log(str.at(2)) // l
```
___

<h1 align = 'center'>Numbers</h1>


<h1 align = 'center'>Number - METHODS</h1>

## The `Math.floor()` function rounds down a number to the next smallest integer.
```javascript
    let num = 4.8
    console.log(Math.floor(num)) // 4
```

## The `Math.ceil()` method rounds a decimal number up to the next largest integer and returns it.
```javascript
    let num = 4.3
    console.log(Math.ceil(num)) // 5
```

## The `Math.round()` function returns the number rounded to the nearest integer.
```javascript
    let num = 4.3
    console.log(Math.round(num)) // 4
```

## The `max()` method finds the maximum value among the specified values and returns it.
```javascript
    console.log(Math.max(2,3,7,4,9,1,0,5,2)) // 9
```

## The `min()` method finds the minimum value among the specified values and returns it.
```javascript
    console.log(Math.min(2,3,7,4,9,1,0,-5,2)) // -5
```

## The `pow()` method computes the power of a number by raising the second argument to the power of the first argument.
```javascript
    console.log(Math.pow(2,3)) // 8
```

## The `sqrt()` method computes the square root of a specified number and returns it
```javascript
    console.log(Math.sqrt(25)) // 5
```

## The `abs()` method finds the absolute value of the specified number (without any sign) and returns it.
```javascript
    console.log(Math.abs(-25)) // 25
```

## The `Math.random()` function returns a floating-point, pseudo-random number between 0 (inclusive) and 1 (exclusive).
```javascript
    console.log(Math.rendom()*10) // 4.8217871263716
```

## The `isNaN()` function checks if a value is NaN (Not-a-Number) or not.
```javascript
    let nan = NaN
    console.log(isNaN(nan)) // true
```





