# 🛠️ Computer Repair Shop Management

## 📌 Overview
This is a **Full-Stack MERN** (MongoDB, Express, React, Node.js) project designed to efficiently manage a **computer repair shop**. The system features **store-based licensing**, ensuring that each store operates independently with a valid **license key** upon payment.

## 🚀 Features

- **Store Licensing System**: Stores must purchase a license key to use the system.
- **Role-based Access**:
  - **Admin**: Manages products, employees, and store settings.
  - **Employee**: Creates and updates orders.
- **Order Management**:
  - Add customer details (phone, device type, issue description, etc.).
  - Track order progress (from *not completed* to *completed*).
- **Inventory Management**: Keep track of spare parts and stock levels.
- **QR Code Integration**: Orders have unique QR codes for quick access and tracking.

## 🏗️ Tech Stack

- **Frontend**: React, React Router
- **Backend**: Node.js, Express.js, MongoDB
- **Authentication**: JWT-based authentication & authorization
- **Database**: MongoDB (Mongoose ORM)
- **Storage**: Cloudinary for images
- **Deployment**: Netlify (Frontend), Render (Backend)

## 📦 Installation

1. **Clone the repository:**

2. **Install dependencies:**
   ```sh
   # Backend
   cd inventory-management-backend
   npm install

   # Frontend
   cd inventory-management-frontend
   npm install
   ```

3. **Set up environment variables:**
   - Create a `.env` file in the `server` folder and add:
     ```sh
     MONGO_URI
     JWT_SECRET
     ```
   
4. **Run the application:**
   ```sh
   # Start backend
   cd inventory-management-backend
   npm start

   # Start frontend
   cd inventory-management-frontend
   npm start
   ```

## 📜 License
This project is licensed under a **store-based licensing system**. Each store must obtain a valid **license key** to use the system.

## ✨ Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

## 📞 Contact
For inquiries, feel free to reach out:
- **Email**: your-email@example.com
- **Facebook**: [Your Profile](https://www.facebook.com/trananhtuan1173)
- **GitHub**: [Your GitHub](https://github.com/anhtuan1172003)

---
⭐ If you like this project, don’t forget to **star** the repo!
