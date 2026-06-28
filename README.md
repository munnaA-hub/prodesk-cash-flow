# ProDesk Cash Flow

A clean, responsive, and lightweight financial tracking dashboard built to manage monthly income and expenditures. This tool helps users stay on top of their budgets, visualize financial health with dynamic charts, and download reports for documentation.

---

## 🚀 Features

*   **Salary & Expense Management:** Add your dynamic monthly salary and record daily expenses instantly.
*   **Real-time Analytics:** Automated calculation of total expenses and current remaining balance.
*   **Low Balance Alerts:** Instant visual triggers and warning messages when your remaining balance drops below 10% of your initial salary.
*   **Live Exchange Rate Check:** Direct integration with external currency API to instantly track real-time exchange rates (e.g., INR to USD conversion check).
*   **Interactive Visualizations:** Built-in dynamic chart showcasing the analytical split between total expenses and left balance.
*   **Export as PDF:** Generate and download a perfectly formatted, scannable Cash Flow Report PDF containing full list items directly to your device.
*   **Persistent Storage:** Uses browser `localStorage` so your data stays saved even after refreshing the page.

---

## 🛠️ Tech Stack

*   **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3
*   **Libraries:** Chart.js (Data visualization), jsPDF (PDF reporting)
*   **API Used:** Frankfurter API (Live Currency Conversions)

---

## 📂 Project Structure

```text
prodesk-cash-flow/
│
├── cash-flow/
│   ├── index.html    # Layout and structural markup
│   ├── style.css     # UI elements, theme, and responsiveness
│   └── app.js        # Core logical handler, local storage, API calls, and PDF generation
└── README.md         # Documentation
