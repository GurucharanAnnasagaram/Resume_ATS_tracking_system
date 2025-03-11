Key Features:
PDF Resume Processing:

Users upload their resume in PDF format.
The system extracts the first page of the resume, converts it into an image, and encodes it in Base64 format for AI processing.
AI-Powered Resume Evaluation:

Uses Google Gemini Pro Vision to analyze resumes and compare them with a given job description.
Provides insights into strengths and weaknesses of the candidate’s profile.
ATS Matching Score Calculation:

The AI evaluates how well the resume matches the job description.
Outputs:
Percentage Match
Keywords Missing
Final Thoughts
Streamlit UI:

Text area to enter the job description.
File uploader to upload resumes in PDF format.
Buttons for different functionalities:
Tell Me About the Resume: Provides an AI-generated review of the resume.
Percentage Match: Calculates how well the resume aligns with the job description.
Technologies Used:
Streamlit: For web-based UI.
Google Gemini Pro Vision: For AI-driven resume analysis.
pdf2image & PIL (Pillow): For processing PDF resumes into images.
Base64 Encoding: To encode images for AI processing.
