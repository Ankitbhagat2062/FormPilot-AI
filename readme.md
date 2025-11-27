# FormPilot AI

FormPilot AI is an intelligent MERN-based automation platform designed to simplify complex online form submissions. It reads form webpages, extracts required details, validates documents, auto-fills fields, and completes full submission — minimizing human error and saving time.

---

## 🚀 Key Features

### 1. **AI-Powered Form Reader**
- Users provide a form link (URL).
- The system automatically identifies:
  - Required form fields
  - Required documents
  - Specifications (format, size, dimensions, aspect ratio)
  - Repeated personal details (name, address, DOB, etc.)

### 2. **Intelligent Document Verifier**
- AI detects the type of uploaded document (photo, signature, transcript, citizenship, etc.).
- Warns users if they upload the wrong document.
- Ensures the document matches the form's requirements.

### 3. **Automatic Document Conversion**
- Converts and optimizes files automatically:
  - JPG ↔ PNG
  - JPG → PDF
  - Compresses large files
  - Adjusts width × height
  - Fixes resolution, cropping, and file size

### 4. **Automated Form Completion**
- AI extracts information from uploaded files.
- Autofills all required form fields accurately.
- Reduces chances of manual typing errors.

### 5. **Single Profile for Multiple Forms**
- Users create their profile once.
- FormPilot automatically reuses stored data for future forms.
- Saves time and eliminates repeated typing.

### 6. **AI Submission Assistant**
- After completing and attaching documents:
  - The system submits the form automatically.
  - Saves form screenshots and submission receipts.

### 7. **Error Prevention System**
- Detects inconsistent names, DOBs, or mismatched documents.
- Warns the user before submitting.
- Ensures all fields meet the form's exact requirements.

---

## 🛠️ Tech Stack (MERN)
- **MongoDB** – User profiles, saved data, document metadata
- **Express.js** – Backend API, file processing handlers
- **React.js** – User interface & dashboard
- **Node.js** – AI document-processing pipelines and automation scripts

Additional optional integrations:
- OCR Engines (Tesseract/Google Vision)
- AI Models for document classification
- Puppeteer/Playwright for autofill & submission automation

---

## 🎯 Purpose of the Project
FormPilot AI helps students, job applicants, and everyday users who struggle with:
- Confusing form instructions
- Wrong file formats
- Form submission errors
- Time-consuming repetitive tasks

This system automates the entire workflow — from reading the form to submitting it.

---

## 📌 Why FormPilot AI?
- Saves time
- Eliminates manual errors
- Perfect for government forms, college forms, scholarships, visas, job portals, etc.
- Reduces stress for users who are not tech-savvy

---

## 📄 License
This project is open-source for hackathon demonstration purposes.

---

## 💬 Feedback & Contributions
Feel free to open issues or submit pull requests to improve the platform.

