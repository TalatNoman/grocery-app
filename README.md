# Fresh Basket — Premium Online Grocery Store

Fresh Basket is a modern, high-performance grocery selling application. It features a stunning dark-themed UI, a dynamic product catalog, session-based cart management, and a complete checkout flow.

![Fresh Basket Home Page](file:///C:/Users/HP/.gemini/antigravity/brain/7e9f4b5a-d09d-4b0a-acae-18706a7e2ea7/home_page_1777907481664.png)

## ✨ Key Features

- **Premium Glassmorphic Design**: A state-of-the-art dark interface built for a premium shopping experience.
- **Dynamic Browsing**: Filter products by 8+ categories (Fruits, Vegetables, Dairy, etc.) or search in real-time.
- **Smart Cart**: Add, update, and remove items with persistent sessions.
- **Checkout Flow**: Complete delivery details form with instant order confirmation.
- **Responsive Layout**: Optimized for both desktop and mobile browsing.
- **Micro-animations**: Subtle hover effects and transitions for enhanced UX.

## 🛠️ Tech Stack

### Frontend
- **HTML5 & Vanilla CSS3**: Custom design system with modern CSS variables.
- **Vanilla JavaScript**: Modular architecture with a custom hash-based router.
- **Google Fonts**: Uses "Inter" for high readability and premium aesthetics.

### Backend
- **Node.js & Express**: Robust REST API for products, cart, and orders.
- **UUID**: Secure session and order ID generation.
- **CORS**: Configured for secure cross-origin requests.
- **In-memory Store**: Fast data management for demonstration purposes.

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/TalatNoman/grocery-app.git
   cd grocery-app
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the server**:
   ```bash
   npm start
   ```

4. **Open in Browser**:
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```text
grocery-app/
├── public/             # Frontend assets
│   ├── css/            # Style sheets
│   ├── js/             # JS modules (api, products, cart, checkout, app)
│   └── index.html      # Main entry point
├── server/             # Backend source
│   ├── data/           # Product catalog data
│   ├── routes/         # Express API routes
│   ├── server.js       # Main server file
│   └── store.js        # In-memory data management
├── package.json        # Dependencies and scripts
└── README.md           # Project documentation
```

## 📝 License
This project is for demonstration purposes. Feel free to use and modify it for your own learning!
