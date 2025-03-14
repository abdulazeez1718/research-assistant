# research-assistant
Research Assistant Chrome Extension

Overview

The Research Assistant is a Google Chrome extension powered by  Gemini AI API, designed to help users quickly summarize long texts. Whether you're reading articles, research papers, or any web content, this tool extracts key points efficiently to save time and improve productivity.

Features

🚀 AI-Powered Summarization: Uses Gemini AI API to generate concise summaries.

🌐 Seamless Integration: Works directly within Chrome for easy access.

🎨 User-Friendly UI: Minimalistic and intuitive design.

⚡ Efficient Backend: Built with  Spring Boot for performance and scalability.

🔧 API Requests: Tested and optimized using  Postman.

🖥 Lightweight Frontend: Developed with HTML, CSS, JavaScript, and JSON.

Technologies Used

 Backend: Spring Boot

 API Testing: Postman

 Frontend: HTML, CSS, JavaScript, JSON

 AI Model: Gemini AI API

Installation & Setup

1. Clone the Repository

git clone https://github.com/your-username/research-assistant-extension.git
cd research-assistant-extension

2. Backend Setup

Prerequisites

Install Java (JDK 17 or later)

Install Maven

Set up the Gemini AI API key

Run the Backend

cd backend
mvn spring-boot:run

3. Chrome Extension Setup

Load the Extension

Open Google Chrome.

Go to chrome://extensions/.

Enable Developer mode (toggle at the top right).

Click Load unpacked.

Select the chrome-extension folder from the cloned repository.

Usage

Highlight any text on a webpage.

Click on the Research Assistant extension icon.

View the AI-generated summary instantly.

API Configuration

Get a Gemini AI API key from Google AI

Add the API key to the backend's application.properties file:
