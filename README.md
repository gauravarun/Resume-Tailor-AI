✨ AI Resume Tailor
 
 A simple, single-file web application that uses the Google Gemini API to tailor a candidate's existing
 resume (uploaded as a PDF) to a specific job description. The output is provided as formatted HTML,
 making it easy to copy and paste into Word or Google Docs without losing bolding or list structures.
 
 🚀 Features
 
 PDF Parsing: Upload your existing resume (PDF format) to extract the text content.

 Job Description Input: Paste a job description or use the experimental URL fetching feature.

 Gemini AI Optimization: Rewrites your resume content to highlight relevant skills and incorporate
 keywords from the job description for better ATS (Applicant Tracking System) compatibility.

 Formatted Output: Generate and download the result as a self-contained .html file, or copy the
 formatted text directly to your clipboard.

 Model Selection: Choose different Gemini models based on your preference and API key access.

 Error Handling: Includes exponential backoff for API calls to handle transient rate-limiting issues.

 ⚙ How to Run Locally
 
 Since this is a single HTML file, getting it running is very easy!
 1. Clone the Repository:
 git clone [https://github.com/gauravarun/Resume-Tailor-AI.git]
 2. Open the File: Simply open the index.html file in your favorite web browser (e.g., Chrome,
 Firefox).
 open index.html 
 3. Start Using: The application will load immediately.
 
 🔑 API Key Setup (Required)
 
 This application requires access to the Google Gemini API to function.
 1. Get an API Key: Obtain a key from Google AI Studio:
 Go to the 
    Google AI Studio API Key page :https://gemini.google.com/app/76310abae3d6e511


    Click "Create API key" and copy the generated key (it starts with AIza... ).

 2. Enter the Key: Paste your copied API key into the "Google Gemini API Key" field within the
 application. The key is only stored in your browser session and is used directly for API calls.
 
 📝 Usage
 
 1. Enter API Key: Paste your Gemini API Key.
 2. Input Job Description: Paste the text of the job you are applying for into the Job Description box.
 3. Input Resume: Click the upload box in the Your Resume section and select your PDF resume. The
 text will be parsed and displayed in the box below.
 4. Generate: Click the "✨ Generate Tailored Resume" button.
 5. Review Results: The app will switch to the Tailored Resume tab.
 6. Export:
 Click "Copy Formatted Text" and paste directly into Word or Google Docs to retain
 formatting.
 Click "Download .html" to save the formatted resume as an HTML file, which you can open
 and copy the rich text from