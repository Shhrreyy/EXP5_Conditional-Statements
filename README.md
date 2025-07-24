# EXP 5: Conditional and Switch Statements in C++

## 🔰 Aim

To understand and apply decision-making in C++ using:
1. **If-else statements** to check conditions like even/odd, vowel/consonant, and largest number.
2. **Switch-case statements** for basic menu-driven logic and arithmetic operations.

---

## 📚 Theory

C++ provides conditional and branching mechanisms that control program flow based on given conditions. These include:

### 🔹 If-Else:
Used to test **multiple conditions** using `if`, `else if`, and `else`. It allows more flexible comparison logic.

### 🔹 Switch-Case:
Used for **multi-way branching**. Ideal when a variable can match against several constant values. Each case is followed by a block of code and usually ends with a `break` statement to prevent fall-through.

---

## 🧠 Algorithms

### ✅ 1. Even or Odd

1. Start  
2. Input a number  
3. If `number % 2 == 0`, it is even  
4. Else, it is odd  
5. End  

---

### ✅ 2. Vowel or Consonant

1. Start  
2. Input a character  
3. Convert to lowercase (if needed)  
4. If character is 'a', 'e', 'i', 'o', 'u' → Vowel  
5. Else if it’s an alphabet → Consonant  
6. Else → Not an alphabet  
7. End  

---

### ✅ 3. Largest of Three Numbers

1. Start  
2. Input three numbers `a`, `b`, `c`  
3. Compare using `if`:
   - If `a >= b && a >= c` → a is largest  
   - Else if `b >= a && b >= c` → b is largest  
   - Else → c is largest  
4. End  

---

### ✅ 4. Basic Switch-Case (Option Menu)

1. Start  
2. Display a simple menu with n options  
3. Take user input as `choice`  
4. Use `switch(choice)`:
   - Case 1 → Display Message 1  
   - Case 2 → Display Message 2  
   - Case 3 → Display Message 3
   - .
   - .
   - . 
   - Default → Invalid choice  
5. End  

---

### ✅ 5. Switch-Case Calculator

1. Start  
2. Input two numbers `a`, `b`  
3. Input operation symbol (`+`, `-`, `*`, `/`)  
4. Use `switch(op)`:
   - Case '+' → Add  
   - Case '-' → Subtract  
   - Case '*' → Multiply  
   - Case '/' → Divide (if `b != 0`)  
   - Default → Invalid operation  
5. End  

---

## ✅ Conclusion

This experiment provides hands-on practice with **conditional (`if-else`)** and **branching (`switch-case`)** statements in C++. Through five different real-life inspired programs, students learn how to direct control flow based on various logical and arithmetic conditions. These tools are foundational for all types of programming — from simple automation to complex decision-making logic.

---

## 📌 Topics Covered

- Conditional statements (`if`, `else if`, `else`)
- Logical operators (`==`, `>=`, `%`)
- Switch-case syntax and structure
- Menu-driven programs
- Operator-based calculations using switch
