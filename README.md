# paper-calculator-
A lightweight and installable Progressive Web App that helps users calculate the cost of paper based on custom dimensions, sheet layouts, and multi-item orders. Includes a theme switcher, PDF invoice export, and settings to define custom pricing. Ideal for print shops, designers, and paper product businesses.
# 📄 Paper Price Calculator (PWA)

**Paper Price Calculator** is a fully responsive **Progressive Web App (PWA)** designed for printing businesses, designers, and paper suppliers. This tool simplifies the process of calculating paper costs based on custom sizes and quantities, helps optimize sheet layouts, and supports multiple items in one order. With light/dark theme support, offline functionality, and PDF invoice generation, it's your go-to solution for managing paper pricing efficiently.

---

## 🚀 Features

- ✅ **Paper Price Calculator** – Calculates price based on width, height, and quantity.
- ✅ **Base Sheet Optimizer** – Determines how many pieces fit on a base sheet, considering gutters.
- ✅ **Multi-Item Calculation** – Add multiple items with custom dimensions and quantities.
- ✅ **PDF Invoice Export** – Generate printable PDF invoices for each calculation.
- ✅ **Theme Switcher** – Easily switch between light and dark modes.
- ✅ **PWA Support** – Fully installable on mobile or desktop with offline access.
- ✅ **Custom Pricing** – Set and save your own price per cm² from reference dimensions and price.
- ✅ **Responsive Design** – Works seamlessly across all screen sizes.
- ✅ **Contact Form** – Built-in form using Web3Forms for sending messages directly.

---

## 📦 Technologies Used

- **HTML5, CSS3, JavaScript (Vanilla)**
- [`jsPDF`]– for PDF generation
- [`html2canvas`] – for screenshot rendering into PDF
- **Web3Forms API** – for handling contact form submissions
- **Web App Manifest** – for enabling PWA install capabilities
- *(Optional)* Service Worker support (coming soon)

---

## 🧮 How It Works

### ➤ Step-by-step Workflow

1. **Set Your Base Price**  
   Navigate to the **Settings** page and enter a reference width, height, and total price. The app will calculate price per cm² and save it for future use.

2. **Calculate Paper Price**  
   Input the width, height, and quantity of your item in the **Paper Price** section. The app computes total area and pricing, and lets you export an invoice as PDF.

3. **Optimize Base Sheet Layout**  
   In the **Base Sheet** tab, input the full sheet size, gutter spacing, and piece size. It calculates how many pieces fit, used area, waste area, and total cost.

4. **Multi-Item Costing**  
   Use the **Multi-item** section to add various sized items in bulk. You’ll get the total cost and a breakdown for each item.

5. **Export & Install**  
   Every result section offers a **Print Invoice** button. You can also install the app via the **Download** section following mobile instructions.

---

## 📱 How to Download the App on Mobile

You can install the Paper Price Calculator app directly to your device and use it offline with the following steps:

### 📲 iOS (Safari)
1. Open the app in **Safari**.
2. Tap the **Share** icon (the square with an upward arrow).
3. Scroll down and tap **Add to Home Screen**.
4. Choose a name for the app, and tap **Add**.
   
   Once added, the app will appear on your home screen like a native app. It can be launched directly from there without needing to open Safari.

### 📲 Android (Chrome)
1. Open the app in **Chrome**.
2. Tap the **Menu (⋮)** icon in the top-right corner.
3. Tap **Add to Home Screen**.
4. Choose a name for the app, and tap **Add**.

   The app will be added to your home screen and can be accessed like a native app, even when offline.

---

## 🧾 1. Paper Price Page

Calculate the total price for a paper piece based on its **width**, **height**, and **quantity**. The result is calculated using your defined price per cm².

**Key Features:**
- Calculates area and total price.
- Allows PDF export of invoice.

![Paper Price Page](screenshots/paper-price.png)

---

## 📐 2. Base Sheet Page

Find out how many small pieces can fit on a larger base sheet, taking into account gutters/spaces. It calculates **used area**, **waste area**, and estimated total price.

**Key Features:**
- Layout simulation with gutters.
- Accurate material optimization.
- Price calculation and invoice export.

![Base Sheet Page](screenshots/base-sheet.png)

---

## 📋 3. Multi-Item Page

Add multiple items of varying sizes and quantities to calculate a **combined total price**. Ideal for bulk orders.

**Key Features:**
- Tracks multiple item entries.
- Calculates individual and total costs.
- PDF export support.

![Multi-item Page](screenshots/multi-item.png)

---

## 🎨 4. Theme Page

Easily toggle between **light and dark mode** to enhance your visual experience.

**Key Features:**
- Smooth theme switching.
- Saves preference locally.

![Theme Page](screenshots/settings-theme.png)

---

## ⚙️ 5. Settings Page

Set your own **reference price** per cm² based on a known sheet size and total price. This sets the foundation for accurate calculations across all other pages.

**Key Features:**
- Customizable width, height, and price.
- Saves data to local storage.
- Real-time price per cm² update.

![Settings Page](screenshots/settings.png)

---

## 📨 6. Content (Contact Page)

Users can send inquiries or feedback directly through a **Web3Forms-powered** contact form.

**Key Features:**
- Full name, email, phone, subject, and message fields.
- Submission feedback and form reset.

![Contact Page](screenshots/contact.png)

---

## 📥 7. Download Page

Guides users through the process of installing the app on their mobile home screen for **offline use**.

**Key Features:**
- iOS-specific and Android-specific install instructions.
- Designed to improve accessibility and UX.

![Download Page](screenshots/download.png)

---

## 🛠 Installation (For Developers)

To run the project locally or customize it:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/paper-price-calculator.git
cd paper-price-calculator
