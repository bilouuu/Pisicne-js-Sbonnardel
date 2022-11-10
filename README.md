# Pisicne-js-Sbonnardel
 ***************ex00**************

function substract(a,b){
return a - b;
  
}

***********ex1**************$

function add(a,b){
  return a + b;
}

*******ex2*********

function multiply (a, b) {
 return a * b; 
}

*******exo3******

function divide (a, b){
     if (b == 0){
       return ("Forbidden")
     }else{
       return a/b; 
 }
 
 *******ex4******
 function modulo (a, b){
return a % b;
  }
  
  *****ex5*******
  
for (let i = 0; i <=10; i++{
console.log (i); 
}

*******ex6*******

let i=0
while (i<=100){
  console.log (i)
  i=i+2}



*****ex7******

const userName = prompt ("what's your name?")
console.log("Have a nice day " + userName + " .")

******ex8******

console.log("Welcome to my secret diary !")

const name=prompt("What's your name ?");

if (name === "David") {
  console.log("I really wanna stay at your house, and i hope this works out");
} else {
  console.log("Get away !");
}
 
 *******ex9*****
 
 function choomChoom(a){
 if(a % 2 ==0){
 return "choom"
 }else{
 return "ChoomChoom"}
  }
  
*****ex10******

function cyberNumber(a){

if (a % 3 == 0 && a % 5 == 0  ) {
  console.log("CyberPunk2077");
  return "CyberPunk2077";
}  if ( a % 3 == 0){
  console.log("Cyber")
  return "Cyber"
} if (a % 5 == 0 ){
  console.log("Punk");
  return "Punk";
}  else {
console.log("pas mutliple de 3 et 5")}
}

*****ex11*******

function bissextile (year){
if (year % 4 == 0 && year % 100 != 0 || year % 400 == 0) {
console.log("0")
return 0
} else {
console.log("1")
return 1}
}

bissextile (1700)

module.exports = {
bissextile
}



*****ex12********

function toto (a,b) {
  console.log(((a+b)*b)/2;
  return((a+b)*b)/2
}

module.exports = {
toto
}
 
 
