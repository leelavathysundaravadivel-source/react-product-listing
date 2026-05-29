# 🛒 React JS Product Listing Application

A dynamic, stateful product catalog application built using **React JS** and **Vite**. The application handles product listing workflows, complex data operations, and interactive shopping basket mechanics completely on the frontend.

### 🌟 Core Capabilities & Features
- **Component Separation:** Built using clean, independent, reusable components (`Navbar`, `SearchBar`, `FilterSort`, `ProductList`, `ProductCard`, and `Cart`).
- **State Management:** Uses centralized React hooks (`useState` and `useEffect`) as a single source of truth to manage variables dynamically without manual DOM tracking.
- **Dynamic Array Engineering:** Combines case-insensitive text search filtering, strict category dropdown sorting, and price aggregation tracking using native JavaScript array methods (`.map()`, `.filter()`, and `.reduce()`).
- **Shopping Cart Mechanics:** Add and remove product quantities in real-time with automatic total bill calculations.
- **Responsive Layout:** Powered by a clean Bootstrap grid system that instantly refactors across desktop, tablet, and mobile displays.

### 🛠️ Directory Architecture
The workspace strictly mirrors the recommended folder structure:
```text
react-product-listing/
├── src/
│   ├── components/  # Reusable UI layout elements
│   ├── data/        # Static 8-product data grid layer
│   ├── styles/      # Minimalist layout styling variables
│   ├── App.jsx      # Core application logic controller
│   └── main.jsx     # Vite core initialization hub
