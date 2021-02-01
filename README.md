# SEI Week 1 Assessment

### Bash (Terminal)

#### For EACH and EVERY question in this section, assume you are in the `~/buffy` directory:

1. Make two directories inside `~/buffy`: `scoobies` and `vamps`:
<br><br><br>
cd buffy
mkdir scoobies 
mkdir vamps

2. Create files in `scoobies` named `buffy.txt` and `angel.txt`:
<br><br><br> 
cd scoobies 
touch buffy.txt
touch angel.txt

3. Copy `angel.txt` into the `vamps` directory:
<br><br><br>
mv angel.txt vamps

4. Delete the `vamps` directory and everything inside it:
<br><br>
rmdir vamps
### JS Variables

1. Assign the string "Ahab" to a variable named `captain`:
<br><br>
var captain = "Ahab"

2. Using the `captain` variable instead of the text "Ahab", use string concatenation to form the string "Oh Ahab, my Ahab!", assigning it to a variable named `phrase`:
<br><br>
var phrase = "Oh " + captain + ", my " + captain + "!"

### JS Conditionals
```js
var souls = 3;
var lifeRafts = 2;
```

1. Assuming the above variables, write an `if` statement that console.logs "SOS!" if there are more `souls` than `lifeRafts` (no need to write a function, just the `if` statement please):
<br><br>
if(souls > lifeRafts) {
    console.log("SOS!)
}


### Data Structures - JS Arrays

1. Create an array named `weekend` with just a string 'Saturday' in it:
<br><br>
var weekend = ["Saturday"];
2. Add the string 'Sunday' to the end of the `weekend` array:
<br><br>
weekend.push("Sunday");
3. Now add the string 'Friday' to the front of the `weekend` array:
<br><br>
weekend.unshift("Friday")
4. Using square bracket notation, access 'Saturday' in the `weekend` array and assign to a variable named `day` (Note: the array has three days in it as this point):
<br><br>
var day = weekend[1];
5. Remove 'Friday' from the array:
<br><br>
weekend.shift();
6. Loop through the `weekend` array and for each element in it, print `"Woohoo! It's finally <day name>"`
for(i = 0; i <= weekend.length; i ++){
    console.log("Woohoo! It's finally " + weekend[i])
}
### Data Structures - JS Objects

#### Don't forget to use a `var` or `let` when defining new variables...

1. Write an object literal named `brain` having a property with a key of `energyLevel` and a numeric value of `10`:
<br><br>
var brain = {
    energyLevel: 10
};
2. Assign the value of the property `energyLevel` to a variable named `energy`:
<br><br>
var energy = brain.energyLevel;
3. Add a `dream` property to the `brain` object that holds the string  'electric sheep':
<br><br>
brain.dream = "electric sheep";
### JS Functions

1. Write a function named `computeArea` that has two parameters, `length` & `width`, and **returns** the area of a rectangle (the product of `length` and `width`):
function computeArea(length, width) {
    var area = length * width
    console.log(area)
};
<br><br><br><br>

2. Invoke the `computeArea` function with `3` and `4` as arguments and save the returned result to a variable named `area`:<br><br>
var area = computeArea(3, 4);

3. Write a function `findMax` that takes in 1 paramater, an array of numbers, and returns the highest number in that array.

function findMax(numbers){
    const max = 0
    for(i = 0; i <= numbers.length; i++){
        if(numbers[i] >= max){
            max = numbers[i]
        }
    }
    console.log(max)
};
