# PROG8830: Practical Lab 8 – Terraform Advanced Features

## Overview
This project demonstrates advanced Terraform features including loops, functions, and modular infrastructure for a web application.

## How to Run
1. Install Terraform CLI.
2. Clone this repo.
3. Run `terraform init`, `terraform plan`, and `terraform apply`.

## Tasks Breakdown

### Task 1: Loops
- Used `count` inside a module to create 3 identical EC2 instances.
- Used `for_each` to create security groups with unique ports.

### Task 2: Functions
- Demonstrated string, numeric, collection, date/time, and networking functions.

### Task 3: Enhancements
- Refactored EC2 creation into a reusable module.
- Used dynamic expressions for better flexibility.

## Lessons Learned
- `count` is ideal for identical resources; `for_each` is better for unique configurations.
- Functions simplify logic and improve reusability in IaC.

## Author
Zafar Ahmed Shaik
