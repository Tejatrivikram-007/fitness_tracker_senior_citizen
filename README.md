# Community Safety & Service Platform (Django)

A **Django-based web application** designed to provide a **community safety and service platform**.
The system includes **user profiles, emergency contacts, SOS alerts, service vendors, events, and activity tracking** to support community engagement and safety.

---

# 🚀 Features

### 👤 User Management

* User registration and authentication
* Extended user profile
* Profile completion tracking
* Profile photo upload
* Bio and address management

### 🩺 Medical & Emergency Information

* Blood type storage
* Date of birth & automatic age calculation
* Emergency contacts
* Quick access medical profile

### 🚨 SOS Alert System

* Users can trigger emergency alerts
* SOS records stored for monitoring
* Can be extended to notify contacts or authorities

### 📞 Call Log Tracking

* Store and monitor important call records
* Useful for emergency communication history

### 🏪 Service Vendors

Users can browse or register vendors such as:

* Doctors
* Ambulance services
* Repair services
* Local service providers

Vendor records include:

* Name
* Category
* Contact details
* Description

### 📅 Community Events

* Event creation and management
* Event categorization
* Event listing for community members

### 📊 Activity / Usage Tracking

* System tracks some application usage data
* Can be used for analytics and engagement monitoring

---

# 🏗 Project Architecture

The project follows **Django's MVT Architecture**.

```
Model   → Database Structure
View    → Business Logic
Template → Frontend (HTML)
```

### Components

**Models**

* Define database tables
* Handle relationships between entities

**Views**

* Handle CRUD operations
* Process business logic

**Templates**

* HTML pages rendered for users
* Display dynamic data

**URLs**

* Map routes to views

---



---

# ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/community-safety-platform.git
cd community-safety-platform
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```
venv\Scripts\activate
```

**Linux / Mac**

```
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install django
```

If a requirements file is added:

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

---

### 5️⃣ Create Admin User

```bash
python manage.py createsuperuser
```

---

### 6️⃣ Run Development Server

```bash
python manage.py runserver
```

Open in browser:

```
http://127.0.0.1:8000
```

---

# 🗄 Database

Default database:

```
SQLite3
```

File location:

```
db.sqlite3
```

You can switch to:

* PostgreSQL
* MySQL

by modifying `settings.py`.

---

# 🛠 Technologies Used

* **Python**
* **Django**
* **SQLite**
* **HTML**
* **CSS**
* **Django Templates**

---

# 🔐 Admin Panel

Django includes a built-in admin dashboard.

Access:

```
http://127.0.0.1:8000/admin
```

Admins can manage:

* Users
* Profiles
* Vendors
* Events
* SOS Alerts
* Contacts

---

# 📈 Possible Future Improvements

* Mobile app integration
* Real-time SOS notifications
* SMS alerts
* GPS location tracking
* Vendor rating system
* API for external integrations
* Analytics dashboard

---

# 👨‍💻 Author

Developed as a **Django learning and community safety project** demonstrating:

* CRUD operations
* Django ORM
* Authentication
* Template rendering
* Admin management

---

If you want, I can also generate a **much better README with:**

* **badges**
* **screenshots section**
* **API documentation**
* **architecture diagram**
* **portfolio-level GitHub README**

That would make the project look **10× more professional for GitHub.**
