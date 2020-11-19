# JavaScript Arrays


## Initialization
```javascript
let cars = ["Jetta", "GTI", "Beetle"];
```

## Length
```javascript
let cars = ["Jetta", "GTI", "Beetle"];
console.log(cars.length)
```

## Indexing
```javascript
let cars = ["Jetta", "GTI", "Beetle"];
console.log(cars[1]);
```

## Iterating through an array
```javascript
let cars = ["Jetta", "GTI", "Beetle"];
for(let i = 0; i < cars.length; i++){
    console.log(cars[i]);
}
```

## Index out of Bounds
```javascript
let cars = ["Jetta", "GTI", "Beetle"];
for(let i = 0; i < 4; i++){
    console.log(cars[i]);
}
```

### Exercise 1: Summing values in an array
```javascript
let nums = [3, 8, 2, 1];
let sum = 0;
for(let i = 0; i < cars.length; i++){
    sum += nums[i];
}
console.log(sum);
```

## Updating 
```javascript
let cars = ["Jetta", "GTI", "Beetle"];
cars[1] = "Golf";
console.log(cars);
```

## Appending Values
```javascript
let cars = ["Jetta", "GTI", "Beetle"];
cars.push("Passat");
console.log(cars);
```

### Exercise 2: Fill an array
```javascript
let nums = [];
for(let i = 0; i < 5; i++){
    nums.push(3);
}
console.log(nums);
```

## Removing Values
```javascript
let cars = ["Jetta", "GTI", "Beetle"];
let value = cars.pop();
console.log(cars);
console.log(value);
```

## Slicing
```javascript
let cars = ["Jetta", "Golf", "Passat", "Beetle", "VW Bus", "GTI", "ID.4"];
let obsolete = cars.slice(3,5);
console.log(obsolete);
```

### Exercise 3: Split an array in half 
```javascript
let cars = ["Jetta", "Golf", "Passat", "Beetle", "VW Bus", "GTI", "ID.4"];
let middle = cars.length/2;
let front = cars.slice(0, middle);
let back = cars.slice(middle, cars.length);
console.log(front, back);
```


## Two Dimensional Arrays
```javascript
//Intialization
let cars = [
    ["Jetta", "Golf", "Passat"], 
    ["Beetle", "VW Bus", "GTI"], 
    ["ID.4", "GLI", "Atlas"]
];

//Accessing
cars[2][2] = "Tiguan";

//Iterating
for(let i = 0; i < cars.length; i++){
    for(let j = 0; j < cars[i].length; j++){
        console.log(cars[i][j]);
    }
    console.log();
}
```

### Exercise 4: Multiplication Grid
```javascript
let grid = [[0,0,0],[0,0,0],[0,0,0]];
for(let i = 0; i < grid.length; i++){
    for(let j = 0; j < grid[i].length; j++){
        grid[i][j] = (i+1)*)(j+1);
    }
}
console.log(grid);
```
