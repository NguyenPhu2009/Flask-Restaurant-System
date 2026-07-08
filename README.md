# Flask Restaurant Order Manager 🍽️

A full-stack web application designed to streamline restaurant operations. It provides role-specific dashboards to synchronize workflows between the dining area, kitchen, and cashier in real time.

## 🌟 Key Features
* **Role-Specific Dashboards:** Custom templates and logic for Managers, Cashiers, and Kitchen staff[cite: 2].
* **Modular Routing:** Clear separation of concerns with dedicated routes for API endpoints (`routes_api.py`), order processing (`routes_order.py`), and view rendering (`routes_view.py`)[cite: 2].
* **Admin Panel:** Built-in administration interface with custom forms for data management (`admin_panel.py`)[cite: 2].
* **Interactive Frontend:** Asynchronous JavaScript modules (`cashier.js`, `kitchen.js`, `manager.js`, `order-list.js`) handling real-time DOM updates and notifications[cite: 2].

## 🏗️ Folder Structure
* `/project/static`: Contains all CSS and modular JavaScript files for the frontend client[cite: 2].
* `/project/templates`: Jinja2 HTML templates, including reusable layouts (sidebar, master) and role-based views[cite: 2].
* `/project`: Contains core Python logic, database models (`models.py`), and application configurations (`config.py`)[cite: 2].

## 💻 Tech Stack
* **Backend:** Python, Flask[cite: 2]
* **Frontend:** HTML5, CSS3, Vanilla JavaScript[cite: 2]
* **Database:** SQL (Import script: `quan_ly_nha_hang.sql`)[cite: 2]

## 🚀 Getting Started
1. Clone the repository.
2. Install the required dependencies: `pip install -r requirements.txt`[cite: 2].
3. Import the database using `quan_ly_nha_hang.sql`[cite: 2].
4. Run the application: `python project/app.py`[cite: 2].
