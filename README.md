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
