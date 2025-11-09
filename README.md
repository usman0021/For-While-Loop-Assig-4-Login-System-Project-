# 🐍 Python For & While Loop Assignment – Login System & Pattern Generation

This project demonstrates the use of **loops (`for` and `while`)** in Python through practical examples such as a **login system** and **pattern printing**.

It was developed as part of the **Generative AI & Chatbot Course**, focusing on strengthening Python fundamentals like **loops**, **conditional logic**, and **data structures**.

---

## 📘 **Project Overview**

This Jupyter Notebook includes the following exercises:

### 1. 🧠 **Dictionary-Based Login System**
- Stores user credentials (email → password) in a Python **dictionary**.
- Allows users to **add new accounts** dynamically.
- Implements **two versions** of the login system:
  - Using a **`for` loop** (limited login attempts)
  - Using a **`while` loop** (continuous login until success)

### 2. ⭐ **Asterisk Table Generation**
- Generates a **4-column, 6-row** asterisk table using:
  - `for` loop
  - `while` loop  
- Demonstrates the use of **nested loops** to print patterns.

---

## 🚀 **Features**

✅ Dynamic user registration (dictionary updates with user input)  
✅ Login validation with limited and unlimited attempts  
✅ Error handling for incorrect email/password  
✅ Loop-based table printing  
✅ Beginner-friendly, easy-to-follow code  

---

## 💻 **Code Snippet Example**

```python
# Example: Login System using for loop
for attempt in range(3):
    Email = input("Enter your email: ")

    if '@' in Email:
        Password = input("Enter your password: ")

        if Email in users and users[Email] == Password:
            print("Login Successful! Welcome,", Email)
            break
        else:
            print("Incorrect email or password. Try again.")
    else:
        print("Invalid email format.")
else:
    print("Too many failed attempts. Try again later.")
```

---

## 🧩 **Asterisk Table Example**

```python
rows = 6
columns = 4

for i in range(rows):
    for j in range(columns):
        print("*", end=" ")
    print()
```

**Output:**
```
* * * *
* * * *
* * * *
* * * *
* * * *
* * * *
```

---

## 🧠 **Concepts Practiced**

- `for` and `while` loops  
- Nested loops for pattern generation  
- Dictionaries for data storage  
- Conditional logic and input validation  
- Basic algorithmic thinking  

---

## 🛠️ **Requirements**

- Python 3.x  
- Jupyter Notebook or any Python IDE  

Install Jupyter if needed:
```bash
pip install notebook
```

Run the notebook:
```bash
jupyter notebook
```

---

## 📚 **References**

- [Official Python Docs – Loops](https://docs.python.org/3/tutorial/controlflow.html#for-statements)
- [Python Dictionaries](https://docs.python.org/3/tutorial/datastructures.html#dictionaries)
- [Python While Loops](https://docs.python.org/3/tutorial/controlflow.html#break-and-continue-statements-and-else-clauses-on-loops)

---

## 👨‍💻 **Author**

**Muhammad Usman Khan**
AI Generative & Chatbot Course Student
*Instructor: Engr Muhammad Junaid Riaz*

---

⭐ **If you found this project useful, please star the repository on GitHub!**
