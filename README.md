# Advanced Java Practical Editor

A web application for editing Advanced Java practical documents. This application allows users to modify their name and roll number in DOCX files.

## Features
- Modern UI with Shadcn and GSAP animations
- Easy document editing
- Automatic file download
- Responsive design

## Local Development
1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
python app.py
```

3. Visit http://localhost:5000 in your browser

## Deployment Instructions

### Deploying to Render.com

1. Create a new account on [Render](https://render.com)
2. Click "New +" and select "Web Service"
3. Connect your GitHub repository
4. Fill in the following details:
   - Name: advanced-java-editor
   - Environment: Python 3
   - Build Command: `pip install -r requirements.txt`
   - Start Command: `gunicorn wsgi:app`
5. Click "Create Web Service"

### Environment Variables
No environment variables are required for basic deployment.

## Support
For any issues or questions, please open an issue in the GitHub repository. 