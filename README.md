# 🍽️ TastyBook

TastyBook is a Django-based recipe sharing web application designed for food enthusiasts to discover, post, and discuss a wide variety of recipes. Whether you're a home cook or a professional chef, TastyBook provides a collaborative platform to inspire and be inspired.

---

## 🌐 App Overview

- **App Name:** TastyBook  
- **Domain:** Food & Beverage / Community Web App  
- **Platform:** Web  
- **Framework:** Django (Python)  
- **Database:** SQLite (development), compatible with PostgreSQL or MySQL  

---

## 🎯 Features

- ✅ User registration and login  
- ✅ Add, edit, delete recipes  
- ✅ Browse and search recipes  
- ✅ Comment and rate recipes  
- ✅ Categorized by meal type (breakfast, lunch, dessert, etc.)  
- 📷 Upload images of recipes  
- 🔍 Search by ingredients, recipe name, or tags  
- 👥 User profile with their posted recipes  

---

## 🚀 How to Run the App

### Prerequisites

- Python 3.8+  
- Django 4.x  
- Virtualenv (recommended)

- ScreenShots:
<img width="1470" height="956" alt="Screenshot 2025-07-20 at 1 11 52 PM" src="https://github.com/user-attachments/assets/d905241c-2419-4ad5-a050-1de53b82a392" />
<img width="1470" height="956" alt="Screenshot 2025-07-20 at 1 09 44 PM" src="https://github.com/user-attachments/assets/ed70bc6b-8b1f-4b19-8b7b-14576e69db78" />

<img width="1470" height="956" alt="Screenshot 2025-07-20 at 1 09 49 PM" src="https://github.com/user-attachments/assets/ed312e13-84ba-4258-992d-12a6d9fe0a73" />
<img width="1470" height="956" alt="Screenshot 2025-07-20 at 1 11 34 PM" src="https://github.com/user-attachments/assets/6837684e-a66b-47eb-84aa-a45c9c6e5aad" />
<img width="1470" height="956" alt="Screenshot 2025-07-20 at 1 11 42 PM" src="https://github.com/user-attachments/assets/4a7fa1e4-d82d-4eba-80f4-d75243ce9984" />
<img width="1470" height="956" alt="Screenshot 2025-07-20 at 1 11 45 PM" src="https://github.com/user-attachments/assets/9a4c6588-56f7-45e8-9bc9-622c2cbbc544" />

  

### Setup Steps

```bash
# Clone the repository
git clone https://github.com/yourusername/TastyBook-Django.git
cd TastyBook-Django

# Create a virtual environment and activate it
python -m venv env
source env/bin/activate  # on Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Migrate the database
python manage.py migrate

# Create a superuser (admin)
python manage.py createsuperuser

# Run the server
python manage.py runserver




