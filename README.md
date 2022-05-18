# codewars
// Write a function "greet" that returns "hello world!"
function greet() {
  return "hello world!";
} 
function isDivideBy(number, a, b) {
  // good luck
if (number % a === 0 && number % b === 0) {
  return true;
} else {
  return false;
}
}
function capitalizeWord(word) {
  return word[0].toUpperCase() + word.slice(1);
 
}
function findNeedle(haystack) {
  // your code here
   return 'found the needle at position ' + haystack.indexOf('needle');
  
}
function solution(str) {
	for (var solution = '', i = str.length - 1; i >= 0; i--) {
		solution += str[i];
	}
	return solution;
}
function digitize(n) {
  //code here
  var str = String(n);
  return str.split('').map(Number).reverse()
}
function even_or_odd(number) {
	var x = number % 2;
  if (x === 0) {
		return "Even";
	} else {
		return "Odd";
	};
}
function positiveSum(arr) {
 let sum = 0;
 for(let i = 0; i < arr.length; i++) {
   if(arr[i] > 0) {
    sum += arr[i];
  }
 }
return sum;
}
function makeNegative(num){
  if (num>0){
    return -num
  }
  else if (num<0){
    return num
  }
  else {
    return 0
  }
}
function opposite(number) {
return -number;
}
function removeChar(str){
 //You got this!
 return str.slice(1, str.length - 1);
};
function boolToWord( bool ){
  if (bool) {
    return "Yes";
  } else {
    return "No";
  }
}

function repeatStr (n, s) {
  return s.repeat(n);
}
var summation = function (num) {
  // Code here
 let sum = 0;
  for (let i = 0; i <= num; i++){
    sum +=i;
  }
  return sum;
}
function numberToString(num) {
  // Return a string of the number here!
  return num.toString();
}
class SmallestIntegerFinder {
  findSmallestInt(args) {
   let smallest;

    for(let i = 0; i < args.length; i++){
        if(args[i] <= args[0]) {
          args[0] = args[i];
          smallest = args[i];
        }
    }

    return smallest
}
}  
 function noSpace(x) {
    let newStr = ''
    for(let i = 0; i < x.length; i++) {
        if(x[i] !== " "){
            newStr += x[i]
        }
    }
    return newStr
} 
function countSheeps(arrayOfSheep) {
  // TODO May the force be with you
  let counter = 0;
  for(let i = 0; i < arrayOfSheep.length; i++) {
    if(arrayOfSheep[i]) counter += 1
  }
  return counter
}
function squareSum(numbers){
let sum = 0;
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i] ** 2;
  }
  return sum;
}
function isDivisible(n, x, y) {
 return (n % x == 0 && n % y == 0) ? true : false; 
}
function century(year) {
  // Finish this :)
  let a = 0;
  while(year > 0) {
    year = year - 100;
    a = a + 1;
  }
  return a;
}

function basicOp(operation, value1, value2)
{
  // Code
   if(operation == '+')return value1 + value2;
     
    if(operation == '-')return value1 - value2;
      
    if(operation == '*')return value1 * value2;
     if(operation == '/')return value1 / value2;
}
function basicOp(operation, value1, value2) {
    switch (operation) {
        case '+':
            return value1 + value2;
        case '-':
            return value1 - value2;
        case '*':
            return value1 * value2;
        case '/':
            return value1 / value2;
        default:
            return 0;
    }
}
function abbrevName(name){
  var nam = name.split(' ');
  return (nam[0][0] + '.' + nam[1][0]).toUpperCase();
}
function abbrevName(name){
    name = name.toUpperCase().split(' ');
    return name[0][0] + '.' + name[1][0];
}
function arrayPlusArray(arr1, arr2) {

  return arr1.concat(arr2).reduce((a, b) => a + b);
}//something went wrong
function litres(time) {
  return Math.floor(time / 2);
}
const quarterOf = (month) => {
  // Your code here
  if (month >= 1 && month <= 3) {
    return 1;
  } else if (month >= 4 && month <= 6) {
    return 2;
  } else if (month >= 7 && month <= 9) {
    return 3;
  } else {
    return 4;
  }
}
function expressionMatter(a, b, c) {
 // highest achievable result
  var maxResult = Math.max(
        a+b+c,
        a*b*c,
        a*b+c,
        a*(b+c),
        a+b*c,
        (a+b)*c
    );
    return maxResult;
}
function maps(x){
  return x.map(n => n * 2);
}
var stringToNumber = function(str){
  // put your code here
  
  return parseInt(str);
}
function getCount(str) {
  var vowelsCount = 0;
  
  // enter your majic here
  const vowelArr = ['a', 'e', 'i', 'o', 'u'];
  for (let char of str) {
    if (vowelArr.includes(char)) {
      vowelsCount++;
    }
  }
  
  return vowelsCount;
}
function getCount(str) {
  var vowelsCount = 0;
  var vowels = ["a","e","i","o","u"];
  for(var i = 0;i < str.length;i++){
    for(var j=0;j<vowels.length;j++){
      if(str[i] === vowels[j]){
        vowelsCount++;
      }
    }
  }
  
  return vowelsCount;
}
function greet(name){
  //your code here
  return "Hello, " + name + " how are you doing today?";
}
function greet(name){
  
  if(name === "Johnny"){
    return "Hello, my love!";
} else {return "Hello, " + name + "!";
  }
  }
function booleanToString(b){
  //your code here
  if (b) {
    return 'true';
  } else {
    return 'false';
  }
}
function doubleInteger(i) {
  // i will be an integer. Double it and return it.
  return i * 2;
}
function getAverage(marks){
  return Math.floor(marks.reduce((a, b) => a + b) / marks.length);
}
function invert(array) {
   return array.map(num => num * -1) ;
}
function past(h, m, s){
  //#Happy Coding! ^_^
  const hourInMilisec = h * 60 * 60 * 1000;
  const minInMilisec = m * 60 * 1000;
  const secInMilisec = s * 1000;
  return hourInMilisec + minInMilisec + secInMilisec;
}
function makeUpperCase(str) {
  // Code here
  return str.toUpperCase();
}
function hero(bullets, dragons){
//Get Coding!
   if (bullets >= dragons * 2) {
    return true;
  } else {
    return false;
  }
}
function reverseWords(str){
  let array = str.split(" ");
 array.reverse(); 
  return array.join(" ");// reverse those words
}
 
function countPositivesSumNegatives(input) {
if (input == null || input.length < 1){
  return [];
}
var newArray = [0, 0];
for (var i = 0; i < input.length; i++){
  if (input[i] > 0)
    {
    newArray[0] += 1;
    }
  else {
    newArray[1] += input[i];
  }
  }
return newArray;
}
function countPositivesSumNegatives(input) {
  var newArr = [];
  var positiveNumber = 0;
  var negativeNumber = 0;
  
  // Validate Input
  if (input === null || input.length === 0)
    return newArr;
  
  // Loop through array of Numbers 
  for (var i = 0; i < input.length; i++) {
    if (input[i] == 0)
     continue;
  
    // Count positives
    else if (input[i] > 0) 
      positiveNumber++;     
        
    // Sum negatives
    else if (input[i] < 0) 
      negativeNumber += input[i];
    
  }
  
  // Prepare Output
  newArr.push(positiveNumber);
  newArr.push(negativeNumber);
  
  return newArr;
  }
function bmi(weight, height) {
  let bmi = weight / (height * height);
  if (bmi <= 18.5) {
    return "Underweight";
  } else if ( bmi <= 25.0) {
    return "Normal";
  } else if ( bmi <= 30.0) {
    return "Overweight";
    } else{
      return "Obese";
    }

}


function solution(number){
  
    let counter = 0
    for(let i = 1; i < number; i++) {
        if(i % 3 === 0 || i % 5 === 0) {
            counter += i
        }
    }
    return counter
}

function check(a, x) {
if (a.includes(x)) {
  return true
}else {
  return false
}
}

  
    }

}

  const position = queue.reverse().indexOf('wolf');
  return position === 0 ? 'Pls go away and stop eating my sheep' : 

function paperwork(n, m) {
  if (n > 0 && m > 0) {
    return n * m
  } else {
    return 0
  }
  
}


function DNAtoRNA(dna) {
return dna.replace(/T/g, 'U')
}




function sum (numbers) {
    "use strict";
 return numbers.reduce((a, b) => a + b, 0);
    
};



function areYouPlayingBanjo(name) {
  if (/^[rR]/.test(name))return `${name} plays banjo`;
  return `${name} does not play banjo`;
  
}



var countSheep = function (num){
  let answer = "";
  for(let i = 1; i <= num; i++){
    answer+= `${i} sheep...`
}
  return answer
}

 
 
 function stringToArray(string){
  return string.trim().split(" ")

	// code code code

}


// Write here your multiply-function
function multiply (a, b) {
  return a * b
}


function points(games) {
  // your code here
    let totalPoints = 0;
    let result;
    for (let i = 0; i < games.length; i++) {
        result = games[i];
        if (result[0] > result[2]) {
            totalPoints += 3;
        } else if (result[0] === result[2]) {
            totalPoints += 1;
        }
    }
    return totalPoints;
}



  function elevator(left, right, call){
  return Math.abs(call - left) < Math.abs(call - right) ? 'left' : 'right'
}
  // code on! :)

  

function betterThanAverage(classPoints, yourPoints) {
  return yourPoints > classPoints.reduce((x, y) => x + y, 0)/classPoints.length 
}



function checkForFactor (base, factor) {
  if(base%factor !==0){
    return false}
  else {
  return true} // code here
}


function simpleMultiplication(number) {
     return number * (number % 2 > 0 ? 9 : 8)
}




class Kata {
  static getVolumeOfCuboid(length, width, height) {
   return length * width * height;
  }
}




function plural(n) {
 return !(n === 1);
}



function stringClean(s){
 return s.replace(/[0-9]/g,'');
}

function stringClean(s){
  return s.replace(/\d/g, "");
}




function add(a,b){
    return a+b
}

function divide(a,b){
    return a/b
}

function multiply(a,b){
    return a*b
}

function mod(a,b){
    return a%b
}
   
function exponent(a,b){
    return Math.pow(a, b)
}
    
function subt(a,b){
    return a-b
}


function solution(str){
  let arr = str.split("")
  arr.reverse()
  return arr.join("")
}



const areaOrPerimeter = function(l , w) {
 if (l === w){
   return l * w
 } else{
   return 2 * (l + w)
 }
};







