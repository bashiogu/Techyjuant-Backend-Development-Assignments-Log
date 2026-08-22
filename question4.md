a. local variable

function animalName() {

var horse = 'dindy';    // local variable. variable declared with the curly brackets.

console.log(horse);
}

animalName();



b. global variable

var horse = 'dindy';     // global variable, variable declared outside the curly.

function animalName() {

    console.log(horse);
}
  