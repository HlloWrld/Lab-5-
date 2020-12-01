// Observe the list of people below
const people = [ { name: "John Doe", age: 16 },
                 { name: "Thomas Calls", age: 19 },
                 { name: "Liam Smith", age: 20 },
                 { name: "Jessy Pinkman", age: 18 }
                ];

// Observe the coffeeLovers list containing people who are coffee lovers
const coffeeLovers = ["John Doe", "Liam Smith", "Jessy Pinkman"];


// 1. Filter all people above the age of 18 (use a function called ageAbove18) --- Using filter Higher Function
//unsure how to console.log to check that this is working for ageAbove18 code below
const ageAbove18 = (array) => {
    return array.filter((personName) => personName.age > 18);
    console.log(ageAbove18);
};

// Backup that I am pretty sure works below
// const ageAbove18 = (array) => {
//     return array.filter(personName => personName.age > 18);
//     console.log(ageAbove18);
// };

// 2. Transform the people array so all people in the array who are in coffeeLovers have a property --- Using map Higher function
const addCoffeeLoverProperty = (array) => {
    return array.map((person, arrayOfCoffeeLovers) => {
        let namesOfPeople = personName.name;
            if(arrayOfCoffeeLovers.coffeeLoverIndex(personName.name) !== true) {
                personName.coffeeLovers = false;
            } else {
                personName.coffeeLovers = true;
            }
    })
};

// 3. Get the total summed age of all people who are coffee lovers and above the age of 18 (Use a function called ageReducer) ---- Using reduce Higher function
const ageReducer = (coffeeOver18) => {
    coffeeOver18.reduce((add1, add2) => {
        let peopleSum = add1.age + add2.age;
        console.log(peopleSum);
    })
};

// Wondering if you can do coffeeLovers + people.name?
// const ageReducer = (coffeeOver18) => {
//     coffeeOver18.reduce(coffeeLovers, people.name) => {
//         let peopleSum = coffeeLovers + people.name;
//         console.log(peopleSum);
//     }
// };

const coffeeLoversAbove18 = people.filter(ageAbove18).map(addCoffeeLoverProperty);
const totalAgeOfCoffeeLoversAbove18 = coffeeLoversAbove18.reduce(ageReducer);

// Trying to figure out how if I should use backtick and $ sign for this but I am unsure 
console.log("The total age of all the coffee lovers that are over the age of 18 is: " `${totalAgeOfCoffeeLoversAbove18}`);
console.log(totalAgeOfCoffeeLoversAbove18);
