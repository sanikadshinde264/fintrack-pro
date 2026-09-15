# 💰 FinTrack Pro

A simple web-based expense tracking dashboard to log daily expenses and view spending analytics.

## 📖 Overview
FinTrack Pro is a front-end only expense tracker built with HTML, CSS, and JavaScript. Users can add expenses, categorize them, and view daily, weekly, and monthly totals along with a chart showing spending by category. All data is saved in the browser using Local Storage, so no login or internet connection is required after loading the page.

## ❓ Problem Statement
Most people find it hard to keep track of daily expenses using notebooks or memory, and don't get a clear picture of where their money goes. FinTrack Pro solves this by giving a quick and easy way to log expenses and instantly see totals and spending patterns.

## ✨ Features
- Add expenses with name, amount, date, and category
- View daily, weekly, and monthly total spending
- See a doughnut chart of spending by category
- View all past transactions in a table
- Delete any transaction
- Data is saved automatically in the browser
- Simple, responsive design that works on mobile and desktop

## 🛠️ Tools & Technologies
- HTML5
- CSS3
- JavaScript
- Chart.js (for charts)
- GSAP (for animations)
- Font Awesome (icons)
- Browser Local Storage (for saving data)

## ⚙️ Methods / Methodology
1. User fills the form to add an expense (name, amount, date, category).
2. The app validates the input and saves it to Local Storage.
3. Totals (daily, weekly, monthly) are calculated from all saved expenses.
4. A chart is generated showing total spending per category.
5. The transaction table is updated to show all expenses, with an option to delete any entry.

## 📁 Project Directory Structure
```
FinTrack-Pro/
├── index.html      → Main page (form, chart, tables)
├── style.css       → Styling and layout
├── script.js       → App logic (add/delete expenses, totals, chart)
└── README.md       → Project documentation
```

## 📊 Output
The dashboard has two parts:
- **Left side:** Form to add expenses + chart showing category-wise spending
- **Right side:** Daily/weekly/monthly total cards + full transaction history table

## 🔍 Key Insights
- Users can quickly see which category they spend the most on.
- Helps compare short-term (daily/weekly) spending with monthly spending.
- Encourages better spending awareness through visual feedback.

## 📈 Results & Conclusion
FinTrack Pro works as a simple, functional expense tracker that runs fully in the browser without any backend. It successfully tracks expenses, calculates totals, and shows spending patterns using a chart, making it a useful and practical mini finance tool.

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```
2. Navigate to the project directory.
3. Open the `index.html` file in any modern web browser.
4. Start using the application.

## 🚧 Future Work
- Add option to export data as CSV/PDF
- Add monthly budget limits with alerts
- Add login system to sync data across devices
- Add filter/search for transactions
- Add dark/light theme option

## 👤 Author and Contact

**Sanika Shinde** <br>
📧 [sanikadshinde264@gmail.com] | 🔗 [www.linkedin.com/in/sanikadshinde264] 
