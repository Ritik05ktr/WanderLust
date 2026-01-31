# WanderLust – Full Stack Hotel Booking Web Application

WanderLust is a full-stack hotel booking platform inspired by Airbnb.  
It allows users to explore listings, create properties, leave reviews, and manage bookings with authentication.

---
## 📸 Screenshots

### 🏠 All Listings Page
![All Listings](./ScreenShots/All%20Listings.png)

### ➕ New Listing Page
![New Listing](./ScreenShots/New%20Listing.png)

### ✏️ Edit Listing Page
![Edit Listing](./ScreenShots/Edit%20Listing.png)


## 🚀 Tech Stack

**Frontend**
- HTML, CSS, Bootstrap, EJS  

**Backend**
- Node.js  
- Express.js  

**Database**
- MongoDB  
- Mongoose  

**Other Tools**
- Passport.js (Authentication)  
- Express Session  
- Method Override  
- MVC Architecture  

---

## ✨ Features

- User Registration and Login
- Create, Read, Update, Delete (CRUD) Listings
- Review and Rating System
- Secure Session-based Authentication
- Responsive UI
- MongoDB Database Integration

---

## 📂 Project Structure

WanderLust/
│── models/
│── routes/
│── views/
│── public/
│── utils/
│── init/
│── app.js
│── package.json

## ⚙️ Installation & Setup

Follow these steps to run the project locally:

### 1️⃣ Go to the project folder
cd WanderLust

2️⃣ Install dependencies
npm install

3️⃣ Start MongoDB
mongod


If you are using MongoDB Atlas, add your connection string in .env or app.js.

4️⃣ Run the server
node app.js
or (recommended for development)

npm run dev

5️⃣ Open in browser
http://localhost:8080/listings
