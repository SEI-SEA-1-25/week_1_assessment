# SEI Week 1 Assessment

### Bash (Terminal)

#### For EACH and EVERY question in this section, assume you are in the `~/buffy` directory:

1. Make two directories inside `~/buffy`: `scoobies` and `vamps`:
   mkdir scoobies vamps
   <br><br><br>

2. Create files in `scoobies` named `buffy.txt` and `angel.txt`:

cd scoobie

touch buffy.text angel.txt
<br><br><br>

3. Copy `angel.txt` into the `vamps` directory:

cp angel.txt vamps

<br><br><br>

4. Delete the `vamps` directory and everything inside it:
   rmdir vamps
   <br><br>

### JS Variables

1. Assign the string "Ahab" to a variable named `captain`:
   const captain = "Ahab"

<br><br>

2. Using the `captain` variable instead of the text "Ahab", use string concatenation to form the string "Oh Ahab, my Ahab!", assigning it to a variable named `phrase`:

let phrase = `Oh ${captain}, my ${captain}! `
<br><br>

### JS Conditionals

```js
var souls = 3;
var lifeRafts = 2;
```

1. Assuming the above variables, write an `if` statement that console.logs "SOS!" if there are more `souls` than `lifeRafts` (no need to write a function, just the `if` statement please):

if (souls > lifeRafts){
console.log("SOS!")
}
<br><br>

### Data Structures - JS Arrays

1. Create an array named `weekend` with just a string 'Saturday' in it:
   let weekend = ["Saturday"]
   <br><br>

2. Add the string 'Sunday' to the end of the `weekend` array:
   weekend.push("Suday")
   <br><br>

3. Now add the string 'Friday' to the front of the `weekend` array:
   weekend.unshift("weekend")
   <br><br>

4. Using square bracket notation, access 'Saturday' in the `weekend` array and assign to a variable named `day` (Note: the array has three days in it as this point):

let day = weekend[1]
<br><br>

5. Remove 'Friday' from the array:
   weekend.shift()
   <br><br>

6. Loop through the `weekend` array and for each element in it, print `"Woohoo! It's finally <day name>"`

if (i= 0; i < weekend.length; i++){
console.log(`Woohoo! Its finally ${weekend[i]}`)
}

### Data Structures - JS Objects

#### Don't forget to use a `var` or `let` when defining new variables...

1. Write an object literal named `brain` having a property with a key of `energyLevel` and a numeric value of `10`:

let brain = {
energyLevel: 10,
}
<br><br>

2. Assign the value of the property `energyLevel` to a variable named `energy`:
   brain.energyLevel = energy;
   <br><br>

3. Add a `dream` property to the `brain` object that holds the string 'electric sheep':
   brain.dream = 'electric sheep';
   <br><br>

### JS Functions

1. Write a function named `computeArea` that has two parameters, `length` & `width`, and **returns** the area of a rectangle (the product of `length` and `width`):

function computeArea (l,w){
return l \* w;
}
<br><br><br><br>

2. Invoke the `computeArea` function with `3` and `4` as arguments and save the returned result to a variable named `area`:
   computeArea(3,4);
   <br><br>

3. Write a function `findMax` that takes in 1 paramater, an array of numbers, and returns the highest number in that array.

function findMax (arr){
for (i = 0; i < arr.length; i++){
let value = value + arr;
}
console.log(value);

}
