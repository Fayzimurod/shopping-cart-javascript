# 🛒 Shopping Cart JavaScript

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-yellow)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-latest-orange)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-latest-blue)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

A lightweight, responsive shopping cart application built with pure JavaScript. Perfect for learning DOM manipulation, event handling, and basic e-commerce functionality.

![Shopping Cart Demo](image/screenshot.png)

## ✨ Features

- **Product Display Grid** - Clean product cards with images, names, and prices
- **Add to Cart** - One-click addition of products to shopping cart
- **Real-time Quantity Update** - Visual indicator of items in cart
- **Cart Management** - Increase/decrease quantities or remove items
- **Live Price Calculation** - Automatic total price updates
- **Smooth Animations** - Sliding cart panel with transition effects
- **Responsive Design** - Works on desktop and mobile devices
- **Selection Highlight** - Custom text selection styling

## 🚀 Live Demo

[View Live Demo](#) (Add your deployed link here)

## 📋 Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of JavaScript (for modifications)

## 🎯 How to Use

### Adding Items to Cart
- Browse through the product grid
- Click **"Add To Card"** on any product
- The cart icon shows the total quantity of items
- Cart panel slides in from the right

### Managing Cart Items
- **Increase quantity** - Click the `+` button
- **Decrease quantity** - Click the `-` button (removes item at 0)
- **View total** - Check the bottom of cart panel
- **Close cart** - Click the "Close" button

### Cart Controls
| Control | Action |
|---------|--------|
| Cart Icon | Opens shopping cart |
| + Button | Increases item quantity |
| - Button | Decreases/removes item |
| Close Button | Closes cart panel |

## Key Features Explained

### Cart State Management
- `listCards[]` array maintains cart items
- Each item tracks quantity and calculates subtotal
- Empty items are removed from array

### Dynamic UI Updates
- Real-time total price calculation
- Live quantity counter on cart icon
- Automatic cart display refresh

### Smooth Transitions
- Cart slides in/out using CSS transforms
- Body class toggles for active states
- Container shifts for visual feedback

## 📱 Responsive Design

The application adapts to different screen sizes:
- **Desktop** - Full grid layout with 3-4 products per row
- **Tablet** - 2-3 products per row
- **Mobile** - Single column layout with adjusted cart width

## 🔧 Technical Details

### Dependencies
- **Zero external dependencies** - Pure vanilla JavaScript
- No frameworks or libraries required
- Lightweight and fast loading

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

### Performance Optimizations
- Minimal DOM manipulations
- Efficient array operations
- CSS transitions for smooth animations

## 🐛 Known Issues

- Cart container shift may need adjustment on very small screens
- Images should be optimized for faster loading
- No form validation for checkout (intentional for demo)

## 🙏 Acknowledgements

- Shopping icon from SVG repository
- Product images for demonstration purposes
- Inspired by modern e-commerce platforms

## 🎯 Use Cases

### Learning Resource
Perfect for beginners learning:
- JavaScript DOM manipulation
- Event handling in vanilla JS
- CSS transitions and animations
- Array methods and object manipulation

### Starting Template
Great foundation for:
- E-commerce prototypes
- Shopping experience demos
- UI/UX testing
- Portfolio projects

### Quick Demo
Ideal for:
- Client presentations
- Concept validation
- User testing
- Design iterations
