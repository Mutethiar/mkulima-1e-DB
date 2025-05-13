
# MUKLIMA-1e

## Project Description

**MUKLIMA-1e** is a platform designed to connect farmers directly with clients by enabling the management of farm operations, product listings, and real-time communication. The platform supports data entry, product tracking, order processing, and farm analytics, offering a comprehensive and intuitive solution for modern farmers.

## Features

- Farmer and client user registration
- Product listing and management
- Order placement and tracking
- Farm production logs (milk, feed, livestock)
- Direct messaging between users
- Role-based access and real-time analytics

## Database Setup

This project uses MySQL. To set up the database, run the SQL commands from the included `muklima_schema.sql` file using a tool like MySQL Workbench or the MySQL CLI.

```
mysql -u your_username -p < muklima_schema.sql
```

## Tables Included

- `users`: Stores information about farmers and clients
- `products`: Products listed by farmers
- `orders`: Orders placed by clients
- `production_logs`: Records of production data
- `messages`: Optional chat functionality between users

## Getting Started

Ensure MySQL is installed and running. Update your Python application's database connection settings to match your local MySQL configuration.

---

© 2025 MUKLIMA-1e
