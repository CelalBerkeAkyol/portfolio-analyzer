# Interactive Portfolio Scenario Simulator

## About This Project

This is a standalone, client-side web application for building and analyzing hypothetical investment portfolios. It allows users to dynamically create a portfolio, define their own financial assumptions for each asset, and instantly simulate the potential outcomes under different market scenarios.

Everything is processed in your browser; no data is saved to a server, and no external files are needed. This makes it a quick, private, and powerful "what-if" analysis tool for investors.

![Screenshot of the Simulator](./images/Screenshot%202025-09-07%20at%2020.34.46.png)
![Screenshot of the Simulator](./images/Screenshot%202025-09-07%20at%2020.35.11.png)

## Features

- **Dynamic Portfolio Builder:** Add, edit, or remove various asset classes on the fly.
- **Customizable Assumptions:** For each asset, you can define a custom:
  - Risk Score (1-10)
  - Expected returns for **Bad, Base, and Good** scenarios.
  - Whether it is a USD-based asset.
- **Global Currency Simulation:** Input your global assumptions for the USD/TRY exchange rate's performance in different scenarios to see its compounding effect on your USD-based assets.
- **Comprehensive Scenario Analysis:** Instantly view the calculated total portfolio return and final monetary value for the three distinct market conditions.
- **Rich Visualization:** An interactive doughnut chart (powered by Chart.js) and a detailed list with progress bars provide a clear view of your asset allocation.
- **Weighted Risk Score:** Understand the overall risk profile of your custom-built portfolio at a glance.
- **Single-File Application:** The entire tool is self-contained in a single HTML file, making it extremely portable and easy to use.

## Technology Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Charting Library:** [Chart.js](https://www.chartjs.org/)

## How to Use

This tool is designed for simplicity. **No local server is required.**

1.  Download the `.html` file.
2.  Open it directly in any modern web browser (like Chrome, Firefox, or Edge).
3.  **Step 1: Set Global Assumptions**
    - At the top of the page, enter your percentage expectations for the annual USD/TRY exchange rate increase under Bad, Base, and Good scenarios.
4.  **Step 2: Build Your Portfolio**
    - Use the pre-filled rows or click "Yeni Varlık Satırı Ekle" (Add New Asset Row) to create your portfolio.
    - For each row, fill in the asset's name, risk score, scenario returns, and whether it's USD-based.
    - Enter the current amount you hold in TL in the "Tutarınız (TL)" field.
    - Use the "Sil" (Delete) button to remove unwanted assets.
5.  **Step 3: Analyze the Results**
    - Click the "Portföyü Hesapla" (Calculate Portfolio) button.
    - The results will instantly appear below, showing the overall risk, a pie chart of your distribution, a detailed asset list, and the complete scenario analysis.
