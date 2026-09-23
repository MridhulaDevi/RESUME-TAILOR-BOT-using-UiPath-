# Smart Resume Tailor Bot 🤖

A UiPath RPA automation that dynamically tailors resumes based on Job Descriptions by extracting relevant skills using Regex, updating a resume template, generating a PDF, and sending the customized resume through email.

## 📌 Overview

Applying for multiple job roles often requires modifying a resume according to the skills and requirements mentioned in each Job Description.

The **Smart Resume Tailor Bot** automates this process using UiPath.

The bot:

1. Reads candidate information from Excel.
2. Reads Job Description (`.txt`) files from an input folder.
3. Extracts relevant technical and soft skills using Regex.
4. Generates a customized professional summary.
5. Updates a Word resume template using placeholders.
6. Generates the customized resume as a PDF.
7. Sends the resume through email.
8. Logs the result and updates the UiPath Queue transaction status.

---

## 🚀 Features

- 📄 Job Description text processing
- 🔎 Regex-based skill extraction
- 📝 Dynamic resume customization
- 📊 Excel-based candidate data
- 📑 Microsoft Word automation
- 📄 Automatic PDF generation
- 📧 SMTP email automation
- ⚙️ UiPath Orchestrator Assets
- 📦 UiPath Queue-based transaction processing
- 🛡️ Try-Catch exception handling
- 📋 Execution logging

---

## 🛠️ Technologies Used

- **UiPath Studio**
- **UiPath Orchestrator**
- **RPA**
- **Regex**
- **Microsoft Excel**
- **Microsoft Word**
- **SMTP / Gmail**
- **PDF Automation**
- **VB.NET Expressions**

---

## 🏗️ Project Structure

Currently, the project is implemented using a single UiPath workflow:

```text
Smart-Resume-Tailor/
│
├── Main.xaml
└── README.md
