# JavaScript Loops

Author: Kaleb Burd

Length: TBD

---

## While loop
```javascript
let count = 0;
while(count < 5){
    console.log("Hola Mundo!");
    count++;
}
```

## Infinite loop
```javascript
//Don't Run!
let count = 0;
while(count < 5){
    console.log("Hola Mundo!");
}
```

## Excercise 1: Guess a random number
```javascript
let randomNumber = Math.floor(Math.random() * 10) + 1; 
let userGuess = prompt("Guess a number between 1 - 10");
while(randomNumber != userGuess){
    userGuess = prompt("Try again. Guess a number between 1 - 10");
}
alert(`Correct! The answer was ${randomNumber}`);
```

## Do while
```javascript
let randomNumber = Math.floor(Math.random() * 10) + 1; 
let userGuess;
do{
    userGuess = prompt("Try again. Guess a number between 1 - 10");
} while(randomNumber != userGuess);
alert(`Correct! The answer was ${randomNumber}`);
```

## Sentinel Values
```javascript
let iceCubeAnswer;
do{
    iceCubeAnswer = prompt("Are we there yet?:"));
} while(iceCubeAnswer === "N");
alert(`Hooooooray!!!`);
```

## Excercise 2: Sum Total
```javascript
let count = 0;
let total = 0;
while(count <= 5){
    total += count;
    count++;
}
alert(`Your sum was ${total}`);
```

## For Loop 
```javascript
let total = 0;
for(let count = 0; count <= 5; count++){
    total += count;
}
alert(`Your sum was ${total}`);
```

## Excercise 3: Start, Stop, Step
Create for loops that do the following:
* Counts from 0 to 4, one at a time
* Counts from 1 to 9, one at a time
* Counts from 0 to 7, two at a time
* Counts from 5 to 0, one at a time
* Counts from 10 to -10, three at a time

## Break
```javascript
for(let i = 0; i < 10; i++){
    if(i === 5){
        break;
    }
    console.log(i);
}
```
## Continue
```javascript
for(let i = 0; i < 10; i++){
    if(i === 5){
        continue;
    }
    console.log(i);
}
```

## Loop and DOM
```html
<!DOCTYPE html>
<html lang="en">
    <body>
        <div id="example"></div>
    </body>
    <head>
        <script src="script.js"></script>
    </head>
<html>
```
```javascript
let output = "";
for(let i = 1; i <= 10; i++){
    output += `<p>"${i}</p>`;
}
document.getElementById("example").innerHTML = output;
```

## Exercise 4: User chooses the list type
```html
<!DOCTYPE html>
<html lang="en">
    <body>
        <div id="example"></div>
    </body>
    <head>
        <script src="script.js"></script>
    </head>
<html>
```
```javascript
//Generate the html list items
let listItems = "";
for(let i = 1; i <= 10; i++){
    listItems += `<li>${i}</li>`;
}

// Determine what type of list to use
let answer = prompt("Ordered List? (Y/N)");
let output = (answer === "Y") ? `<ol>${listItems}</ol>` : `<ul>${listItems}</ul>`;

//Update the html
document.getElementById("example").innerHTML = output;
```


