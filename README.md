# Quote Command: Profit Protection & Logistics for Trades 🔨

<img width="2813" height="1514" alt="Quote Command Dashboard" src="https://github.com/user-attachments/assets/75176f87-89df-44b0-a1f8-34b08751a11a" />

> "Moving from sawdust-covered notes to digital precision."

**Quote Command** is a mobile-first pricing and logistics engine designed specifically for independent tradespeople. It transforms the chaotic, manual process of estimating construction jobs into a standardised, margin-protected workflow.

## 🚩 The Problem: "The Admin Bottleneck"

For independent joiners and tradespeople, quoting and material ordering are often the biggest time-sinks. My client spends significant time on the road, balancing notebooks, loose scraps of paper, and mental "guesstimates."

### The Pain Points

* **Batch Overload:** Returning home with 10+ quotes to type up manually takes hours of personal time.
* **Margin Drift:** Forgetting small fixings or underestimating labour eats into the weekend's profit.
* **Logistical Chaos:** Handwritten material lists are easily lost or misread at the merchant's counter.

## 🚀 The Solution: A Digital Daybook

Quote Command is a **Single Page Application (SPA)** that acts as a comprehensive "Digital Daybook." It allows users to rapidly stack quotes and generate material orders while on-site.

### Key Features

* **🧮 Hybrid Labour Engine:** Support for both Hourly and Day rates. Tradespeople can toggle based on how they prefer to bill.
* **🎯 Target Quote Mode:** A "work-backwards" feature. Enter a manual total price, and the engine instantly calculates the resulting profit and margin based on costs.
* **🛒 Smart Materials List:** A dedicated tab for building shop lists. Includes "Quick Add" buttons for common site items (OSB, Postcrete, Fixings) to minimize typing.
* **🖨️ Merchant-Ready Export:** Generates a clean, high-contrast PDF/Print view of the materials list, complete with checkboxes for the merchant to tick off during loading.
* **📂 CSV Batch Export:** One-click export of all pending quotes for seamless integration with accounting software like Xero or QuickBooks.

## 🛠️ Technical Implementation

Built with a **Local-First** philosophy to ensure the app remains functional on-site, even with poor signal.

### Tech Stack

* **Core:** HTML5, Vanilla JavaScript (ES6+)
* **Styling:** Tailwind CSS (Utility-first for a rugged, mobile-responsive UI)
* **Visualisation:** Chart.js for real-time cost vs. profit breakdowns.
* **Icons:** Lucide Icons.

### The "Bridge" Workflow

This app acts as the frontline terminal for a larger automation ecosystem:

1. **Capture:** User logs quotes and material needs via the mobile SPA.
2. **Order:** Materials list is printed/PDF'd to the merchant.
3. **Automate:** CSV export triggers a **Google Apps Script** backend to generate formal PDF invoices and update financial trackers.

## 🚀 Getting Started

No build step or server is required. This is a lightweight, client-side application.

### Prerequisites

A modern web browser (Optimised for Safari/iOS and Chrome/Android).

### View the Demo

<https://nicola-empower.github.io/quote-command/>

### Built by [Nicola Berry](https://empowerdigitalsolutions.co.uk)

**Empower Digital Solutions** | *Bespoke Web Applications & Automation*
