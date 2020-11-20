# Conditionals

## Boolean
```javascript
let alpha = false;
let beta = true;
```

## Relational Operators
```javascript
console.log(2 < 5);
console.log(2 > 5);
console.log(2 <= 5);
console.log(2 >= 2);
```

## Strict Equality
```javascript
console.log(2 === 5);
console.log(5 === 5);
console.log(5 === "5");
```

## Abstract Equality
```javascript
console.log(2 == 5);
console.log(5 == 5);
console.log(5 == "5");
```

## Strict Inequality
```javascript
console.log(2 !== 5);
console.log(5 !== 5);
console.log(5 !== "5");
```

## Abstract Inequality
```javascript
console.log(2 != 5);
console.log(5 != 5);
console.log(5 != "5");
```

## If Statements
```javascript
let age = 22;
if(age > 17){
    console.log("You can vote!");
}
```

## Else Statements
```javascript
let age = 22;
if(age > 17){
    console.log("You can vote!");
}
else{
    console.log("You're too young :(");
}
```

## Else If Statements
```javascript
let age = 22;
if(age > 17){
    console.log("You can vote!");
}
else if(age > 15){
    console.log("You can drive!");
}
else{
    console.log("You're too young :(");
}
```

## Exercise 1: Grades
```javascript
let grade = Number(prompt("Enter your grade:"));

if(grade >= 90){
    console.log("Grade: A");
}
else if(grade >= 80){
    console.log("Grade: B");
}
else if(grade >= 70){
    console.log("Grade: C");
}
else if(grade >= 60){
    console.log("Grade: D");
}
else{
    console.log("Grade: F");
}
```

## Edge Cases
```javascript
let age = 17.5;
if(age > 17){
    console.log("You can vote!");
}
else if(age > 15){
    console.log("You can drive!");
}
else{
    console.log("You're too young :(");
}
```

## Exercise 2: Adjust Ranges
```javascript
let age = 17.5;
if(age >= 18){
    console.log("You can vote!");
}
else if(age >= 16){
    console.log("You can drive!");
}
else{
    console.log("You're too young :(");
}
```

## Logical OR
```javascript
let height = 5.5;
let weight = 160;

console.log(height > 5 || weight > 150);
console.log(height < 6 || weight > 170);
console.log(height == 6 || weight > 165);
console.log(height != 5.5 || weight > 165);
```

## Logical AND
```javascript
let height = 5.5;
let weight = 160;

console.log(height > 5 && weight > 150);
console.log(height < 6 && weight > 170);
console.log(height == 6 && weight > 165);
console.log(height != 5.5 && weight > 165);
```


## Logical NOT
```javascript
let height = 5.5;

console.log(!(height > 5));
console.log(!(height == 6));
```

## Exercise 3: TODO

## Ternary
```javascript
let height = 5.5;

console.log(!(height > 5));
console.log(!(height == 6));
```

## Exercise 4: Convert to Ternary
```javascript
//Original
let age = 22;
if(age > 17){
    console.log("You can vote!");
}
else{
    console.log("You're too young :(");
}

//Solution
let age = 22;
let message = (age > 17) ? "You can vote!" : "You're too young :(";
console.log(message);
```

## Switch
```javascript
let day = 3;
switch(day) {
  case 0:
    console.log("Sunday");
    break;
  case 1:
    console.log("Monday");
    break;
  case 2:
    console.log("Tuesday");
    break;
  case 3:
    console.log("Wednesday");
    break;
  case 4:
    console.log("Thursday");
    break;
  case 5:
    console.log("Friday");
    break;
  case 6:
    console.log("Saturday");
    break;
  default:
    console.log("Not a day");
}
```