First condition

console.log(pet);

var pet = 'lucy';    

 // the output is going to be UNDEFINED and this is because, in javascript using var to declare a variable. The variable declaration needs to be at the top of the scope for javascript to execute the code. so that when hoisted, it can be executed.


second condition

console.log(animal);

let animal = 'tom';   // the output cannot be established since javascript cannot access the variable 'animal' before the initialization. In this sample an error will display because the declaration is not readily available to be used.
