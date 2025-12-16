# Pharmacy Database

A PostgreSQL database for managing pharmacy operations: medicines, suppliers, sales, reviews, and inventory.

## 📦 Tables
- **Medicines** – Drug catalog (name, price, manufacturer, prescription status)
- **Suppliers** – Supplier companies and contacts
- **Purchases** – Medicine procurement records
- **Sales** – Sales transactions
- **ProductReviews** – Customer ratings and reviews
- **Inventory** – Stock levels and restocking alerts

## 🔗 Key Features
- **Automatic stock updates** – Triggers adjust inventory on purchases/sales
- **Data integrity** – Constraints for ratings, emails, non-negative stock
- **Optimized queries** – Indexes on frequently searched fields
- **Role-based access** – Predefined roles: admin, manager, pharmacy user
- **Analytics views** – Sales summaries and inventory status

## 🚀 Quick Start
1. Run `schema.sql` to create tables
2. Load sample data
3. Test with example queries

## 📊 Example Queries
* Top-selling medicines
* Medicines needing restock
* Supplier performance
* Customer reviews summary

---
*Course project for Database Design | Kazan State Power Engineering University*
