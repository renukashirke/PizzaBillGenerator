# Pizza Bill Generator App

## Introduction
This Java application is a Pizza Bill Generator that allows users to order pizzas and generates a bill based on their choices. The app supports two types of pizzas: Normal Pizza and Deluxe Pizza, each with different variants and add-ons.

## Problem Statement
The pizza store offers two main types of pizzas:

1. **Normal Pizza:**
   - Two variants: Veg and Non-Veg.
   - Fixed base prices: Veg - 300 INR, Non-Veg - 400 INR.
   - Add-ons: Extra Cheese (100 INR), Extra Toppings (150 INR).
   - Takeaway option with an additional 20 INR charge.

2. **Deluxe Pizza:**
   - Two variants: Veg and Non-Veg.
   - Default add-ons: Extra Cheese and Extra Toppings (no need to order separately).
   - Takeaway option with an additional 20 INR charge.

## Proposed Solution
The solution is implemented using Core Java and Object-Oriented Programming (OOP) principles. Two classes are defined: `Pizza` and `DeluxPizza`. The `Pizza` class represents a generic pizza with methods to add extra cheese, extra toppings, and specify takeaway. The `DeluxPizza` class extends `Pizza` and automatically adds extra cheese and extra toppings by default.

The main class `Main` interacts with the user, takes input for pizza type, variant, add-ons, and takeaway preference, and then generates and displays the bill.
