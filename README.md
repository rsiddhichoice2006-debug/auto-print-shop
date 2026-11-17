# AutoPrint Express - Automated Printing Shop System

A 100% automated self-service printing website and kiosk designed for printing shops.
Customers can upload documents, choose print settings, pay instantly via UPI (GPay, PhonePe, Paytm, BHIM), and printing starts **completely automatically** on your physical printer without any manual operator work.

---

## 🚀 How to Start (One-Click)
Double-click the shortcut on your Desktop:
**`Start AutoPrint Express.bat`**

Or navigate to `C:\Users\ADMIN\.gemini\antigravity\scratch\auto-print-shop` and double-click `start_shop.bat`.

---

## 🌐 URLs & Access
- **Customer Self-Service Kiosk (On Shop PC):**  
  [http://localhost:8000](http://localhost:8000)

- **Customer Mobile Portal (Shop Wi-Fi):**  
  `http://192.168.1.100:8000`  
  *(A ready-to-print QR code is available inside the Admin Dashboard for customers to scan from your counter!)*

- **Store Owner Admin Dashboard:**  
  [http://localhost:8000/admin](http://localhost:8000/admin)  
  - **Default Security PIN:** `1234`

---

## 💰 Configured Pricing Matrix
### Black & White Prints:
- **75 GSM:**
  - A4: **₹5 / page**
  - A3: **₹10 / page**
- **100 GSM:**
  - A4: **₹7 / page**
  - A3: **₹15 / page**

### Color Prints:
- **100 GSM:**
  - A4: **₹10 / page**
  - A3: **₹20 / page**
- **75 GSM:**
  - A4: **₹8 / page**
  - A3: **₹16 / page**

*(You can edit every single price anytime in 1 click from your Admin Dashboard!)*

---

## 🎁 Multiple Sets Bulk Discounts
When a customer orders multiple sets (copies) of the same document, the system automatically applies bulk discounts:
- **1 Set:** Standard price (0% discount)
- **2 - 4 Sets:** 5% OFF
- **5 - 9 Sets:** 10% OFF
- **10 - 19 Sets:** 15% OFF
- **20+ Sets:** 20% OFF

*(All discount percentages and set ranges can be customized in the Admin Dashboard!)*

---

## 🖨️ Connected Hardware
- Detected physical commercial printer: **`TASKalfa 3554ci`**
- Silent Spooler Engine: **SumatraPDF Native Silent Print Engine**
- Secondary printers supported: **Canon iR-ADV 4545 III**, **EPSON L555 Series**, **Microsoft Print to PDF**
