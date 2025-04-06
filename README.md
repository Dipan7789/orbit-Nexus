# Orbit-Nexus
Starring Dipan Chakraborty , Sudutta Mukherjee
ISS Inventory Management System
Overview
This project is a comprehensive inventory management system designed for the International Space Station. It provides tools for tracking supplies, managing storage locations, and optimizing resource utilization in space.

Features
Real-time inventory tracking
Storage optimization algorithms
Expiry date management
Import/export functionality
Interactive storage visualization
User authentication and role-based access
Tech Stack
Frontend: React, TypeScript, Tailwind CSS, shadcn/ui
Backend: Flask (Python)
Data Format: JSON
Containerization: Docker
Getting Started
Prerequisites
Docker
Running the Application
Using Docker
Clone the repository:

git clone <repository-url>
cd iss-inventory-system
Build and run the Docker container:

docker build -t iss-inventory-system .
docker run -p 8000:8000 iss-inventory-system
Access the application at http://localhost:8000

Development Setup
Frontend Development:

npm install
npm run dev
Backend Development:

pip install -r requirements.txt
python app.py
API Endpoints
GET /api/inventory - Get all inventory items
GET /api/inventory/<item_id> - Get specific inventory item
POST /api/inventory - Add new inventory item
License
ISS Inventory Management System is MIT licensed.
