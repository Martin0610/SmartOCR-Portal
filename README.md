SmartOCR Portal

AI-Powered Document Text Extraction & Verification

MOSIP Hackathon 2025 – Problem Statement #4


---

📌 Project Overview

SmartOCR Portal is an intelligent document processing system that uses AI-powered OCR to extract text from identity documents, auto-fill forms, and verify user-entered data in real time. The solution is designed to support MOSIP-based identity workflows by reducing manual effort, errors, and processing time.


---

🎯 Problem Statement

Manual document verification is slow (5–10 minutes per document), error-prone (3–5% error rate), and costly at scale.


---

✅ Solution

SmartOCR Portal automates document processing by extracting text, structuring data, enabling user review, verifying inputs, and generating audit-ready reports.


---

✨ Key Features

⚡ 2–3 second OCR processing

🎯 90–95% accuracy for printed text

📝 Auto-fill forms from documents

✅ Real-time data verification

📊 Downloadable audit reports

🎨 Modern React-based UI

🔌 REST APIs ready for MOSIP integration



---

🏗 Project Structure

smartocr-portal-submission/
├── README.md
├── LICENSE.txt
├── CONTRIBUTING.md
├── PROJECT_SUMMARY.pdf
├── documentation/
│   ├── README.md
│   ├── ARCHITECTURE.md
│   ├── API_DOCUMENTATION.md
│   ├── USER_GUIDE.md
│   ├── INSTALLATION_GUIDE.md
│   └── PRESENTATION_SCRIPT.md
├── source-code/
│   ├── backend/
│   │   ├── main.py
│   │   ├── requirements.txt
│   │   └── README.md
│   └── frontend/
│       ├── index.html
│       ├── src/
│       └── package.json
├── demo/
│   ├── demo-video.mp4
│   ├── sample-documents/
│   └── test-results.json
├── presentation/
│   ├── SmartOCR_Presentation.pptx
│   ├── workflow-flowchart.png
│   ├── architecture-diagram.png
│   └── demo-screenshots/
└── deployment/
└── docker-compose.yml


---

🛠 Technology Stack

Backend

Python 3.9+

FastAPI

Tesseract OCR

Pillow (PIL)

pdf2image


Frontend

React 18

Vite

Tailwind CSS



---

⚙ Prerequisites

Python 3.9+

Node.js 16+

Tesseract OCR (added to system PATH)

Poppler (for PDF support)

Git


Supported OS: Windows, macOS, Linux


---

🚀 How to Run the Application

Backend

1. Open command prompt in source-code/backend


2. Run:

python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt

python main.py




Backend URL:
http://localhost:8000

API Docs:
http://localhost:8000/docs


---

Frontend

1. Open command prompt in source-code/frontend


2. Run:

npm install

npm run dev




Frontend URL:
http://localhost:3000


---

🔍 How It Works

1. Upload document (PDF / PNG / JPG)


2. OCR extracts text fields


3. Data auto-fills form


4. User reviews & edits


5. Verification checks mismatches


6. Audit report generated




---

📊 Performance Metrics

Processing Time: 2–3 seconds per document

Accuracy: 90–95%

Error Rate: <1%

Cost Reduction: ~80%

Throughput: 100+ documents/hour



---

🔗 MOSIP Integration Readiness

Ready to integrate with:

Pre-Registration Module

Registration Client

Identity Verification Services



---

🎬 Demo

Demo Video: demo/demo-video.mp4

Screenshots: presentation/demo-screenshots/

Sample Documents: demo/sample-documents/



---

📚 Documentation

Architecture → documentation/ARCHITECTURE.md

API Docs → documentation/API_DOCUMENTATION.md

User Guide → documentation/USER_GUIDE.md

Installation Guide → documentation/INSTALLATION_GUIDE.md



---

👥 Team
CRESHACKERZ 
B.S ABDUR RAHMAN CRESCENT INSTITUTE OF SCIENCE AND TECHNOLOGY 
Email: mjv3140@gmail.com


---

📄 License

This project is licensed under the MIT License.
See LICENSE.txt for details.


---

🙏 Acknowledgments

Built for MOSIP Hackathon 2025
