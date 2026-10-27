Resume Analyzer 2.0 📄

A modern, browser-based resume analysis and job matching tool.

Resume Analyzer helps users evaluate their resumes, identify important skills, review essential resume sections, and compare their resumes against a job description.

The project combines a premium, minimalist interface with practical resume analysis features to help job seekers improve their resumes.

✨ Features

- Resume Upload: Supports PDF, DOCX, and TXT files.
- Resume Text Analysis: Extracts relevant information from resume content.
- Job Description Matching: Compares resume keywords with a provided job description.
- Resume Score: Generates a rule-based score based on detected resume content and keyword coverage.
- Skill Detection: Identifies relevant technical and professional skills.
- Contact Information Detection: Looks for email addresses, phone numbers, LinkedIn profiles, and GitHub profiles.
- Section Detection: Checks for important sections such as education, skills, and experience.
- Improvement Suggestions: Provides actionable tips to improve resume quality.
- Downloadable Report: Exports analysis results as a text report.
- Sample Analysis: Lets users explore the tool using sample data.
- Responsive UI: Designed for desktop and mobile screens.
- Privacy-Focused Processing: Resume analysis runs in the browser without uploading resume content to a custom backend server.

🛠️ Tech Stack

- HTML5 — Page structure
- CSS3 — Styling, responsive layout, and visual design
- JavaScript — Resume processing and analysis logic
- PDF.js — PDF text extraction
- Mammoth.js — DOCX text extraction

PDF.js and Mammoth.js are loaded through external CDNs, so those file-reading features require an internet connection.

🚀 Getting Started

1. Clone the repository

git clone https://github.com/lovepreet-cmd/resume-analyzer.git

2. Open the project

Navigate to the downloaded project folder.

3. Run the application

Open "index.html" in your web browser.

No custom backend server or database is required for the current version.

📖 How to Use

1. Open Resume Analyzer in your browser.
2. Upload your resume or paste its text.
3. Optionally paste a job description for a job-match analysis.
4. Click Analyze Resume.
5. Review the detected skills, resume sections, score, and suggestions.
6. Download your analysis report if needed.

🎨 UI Design

The interface follows a modern, minimalist design philosophy featuring:

- A charcoal-black and warm-ivory colour palette
- Clean typography and generous spacing
- Rounded dashboard cards
- Resume analysis and job-match panels
- Responsive layouts for different screen sizes

🔒 Privacy and Limitations

Resume content is processed locally in the browser by the application. However, the PDF.js and Mammoth.js libraries are fetched from external CDNs, which means an internet connection is needed for those features.

The current version uses rule-based analysis, not a trained AI model. Its score is an indicative measure of detected content and keyword overlap, not an official ATS score, hiring prediction, or guarantee of selection. Scanned PDFs may require OCR or manual text input.

🔮 Future Improvements

- AI-powered resume feedback
- More detailed job-description matching
- Missing-skill recommendations
- Resume formatting and readability checks
- PDF export for analysis reports
- Resume history and saved reports
- OCR support for scanned resumes
- Optional backend integration for advanced analysis

👨‍💻 Developer

Lovepreet
B.Tech Computer Science & Engineering Student

- GitHub: "@lovepreet-cmd" (https://github.com/lovepreet-cmd)
- LinkedIn: "Lovepreet on LinkedIn" (https://www.linkedin.com/in/lovepreet-mathur-4600b1413/)

📌 Project Status

Version: 2.0
Status: Prototype / Active Development

---

Built as a learning project to explore frontend development, text processing, resume analysis, and job-description matching.
