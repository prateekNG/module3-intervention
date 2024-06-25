##  Escape Room JavaScript: A Collaborative Coding Adventure 

###  Station 1: The Decryption Chamber (Variables, Operators, If-Else) 

**Detailed Breakdown:**

**Scenario:**

The year is 1939.  A shadow has fallen over Europe as the Nazi regime tightens its grip.  Our heroes, a group of Allied spies, have infiltrated a hidden bunker, rumored to hold the key to derailing a devastating new weapon.  They find themselves in a dimly lit chamber dominated by a cipher machine, its gears whirring ominously. A cryptic message is pinned beside it, along with a set of seemingly random numbers. The spies soon realize they must crack the code to progress further into the bunker and foil the enemy's plans.

**Puzzle Objective:**  Decipher a coded message using a mathematical formula, variables, and conditional statements to reveal the location of the key to the next room. 

**Puzzle Elements:**

* **The Coded Message:** 
    * Displayed on a screen or printed: "73 104 101 32 107 101 121 32 105 115 32 ..."
    * Represents a sentence where each number corresponds to a letter's ASCII code.
* **The Formula:**
    * Hidden in plain sight (e.g., etched into the side of the cipher machine):  `(number - key) / 2 = ASCII code`
    * "key" is a constant number the students need to discover through trial and error or additional clues.
* **Additional Clues:**
    * Scattered around the station:
        * A discarded notepad with examples of ASCII codes and their corresponding letters.
        * A torn map with specific locations circled (each corresponding to a potential "key" value).
        * A riddle that hints at the importance of subtracting and dividing to reveal the true meaning.

**JavaScript Tasks:**

1. **Declare Variables:** Students must declare variables to store:
    * Each number from the coded message (or the entire message as an array). 
    * The "key" value they will experiment with.
    * The calculated ASCII code (using the formula).
    * The decrypted letter (converted from the ASCII code).

2. **Apply Operators:** Students will use:
    * Subtraction (-) to subtract the "key" from each number in the message.
    * Division (/) to divide the result by 2. 
    * Assignment operator (=) to store results in variables.

3. **Implement If-Else:** Students will use conditional statements:
    * To check if the calculated ASCII code falls within the valid range for letters (65-90 for uppercase, 97-122 for lowercase).
    * If true, the program should convert the ASCII code to the corresponding letter.
    * If false, the program could display an error message or a blank space, prompting students to re-evaluate their chosen "key" value.

4. **Output:** 
    * The program should display the decrypted letters in sequence, ultimately revealing the hidden message: "The key is [location]."

**Unlocking Station 2:**

* The decrypted message reveals the location of the key needed to unlock Station 2 (e.g.,  "The key is behind the portrait").

**Hints:**

* **General:** "Remember how ASCII codes represent characters."
* **Syntax:** "Use `String.fromCharCode()` to convert ASCII codes to letters."
* **Logic:**  "Try different values for the 'key' and see how the output changes. What happens when you use a value that's too high or too low?"

**This station sets a strong foundation for the subsequent stations by requiring students to:**

* Understand and apply basic JavaScript concepts.
* Break down a problem into smaller, manageable steps.
* Debug their code and test different solutions.
* Work collaboratively and communicate effectively within their teams. 
