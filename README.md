# 🛒 E-Commerce Store (Fullstack .NET + React)

## 📖 Overview
This is a fullstack **E-Commerce Store application** built with **.NET 7** on the backend and **React 18** on the frontend.  
The project demonstrates a complete workflow of creating a modern web application — from database, API, authentication, frontend UI, to deployment.  

---

## 🚀 Features
- **Authentication & Authorization**  
  - User registration and login with **ASP.NET Identity**  
- **Product Management**  
  - Paging, searching, sorting, and filtering  
- **Shopping Basket & Orders**  
  - Add/remove items to basket  
  - Checkout flow to create an order  
- **Payment Integration**  
  - Stripe payments with EU **3D Secure** standards  
- **UI/UX**  
  - Built with **Material UI** for a clean and responsive design  
  - Reusable forms using **React Hook Form**  
- **Other Enhancements**  
  - Automapper for object mapping  
  - State management with **Redux**  
  - Client-side routing with **React Router 6**  
- **Deployment**  
  - Hosted on **Heroku**  

---

## 🛠 Tech Stack
- **Backend**: .NET 7, ASP.NET Core Web API, Entity Framework Core, ASP.NET Identity  
- **Frontend**: React 18, Redux, React Router 6, Material UI, React Hook Form, Axios  
- **Database**: SQL Server (via EF Core)  
- **Payments**: Stripe  
- **Deployment**: Heroku  
- **Tools**: Visual Studio Code  

---

## 📸 Screenshots
![Homepage](./images/Homepage%20Store.png)

### Product Page
![Product](./images/Product.png)

### Basket
![Basket](./images/Basket.png)

### Checkout
![Checkout](./images/Checkout.png)

### Billing
![Billing](./images/Billing.png)

### Order History
![Order History](./images/Order%20History.png)

### Sign-in
![Sign-in](./images/Sign-in.png)

---

## ⚡ Getting Started
### Prerequisites
- Node.js  
- .NET 7 SDK  
- SQL Server  

### Installation
1. Clone the repository  
2. Navigate to the backend folder and run:
   dotnet restore
   dotnet ef database update
   dotnet run
Navigate to the frontend folder and run:
  npm install
  npm start
