# CWharry.Js
//arithmetic oparetor
let a = 45;
let b = 4;
console.log("a + b=", a + b)
console.log("a - b=", a - b)
console.log("a / b=", a / b)
console.log("a * b=", a * b)
console.log("a ** b=", a ** b)
console.log("a % b=", a % b)//indicates the reminder
console.log("--a=", --a) 
//assignment operator
let c=1;
c=c+5; //c+=5  all the same
console.log(c)

//comparison operator
let comp1=5;
let comp2=6;
console.log("comp1==comp2 is",comp1==comp2)//false  1
console.log("comp1!=comp2 is",comp1!=comp2)//true   2
console.log("comp1===comp2 is",comp1===comp2)//false   3
console.log("comp1!==comp2 is",comp1!==comp2)//true    4
//but if i make comp2 a string then 1 & 2 will remain same but 3&4 will change
let comp3=5;
let comp4="5";// but comp1 was 6
console.log("comp3==comp4 is",comp3==comp4)//false  1
console.log("comp3!=comp4is",comp3!=comp4)//true   2
console.log("comp3===comp4 is",comp3===comp4)//false   3
console.log("comp3!==comp4is",comp3!==comp4)//true    4
//SO (===) OR (!==) DOESNOT ONLY VARIFY THE NUMBER OR ELEMENT BUT ALSO THE TYPE...



//logical operator
let x=5;
let y=6;
console.log(x<y && x==4)//&& is ligical AND
console.log(x>y || x==4)//|| is logical OR
console.log(!true)// ! is logical not
