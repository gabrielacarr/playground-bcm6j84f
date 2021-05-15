// create an array
let favoriteFoods = ["pizza", "tacos", "pasta"];


// change last element
// favoriteFoods[2] = "veggie burgers";
favoriteFoods[favoriteFoods.length - 1] = "veggie burgers";

// remove first element and store in variable
let formerFavoriteFood = favoriteFoods.shift();

// add to end of arrays
favoriteFoods.push("nachos");

// add to start of array
favoriteFoods.unshift("veggie platter");




// check
console.log(`former favorite food removed: ${formerFavoriteFood}`);
console.log(favoriteFoods);