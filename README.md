# AI-Based Resume Matcher  
An AI-powered web application that matches resumes against job descriptions using NLP techniques. It provides a similarity score and highlights missing keywords, helping HR and recruitment teams screen candidates efficiently.

Features include inputting a job description and uploading multiple resumes (PDF, DOCX, TXT), calculating similarity scores between job description and resumes using NLP embeddings, displaying top matching resumes with scores, and a user-friendly responsive UI with file upload and result visualization. Built with Flask backend and Bootstrap frontend.

Tech stack: Python, Flask, Gunicorn, spaCy, Transformers (HuggingFace), scikit-learn, HTML, Bootstrap 4, deployed on Render.com.
## Installation & Setup

Clone the repo by running:

    ```bash
    git clone https://github.com/YOUR_USERNAME/AI-Resume-Matcher.git
    cd AI-Resume-Matcher
    python -m venv env
# Windows
    .\env\Scripts\activate
# Mac/Linux
    source env/bin/activate
    pip install -r requirements.txt

## Usage

- Paste the job description text in the provided textarea.  
- Upload multiple resume files (PDF, DOCX, or TXT).  
- Click **Match Resumes** to get similarity scores and missing keywords.
## Deployment
This project is deployed on Render.com. To deploy yourself:

Create a Procfile with the following content:
web: gunicorn main:app

Push your repo to GitHub.

Connect your GitHub repo to Render.com and deploy as a Python web service.

## Contributions
Contributions are welcome! Please open an issue or submit a pull request.

## Contact

Created by Vishal Singh Kashyap  
Email: [your-singhvishalk165@gmail.com]  
LinkedIn: [https://linkedin.com/in/vishal-kashyap](https://www.linkedin.com/in/vishal--kashyap/)
