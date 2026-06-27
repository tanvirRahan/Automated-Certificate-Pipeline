# 🎓 Automated Certificate Generator Pipeline

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tanvirRahan/Automated-Certificate-Pipeline/blob/main/certificates.ipynb)

An industry-grade ETL (Extract, Transform, Load) pipeline built with Python to automate the mass generation of professional certificates. It extracts data from structured datasets, dynamically generates role-specific summaries and tracking IDs, and outputs high-quality PDFs.

## 🚀 Technical Highlights
* **Dynamic Content Injection:** Automatically maps and writes high-impact performance summaries based on the candidate's technical domain (Frontend, Backend, SQA, UI/UX).
* **Smart Reference Tracking:** Auto-generates unique Reference Numbers using custom text-parsing logic based on the candidate's nomenclature structure.
* **Headless Conversion:** Utilizes LibreOffice in headless mode via CLI for 100% accurate `.docx` to `.pdf` conversion, preserving complex document geometries and MS Word native formatting (e.g., Justified text arrays).
* **Automated Batch Processing:** Ingests `pandas` dataframes and processes batches of certificates directly into an optimized `.zip` archive.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Data Engineering:** `pandas`, `openpyxl`
* **Template Engine:** `docxtpl`, `python-docx`
* **Infrastructure:** `LibreOffice` (Headless environment)

## 💻 Execution
This project is designed as executable documentation via Google Colab. 
1. Click the **Open in Colab** badge above.
2. The notebook will automatically fetch the `sample_data.xlsx` and `certificate_template.docx` files from this repository.
3. Run the cells sequentially to observe the pipeline in action.

---
*Built with professional workflow automation and data processing standards.*
