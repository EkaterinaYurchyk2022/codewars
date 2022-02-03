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
  
