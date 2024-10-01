# Billing and Inventory Management System
 A easy to use billing and inventory management system in java with database fully dynamic

## Overview

This system is designed to provide an affordable, user-friendly solution for small and local businesses. It helps maintain product inventory and generates client bills in PDF format, with features for tracking sales, managing inventory, and generating reports (weekly/monthly).

## Features

- **Inventory Management**: Add, update, delete, and deactivate products with auto-generated product IDs.
- **Billing System**: Generate bills with GST, validate product availability, and auto-update inventory after each sale.
- **Sales Reporting**: View sales records, filter by month, and print or save reports.
- **PDF Bill Generation**: Generate and print customer bills with sales summaries.
  
## Technology Stack

- **Language**: Java (String, 2D Arrays)
- **Frontend**: Java Swing and AWT for GUI (`JFrame`, `JPanels`, `JTextFields`, `JButtons`, `JTables`)
- **Backend**: MySQL (Database: `billing_system` with tables `products` and `sales`)

## Modules

1. **Login**: Secure login with hardcoded credentials, includes a "show password" feature.
2. **Home Page**: Central hub to navigate between modules.
3. **New Product**: Add new products with auto-generated product IDs and GST category selection.
4. **Update Product**: Modify product details, activate/deactivate products, or delete discontinued items.
5. **Product Details**: View complete inventory details, print inventory table if needed.
6. **Billing**: Add customer details, select available products, calculate total (with GST), generate and print bills.
7. **Sales**: View sales records by month, display total quantities and sales values, print sales reports.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YourRepo/BillingSystem.git
