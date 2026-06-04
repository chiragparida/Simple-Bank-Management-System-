#Bank-Management-System-
Bank Management System — Overview This is a REST API built with FastAPI and Uvicorn in Python that simulates a basic banking system. Here's what it does:
What it is
A backend web application that runs on your local machine and handles bank account operations through API endpoints. No frontend UI — you interact with it via Swagger UI at http://localhost:8001/docs or tools like Postman.

What it can do
Account Management (CRUD)

Create a new bank account with owner name, email, account type and initial deposit
Read — view one account or list all accounts
Update — change account holder's name, email, or account type
Delete — close an account (only if balance is zero)

Banking Operations

Deposit — add money to an account
Withdraw — take money out (blocks if insufficient funds)
Transfer — move money between two accounts

Transaction History

View all transactions for a specific account
View every transaction across all accounts

Done By-Chirag Parida and  Kaushik Laxman Gadipelly
