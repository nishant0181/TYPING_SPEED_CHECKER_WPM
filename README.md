# TYPING_SPEED_CHECKER_WPM

# 🖥️ Typing Speed Tester — Java CLI App

This is a simple **Typing Speed Tester** built using pure Java.  
It helps users test how fast they can type a given sentence — and calculates their **Words Per Minute (WPM)**.

---

## 🎯 Features

- Command-line interface (CLI)
- Displays a fixed sentence to type
- Records start and end time using `System.currentTimeMillis()`
- Calculates total time taken
- Counts total words typed
- Calculates and displays WPM
- (Optional) Checks whether typed sentence matches the original

---

## 🧠 Concepts Used

| Concept                  | Description                            |
|--------------------------|----------------------------------------|
| `Scanner`                | To take user input  
| `System.currentTimeMillis()` | To measure typing duration  
| `String.split(" ")`      | To count words typed  
| Math operations          | To convert milliseconds to WPM  
| Conditional logic        | (Optional) To check correctness

---

## 🧪 Sample Output

WELCOME TO TYPING SPEED TESTER!
Type this sentence as fast as you can: "Java is powerful and fun to learn."
Press ENTER when you're ready...

Now type the sentence:
Java is powerful and fun to learn.
You took 11000 milliseconds.
You typed 7 words.
Your WPM is: 38.18
✅ You typed the sentence correctly!

yaml
Copy
Edit

---

## 💡 How to Run

1. Copy the code into a file named `TypingSpeed.java`
2. Compile the file:
   ```bash
   javac TypingSpeed.java
Run the program:

bash
Copy
Edit
java TypingSpeed
📌 Author
Nishant Dhanani
Java Developer | Building Strong Foundations in Tech


📚 Future Improvements
Show a random sentence each time

Support multiple rounds

Store high scores or fastest times

Add accuracy % (letter-by-letter comparison)

🧭 Learning Outcome
This project helped build confidence in:

Java basics

Timers and speed calculations

String and input handling

Writing clean, working CLI tools

⭐ Feel free to fork, star, or build on top of it!
