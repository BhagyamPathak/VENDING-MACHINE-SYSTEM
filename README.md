
# 🧾 Vending Machine Managing System

This is a Python desktop application built with the `tkinter` library to manage a simple vending machine billing system. It includes a login screen for authentication, followed by a billing interface where item details, customer information, and cost calculations are handled.

---

## 🔐 Login Credentials

To access the billing system, use the following credentials:

- **Username:** `abc`
- **Password:** `123`

---

## ✨ Key Features

- ✅ **Login Authentication**  
  Prevents unauthorized access with hardcoded username and password.

- 🧾 **Bill Generation**  
  - Generates a random bill number for each transaction  
  - Records customer name, item name, quantity, and cost  
  - Calculates total cost instantly  
  - Displays current date, time, and day of the week  
  - Saves each transaction to `data.txt` for record-keeping

- ♻️ **Reset & Total Functionality**  
  - `Total`: Calculates and displays the total cost  
  - `Reset`: Clears all input fields for new billing

---

## 🧮 Example Workflow

1. Open the app and log in using the provided credentials.
2. Enter the customer name, item name, quantity, and cost per item.
3. Click `Total` to view the cost or `Bill` to save and generate the bill.
4. The bill data is saved to `data.txt` in the project directory.

---

## 💾 File Output

All billing data is appended to a file called `data.txt`, which includes:
- Bill number
- Customer name
- Item details
- Quantity and cost
- Date, time, and day of the week

---

## 🛠 Requirements

- Python 3.x
- No external libraries required (uses only standard Python libraries)

---

## 🚀 How to Run

Make sure you have Python 3 installed. Then run the file using:

```bash
python vending_machine.py
