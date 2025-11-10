# 🍽️ Foodies Hub - Custom Food Ordering Platform (Django)

The **Foodies Hub** is a dedicated, high-volume e-commerce platform engineered specifically for a hotel environment. It is designed to handle rapid, secure order processing, real-time inventory adjustments, and provide a robust administrative portal for staff to manage product fulfillment.

## ✨ Key Project Highlights

* **High-Volume Order Engineering:** Engineered a dedicated e-commerce platform capable of managing high-volume order processing, secure transactions, and real-time inventory updates using **Django** and a custom **RESTful API**.
* **ORM Optimization & Integrity:** Designed and optimized the **Django ORM** data schema (using normalized tables for `Orders`, `OrderItems`, and `Inventory`) to ensure rapid transaction processing, prevent data concurrency issues, and maintain absolute data integrity.
* **Custom Staff Management Portal:** Leveraged the **Django Admin** interface to create a custom, role-based panel for hotel staff, enabling real-time management of products, inventory, and seamless update of order fulfillment status.
* **Secure State Management:** Implemented secure, **session-based authentication** for various user roles (Customer, Staff/Admin) and built automated server-side logic for crucial state changes (order confirmation, status updates).

## ⚙️ Core Features

### Customer Experience
* **Menu Browsing:** Fast and easy navigation of the hotel's menu, categorized for quick selection.
* **Shopping Cart:** Persistent cart management and secure checkout process.
* **Order Tracking:** Ability for customers to view the current status (e.g., received, preparing, delivered) of their active and historical orders.

### Staff/Admin Management Portal
* **Order Dashboard:** Real-time dashboard display of new, pending, and fulfilled orders.
* **Inventory Control:** Staff can adjust stock levels, update pricing, and modify product details via the custom admin interface.
* **Fulfillment Workflow:** Seamless tools for staff to update the order status, notifying the customer when the order is ready or delivered.

## 💻 Technical Stack

| Component | Technology | Role in the Project |
| :--- | :--- | :--- |
| **Back-End Framework** | **Django (Python)** | Core business logic, routing, and processing of all orders and user data. |
| **API** | **Django REST Framework (DRF)** | Used for robust API endpoint creation, facilitating order submission and status updates. |
| **Data Management** | **Django ORM** | Used for all database modeling and advanced query construction, focused on relational optimization. |
| **Authentication** | **Session-based Security** | Secure user login and authorization, crucial for protecting staff and customer data. |
| **Front-End** | HTML, CSS, JavaScript, Bootstrap | Developed the responsive and intuitive ordering interface. |

---

## 🏃 How to Run the Project Locally

### Prerequisites
* Python 3.8+
* `pip` and `venv` (recommended)

### 1. Clone the Repository and Setup Environment
```bash
git clone [Your GitHub URL Here]
cd foodies-hub-django # Replace with your actual folder name

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install required packages (Django, DRF, etc.)
pip install -r requirements.txt
