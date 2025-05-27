# paper-calculator-
A lightweight and installable Progressive Web App that helps users calculate the cost of paper based on custom dimensions, sheet layouts, and multi-item orders. Includes a theme switcher, PDF invoice export, and settings to define custom pricing. Ideal for print shops, designers, and paper product businesses.
# 📄 Paper Price Calculator (PWA)

A Progressive Web App (PWA) built to calculate paper prices, base sheet layouts, and multiple custom item costs with support for dark/light themes, PDF export, and offline usage. Perfect for printing businesses and designers.

## 🚀 Features

- ✅ **Paper Price Calculator** — Calculates cost based on dimensions and quantity.
- ✅ **Base Sheet Optimizer** — Helps optimize how many pieces fit per base sheet.
- ✅ **Multi-Item Calculation** — Add multiple items and calculate total cost.
- ✅ **PDF Invoice Export** — Generate printable invoices directly from the browser.
- ✅ **Theme Switcher** — Toggle between dark and light modes.
- ✅ **PWA Support** — Installable on mobile and desktop with offline access.
- ✅ **Settings** — Set custom price per cm² based on reference dimensions and price.
- ✅ **Responsive UI** — Mobile-friendly and supports standalone fullscreen display.
- ✅ **Contact Form** — Direct email contact via Web3Forms integration.

## 📦 Technologies Used

- HTML5, CSS3, JavaScript (Vanilla)
- [jsPDF](https://github.com/parallax/jsPDF) for PDF generation
- [html2canvas](https://github.com/niklasvh/html2canvas) for DOM rendering
- Web3Forms API for contact submissions
- PWA Manifest & Service Worker support

## 🧮 How It Works

- Set a base price per square centimeter via **Settings**.
- Use the **Paper Price** page to calculate the total cost based on width, height, and quantity.
- On **Base Sheet**, simulate sheet layout with gutters.
- Add multiple items in **Multi-item** to get cumulative cost.
- Use **Download** section for install instructions on iOS devices.

## 🛠 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/paper-price-calculator.git
cd paper-price-calculator
