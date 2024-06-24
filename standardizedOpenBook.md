## Summative Coding Assessment Outline - Javascript Fundamentals

### 1. Objectives

This assessment aims to evaluate students' understanding of fundamental programming constructs in Javascript, covering:

- Basic control flow using conditional statements.
- Iterative problem solving using `while` loops.
- Application of arrays to manipulate numerical data.

### 2. Scope

The assessment will cover the following concepts from the module:

- **Variables and Data Types:** Numbers only (including decimals)
- **Input/Output:** `readline-sync` package (`questionInt()`), `console.log()`
- **Operators:** Arithmetic, Assignment, Comparison, `Math.floor()`
- **Conditional Statements:** `if`, `else`, `else if`
- **Loops:** `while` loops only (including nested loops)
- **Arrays:** Single dimensional arrays of numbers, declaration, initialization, accessing and modifying elements

### 3. Scope Limitations (Strict)

The assessment **will NOT** include:

- String data type or any string manipulation.
- Logical operators (`&&`, `||`, `!`), including strictly equals (`===`).
- `for` loops or any other looping constructs besides `while`.
- Multi-dimensional arrays, objects, or any other data structures.
- Functions or function calls.

### 4. Detailed Outline (Question Patterns)

**Category 1: Basic Control Flow (10 marks)**

- **Objective:** Assess understanding of `if`, `else`, and `else if` statements.
- **Pattern:** 
    - Present a scenario requiring a simple decision based on numerical input.
    - Students should write a program that:
        1. Takes numerical input using `questionInt()`.
        2. Uses `if`, `else`, and/or `else if` statements to evaluate conditions involving the input and potentially other numerical values.
        3. Outputs the result or a message based on the evaluation using `console.log()`.

**Category 2: Loops with Control Flow (20 marks)**

- **Objective:** Evaluate the application of `while` loops along with conditional statements.
- **Pattern:** 
    - Present a problem requiring iterative processing of numerical input until a specific condition is met.
    - Students should write a program that:
        1. Uses a `while` loop to repeatedly:
            - Takes numerical input using `questionInt()`.
            - Applies `if`, `else`, and/or `else if` statements for conditional processing within the loop.
            - Performs calculations or operations based on the input and conditions.
        2. Outputs the final result or a message after the loop terminates using `console.log()`.
    - May involve nested `while` loops for more complex scenarios.

**Category 3: Arrays and Combined Concepts (20 marks)**

- **Objective:** Assess the ability to use arrays alongside previously learned concepts.
- **Pattern:** 
    - Present a problem involving the manipulation of a single-dimensional array of numbers.
    - Students should write a program that:
        1. Declares and initializes a numerical array.
        2. Uses a `while` loop to iterate through the array elements.
        3. Within the loop:
            - Applies `if`, `else`, and/or `else if` statements for conditional processing based on array element values.
            - Performs calculations or modifications on array elements based on conditions.
        4. Outputs the final array or a result based on the array manipulation using `console.log()`.
    - May involve finding specific elements, calculating sums/averages, or rearranging elements within the array. 
