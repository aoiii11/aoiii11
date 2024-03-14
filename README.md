第三章習題答案

console.log(2 * 10); // Exercise 1
console.log(100 % 7); // Exercise 2
console.log(Math.pow(10, 3)); // Exercise 3
console.log("5" + 10); // Exercise 4
console.log(!true); // Exercise 5
console.log("hello" + "world"); // Exercise 6
console.log(typeof 123); // Exercise 7
console.log("2" < 4); // Exercise 8
console.log(15 > 10 && 15 <= 20); // Exercise 9
console.log("hello" !== undefined && "hello" !== false); // Exercise 10
console.log(25 % 2 === 0 ? "Even" : "Odd"); // Exercise 11
let x = 10, y = 20;
console.log(x > y ? x : y); // Exercise 12

第四章習題答案

// 1. if-else statement
let number = 250; // example number
if (number < 100) {
  console.log("Less than 100");
} else if (number === 400) {
  console.log("Exactly 400");
} else {
  console.log("Other number");
}

// 2. Sum of odd numbers and sum of numbers divisible by 3
let sumOdd = 0, sumDiv3 = 0;
for (let i = 1; i <= 10; i++) {
  if (i % 2 !== 0) sumOdd += i;
  if (i % 3 === 0) sumDiv3 += i;
}
console.log(`Sum of odd numbers: ${sumOdd}`);
console.log(`Sum of numbers divisible by 3: ${sumDiv3}`);

// 3. for loop to print a series of numbers (not clear which series, assuming 1 to 10)
for (let i = 1; i <= 10; i++) {
  console.log(i);
}

// 4. for loop with powers of 2
for (let i = 1; i <= 10; i++) {
  console.log(2 ** i);
}

// 5. while loop (since the operation and condition are not specified, I'll use a placeholder)
let count = 0;
while (count < 5) {
  console.log(count);
  count++;
}

// 6. another while loop example (details not specified)
count = 10;
while (count > 0) {
  console.log(count);
  count--;
}

// 7. do...while loop example (details not specified)
do {
  console.log("This will print at least once");
} while (false);

// 8. for...of loop to iterate over an array
let array = [1, 5, 2, 7, 3];
for (let value of array) {
  console.log(value);
}

// 9. for loop over an array to print values
let arrayOfValues = [2, 3, 4, 5, 6, 7, 8];
for (let i = 0; i < arrayOfValues.length; i++) {
  console.log(arrayOfValues[i]);
}

// 10. for...in loop to iterate over the properties of an object
let object = { c: 3, d: 4, e: 5 };
for (let key in object) {
  console.log(key + ": " + object[key]);






