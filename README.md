// Addition of two numbers
function addNumbers(num1, num2) {
  return num1 + num2;
}

// Multiplication of two numbers
function multiplyNumbers(num1, num2) {
  return num1 * num2;
}

// Deletion of two numbers
function deleteNumbers(num1, num2) {
  return num1 - num2;
}

// Example usage
const x = 5;
const y = 3;

const sum = addNumbers(x, y);
console.log(`The sum of ${x} and ${y} is ${sum}`);

const product = multiplyNumbers(x, y);
console.log(`The product of ${x} and ${y} is ${product}`);

const diff = deleteNumbers(x, y);
console.log(`The difference of ${x} and ${y} is ${diff}`);
