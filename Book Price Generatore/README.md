# 📚 Book Price Generator (Java Swing GUI)

## 📖 Introduction

This is a **simple Java Swing GUI application** that generates the total price of books based on the **book code, quantity, and customer type**.

The program allows the user to enter book details and automatically calculates:

* Price per book
* Total cost
* Discount based on customer type
* Final net price

The result is displayed in a **formatted bill inside a text area**, making it easy to view all details at once.

This project was created as part of my learning journey while practicing **Java GUI development using Swing**.

---

# 🎯 Purpose of This Project

This project was built to practice:

* Java **Swing GUI components**
* Handling **user input using JTextField**
* Using **JComboBox for selections**
* Implementing **switch statements**
* Performing **basic calculations and logic**
* Displaying formatted output using **JTextArea**

It helped me understand how a simple **billing system works in real-world applications**.

---

# 🖥 Interface Components

The application uses the following GUI elements:

| Component  | Purpose                                                  |
| ---------- | -------------------------------------------------------- |
| JTextField | Takes input like book code, title, author, and quantity  |
| JComboBox  | Selects the customer type (Bookseller, School, Customer) |
| JButton    | Generates the bill                                       |
| JTextArea  | Displays the final bill                                  |

---

# 📥 Inputs Required

The user needs to enter:

* **Book Code**
* **Book Title**
* **Author Name**
* **Quantity**
* **Customer Type** (selected from dropdown)

Customer types available:

* Bookseller
* School
* Customer

---

# 💰 Book Price List

The price is automatically determined based on the **Book Code**.

| Book Code   | Price                |
| ----------- | -------------------- |
| B101        | ₹350                 |
| B102        | ₹500                 |
| B103        | ₹200                 |
| Other Codes | ₹250 (Default Price) |

---

# 🎁 Discount System

Discount is applied depending on the **customer type**.

| Customer Type | Discount |
| ------------- | -------- |
| Bookseller    | 25%      |
| School        | 20%      |
| Customer      | 5%       |

---

# ⚙ How the Program Works

1. User enters book details in the text fields.
2. User selects customer type from the dropdown.
3. When the **Generate Bill button** is pressed:

   * The program checks the **book code**
   * Assigns the **price per book**
   * Calculates **total price**
   * Applies **discount based on customer type**
4. The **final bill** is displayed in the text area.

---

# 🧾 Example Output

```
Book Code: B101
Title: Java Programming
Author: James Gosling
Quantity: 3
Price per book: ₹350
Total: ₹1050
Discount: ₹262.5
Net Price: ₹787.5
```

---

# 📚 What I Learned From This Project

While building this project I practiced:

* Creating **GUI forms in Java Swing**
* Working with **user inputs**
* Implementing **conditional logic**
* Using **switch expressions**
* Formatting output for better readability

It also helped me understand how small programs can simulate **basic business logic like billing systems**.

---

# 🚀 Future Improvements

Possible improvements for this project:

* Add **database support**
* Save bills automatically
* Add **more book codes**
* Improve GUI design
* Add **error handling for invalid inputs**

---
