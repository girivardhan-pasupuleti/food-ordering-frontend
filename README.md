# 🎨 Online Food Ordering System - Frontend

This repository houses the frontend presentation layer, user interface templates, and client-side styling for the **Food Ordering System**.

---

## 🌐 Live Application & Repositories

- **🚀 Live Deployed App:** [https://food-ordering-backend-zb9o.onrender.com/](https://food-ordering-backend-zb9o.onrender.com/)
- **📂 Frontend Repository:** [food-ordering-frontend](https://github.com/girivardhan-pasupuleti/food-ordering-frontend)
- **⚙️ Backend Repository:** [food-ordering-backend](https://github.com/girivardhan-pasupuleti/food-ordering-backend)
- **☁️ Cloud Hosting:** [Render](https://render.com/)

---

## 👥 Demo Test Accounts

Test accounts are pre-configured to evaluate each portal:

| Role | Email | Password | Access / Portal |
|------|-------|----------|-----------------|
| **Admin** | `admin@food.com` | `admin123` | System Analytics, User & Category Management |
| **Restaurant** | `restaurant@food.com` | `restaurant123` | Menu Item Editor, Order Management & Status Updates |
| **Customer** | `customer@food.com` | `customer123` | Cart, Food Catalog, Checkout & Tracking |

---

## 🎨 UI Architecture & Tech Stack

- **Templating Engine:** Thymeleaf / Semantic HTML5
- **CSS Framework:** Bootstrap 5.3.3 & Bootstrap Icons
- **Custom Styling:** Vanilla CSS (`/static/css/style.css`)
- **JavaScript:** Vanilla JS for dynamic DOM interactions and form validation
- **Backend Integration:** Rendered seamlessly by Spring Boot MVC and served securely over HTTPS

---

## 📁 Repository Structure
food-ordering-frontend/ ├── static/ │ └── css/ │ └── style.css # Custom branding, cards, badges, and layout overrides ├── templates/ │ ├── admin/ # Admin Portal views │ │ ├── dashboard.html # Analytics & summary counts │ │ ├── categories.html # Category management │ │ ├── customers.html # Customer list │ │ ├── food-items.html # Global dishes overview │ │ ├── orders.html # Global orders tracker │ │ ├── restaurants.html # Partner restaurant list │ │ └── users.html # Full user accounts directory │ ├── customer/ # Customer Experience views │ │ ├── dashboard.html # Restaurant discovery & food menu │ │ ├── cart.html # Shopping cart with quantity & total calculation │ │ ├── checkout.html # Multi-payment checkout form │ │ ├── menu.html # Restaurant-specific menu │ │ ├── orders.html # Order history & status tracking │ │ └── restaurants.html # Restaurant directory │ ├── restaurant/ # Restaurant Partner views │ │ ├── dashboard.html # Operations dashboard & quick stats │ │ ├── menu.html # Menu management (dishes, pricing, categories) │ │ ├── add-food.html # New dish creation form │ │ └── orders.html # Live order management & status updater │ ├── index.html # Main landing page with portal shortcuts │ ├── login.html # Unified login page with demo test account badges │ └── register.html # New user account registration └── README.md



## 🔗 How It Connects to Backend

1. **Server-Side Rendering (SSR):** Templates use Thymeleaf standard syntax (`th:href`, `th:text`, `th:each`, `th:object`) to bind data provided by the Spring Boot controllers.
2. **Security & Session Handling:** Standard HTTP forms dispatch `POST` requests to Spring Security endpoints (`/login`, `/logout`, `/cart/add`, `/order/place`).
3. **Responsive Mobile-First Design:** Fully adaptable to smartphones, tablets, and desktops using Bootstrap grid.
