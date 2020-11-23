# Two Dimensional Arrays

Author: Kaleb Burd

Length: 1.5 hours

---

## Intialization

```javascript
let cars = [
    ["Jetta", "Golf", "Passat"], 
    ["Beetle", "VW Bus", "GTI"], 
    ["ID.4", "GLI", "Atlas"]
];
```


## Accessing
```javascript
let cars = [
    ["Jetta", "Golf", "Passat"], 
    ["Beetle", "VW Bus", "GTI"], 
    ["ID.4", "GLI", "Atlas"]
];
cars[2][2] = "Tiguan";
```

## Exercise 1: Deriving Iteration
```javascript
let cars = [
    ["Jetta", "Passat", "GLI"],
    ["Beetle", "VW Bus", "CC"],
    ["Golf", "GTI", "Atlas"]
];
```

### Part One:  Print out all elements
```javascript
console.log(cars[0][0])
console.log(cars[0][1])
console.log(cars[0][2])
console.log(cars[1][0])
console.log(cars[1][1])
console.log(cars[1][2])
console.log(cars[2][0])
console.log(cars[2][1])
console.log(cars[2][2])
```

### Part Two: Use i to set row 
```javascript
let i = 0;
console.log(cars[i][0])
console.log(cars[i][1])
console.log(cars[i][2])

i = 1;
console.log(cars[i][0])
console.log(cars[i][1])
console.log(cars[i][2])

i = 2;
console.log(cars[i][0])
console.log(cars[i][1])
console.log(cars[i][2])
```

### Part Three: Use a loop to set i
```javascript
for(let i = 0; i < 3; i++){
    console.log(cars[i][0])
    console.log(cars[i][1])
    console.log(cars[i][2])
}
```

### Part Four: Use j to set column
```javascript
for(let i = 0; i < 3; i++){

    let j = 0;
    console.log(cars[i][j]);

    j = 1;
    console.log(cars[i][j]);

    j = 2;
    console.log(cars[i][j]);

}
```

### Part Five: Use a loop to set j
```javascript
for(let i = 0; i < 3; i++){
    for(let j = 0; j < 3; j++){
        console.log(cars[i][j]);
    }
}
```

## Iterating
```javascript
for(let i = 0; i < cars.length; i++){
    for(let j = 0; j < cars[i].length; j++){
        console.log(cars[i][j]);
    }
    console.log();
}
```

## Exercise 2: Multiplication Grid
```javascript
let grid = [[0,0,0],[0,0,0],[0,0,0]];
for(let i = 0; i < grid.length; i++){
    for(let j = 0; j < grid[i].length; j++){
        grid[i][j] = (i+1)*)(j+1);
    }
}
console.log(grid);
```