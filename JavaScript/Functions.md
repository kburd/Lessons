# JavaScript Functions

Author: Kaleb Burd

Length: 3 hours

---

## Define a function
```javascript
function displayHelloWorld(){
    console.log("Hello World");
}
```

## Calling a function
```javascript
displayHelloWorld();
```

## Excercise 1: Display Hello World 10 times
 ```javascript
for(let i = 0; i < 10; i++){
    displayHelloWorld();
}
```

## Parameters
 ```javascript
function displayDollarAmount(amount){
    console.log(`Amount: ${amount} dollar(s)`);
}
```

## Exercise 2: Add two numbers and display
 ```javascript
function addAndDisplay(a, b){
    console.log(a + b);
}
```

## Return
 ```javascript
function add(a, b){
    return a + b;
}
let answer = add(4,9);
console.log(answer);
```

## Exercise 3: Calculate Circumference
 ```javascript
function circumference(radius){
    return 2 * radius * Math.PI;
}
let answer = circumference(4);
console.log(answer);
```

## Scope
 ```javascript
function circumference(radius){
    let diameter = 2 * radius;
    return diameter * Math.PI;
}
let answer = circumference(4);
console.log(answer);
console.log(diamter);
```

## Function Expressions
```javascript
const circumference = function(radius){ return 2 * radius * Math.PI;}
console.log(circumference(2));
```

## Exercise 4: Area of a circle
```javascript
const area = function(radius){ return Math.PI * Math.pow(radius, 2);}
console.log(area(2));
```

## Lambda
```javascript
const area = radius => Math.PI * Math.pow(radius, 2);
console.log(area(2));
```

## Default Parameters
```javascript
function speak(message = "Hola Mundo"){
    console.log(message);
}
console.log(speak("Hello World"));
console.log(speak());
```

## Spread Operator
```javascript
let data = [1,2,3];
console.log(data);
console.log(...data);
console.log(data[0], data[1], data[2]);
```

## Exercise 5: Using spread operator for parameters
```javascript
function sum(x, y, z){
    return x + y + z;
}
let data = [1,2,3];
let answer = sum(...data)
console.log(answer);
```
