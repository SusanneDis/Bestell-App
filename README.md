# 🍔 Food Order Web App

A responsive web app for ordering food and drinks, featuring a dynamic shopping cart, order confirmation, and Local Storage persistence.

## 📖 Description

This web application allows users to select main dishes, side dishes, and drinks, add them to their shopping cart, and place an order.

The cart contents are preserved when the page is reloaded using **Local Storage** and can be accessed via a native modal `<dialog>` or a sidebar.

The app places a strong emphasis on **accessibility (ARIA)** and **responsive design**.

## ✨ Features

* ✅ Selection of main dishes, side dishes & drinks
* ✅ Dynamic shopping cart in sidebar & dialog
* ✅ Cart persistence using Local Storage
* ✅ Responsive design (desktop & mobile)
* ✅ Native `<dialog>` elements with slide-in animation
* ✅ Keyboard and screen reader support (ARIA)
* ✅ Displays *"Your cart is empty"* when no items have been added
* ✅ Order confirmation after clicking **"Place Order"**

## 🧱 Technologies

* **HTML5**
* **CSS3 (Flexbox, `calc()`, animations)**
* **Vanilla JavaScript (ES6)**
* **Local Storage API**
* **ARIA Accessibility**

## 📂 Project Structure

```text
/food-order-app
│
├── index.html
├── style.css
├── script.js
├── assets
│   ├── icons
│   └── images
└── README.md
```

## ⚙️ Usage

1. Download or clone the project:

```bash
git clone https://github.com/deinname/food-order-app.git
```

2. Open `index.html` in your browser.
3. Select your food and drinks.
4. Open the shopping cart using the cart button.
5. Click **"Place Order"** to display the order confirmation dialog.

## 🧩 Main Functions

| Function                                          | Description                                         |
| ------------------------------------------------- | --------------------------------------------------- |
| `addToCart(type, index)`                          | Adds a product to the shopping cart                 |
| `renderCartContent(containerId)`                  | Renders the cart content in the sidebar and dialog  |
| `openCartDialog()` / `closeCartDialog()`          | Opens and closes the cart dialog                    |
| `sendOrder()`                                     | Displays the order confirmation and clears the cart |
| `saveToLocalStorage()` / `loadFromLocalStorage()` | Saves and loads the cart using Local Storage        |

## 🎨 Design Details

* Buttons provide visual feedback with a short scale animation when clicked
* The dialog smoothly slides in from the left
* An empty cart is clearly communicated to the user
* Consistent typography, spacing, and color contrast
* Responsive layout for desktop and mobile devices

## 👩‍💻 Developer

**Susanne Di Sorbo**
📅 October 2025

## 📜 License

MIT License – free to use and modify.
