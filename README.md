# Budget App

This is my solution for the **Budget App** project from freeCodeCamp's **Scientific Computing with Python** certification.

## 📋 What it does
- Create different budget categories (Food, Clothing, Entertainment, etc.)
- Deposit money into a category
- Withdraw money from a category
- Transfer money between categories
- Generate a text-based **spending chart** showing percentage spent in each category

## 🚀 How to run
```bash
python budget.py
from budget import Category

food = Category("Food")
food.deposit(1000, "initial deposit")
food.withdraw(105.15, "groceries")
food.withdraw(15.89, "restaurant")

clothing = Category("Clothing")
food.transfer(50, clothing)

print(food)
print(create_spend_chart([food, clothing]))
