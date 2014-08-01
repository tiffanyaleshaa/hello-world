hello-world
===========

//Hello everyone!

//I'm a coding newbie. I'm currently learning javascript through Treehouse. 
//It's pretty fun!

confirm("I am ready to play!");
var age = prompt("What's your age");
if (age < 13){
    console.log("You are allowed to play but you take no responsibility.")
}
else 
{
    console.log("Awesome, you can play on!")
}
console.log("You are at a Justin Bieber concert, and you hear this lyric 'Lace my shoes off, start racing.'");
console.log("Suddenly, Bieber stops and says, 'Who wants to race me?'");
var userAnswer = prompt("Do you want to race Bieber on stage?");
if (userAnswer = "yes"){
    console.log("You and Bieber start racing. It's neck and neck! You win by a shoelace!");
}
else {
    console.log("Oh no! Bieber shakes his head and sings 'I set a pace, so I can race without pacing.'");
}
var feedback = prompt("Please rate the game 1 out of 10. (10 being the highest)");
if (feedback > 8){
    console.log("Thank you! We should race at the next concert!");
}
else {
    console.log("I'll keep practicing coding and racing.");
}



//rock, paper, scissor game

var userChoice = prompt("Do you choose rock, paper or scissors?");
var computerChoice = Math.random();

if (computerChoice < 0.34) {
	computerChoice = "rock";
} else if(computerChoice <= 0.67) {
	computerChoice = "paper";
} else {
	computerChoice = "scissors";
} console.log("Computer: " + computerChoice);

var compare = function (choice1, choice2) {
    if (choice1 === choice2) {
         return "The result is a tie!";
    } else if (choice1 === "rock") {
        if (choice2 === "scissors") {
            return "rock wins";
        } else {
            return "paper wins";
        }
    } if (choice1 === "paper") {
        if (choice2 === "rock") {
            return "paper wins";
        } else {
            return "scissors win"
        }
    } else if (choice1 === "scissors") {
         if (choice2 === "rock") {
            return "rock wins";
        } else {
            return "scissors wins";
        }
    }
};
console.log(compare(userChoice,computerChoice));
