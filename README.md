# PIAIC
PIAIC Assignments
# **Getting Started Exercises with TypeScript and Node.js**

## 1- Install [Node.js], [TypeScript] and [VS Code] on your computer

1. To install VS Code, simply download from [https://code.visualstudio.com/download](https://code.visualstudio.com/download) and install it
2. Search on Google “Node.js download”
3. Download latest version and simply install it
4. To check Node.js installed> open Command Prompt and type “node -v” 
5. This command shows version of node.js
6. To install “TypeScript”> type this command on cmd “npm i -g typescript@latest”
7. Check version of TypeScript “tsc -v”

### Command Prompt

npm init -y   >> for specific changes in fie

tsc —init     >> to initialize TypeScript 

open file in VS Code tsconfig.json

change "target": "ES2016” into "target": "ES2022”

change "module": "commonjs” into "module": "NodeNext”    //for ease of user input

Uncomment "moduleResolution": "node

and change into "moduleResolution": "NodeNext””

## 2- Personal Message: Store a person’s name in a variable, and print a message to that person. Your message should be simple, such as, “Hello Eric, would you like to learn some Python today?”

let name : string = 'Anas! \nWhould you like to learn TypeScript?';

console.log(name);

## 3- Name Cases: Store a person’s name in a variable, and then print that person’s name in lowercase, uppercase, and titlecase.

let studentName: string = "Anas Shafiq";

console.log("Lowercase: " + studentName.toLowerCase());

console.log("Uppercase: " + studentName.toUpperCase());

console.log("Titlecase: " + toTitleCase(studentName));

function toTitleCase(str: string): string {

  return str.replace(/\w\S*/g, (txt: string) => {
  
    return txt.charAt(0).toUpperCase() + txt.substr(1).toLowerCase();
    
  });
  
}

## 4- Famous Quote: Find a quote from a famous person you admire. Print the quote and the name of its author. Your output should look something like the following, including the quotation marks:

const quote: string = 'A person who never made a mistake never tried anything new.';

const author: string = 'Albert Einstein';

console.log(`"${quote}"`);

console.log(`- ${author}`);

## 5- Famous Quote 2: Repeat Exercise 4, but this time store the famous person’s name in a variable called famous_person. Then compose your message and store it in a new variable called message. Print your message.

const famous_person: string = 'Albert Einstein';

const quote: string = 'A person who never made a mistake never tried anything new.';

const message: string = `"${quote}"\n- ${famous_person}`;

console.log(message);

## 6- Stripping Names: Store a person’s name, and include some whitespace characters at the beginning and end of the name. Make sure you use each character combination, "\t" and "\n", at least once. Print the name once, so the whitespace around the name is displayed. Then print the name after striping the white spaces.

let nameWithWhiteSpace: string = "\t\n  John Doe \n\t";

console.log("Name with whitespace: '" + nameWithWhiteSpace + "'");

let strippedName: string = nameWithWhiteSpace.trim();

console.log("Stripped name: '" + strippedName + "'");

## 7- Number Eight: Write addition, subtraction, multiplication, and division operations that each result in the number 8. Be sure to enclose your operations in print statements to see the results.

// Addition

const addition = 5 + 3;

console.log("Addition: " + addition); // Output: Addition: 8

// Subtraction

const subtraction = 12 - 4;

console.log("Subtraction: " + subtraction); // Output: Subtraction: 8

// Multiplication

const multiplication = 2 * 4;

console.log("Multiplication: " + multiplication); // Output: Multiplication: 8

// Division

const division = 24 / 3;

console.log("Division: " + division); // Output: Division: 8

## 8- You should create four lines that look like this:
console.log(5 + 3)
Your output should simply be four lines with the number 8 appearing once on each line.

console.log("8");

console.log("--------");

console.log("8");

console.log("--------");

console.log("8");

console.log("--------");

console.log("8");

## 9- Favorite Number: Store your favorite number in a variable. Then, using that variable, create a message that reveals your favorite number. Print that message.

const favoriteNumber = 7;

console.log("My favorite number is " + favoriteNumber + ".");

## 10- Adding Comments: Choose two of the programs you’ve written, and add at least one comment to each. If you don’t have anything specific to write because your programs are too simple at this point, just add your name and the current date at the top of each program file. Then write one sentence describing what the program does.

// This program stores my favorite number in a variable and prints a message revealing it.

const favoriteNumber = 7; // Store my favorite number (7) in a variable called favoriteNumber.

console.log("My favorite number is " + favoriteNumber + "."); // Print a message revealing my favorite number using string concatenation.


// This program prints four horizontal lines using the "-" character.

console.log("--------"); // Print the first horizontal line.

console.log("--------"); // Print the second horizontal line.

console.log("--------"); // Print the third horizontal line.

console.log("--------"); // Print the fourth horizontal line.

## 11- Names: Store the names of a few of your friends in a array called names. Print each person’s name by accessing each element in the list, one at a time.

