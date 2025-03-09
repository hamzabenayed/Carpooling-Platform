# 🚀 Ride-Sharing Platform

## 📌 Project Overview
A ride-sharing platform that connects passengers with drivers offering carpooling services. The platform allows users to find, book, and manage rides efficiently, promoting affordable and eco-friendly transportation. It provides users with a seamless booking experience and ensures ride details are clear and accessible.

## ✨ Key Features
- **🚗 Ride Listings** – Users can post and browse available rides with details such as departure time, destination, and available seats.
- **🔍 Real-Time Search** – A dynamic search system that helps users find carpooling options based on location, schedule, and preferences.
- **📅 Booking System** – Secure seat reservations with instant confirmations from drivers.
- **📜 Trip Details** – Provides users with comprehensive trip details, including driver information, route, pricing, and estimated arrival time.

## 🛠️ Technologies Used
- **Frontend Development:** HTML, CSS, Bootstrap
- **Backend Development:** Symfony (PHP)
- **Database Management:** MySQL
- **Containerization:** Docker
- **Security Implementation:** Data encryption, Role-based access control (RBAC)
- **Deployment:** Docker for scalability and ease of deployment

## 🚀 Installation & Setup
### Prerequisites
Ensure you have the following installed:
- **PHP** (Latest version with Symfony support)
- **MySQL** (For database management)
- **Docker** (For containerized deployment)
- **Composer** (For PHP dependency management)

### Steps to Run the Project
1. **Clone the repository**
   ```bash
   git clone https://github.com/hamzabenayed/Carpooling-Platform.git
   cd ride-sharing-platform
   ```
2. **Install dependencies**
   ```bash
   composer install
   ```
3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   Update database credentials in `.env` file.

4. **Run database migrations**
   ```bash
   php bin/console doctrine:migrations:migrate
   ```

5. **Start the Symfony development server**
   ```bash
   php bin/console server:run
   ```

6. **Run using Docker** (Optional)
   ```bash
   docker-compose up --build
   ```

## 📊 API Documentation
API documentation is available via Swagger:
- Run the backend server and navigate to:
  ```
  http://localhost:8000/api/docs
  ```

## 🤝 Contributing
Contributions are welcome! If you’d like to improve the project, follow these steps:
1. Fork the repository.
2. Create a new branch (`feature-branch-name`).
3. Make your changes and commit them.
4. Push to your fork and submit a Pull Request.

## 📬 Contact
📩 **Hamza Ben Ayed**  
📌 [LinkedIn](https://www.linkedin.com/in/hamza-ben-ayed-307ab223b/)  
📧 Email: hamzabenayed2000@gmail.com

---
🔹 *This project is open-source. Contributions and suggestions are welcome!* 🚀
