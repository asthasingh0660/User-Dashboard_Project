# 📊 User Dashboard

This is a responsive admin dashboard built with **React**, **TypeScript**, and **Vite**, featuring dynamic user/product management, reusable components, and interactive data visualizations. It is styled using **SCSS** and supports mobile-first responsive design using **Flexbox** and **CSS Grid**.

---

## 🚀 Demo

> will be deployed on Vercel after the final edit.

---

## 🛠️ Tech Stack

| Tech            | Description                             |
|-----------------|-----------------------------------------|
| React           | Component-based UI framework            |
| TypeScript      | Strongly typed JavaScript               |
| Vite            | Lightning-fast build tool               |
| SCSS            | Modular and maintainable styling        |
| React Router    | Declarative client-side routing         |
| Recharts        | Interactive charting and data display   |

---

## 📁 Directory Structure
root/
├── public/ # Static assets
├── src/
│ ├── components/ # Reusable UI elements
│ │ ├── add/ # Add user/product forms
│ │ ├── barChartBox/ # Bar chart display
│ │ ├── bigChartBox/ # Main dashboard chart
│ │ ├── chartBox/ # Mini chart widgets
│ │ ├── dataTable/ # Tabular user/product list
│ │ ├── footer/ # Footer section
│ │ ├── menu/ # Sidebar navigation
│ │ ├── navbar/ # Top navbar
│ │ ├── pieChartBox/ # Pie chart visual
│ │ ├── single/ # Single item view
│ │ ├── topBox/ # Top stat widgets
│ ├── pages/ # Page-level routes
│ │ ├── home/ # Dashboard home
│ │ ├── login/ # Login page
│ │ ├── users/ # All users
│ │ ├── user/ # User details
│ │ ├── products/ # All products
│ │ ├── product/ # Product details
│ ├── styles/ # Global SCSS styles
│ ├── App.tsx # App routing and layout
│ ├── main.tsx # App entry point
│ ├── data.ts # Mock data for tables/charts
├── index.html


---

## 🧩 Features

### ✅ Responsive Design
- Mobile-friendly layout using **CSS Grid** & **Flexbox**
- Collapsible sidebar on smaller screens
- Scrollable tables and forms on mobile devices

### 👤 User & Product Management
- List, view, and add users/products
- Reusable form component
- Dynamic routing (e.g., `/user/:id`, `/product/:id`)

### 📊 Interactive Dashboards
- **Bar**, **Pie**, and **Line** charts using Recharts
- Dashboard insights like revenue, sales trends, and more

### 🔐 Authentication (Basic)
- Login page structure included
- Ready for integration with backend APIs

---

## 🌐 Routes Overview

| Path               | Description               |
|--------------------|---------------------------|
| `/`                | Dashboard home            |
| `/login`           | Login page                |
| `/users`           | List of users             |
| `/user/:id`        | View single user          |
| `/users/add`       | Add new user              |
| `/products`        | List of products          |
| `/product/:id`     | View single product       |
| `/products/add`    | Add new product           |
|------------------------------------------------|

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/your-username/User-dashboard-Project.git
cd astha-dashboard

# Install dependencies
npm install

# Run the development server
npm run dev

🧪 Testing the App
Visit http://localhost:5173/ to see the dashboard.

Use /login for the login screen.

Navigate to /users, /products, etc., for demo pages.

📌 Future Improvements
🔐 Full authentication system with token-based login

🌐 Backend integration for real-time data

🧾 Role-based access control

🙌 Acknowledgements
React
Vite
Recharts
SCSS
React Router
