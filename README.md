# 🍕 Food Delivery Website

A modern, full-featured food delivery web application built with React and Vite.

## ✨ Features

- 🔐 **User Authentication** - Secure login and signup system
- 👤 **User Profile** - Manage personal information and delivery details
- 🛒 **Shopping Cart** - Add, remove, and manage food items
- 💳 **Smart Checkout** - Auto-fill delivery information from profile
- 🎁 **Promo Codes** - Apply discount codes with persistence across navigation
- 📦 **Order Tracking** - Track order status and history
- 📱 **Responsive Design** - Works seamlessly on all devices
- 💰 **INR Pricing** - Prices in Indian Rupees (₹)

## 🎯 Promo Codes

Try these promo codes at checkout:
- `FOOD10` - 10% discount
- `SAVE20` - 20% discount
- `FIRST50` - ₹50 off

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ekan45/food-delivery.git
cd food-delivery
```

2. Navigate to frontend directory:
```bash
cd frontend
```

3. Install dependencies:
```bash
npm install
```

4. Run the development server:
```bash
npm run dev
```

5. Open your browser and visit `http://localhost:5173`

## 📁 Project Structure

```
food-delivery/
└── frontend/
    ├── src/
    │   ├── components/     # Reusable components
    │   ├── pages/          # Page components (Home, Cart, Profile, etc.)
    │   ├── context/        # React Context for state management
    │   ├── assets/         # Images and static assets
    │   └── App.jsx         # Main application component
    ├── public/             # Public assets
    └── package.json        # Dependencies and scripts
```

## 🛠️ Technologies Used

- **React** - Frontend framework
- **Vite** - Build tool and dev server
- **React Router** - Navigation and routing
- **Context API** - State management
- **CSS** - Styling

## 📱 Pages

- **Home** - Browse food menu and add items to cart
- **Cart** - Review cart, apply promo codes, and checkout
- **Profile** - Manage user information
- **Place Order** - Enter delivery details and complete order
- **Orders** - View order history and track deliveries

## 🎨 Key Features

### Auto-Fill Delivery Information
Save time by automatically filling delivery information from your profile when placing orders.

### Persistent Promo Codes
Applied promo codes persist even when you navigate away from the cart - no need to re-enter!

### Order Management
Track all your orders with real-time status updates and detailed order history.

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

Ekankika Pradhan

---

Made with ❤️ using React and Vite
