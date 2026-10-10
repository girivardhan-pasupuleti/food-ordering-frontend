# Food Ordering System - Frontend

This repository houses the frontend presentation layer and UI templates for the **Food Ordering System**.

## 🎨 UI Architecture & Tech Stack
- **Templating**: Thymeleaf / HTML5
- **Styling**: Vanilla CSS (Responsive Design, Flexbox/Grid, Modern Theme)
- **Client Scripting**: Vanilla JavaScript
- **Backend Repository**: [food-ordering-backend](https://github.com/girivardhan-pasupuleti/food-ordering-backend)

## 📁 Project Structure
`
food-ordering-frontend/
├── templates/
│   ├── admin/             # Admin portal (users, categories, food items, orders)
│   ├── customer/          # Customer portal (restaurants, menu, cart, checkout, orders)
│   ├── restaurant/        # Restaurant portal (dashboard, menu editor, live orders)
│   ├── index.html         # Landing page
│   ├── login.html         # Authentication (Sign in)
│   └── register.html      # Authentication (Registration)
└── static/
    ├── css/               # Core stylesheets
    └── js/                # Interactive behaviors and client-side logic
`

## 🚀 Portals & Features
- **Customer Portal**: Browse partner restaurants, view categorized menus, interactive shopping cart, checkout, order tracking, and reviews.
- **Restaurant Portal**: Real-time incoming order dashboard, menu management (add/edit food items and pricing).
- **Admin Portal**: System analytics dashboard, category management, restaurant approvals, and customer administration.
