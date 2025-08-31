Audio Intelligence Hub
This is a single-page interactive web application that transforms audio files into structured insights using the Google Gemini API. The app is designed for easy local use and deployment on platforms like GitHub Pages.

Features
Audio-to-Text Transcription: Accurately transcribes audio from any language.

Language Translation & Refinement: Automatically translates the transcript into clean, professional English.

AI-Powered Summarization: Generates a concise summary of the transcribed content.

Interactive Q&A: Creates a list of questions and answers to help you review the material.

Key Topic Identification: Extracts the most important keywords and themes.

How to Run the Project
This application is designed as a single, self-contained HTML file, making it very easy to run.

Option 1: Run Locally (Recommended)
Save the file: Save the index.html file to your local machine.

Open in Browser: Simply open the index.html file in your preferred web browser (e.g., Chrome, Firefox, Safari).

Option 2: Deploy to GitHub Pages
Create a New Repository: Go to GitHub and create a new repository.

Upload the file: Upload the index.html file to the root of your new repository.

Enable GitHub Pages:

Go to your repository's Settings.

Navigate to the Pages section on the left-hand menu.

Under "Build and deployment," choose Deploy from a branch.

Select the main branch and the / (root) folder, then click Save.

Your application will now be live at a URL like https://[your-username].github.io/[your-repository-name]/.

Online Dependencies
This application requires an internet connection to function because its core intelligence relies on external services. The index.html file contains the logic to call these services:

Google Gemini API: This is the large language model that handles all transcription, translation, and text-processing tasks.

CORS Proxy: A proxy is used to bypass browser security restrictions (CORS) when fetching audio files from external URLs.

Note: The application will not work without an active internet connection.
