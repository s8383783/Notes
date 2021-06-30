## Javascript
To assign a value in Java you must type 
let x = y
You can only use let once and in order to reassign the variable you would write the following 
x = z
We have now changed the value of X but inputting the above. 
When we want to print things to our console we use the console.log code, we can also use 'return' but this is used when creating a function. 
To create a function we start with the word 'function' after that we name it, and add the logic afterwords. A function takes a simple piece of code and saves it in the block of code. Variables can be taken into the function but not out, so you must be care when naming and declaring your variables. An example of a function is below. 
Example 
function Addsum(num1, num2){
    let answer = num1 + num2
    return answer
}
But in order to get the answer to this function we must also put
console.log(Addsum())

We can also gather user input by using the prompt command like below

function FullName(){
let FirstName = prompt('What is your first name?');
let LastName = prompt('What is your last name?');
return FirstName + ' ' + LastName}

console.log(FullName())