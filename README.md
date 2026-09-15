# 💰 FinTrack Pro

A simple and responsive web-based expense tracking dashboard for recording daily expenses and analyzing spending patterns.

## 📖 Overview

**FinTrack Pro** is a front-end expense tracking application built using HTML, CSS, and JavaScript. It allows users to add and manage expenses, categorize transactions, and view daily, weekly, and monthly spending totals along with a visual spending chart.

All expense data is stored locally in the browser using **Local Storage**, so no login, backend, or internet connection is required after the application is loaded.

## ❓ Problem Statement

Tracking daily expenses using notebooks or memory can be difficult and may not provide a clear understanding of spending habits.

**FinTrack Pro** provides a simple solution by allowing users to record expenses and instantly view spending totals, transaction history, and category-wise spending patterns.

## ✨ Features

* ➕ Add expenses with name, amount, date, and category
* 📅 View daily, weekly, and monthly spending totals
* 🍩 View a doughnut chart of category-wise spending
* 📋 View complete transaction history in a table
* 🗑️ Delete individual transactions
* 💾 Automatically save data using browser Local Storage
* 📱 Responsive design for mobile and desktop devices
* 🎨 Simple and user-friendly interface

## 🛠️ Tools & Technologies

* **HTML5** – Structure and content
* **CSS3** – Styling and responsive layout
* **JavaScript** – Application logic and calculations
* **Chart.js** – Spending visualization
* **GSAP** – Animations
* **Font Awesome** – Icons
* **Browser Local Storage** – Local data persistence

## ⚙️ Methodology

1. The user enters an expense including name, amount, date, and category.
2. The application validates the entered information.
3. The expense is stored in the browser's Local Storage.
4. Daily, weekly, and monthly totals are calculated from the stored transactions.
5. Category-wise spending is calculated and displayed using a doughnut chart.
6. All transactions are displayed in the transaction history table.
7. Users can delete individual transactions whenever required.

## 📁 Project Directory Structure

```text
fintrack-pro/
├── index.html      → Main application page
├── style.css       → Styling and responsive layout
├── script.js       → Application logic and expense management
└── README.md       → Project documentation
```

## 📊 Output

The dashboard consists of two main sections:

* **Left Section:** Expense entry form and category-wise spending chart
* **Right Section:** Daily, weekly, and monthly spending cards along with the complete transaction history

## 🔍 Key Insights

* Users can quickly identify their highest-spending categories.
* Daily, weekly, and monthly summaries make spending easier to understand.
* Visual charts provide a quick overview of spending patterns.
* Local Storage allows expenses to remain available even after refreshing the browser.
* The application encourages better awareness of personal spending habits.

## 📈 Results & Conclusion

**FinTrack Pro** successfully provides a simple and functional solution for managing personal expenses directly within the browser.

The application can record transactions, calculate spending summaries, display category-wise analytics, and maintain data using Local Storage without requiring a backend or database.

## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/sanikadshinde264/fintrack-pro.git
```

### 2. Navigate to the Project Directory

```bash
cd FinTrack-Pro
```

### 3. Open the Application

Open the `index.html` file in any modern web browser.

### 4. Start Tracking Expenses

Add your expenses, select categories, and view your spending analytics directly from the dashboard.

> **Note:** Since FinTrack Pro is a front-end application, no server or backend setup is required.

## 🚧 Future Enhancements

* 📥 Export expense data as CSV/PDF
* 💰 Add monthly budget limits and spending alerts
* 🔐 Add user authentication
* ☁️ Synchronize data across multiple devices
* 🔎 Add transaction search and filtering
* 🌙 Add dark/light theme support
* 📊 Add advanced spending analytics

## 👤 Author

**Sanika Shinde**

📧 [sanikadshinde264@gmail.com](mailto:sanikadshinde264@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/sanikadshinde264/)
