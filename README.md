# queen_mall_system
Smart Mall Billing System is a Python desktop app for managing billing in mall shops. Features include itemized billing, customer management, invoice generation, speech-based entry, QR code and manual code scanning — all with a stylish Tkinter GUI and MySQL integration.

# 👑 Queen Mall Billing System

Queen Mall Billing System is a Python-based desktop application designed to streamline billing operations across multiple shops in a mall. It offers a stylish, user-friendly interface and robust backend features integrated with MySQL.

## 🚀 Features

- 🧾 Itemized billing with GST calculation
- 🗣️ Speech-to-text item entry (Shop 2)
- 📷 QR code scanning for items (Shop 3)
- 🔢 Manual code entry for items (Shop 4)
- 👥 Customer management with reward points
- 🧾 Colorful invoice PDF generation and WhatsApp sharing
- 📊 Invoice reports with date-wise and customer-wise filtering
- 🔐 Login system for shop access

## 🛠️ Technologies Used

- Python (Tkinter)
- MySQL (via PyMySQL)
- ReportLab for PDF invoice generation
- SpeechRecognition for voice input
- OpenCV for QR code reading
- GitHub Desktop for version control

## 📦 Setup Instructions

1. Clone this repository:
git clone https://github.com/Dhivyalakshmi-M/queen_mall_system.git

markdown
Copy
Edit
2. Install required libraries:
pip install pymysql reportlab opencv-python speechrecognition pywhatkit

pgsql
Copy
Edit
3. Set up the MySQL database using the provided schema.
4. Run `main_mall.py` to start the application.

## 📁 Project Structure

queen_mall_system/
├── billing_shop1.py
├── billing_shop2.py
├── billing_shop3.py
├── billing_shop4.py
├── customer_page.py
├── invoice_page.py
├── login.py
├── main_mall.py
├── shop_selection.py
├── PyWhatKit_DB.txt

yaml
Copy
Edit

## 📬 Contact

For any queries or feedback, contact **Dhivyalakshmi M** via GitHub Issues or Discussions.

---
