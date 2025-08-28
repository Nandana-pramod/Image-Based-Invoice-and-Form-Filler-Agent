Invoice & Form Data Extraction System

A Flask-based web application for extracting structured data from invoices and forms using OCR (Tesseract + OpenCV).
The system supports PDF and image uploads, automatically extracts invoice metadata and line items, and consolidates results into a single Excel file for further analysis.

✨ Key Features

📂 Upload invoices in PDF, JPG, PNG, JPEG formats.

🔎 Extracts Invoice Number, Date, and Line Items.

📊 Consolidates extracted data into Excel (all_invoices.xlsx).

➕ Automatically appends new invoices to existing records.

🌐 Intuitive Flask web interface with simple upload & results display.

🛠 Tech Stack

Backend: Flask (Python)

OCR: Tesseract OCR, OpenCV

Data Processing: Pandas, OpenPyXL

Frontend: HTML, Bootstrap
