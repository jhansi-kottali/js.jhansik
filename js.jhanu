// create an Array to store animals
let animals = [];

// this function will take in some values as parameters , create an newAnimal object using the 
//parameters passed to it for its metadata, and store it in the above array.
function mintAnimal(name, species, age, color) {
    let newAnimal = {
        name: name,
        species: species,
        age: age,
        color: color
    };
    animals.push(newAnimal);
    console.log("Minted: " + name);
}

// create a "loop" that will go through  an "array" of animals and print their metadata with console.log()
function listAnimals() {
    for (let i = 0; i < animals.length; i++) {
        console.log("\nID: \t\t" + (i + 1));
        console.log("Name: \t\t" + animals[i].name);
        console.log("Species: \t" + animals[i].species);
        console.log("Age: \t\t" + animals[i].age);
        console.log("Color: \t\t" + animals[i].color);
    }
}

// Function to get total supply of animals
function getTotalSupply() {
    console.log("\nTotal Animals: " + animals.length);
}

// Call the functions
mintAnimal("Fido", "Dog", 3, "Brown");
mintAnimal("Whiskers", "Cat", 2, "Gray");
mintAnimal("Snowball", "Hamster", 1, "White");
mintAnimal("Buddy", "Dog", 4, "Black");
listAnimals();
getTotalSupply();
