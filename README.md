# 🧾 PROFUTUNNY INVESTMENTS - Invoice Generator

A modern, responsive, and **Safari-compatible web app** for creating professional invoices quickly and easily.  
Designed for **mobile and desktop**, it works perfectly on **iPhone (Safari)**, **Android**, and **PC browsers**.

🌐 **Live Demo:** [https://kutch23.github.io/invoicegen/](https://kutch23.github.io/invoicegen/)

---

## 🚀 Features

✅ **Easy Invoice Creation**
- Add, edit, and remove items dynamically.  
- Auto-calculates totals and updates instantly.  

✅ **Company Branding**
- Upload your own company logo or use an image URL.  
- All branding info is saved locally for reuse.

✅ **PDF Export (Safari-Optimized)**
- Generate and download invoices as high-quality PDFs.  
- Works seamlessly on Safari for iPhone and macOS.  

✅ **Smart Auto-Save**
- Uses `localStorage` to automatically save invoice data.  
- Reload the page and continue where you left off.  
- Includes a **“Clear Saved Data”** button to start fresh.

✅ **Fully Offline**
- Works without an internet connection once loaded.

---

## 💡 How to Use

1. Visit: [https://kutch23.github.io/invoicegen/](https://kutch23.github.io/invoicegen/)  
2. Fill in:
   - Company and customer details  
   - Invoice number and date  
   - Line items (description, quantity, price)
3. Click **Generate Invoice** to preview.  
4. Tap **Download PDF** to save or share your invoice.  
5. Your progress is saved automatically.

---

## 🛠️ Technology Stack

- **HTML5 / CSS3 / JavaScript (Vanilla)**
- [html2canvas](https://html2canvas.hertzen.com/) – for rendering invoices  
- [jsPDF](https://github.com/parallax/jsPDF) – for PDF generation  
- Optimized for **Safari, Chrome, and Edge**

---

## 📱 Supported Platforms

- ✅ iPhone & iPad (Safari)
- ✅ Android devices (Chrome)
- ✅ Windows & macOS browsers

---

## 🧰 Developer Notes

Run locally:
```bash
# Clone repository
git clone https://github.com/kutch23/invoicegen.git

# Open folder
cd invoicegen

# Open in browser
open index.html   # macOS
# or
start index.html  # Windows
