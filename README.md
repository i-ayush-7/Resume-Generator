# 📄 LinkedIn to AI Resume Generator

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Ready-orange)
![Gemini API](https://img.shields.io/badge/AI-Gemini%202.5%20Flash-green)

A Python-based tool designed to run on **Google Colab** that automates the creation of a professional resume. It extracts raw data from your LinkedIn profile PDF, processes it using Google's **Gemini 2.5 Flash** model to enhance content and formatting, and generates a polished, ready-to-use Resume PDF.

---

## 🚀 Features

* **PDF Extraction:** Detailed parsing of LinkedIn profile PDFs to extract work history, education, skills, and certifications.
* **AI-Powered Content Enhancement:** Uses `gemini-2.5-flash` to rewrite bullet points, optimize summaries, and structure data for maximum impact.
* **Automated PDF Generation:** Converts the processed AI output into a clean, professional PDF resume.
* **Cloud-Native:** Fully configured to run seamlessly in Google Colab without local environment setup.

---

## 🛠️ Tech Stack

* **Language:** Python
* **Environment:** Google Colab
* **AI Model:** Google Gemini 2.5 Flash (via Google Gen AI SDK)
* **Libraries:** `PyPDF2` (for extraction), `reportlab` or `fpdf` (for generation), `google-generativeai`.

---

## 📋 Prerequisites

Before running the notebook, ensure you have the following:

1. **Google Account:** To access Google Colab.
2. **Gemini API Key:** You need a valid API key from Google AI Studio.
   * [Get your API Key here](https://aistudio.google.com/app/apikey)
3. **LinkedIn Profile PDF:**
   * Go to your LinkedIn Profile -> Click "More" -> "Save to PDF".

---

## 🏃‍♂️ How to Run

1. **Open the Notebook:**
   Click the badge below to open the project directly in Google Colab:
   
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK_HERE)

2. **Install Dependencies:**
   Run the first cell to install the required Python libraries.
   ```python
   !pip install -q -U google-generativeai pypdf2 reportlab
