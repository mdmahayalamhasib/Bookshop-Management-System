# Bookshop Management System

A desktop-based Bookshop Inventory & Point-of-Sale (POS) Management System built with **C# (.NET WinForms)**, **ADO.NET**, and **Microsoft SQL Server**. Designed with role-based access control to streamline book stock tracking, billing/invoicing, user administration, and sales reporting.

## Key Features
- **Role-Based Authentication:** Secure login workflow routing users to dedicated **Admin** and **Salesman** dashboards.
- **Book Inventory Management (CRUD):** Add, update, search, and monitor book records including ISBN, category, unit cost, selling price, and real-time stock quantities.
- **POS Billing & Auto-Invoicing:** Interactive sales cart that calculates line totals and generates sequential invoice IDs (INV-001, INV-002, ...) automatically.
- **Sales & Low-Stock Analytics:** Dashboard summaries displaying total revenue, invoice history, and low-stock alerts.
- **User Administration:** Admin controls to manage staff accounts and assign roles (Admin / Salesman).

## Tech Stack
- **Language & Framework:** C#, .NET Framework (Windows Forms)
- **Data Access:** ADO.NET (SqlConnection, SqlCommand, SqlDataAdapter)
- **Database:** Microsoft SQL Server Express (Bookshop)
- **IDE & Tools:** Visual Studio, SQL Server Management Studio (SSMS)

## Setup & Installation
1. **Clone the Repository:** git clone https://github.com/mdmahayalamhasib/Bookshop-Management-System.git
2. **Initialize the Database:** Open SQL Server Management Studio (SSMS), connect to (local)\SQLEXPRESS, create a database named Bookshop, open database/script.sql, and execute (F5).
3. **Configure Connection String:** Update the SQL Server Data Source in BookshopManagementSystem/DataAccess.cs and BookshopManagementSystem/FormLogin.cs if your local instance differs.
4. **Build & Run:** Open BookshopManagementSystem.sln in Visual Studio, rebuild (Ctrl + Shift + B), and press F5.

## Demo Credentials
| Role | User ID | User Name | Password |
| :--- | :--- | :--- | :--- |


| **Admin** | u-001 | Admin | 1 |
| **Salesman** | u-002 | John Smith | 1 |

