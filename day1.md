# 📘 My JavaScript Learning Journey

Welcome to my personal documentation of learning JavaScript from beginner to advanced level.

---

## 📅 Day 1 – April 1, 2025

---

### 🧠 Topics Covered
- ✅ Variables (`let`, `const`, `var`)
- ✅ Data Types
- ✅ Operators

---

### 📦 What is Variables?

> A variable is like a container that stores data — like a box with a label on it. You can put something in it (like a name, number, or list), and use it later in your program.

#### 🔹 There are 3 ways to declare variables:
- `var` → (older way)  
- `let` → (most common used)  
- `const` → (value that can't change)

#### 💡 Example:
```javascript
var name = "David";
let age = 21;
const country = "Philippines";
```

---

### 🧊 What is Data Types?

> Data types describe the kind of value a variable can hold.

#### 🔸 1. Primitive Data Types
- **String** → `"Hello"`
- **Number** → `21`
- **Boolean** → `true` or `false`
- **Undefined**
- **Null**
- **BigInt** → `12345678n`
- **Symbol** → `Symbol("id")`

#### 🔸 2. Non-Primitive Data Types
- **Object** → `{ name: David, age: 21 }`
- **Array** → `["hello", "apple", "bananq"]`
- **Function** → `function() {}`
### Example
```javascript
let name = "David";
let age = 21;
let male = true;
let status;
let life = null;
let money = 100,000,000.00;
```
---

### ⚙️ Operation

> An operation is an action that performs something on one or more values (called operands) using operators.

---

#### ➕ 1. Arithmetic Operations
Addition, Subtraction, Multiplication, Division, Modulo, Exponent  
**Operators:** `+`, `-`, `*`, `/`, `%`, `**`
### Example
```javascript
//Addition
let sum = 10 + 5;
console.log(sum); // 15

//Subtraction
let difference = 10 - 3;
console.log(difference); // 7

//Multiplication
let product = 4 * 2;
console.log(product); // 8

//Division
let quotient = 20 / 5;
console.log(quotient); // 4

//Modulo
let remainder = 7 % 3;
console.log(remainder); // 1

//Exponent
let power = 2 ** 3;
console.log(power); // 8 (2 × 2 × 2)

```
---

#### 🧮 2. Assignment Operations
**Operators:** `=`, `+=`, `-=`, `*=`
### Example
```javascript
// Basic Assignment
let x = 10;
console.log(x); // 10

// Add and Assign
x += 5; // x = x + 5
console.log(x); // 15

// Subtract and Assign
x -= 3; // x = x - 3
console.log(x); // 12

// Multiply and Assign
x *= 2; // x = x * 2
console.log(x); // 24

// Divide and Assign
x /= 4; // x = x / 4
console.log(x); // 6

// Modulo and Assign
x %= 5; // x = x % 5
console.log(x); // 1

// Exponent and Assign
x **= 3; // x = x ** 3
console.log(x); // 1 (1 to the power of 3 is still 1)

```
---

#### 🧪 3. Comparison Operations
- `==`  
- `===`  
- `!=`  
- `>`  
- `<`  
- `<=`  
- `>=`
### Example
```javascript
// Equal (==) - compares value only (not type)
console.log(5 == "5"); // true

// Strict Equal (===) - compares value AND type
console.log(5 === "5"); // false

// Not Equal (!=) - value only
console.log(10 != "10"); // false

// Strict Not Equal (!==) - value and type
console.log(10 !== "10"); // true

// Greater Than (>)
console.log(7 > 5); // true

// Less Than (<)
console.log(3 < 8); // true

// Greater Than or Equal To (>=)
console.log(5 >= 5); // true

// Less Than or Equal To (<=)
console.log(4 <= 2); // false

```
---

#### 🔗 4. Logical Operations
- `&&` → and  
- `||` → or  
- `!` → not
```javascript
// AND (&&) - true only if both conditions are true
console.log(true && true);   // true
console.log(true && false);  // false

// OR (||) - true if at least one condition is true
console.log(true || false);  // true
console.log(false || false); // false

// NOT (!) - reverses the truthiness
console.log(!true);  // false
console.log(!false); // true

// Combined Example
let age = 20;
let hasID = true;

// Check if allowed to enter
console.log(age >= 18 && hasID); // true

// Check if minor or missing ID
console.log(age < 18 || !hasID); // false
~
```
---

### ✅ What I Learned
- Difference between `let` and `var`
- Template literals
- Basic arithmetic operations

---

### ❓ Challenges
- Forgot about scope with `let` vs `var`
- Mixed `==` and `===`

---

### 📚 Resources
- [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)  
- [JavaScript Crash Course – YouTube](https://www.youtube.com/watch?v=hdI2bqOjy3c)

---

> 🧠 _“Learning to code is like learning a new language. Practice, patience, and persistence are the keys!”_
