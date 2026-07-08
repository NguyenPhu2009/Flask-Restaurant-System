# Flask Restaurant Order Manager

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

A full-stack web application designed to streamline restaurant operations. It provides role-specific dashboards to synchronize workflows between the dining area, kitchen, and cashier in real time.

* **Backend:** Python, Flask
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Database:** SQL (Import script: `quan_ly_nha_hang.sql`)

## 🌟 Key Features
* **Role-Specific Dashboards:** Custom templates and logic for Managers, Cashiers, and Kitchen staff.
* **Modular Routing:** Clear separation of concerns with dedicated routes for API endpoints (`routes_api.py`), order processing (`routes_order.py`), and view rendering (`routes_view.py`).
* **Admin Panel:** Built-in administration interface with custom forms for data management (`admin_panel.py`).
* **Interactive Frontend:** Asynchronous JavaScript modules (`cashier.js`, `kitchen.js`, `manager.js`, `order-list.js`) handling real-time DOM updates and notifications.

## 🏗️ Folder Structure
* `/project/static`: Contains all CSS and modular JavaScript files for the frontend client.
* `/project/templates`: Jinja2 HTML templates, including reusable layouts (sidebar, master) and role-based views.
* `/project`: Contains core Python logic, database models (`models.py`), and application configurations (`config.py`).

## 🚀 Getting Started
1. Clone the repository.
2. Install the required dependencies: `pip install -r requirements.txt`.
3. Import the database using `quan_ly_nha_hang.sql`.
4. Run the application: `python project/app.py`.
