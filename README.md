# messageGenerator

The attached code, is a progran which will generate **random messages**,
each time a user runs the program. 

const message = ["man", "boy", "kid", "women", "brother"];
const words = ["the greather the mass the more attraction ", "lil bro shush please", "i forgot what he said"]

const generator = message[Math.floor(Math.random() * 5)];

const poem = words[Math.floor(Math.random() * 3)];

function messageGenerator(){
    console.log( `Ones a ${generator} said "${poem}".`)
}

messageGenerator();
