# Releases

# Release0: Functions by Codecademy

Login/SignUp to Codecademy & Finish all function exercises on Codecademy

Click [here](https://www.codecademy.com/courses/functions-in-javascript-2-0/0/1) to begin :)

# Release1: Functions

- Create an empty function with multiple comments inside of it
- Create an function `FirstFunction` that would return a string "Finding Fanny"
- Write a function called add that takes in two parameters - number1 and number2 - and returns their sum.

- Consider the following code:
```
(function() {
   var a = b = 5;
})();

console.log(b);
```
What will be printed on the console?

- Create “native” methods
Define a repeatify function on the String object. The function accepts an integer that specifies how many times the string has to be repeated. The function returns the string repeated the number of times specified. For example:

```console.log('hello'.repeatify(3));```
Should print hellohellohello.

- Hoisting
What’s the result of executing this code and why.
```
function test() {
   console.log(a);
   console.log(foo());
   
   var a = 1;
   function foo() {
      return 2;
   }
}

test();
```

- How `this` works in JavaScript. 
What is the result of the following code? Explain your answer.

```
var fullname = 'John Doe';
var obj = {
   fullname: 'Colin Ihrig',
   prop: {
      fullname: 'Aurelio De Rosa',
      getFullname: function() {
         return this.fullname;
      }
   }
};

console.log(obj.prop.getFullname());

var test = obj.prop.getFullname;

console.log(test());
```


-  Before we dive into Object Oriented Programming, let's revisit JavaScript objects. Give your motorBike object a wheels, engines and seats attribute and set them to numbers.


```

var car = {
  "wheels":4,
  "engines":1,
  "seats":5
};

var motorBike = {

  // Only change code below this line.

};
```

# Release2: More Functions

- Write a JavaScript function to find longest substring in a given a string without repeating characters. 

- Write a JavaScript function that returns the longest palindrome in a given string. 

Note: According to Wikipedia "In computer science, the longest palindromic substring or longest symmetric factor problem is the problem of finding a maximum-length contiguous substring of a given string that is also a palindrome. For example, the longest palindromic substring of "bananas" is "anana". The longest palindromic substring is not guaranteed to be unique; for example, in the string "abracadabra", there is no palindromic substring with length greater than three, but there are two palindromic substrings with length three, namely, "aca" and "ada".
In some applications it may be necessary to return all maximal palindromic substrings (that is, all substrings that are themselves palindromes and cannot be extended to larger palindromic substrings) rather than returning only one substring or returning the maximum length of a palindromic substring.

- Write a JavaScript function that accept a list of country names as input and returns the longest country name as output.
```
Sample function : Longest_Country_Name(["Australia", "Germany", "United States of America"])
Expected output : "United States of America"
```

- Write a JavaScript function that accepts two arguments, a string and a letter and the function will count the number of occurrences of the specified letter within the string.
```
Sample arguments : 'w3resource.com', 'o'
Expected output : 2 
```
- Write a JavaScript function that generates a string id (specified length) of random characters.
```
Sample character list : "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789"
```