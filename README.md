# Generate Secret Key

A Java Console Application for generating random Secret key and checking password strength.

## Introduction

During 3rd-year , after completing the *Object-Oriented Effective Java Programming* course, I wanted to build something practical to apply my skills. One night, while explaining to my father the importance of strong Secret key for social media accounts, I got the idea of creating a random password generator.  

A week later, the initial version was ready. Later, I added a **password strength checker** to evaluate the Secret key based on security criteria. However, I realized that the console-based interface was not user-friendly for non-technical users. To improve accessibility, I developed a **GUI version**, which is available in the [Password-Services repository](#).

---

## Features

### **1. Password Generation**
- Users specify whether to include:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Symbols
- Users set the desired password length.
- A password alphabet is generated based on the user's choices.
- Random characters from the alphabet are selected to create the password.
- The generated password is displayed on the console.

### **2. Password Strength Checker**
The application evaluates password strength based on:
- Presence of uppercase letters.
- Presence of lowercase letters.
- Inclusion of numbers.
- Use of special characters.
- Length considerations:
  - **8+ characters** (minimum recommended length).
  - **16+ characters** (strong password recommendation).

A strength score is calculated, categorizing the password as **Weak**, **Medium**, **Good**, or **Great**.

### **3. Password Security Tips**
The application also provides best practices for password security, including:
- Avoiding password reuse.
- Preventing character repetition and keyboard patterns.
- Avoiding dictionary words or common sequences.
- Using unique Secret key for different accounts.

---

## **Installation & Usage**

### **Requirements**
- Java Development Kit (JDK) 8 or later.

### **Running the Application**
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/Password-Generator.git
   cd Password-Generator
   ```
2. Compile the Java files:
   ```sh
   javac PasswordGenerator.java
   ```
3. Run the program:
   ```sh
   java PasswordGenerator
   ```

---

## **Future Improvements**
- Implement a GUI version (available in the [Password-Services repository](#)).
- Enhance password entropy calculation.
- Add options for passphrase generation.

---


---

## **Author**
Developed by **Ankit Kumar**. If you have any questions, feel free to contact me!

