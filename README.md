# Budget Planner with Charts

A simple monthly budget planner built for **Veda Technology – Task 25 (Web Development Track)**.
Set a budget per category, log your spending, and see a **Budget vs Actual** chart.

## Features
- Set a monthly budget for each category
- Log expenses per category (with optional note and date)
- Budget vs actual bar chart (Chart.js)
- Over-budget warning banner and status in the summary table
- Delete expenses
- Data saved in the browser with LocalStorage (no backend needed)

## Tech Stack
HTML5 · CSS3 · JavaScript · Chart.js · LocalStorage

## How to Run
1. Download or clone this repo
2. Open `index.html` in any browser (internet needed for the Chart.js CDN)

## How It Works
1. Budgets are stored as `{ category: amount }`
2. Expenses are stored as a list of `{ cat, amt, note, date }`
3. Spending is aggregated per category with a loop, then compared to the budget
4. The chart and tables re-render after every change, and state is saved to LocalStorage

## Sample Data
`sample-data.csv` shows an example of the budget summary (Category, Budget, Spent, Remaining, Status).

## Author
Joshan – Web Development Intern, Veda Technology
