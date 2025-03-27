# 🛒 ShoppyGlobe E-commerce Application

## 📌 Overview
**ShoppyGlobe** is a basic e-commerce application built using **React and Redux**, allowing users to browse products, view product details, add items to the cart, and manage their shopping experience efficiently.

## 🛠️ Tech Stack
- **Frontend:** React, JavaScript, CSS
- **State Management:** Redux
- **Routing:** React Router
- **Data Fetching:** Fetch API, useEffect
- **Performance Optimization:** React.lazy, Suspense

## 🎯 Features
- 🏠 **Home Page:** Displays a list of products fetched from an API.
- 🛍️ **Product List:** Fetches and displays products dynamically.
- 📦 **Product Detail Page:** Shows details of a selected product.
- 🛒 **Cart System:** Add, remove, and modify items in the shopping cart.
- 🔍 **Search Functionality:** Filter products based on search queries.
- 🔄 **State Management:** Utilizes Redux for managing cart state.
- 🚀 **Performance Optimized:** Code splitting and lazy loading for efficiency.
- 🔗 **Routing:** Implemented using React Router for seamless navigation.
- 🎨 **Responsive Design:** Ensures compatibility across devices.

## 📂 Component Structure
```
📦 shoppyglobe
├── 📂 public           # Static assets
├── 📂 src
│   ├── 📂 components  # UI components
│   │   ├── Header.jsx
│   │   ├── ProductList.jsx
│   │   ├── ProductItem.jsx
│   │   ├── ProductDetail.jsx
│   │   ├── Cart.jsx
│   │   ├── CartItem.jsx
│   │   ├── NotFound.jsx
│   ├── 📂 redux       # Redux store, actions, reducers
│   ├── 📜 App.jsx     # Main application component
│   ├── 📜 index.jsx   # Entry point
│   ├── 📜 styles.css  # Global styling
├── 📜 package.json    # Dependencies and scripts
├── 📜 README.md       # Project documentation
```

## 🚀 Installation and Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/alokcode11/shoppyglobe
   cd shoppyglobe
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Start the development server:**
   ```sh
   npm start
   ```

4. **Open the app in your browser:**
   ```sh
   http://localhost:3000
   ```

## 🔧 How to Use
- **View Products:** Browse the homepage to see available products.
- **View Product Details:** Click on a product to see detailed information.
- **Add to Cart:** Click on the "Add to Cart" button to add an item.
- **View Cart:** Click the cart icon in the header to manage items.
- **Remove from Cart:** Use the remove button to delete items.
- **Search Products:** Use the search bar to find specific items.

## 🔥 Performance Optimization
- Implemented **lazy loading** using `React.lazy` and `Suspense`.
- Code splitting to reduce initial load time.
- Optimized API calls using `useEffect` and caching.

## ⚙️ State Management (Redux)
- **Actions & Reducers:** Handles cart functionalities.
- **Selectors:** Efficiently retrieves data.
- **Middleware:** Used for async data fetching.

## 🔗 Routing (React Router)
- `/` - Home (Product List)
- `/product/:id` - Product Details
- `/cart` - Shopping Cart
- `/checkout` - Checkout Page
- `*` - 404 Not Found

## 📌 Future Enhancements
- ✅ User authentication & login system
- ✅ Wishlist functionality
- ✅ Payment gateway integration

## 🤝 Contributing
Feel free to contribute by opening an issue or submitting a pull request!

## 📜 License
This project is open-source and available under the MIT License.

---

🚀 Happy Coding!
