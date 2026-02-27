# Tip Calculator 💰

A simple Python program that calculates how much each person should pay when splitting a bill, including tip.

---

## 🚀 Features

- Takes total bill amount as input
- Allows user to choose tip percentage
- Splits the total bill among multiple people
- Rounds the final amount to 2 decimal places

---

## 🧠 How the Code Works

### 1️⃣ User Input

The program asks the user for:
- Total bill amount
- Tip percentage (10, 12, 15, etc.)
- Number of people splitting the bill

Example:
```
What was the total bill? $100
What percentage tip would you like to give? 10
How many people to split the bill? 4
```

---

### 2️⃣ Convert Tip to Percentage

```
tip_as_percent = tip / 100
```

This converts the tip value (e.g., 10) into decimal form (0.10).

---

### 3️⃣ Calculate Total Bill with Tip

```
total_tip_amount = bill * tip_as_percent
total_bill = bill + total_tip_amount
```

First calculates the tip amount, then adds it to the original bill.

---

### 4️⃣ Split Per Person

```
bill_per_person = total_bill / people
```

Divides the total bill equally among the number of people.

---

### 5️⃣ Round the Final Amount

```
final_amount = round(bill_per_person, 2)
```

Ensures the result shows only 2 decimal places (like real money).

---

## 🖥️ Example Run

```
Welcome to the tip calculator!
What was the total bill? $150
What percentage tip would you like to give? 12
How many people to split the bill? 5
Each person should pay: $33.6
```

---

## 🛠 Built With

- Python 3

---

## 📌 Author

Adonish Chandra Pal  
BCA Student | Aspiring Software Developer
