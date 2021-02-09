# P217_09.02.21_Data-Types

## Lessons topics:

1. **JS Data Types:**
   - [Methods of primitives](https://javascript.info/primitives-methods)
   - [Numbers](https://javascript.info/number)
     - [w3schools - JavaScript Number Methods](https://www.w3schools.com/js/js_number_methods.asp)
     - [MDN - Number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)
   - [Strings](https://javascript.info/string)
     - [w3schools - JavaScript String Methods](https://www.w3schools.com/js/js_string_methods.asp)
     - [MDN - String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
   - [Arrays](https://javascript.info/array)
     - [Array methods](https://javascript.info/array-methods)
     - [w3schools - JavaScript Arrays](https://www.w3schools.com/js/js_arrays.asp)
     - [MDN - Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
   - [Date and time](https://javascript.info/date)
     - [w3schools - JavaScript Date Objects](https://www.w3schools.com/js/js_dates.asp)
     - [MDN - Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)
2. **[Object.keys, values, entries](https://javascript.info/keys-values-entries)**
3. **[Error handling, "try..catch"](https://javascript.info/try-catch)**
     - [w3schools - JavaScript Errors - Throw and Try to Catch](https://www.w3schools.com/js/js_errors.asp)
     - [MDN - Control flow and error handling](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)
     - [MDN - Error](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error)

## Articles to Read and additional videos:

- **Articles:**
  - [How to Handle Monetary Values in JavaScript](https://frontstuff.io/how-to-handle-monetary-values-in-javascript)
  - [Как работать с денежными значениями в JavaScript](https://medium.com/devschacht/how-to-handle-monetary-values-in-javascript-bb0706840f0e)
  - [How JavaScript’s Reduce method works, when to use it, and some of the cool things it can do](https://medium.com/free-code-camp/reduce-f47a7da511a9)
  - [Как работает reduce() в JavaScript, когда его нужно применять и какие крутые вещи можно с ним делать](https://medium.com/@stasonmars/%D0%BA%D0%B0%D0%BA-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%D0%B5%D1%82-reduce-%D0%B2-javascript-%D0%BA%D0%BE%D0%B3%D0%B4%D0%B0-%D0%B5%D0%B3%D0%BE-%D0%BD%D1%83%D0%B6%D0%BD%D0%BE-%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D0%BD%D1%8F%D1%82%D1%8C-%D0%B8-%D0%BA%D0%B0%D0%BA%D0%B8%D0%B5-%D0%BA%D1%80%D1%83%D1%82%D1%8B%D0%B5-%D0%B2%D0%B5%D1%89%D0%B8-%D0%BC%D0%BE%D0%B6%D0%BD%D0%BE-%D1%81-%D0%BD%D0%B8%D0%BC-b650c397bee6)
  - [Why ['1', '7', '11'].map(parseInt) returns [1, NaN, 3] in Javascript](https://medium.com/dailyjs/parseint-mystery-7c4368ef7b21)
  - [7 Types of Native Errors in JavaScript You Should Know](https://blog.bitsrc.io/types-of-native-errors-in-javascript-you-must-know-b8238d40e492)
- **Videos:**
  - [JavaScript Try Catch & Error Handling ES6 Tutorial (2020)](https://youtu.be/ye-aIwGJKNg)
  - [Learning Functional Programming with JavaScript - Anjana Vakil - JSUnconf](https://youtu.be/e-5obm1G_FY)

## Assignments:

1. **Complete below shown exercises from this link:**
   - String Methods
   - Arrays
   - Array Methods
   - Array Sort
   - Dates
   - Math
2. **Watch these videos:**
   - [Map - Functional Programming in JavaScript](https://youtu.be/bCqtb-Z5YGQ?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84)
   - [Reduce basics - Functional Programming in JavaScript](https://youtu.be/Wl98eZpkp-c?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84)
   - [8 Must Know JavaScript Array Methods](https://youtu.be/R8rmfD9Y5-c)
   - [JS Date Object - Getting, Setting & Formatting Dates in JavaScript](https://youtu.be/-eRsWqwcPuk)
3. **JavaScript - Exercises:**
   - Arrays:
     - [`Write a function to filter out falsy values from array.`](https://user-images.githubusercontent.com/74110914/102804742-98769200-43d3-11eb-88a8-94b45ccff3cb.jpg)
       - Input: removeFalsyValues([33, '', 'salam', true, null, false, 0]).
       - Output: [33, 'salam', true].
     - `Write a function to get a random element from array.`
       - Input: getRandomValues([33, '', 'salam', true, null, false, 0]).
       - Output: 0.
     - [`Write a function to remove duplicate values from an array.`](https://user-images.githubusercontent.com/74110914/102804735-96143800-43d3-11eb-994a-0a83cb015c1f.jpg)
       - Input: removeDuplicates([1, 123, 33, 45, 66, 45, 123, 1]).
       - Output: [33, 66].
     - [`Write a function to remove a given values from an array.`](https://user-images.githubusercontent.com/74110914/102804739-97ddfb80-43d3-11eb-9954-5c5ad00d2c0c.jpg)
       - Input: removeFromArray([1, 123, 33, 45, 66], 45).
       - Output: [1, 123, 33, 66].
   - Date:
     - `Write a function to get the month name from a particular date.`
       - Input: getMonthName(new Date("10/11/2009")).
       - Output: "October".
     - `Write a function to get the number of days in a month.`
       - Input: getNumberOfDays(5, 2020).
       - Output: 31.
     - `Write a function which return copyright text with current year.`
       - Input: renderCopyRight().
       - Output: "Copyright © 2020. All Rights Reserved.".
     - `Write a function to check whether a given date is a weekend or not.`
       - Input: isWeekend('Dec 21, 2020').
       - Output: `false`.
   - Number:
     - `Write a function to calculate the percentage (%) of a total number from given.`
       - Input: percentage(2345, 190).
       - Output: "8.10%".
   - String:
     - `Write a function to truncate a text to a certain number of words.`
       - Input: truncate('Lorem ipsum dolor sit amet, consectetur adipisicing elit.', 3).
       - Output: "Lorem ipsum dolor".
     - `Write a function to truncate a text if it is longer than the given characters range. (Truncated strings should end with 3 dots ("…") (by default) or with specified given characters.)`
       - Input: truncateText('Lorem ipsum dolor sit amet, consectetur adipisicing elit.', 20).
       - Output: "Lorem ipsum dolor si…".
       - Input: truncateText('Lorem ipsum dolor sit amet, consectetur adipisicing elit.', 21, "- $$$").
       - Output: "Lorem ipsum dolor sit - $$$".


## Some other useful resources:

- [0.30000000000000004.com](https://0.30000000000000004.com/)
- [What is Random?](https://youtu.be/9rIy0xY99a0)
- [Does it mutate 😱](https://doesitmutate.xyz/)
- [Moment JS](https://momentjs.com/)
