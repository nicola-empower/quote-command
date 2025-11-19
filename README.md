# Quote Command: Profit Protection for Trades 🔨

> "From the back of a cigarette packet to data-driven revenue control."

**Quote Command** is a mobile-first pricing engine designed specifically for independent tradespeople. It transforms the chaotic, manual process of estimating construction jobs into a standardized, margin-protected workflow.

---

## 🚩 The Problem: "The Friday Night Slog"

For independent joiners and tradespeople, quoting is often the bottleneck of the business. My client spends one full day a week on the road visiting potential clients, collecting measurements in a notebook.

### The Pain Points
* **Batch Overload:** Returning home with 10+ quotes to type up manually takes hours of personal evening time.
* **Margin Drift:** "Guesstimating" labour hours or forgetting small materials (screws, glue) eats into profit.
* **Repetitive Strain:** Starting from zero for every client (re-entering hourly rates/VAT) is inefficient.

---

## 🚀 The Solution

Quote Command is a **Single Page Application (SPA)** that acts as a "Digital Daybook." It allows the user to rapidly stack multiple quotes while on the road, visualising profit margins in real-time, and exporting the entire batch for processing.

### Key Features
* **🚀 Rapid Batch Entry:** Core settings (Hourly Rate, Profit Margin) persist between quotes. You only input the variables for the new job.
* **🧮 Dynamic Profit Engine:** Automatically calculates Net Cost, Profit Markup (e.g., 20%), and VAT (20%) instantly.
* **📊 Visual Health Check:** Dynamic Donut Charts (Chart.js) visualise the Labour vs. Materials split, ensuring no job is accepted with thin margins.
* **📂 CSV Batch Export:** One-click export of all pending quotes into a structured CSV file, ready for import into Xero, QuickBooks, or Google Sheets.

---

## 🛠️ Technical Implementation

This project follows a **Local-First** architecture for speed and reliability in low-signal areas (construction sites).

### Tech Stack
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Chart.js](https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white)

* **Core:** HTML5, Vanilla JavaScript (ES6+)
* **Styling:** Tailwind CSS (Utility-first for rapid UI development)
* **Visualization:** Chart.js (Canvas-based rendering for smooth mobile performance)
* **Icons:** Lucide Icons

### Architecture Highlight: The "Bridge" Workflow
This app serves as the input terminal for a larger automation chain:
1.  **Input:** User logs 10 quotes on the road via the App.
2.  **Export:** Generates `cgh_quotes.csv`.
3.  **Automation:** CSV is imported to Google Sheets, where a backend **Google Apps Script** triggers the generation of PDF invoices.

---

## 🚀 Getting Started

This is a lightweight, client-side application. No build step or server is required to test the prototype.

### Prerequisites
A modern web browser (Chrome, Safari, Firefox, Edge).

### View the Demo

   (https://nicola-empower.github.io/quote-command/)
