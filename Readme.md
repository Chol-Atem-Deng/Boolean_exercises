# Boolean Logic Exercises

## Part_I

## 1.2 == "2"; 
True

## 2.2 === 2;
True

## 3.10 % 3;
1

## 4.10 % 3 === 1;
True

## 5.true && false;
False

## 6.false || true;
True

## 7.true || false;
True


## Part_II
(a)

let isLearning = true;
if(isLearning){
    console.log("Keep it up!");
} else {
    console.log("Pretty sure you are learning....");
}

## 1.What should the above code console.log?
It will console.log "Keep it up" because the value of isLearning is truthy.

## 2.Why do we not need to specify if(isLearning === true)? Why does if(isLearning) work on its own?
Because true is a truthy value

(b)

let firstvariable;
let secondvariable = "";
let thirdvariable = 1;
let secretMessage = "Shh!";

if(firstvariable){
    console.log("first");
} else if(firstvariable || secondvariable){
    console.log("second");
} else if(firstvariable || thirdvariable){
    console.log("third");
} else {
    console.log("fourth");
}

## 1.What should the above code console.log? Why?
It will console.log "third" since the third variable is true and the first variable and the second variable are false.this is because the || (or) operator returns true if either condition is true.

## 2.What is the value of firstvariable when it is initialized?
It is undefined because it is not assigned to any value.

## 3.Is the value of firstvariable a “truthy” value? Why?
The value of first variable is a falsey value because undefined is a falsey value.

## 4.Is the value of secondvariable a “truthy” value? Why?
It is a not a truthy value since it is an empty string and empty strings are said to be falsey values.

## 5.Is the value of thirdvariable a “truthy” value? Why?
The third variable is a truthy value since it is a number.All numbers are said to be truthy except for 0 which is a falsey value.


## Part_III

## 1.Research Math.random here and write an if statement that console.log’s “Over 0.5” if Math.random returns a number greater than 0.5. Otherwise console.log “Under 0.5”.
Answered in index.js file

## 2.What is a falsey value? List all the falsey values in JavaScript.
They are values that are actually false when they are used in javaScript.
Examples of falsey values are;undefined,null,Nan,0,false and an empty string ("").