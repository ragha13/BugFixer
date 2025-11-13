# Code-Doctor: AI-Powered GitHub Bug Fixer

Code-Doctor is an **AI-driven GitHub issue fixer** that automatically detects, analyzes, and fixes bugs in your GitHub repository using **Groq AI**.

## 🌟 Features
**1.Fetch Open GitHub Issues** – Retrieves all issues with valid file paths  
**2.AI-Powered Bug Fixing** – Uses **Mixtral-8x7b-32768** for intelligent debugging  
**3.Root Cause Analysis** – Explains why the bug occurred  
**4.Code Fix & Optimization** – AI-generated fixes with best practices  
**5.Branch Selection** – Supports both `main` and `master` branches  
**6.PDF Report Generation** – Download a structured fix report  

---

## Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-repo/Code-Doctor.git
cd Code-Doctor
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file in the project root and add:
```ini
GITHUB_PAT=your_github_personal_access_token_here
GROQ_API_KEY=your_groq_api_key_here
```

### 4️⃣ Run the Application
```bash
streamlit run app.py
```

---

## Usage
1. **Enter your GitHub repository link**
2. **Select the branch (`main` or `master`)**
3. **Click "Fetch & Fix All Issues"**
4. **View AI-generated fixes and explanations**
5. **Download the fix report as a PDF**

---

## Technologies Used
- **Streamlit** – Web UI  
- **GitHub API** – Fetches issues & files  
- **Groq AI (Mixtral-8x7b-32768)** – Code analysis & fixes  
- **FPDF** – Generates downloadable reports  

---


