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
