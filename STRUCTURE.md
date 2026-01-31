# Store Website Structure

This is a front-end store website project with a complete file structure ready for development.

## Project Structure

```
front-end-store-website/
│
├── index.html                          # Main/Home page
├── styles/
│   ├── main.css                        # Main page styles
│   ├── customer/
│   │   ├── products.css                # Products page styles
│   │   ├── login.css                   # Customer login styles
│   │   ├── billing.css                 # Billing information styles
│   │   └── payment.css                 # Payment/Checkout styles
│   └── admin/
│       ├── admin-login.css             # Admin login styles
│       └── admin-dashboard.css         # Admin dashboard styles
├── scripts/
│   ├── main.js                         # Main page scripts
│   ├── customer/
│   │   ├── products.js                 # Products page scripts
│   │   ├── login.js                    # Customer login scripts
│   │   ├── billing.js                  # Billing information scripts
│   │   └── payment.js                  # Payment/Checkout scripts
│   └── admin/
│       ├── admin-login.js              # Admin login scripts
│       └── admin-dashboard.js          # Admin dashboard scripts
├── pages/
│   ├── customer/
│   │   ├── products.html               # Products page
│   │   ├── login.html                  # Customer login page
│   │   ├── billing.html                # Billing information page
│   │   └── payment.html                # Payment/Checkout page
│   └── admin/
│       ├── admin-login.html            # Admin login page
│       └── admin-dashboard.html        # Admin dashboard page
└── assets/
    ├── images/                         # Store images and product photos
    └── icons/                          # Icons and logos

```

## Pages Overview

### Customer-Facing Pages
1. **Main Page** (`index.html`) - Homepage/landing page for the store
2. **Products Page** (`pages/customer/products.html`) - Display and browse products
3. **Customer Login** (`pages/customer/login.html`) - Customer authentication
4. **Billing Information** (`pages/customer/billing.html`) - Customer billing details
5. **Payment/Checkout** (`pages/customer/payment.html`) - Payment processing and checkout

### Admin Pages
1. **Admin Login** (`pages/admin/admin-login.html`) - Admin authentication
2. **Admin Dashboard** (`pages/admin/admin-dashboard.html`) - Admin control panel

## Getting Started

All HTML, CSS, and JS files are currently empty, ready for you to develop. 

To begin:
1. Start with `index.html` for your main page
2. Add your HTML structure, then link the corresponding CSS and JS files
3. Continue with other pages as needed

## Development Notes

- Each page has its own dedicated HTML, CSS, and JS files
- The structure is organized by user type (customer/admin)
- The `assets` folder is ready for images and icons
- All files are empty templates for you to customize

Good luck with your development!
