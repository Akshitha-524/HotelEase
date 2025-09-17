HotelEase is a **Hotel Management System** built with Django that simplifies hotel operations.  
It includes modules for rooms, guests, accounts, and overall hotel administration — all in one system.  

---

## ✨ Features
- 🔑 **Authentication & Roles** – secure login for admins, staff, and guests  
- 🛏️ **Room Management** – track availability, occupancy, and maintenance  
- 👥 **Guest Management** – manage guest details, reservations, and history  
- 📊 **Dashboard** – quick overview of hotel performance  
- 📱 **Responsive UI** – works across desktop, tablet, and mobile  

---

## 📂 Project Structure
HotelEase/
│── accounts/ # User accounts & authentication
│── guest/ # Guest management
│── hotelmanagement/ # Core hotel management logic
│── room/ # Room-related operations
│── screenshots/ # UI screenshots
│── manage.py # Django project manager
│── README.md # Project documentation

yaml
Copy code

---

## ⚙️ Tech Stack
- **Backend**: Django (Python 3.10+)  
- **Database**: SQLite / PostgreSQL (configurable)  
- **Frontend**: HTML, CSS, Bootstrap  

---

## 🚀 Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/Akshitha-524/HotelEase.git
   cd HotelEase
Create virtual environment & install dependencies

bash
Copy code
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
pip install -r requirements.txt
Run migrations & start server

bash
Copy code
python manage.py migrate
python manage.py runserver
