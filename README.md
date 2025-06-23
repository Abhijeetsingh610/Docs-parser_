# 🧾 Document OCR & Gemini Parser

This Colab notebook allows you to extract **structured data** from three types of real-world documents using **OCR** and the **Google Gemini API**:

- 🪪 **Driving Licenses**
- 🛒 **Shop Receipts**
- 📄 **Resumes**

Gemini returns clean, valid **JSON output**, ready for downstream use in applications or systems — all through a simple image upload.

---

## ⚙️ Technologies Used

- 🧠 **Google Gemini API**
- 🖼️ **EasyOCR / Tesseract OCR**
- 🐍 **Python 3.x (Google Colab)**
- 📦 **Libraries**: `requests`, `json`, `pytesseract` / `easyocr`, `Pillow`, `re`

---

## 🚀 How to Run This Project on Colab

### 📂 Open the Colab Notebook

Just click the link below to open the notebook in Colab.  
Make sure you're signed into your Google account.

➡️ **[https://colab.research.google.com/drive/1Vq2dMF97T8USJ6wl07WW1MhrxSlUs6o_?usp=sharing](#)**

---

### 📌 Install Dependencies

The first few code cells will install all required libraries:

- `pytesseract` or `easyocr`
- `Pillow`, `requests`, `json`

---

### 🔑 Set Your Gemini API Key

Replace this line:

```python
GEMINI_API_KEY = "YOUR_GEMINI_API_KEY"
