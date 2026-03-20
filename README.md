# FastAPI-Food-Delivery-App

🍔 Zwiggy - Food Delivery Backend API (FastAPI)
Developed as the Final Project for the Innomatics Research Labs Internship (Feb 2026 Batch). This repository contains a robust backend system for a food delivery application, implementing 20 comprehensive tasks covering RESTful architecture, data validation, and advanced query logic.

🚀 Project Overview
This API manages the end-to-end lifecycle of a food delivery service, from menu browsing to order placement and administrative management. The project is built using FastAPI, ensuring high performance and automatic interactive documentation.

Key Features Implemented:
Menu Operations: Full CRUD for food items, category filtering, and top-rated item discovery.
Order Management: Real-time order placement, status tracking (Preparing/Out for Delivery), and order cancellation.
Business Logic: Automated bill calculation including 5% GST and 10% Service Charges via custom helper functions.
Advanced Data Handling: Implementation of keyword-based Search, Multi-level Sorting (Category & Price), and Pagination.
Admin Tools: Item availability toggles and system-wide order history resets.
📁 Repository Structure
To maintain a professional developer workflow, the project is organized as follows:

main.py: The core application containing all 20 FastAPI endpoints.
requirements.txt: List of necessary Python packages to run the project.
screenshots/: A dedicated folder containing visual proof (Response Body) for all 20 tasks.
README.md: Project documentation and setup guide.
🛠️ Technical Stack
Framework: FastAPI
Data Validation: Pydantic (v2)
Web Server: Uvicorn
Language: Python 3.10+
⚙️ How to Run Locally
Clone the Repo:
git clone [https://github.com/your-username/fastapi-food-delivery-app.git](https://github.com/your-username/fastapi-food-delivery-app.git)
cd fastapi-food-delivery-app
Install Dependencies:

Bash
pip install -r requirements.txt
Start the Server:

Bash
python main.py
or
uvicorn main:app --reload --port 8004
Access Swagger UI:
Go to http://127.0.0.1:8004/docs to interact with all 20 endpoints.
