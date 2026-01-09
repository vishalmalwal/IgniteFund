# IgniteFund - Crowdfunding Platform

A full-stack crowdfunding platform built with the MERN stack (MongoDB, Express, React, Node.js). Users can create, browse, and support meaningful campaigns across various categories.

**Repo**: https://github.com/vishalmalwal/IgniteFund

## 🚀 Features

- **User Authentication**

  - Email/password signup & login
  - Google OAuth integration

- **Campaign Management**

  - Create campaigns with title, description, goal amount, category, and images
  - Browse and search campaigns

- **Categories**

  - Animal Help
  - Parental Help
  - Child Help
  - Sports
  - Personal
  - E-Commerce
  - and more

- **Payment Integration**

  - Razorpay (test mode)
  - PhonePe (sandbox/UAT mode) for simulated transactions

- **Additional Features**
  - Watchlist to track favorite campaigns
  - Responsive and modern user interface

## 🛠️ Tech Stack

- **Frontend**: React + Vite
- **Backend**: Node.js + Express
- **Database**: MongoDB Atlas
- **Authentication**: Passport.js (Google Strategy), express-session
- **Payments**: Razorpay & PhonePe (test/sandbox mode)
- **Other**: dotenv, CORS, JWT

## 📦 Local Setup

### Prerequisites

- Node.js (v18 or higher)
- MongoDB Atlas account
- Google OAuth, Razorpay, and PhonePe test credentials

### Installation Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/vishalmalwal/IgniteFund.git
   cd IgniteFund
   ```

2. **Backend setup**

   ```bash
   cd Backend
   npm install
   # Create .env file with your credentials (MongoDB URI, Google OAuth, Razorpay keys, etc.)
   npm start
   ```

3. **Frontend setup**
   ```bash
   cd ../FrontEnd
   npm install
   npm run dev
   ```

🌟 About
Personal full-stack project to demonstrate proficiency in:

MERN stack development
Third-party API integrations (Google OAuth, Razorpay, PhonePe)
Secure authentication and environment management
Responsive UI design
Debugging and optimizing complex applications
