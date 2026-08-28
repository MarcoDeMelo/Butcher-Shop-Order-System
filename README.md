# Butcher Shop Order System

A C++ console application that processes customer meat orders, calculates prices based on meat type and weight, and generates formatted receipts.

## Features

* Customer name input
* Chicken, pork, and beef order selection
* Weight-based price calculation
* Input validation for meat type and weight
* Multiple customer orders
* Formatted receipt generation
* Receipt output saved to `receipts.txt`

## Supported Meats

| Meat    | Price per kg |
| ------- | -----------: |
| Chicken |        $5.49 |
| Pork    |        $6.80 |
| Beef    |        $8.80 |

## How It Works

The application prompts for a customer's name, meat selection, and weight.

The total cost is calculated based on the selected meat:

```text
Cost = Weight × Price per kg
```

The order information is then written to `receipts.txt` and displayed to the user.

## Input Validation

The application validates:

* Meat selection
* Meat weight
* Weight range between 0 and 100 kg

Invalid input is rejected and the user is prompted to enter the information again.

## Technologies

* C++
* Standard Library
* File I/O
* Console Input/Output

## Purpose

This project demonstrates fundamental C++ programming concepts including input validation, conditional logic, loops, formatted output, file handling, and basic application flow.
