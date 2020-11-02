# Lesson 01 - JavaScript

a website has the 3 basic elements: 
* HTML - the structure of the page. 
* CSS - the design of the page
* JS - make thewwebsite dynamic

JavaScript is a script language. (use interpreter). 95% from the websites today use JS. 
* dynamicly typed. (var)
* Event driven
* one threaded
* asyncronous
* OOP - object oriented programming. 

### interpreter vs compiler

* compiler: IDE - integraded development enviroment. (visual studio, eclipse).
* takes a lot of place in memory. 
* compiles the code to bytes, and then run it. 
* if there is one error - the program will not run. 

* interpreter - Text editor. lightwieght. 
* will execture line-after-line. 
* errors: if there are errors, the program wil run until this line. 


## alert()
alert - popup to the user.
```js
alert("some text");
```

## console.log()
outputs data to the console. 
```js
console.log("");
```

## Variables:
Undefined: it will be the default value, as long as there is no data to the variable. 
Number: includes all types of numbers. (int, float, long, double)
String: "", '', ``. (can be written in 3 ways). 
Boolean: can be only true/false. 

## Prompt()
ask from the user for input. Will allways receive data as string. 
```js
var item = prompt("Enter your item:");
var num = Number(prompt("Enter your number:"));
```

## Interpolation - שרבוב
Allow us to add variables to strings. Works only with backticks. (``)
```js
var user = "John";
var str = `hello ${user}`;
```

## pre / post - increment / decrement:

```js
var num = 1;

console.log(++num);
console.log(--num);
console.log(num++);
console.log(num--);
```

## if - else
if statement will be used if the condition inside `()` is equal to true. 
```js
if(condition){
    // code to execute
}
else if(condition){
    // code to execute
}
else{
    // code to execute
}
```


## switch-case
switch-case can go on multiple options. similar to `if-else`:
* if there is no break after `case` - the program will continue to the next case. 
* default - catches all the other options. there is no need to add break to default.  
```js
switch(variable to use){
    case option 1: // code to execute
    break;
    default: // code to execute
}
```

## class task:

### A.
* create HTML page with script tag.
* ask from the user his age, and validate it. 
* if : age under 0 or age above 120 - invalid age. (alert to user).
* if age above or equal 18 - alert: ENTER. 
* if age under 18 - alert : too young. please come in `years until 18` years.

### B.
* ask from the user a number, and check if it is EVEN / ODD. 
* print to the console the result. 

### C.
* ask from the user for 3 numbers, 
* check in if-else the amount of the number, and show then in the right order. (ascending), to the console. 

### D.
* ask from the user a number, and print to the console if it is positive / negative. 


