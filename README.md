# Polymorphism and Interface Example in Java

This project is a Java-based demonstration of **object-oriented programming principles**, focusing on **polymorphism**, **interfaces**, and **inheritance**. It was designed to simulate a payroll system that processes both employees and invoices using a unified interface.

## Project Structure

- **Interfaces:**  
  - `Payable` – A common interface implemented by all billable entities.

- **Classes:**
  - `Invoice` – Represents a billable invoice.
  - `Employee` (abstract) – Superclass for all employee types.
    - `SalariedEmployee`
    - `HourlyEmployee`
    - `CommissionEmployee`
    - `BasePlusCommissionEmployee`

- **Main Test:**
  - `PayableInterfaceTest` – Demonstrates polymorphic processing of both `Invoice` and `Employee` objects via the `Payable` interface.

## Features

- Demonstrates how interfaces enable **loose coupling**.
- Shows how polymorphism allows processing different object types in a uniform manner.
- Highlights inheritance and method overriding in a class hierarchy.

