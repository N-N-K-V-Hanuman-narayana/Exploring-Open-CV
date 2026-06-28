# 📄 Automated Resume ATS Evaluation System

An AI-powered Resume Analysis System developed using **Python**, **OpenCV**, and **Tesseract OCR** to automatically extract candidate information from resumes and evaluate them using a simple ATS (Applicant Tracking System) scoring algorithm.

---

## 📌 Project Objective

The objective of this project is to automate resume screening by:

- Extracting text from resume PDFs
- Identifying candidate details
- Detecting important resume sections
- Calculating an ATS score
- Providing suggestions to improve the resume

---

## 🚀 Features

- PDF Resume Upload
- PDF to Image Conversion
- Image Preprocessing using OpenCV
- OCR Text Extraction using Tesseract
- Candidate Information Extraction
- Skills Detection
- Education Detection
- ATS Score Calculation
- Resume Rating
- Improvement Suggestions
- JSON Report Generation

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- OpenCV
- Tesseract OCR
- pytesseract
- pdf2image
- Pillow (PIL)
- Regular Expressions (Regex)
- JSON

---

# 📂 Project Structure

```
Automated_Resume_ATS/

│
├── Resume_ATS.ipynb
│
├── resumes/
│     ├── Resume1.pdf
│     ├── Resume2.pdf
│     └── ...
│
├── images/
│     ├── current_resume.png
│     └── processed_resume.png
│
├── output/
│     ├── candidate_information.json
│     ├── parsed_resume.json
│     ├── final_ats_report.json
│     └── ocr_output.txt
│
├── requirements.txt
│
└── README.md
```

---

# 📖 Workflow

```
Resume PDF
      │
      ▼
PDF to Image Conversion
      │
      ▼
Image Preprocessing (OpenCV)
      │
      ▼
OCR Text Extraction
      │
      ▼
Information Extraction
      │
      ▼
ATS Score Calculation
      │
      ▼
Suggestions Generation
      │
      ▼
JSON Report Generation
```

---

# 📚 Modules

## Module 1 – Resume Upload

- Reads resume PDF
- Displays uploaded resume

---

## Module 2 – PDF to Image Conversion

- Converts PDF into image
- Saves image for processing

---

## Module 3 – Image Preprocessing

- Converts image to grayscale
- Noise removal
- Thresholding
- Improves OCR accuracy

---

## Module 4 – OCR Text Extraction

- Uses Tesseract OCR
- Extracts text from processed resume
- Saves extracted text

---

## Module 5 – Information Extraction

Extracts

- Candidate Name
- Email
- Phone Number
- Skills
- Education
- Projects
- Summary

Stores information in JSON format.

---

## Module 6 – ATS Score Calculation

Calculates score based on

- Contact Information
- Skills
- Education
- Projects
- Summary

Maximum Score: **100**

---

## Module 7 – Resume Suggestions

Generates suggestions such as

- Add GitHub Profile
- Add LinkedIn Profile
- Add Certifications
- Add More Technical Skills
- Improve Project Description

---

## Module 8 – Report Generation

Creates

- Candidate Information JSON
- Parsed Resume JSON
- Final ATS Report JSON

---

# ▶️ How to Run

### 1. Install Python packages

```bash
pip install -r requirements.txt
```

---

### 2. Install Tesseract OCR

Download:

https://github.com/UB-Mannheim/tesseract/wiki

Add Tesseract to your system PATH.

---

### 3. Place resumes

Copy all resume PDFs into

```
resumes/
```

---

### 4. Open Notebook

```
Resume_ATS.ipynb
```

Run all cells sequentially.

---

# 📊 Sample Output

```
Candidate Name:
KOTHA ABHI SATHWIK

Email:
24011cseai0030@aiml.suh.edu.in

Phone:
+91-9014779543

Skills:
Python
HTML
CSS
Machine Learning

ATS Score:
90 / 100

Resume Rating:
Excellent

Suggestions:
✔ Add GitHub Profile
✔ Add Certifications
✔ Improve Project Description
```

---

# Future Enhancements

- GUI Application
- React Frontend
- Flask Backend
- Database Integration
- Multiple Resume Comparison
- Job Description Matching
- AI-based Resume Ranking

---

# Author

**Hanuman Narayana**

B.Tech – Computer Science Engineering

Sreenidhi University

---

# License

This project is developed for educational and academic purposes.
