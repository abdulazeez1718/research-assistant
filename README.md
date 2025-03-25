<div align="center">
  <img src="https://raw.githubusercontent.com/abdulazeez1718/research-assistant/main/assets/logo.png" alt="Research Assistant Logo" width="200"/>
  
  # Research Assistant Chrome Extension
  
  <p align="center">
    <img src="https://img.shields.io/badge/Platform-Chrome-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Platform"/>
    <img src="https://img.shields.io/badge/Built_with-Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot"/>
    <img src="https://img.shields.io/badge/Powered_by-Gemini_AI-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Gemini AI"/>
  </p>

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&duration=3000&pause=1000&color=4285F4&center=true&vCenter=true&width=435&lines=AI-Powered+Text+Summarization;Chrome+Extension;Boost+Your+Research+Efficiency" alt="Typing SVG" />
  </a>
</div>

## 🌟 Overview

<img align="right" width="300" src="https://media.giphy.com/media/l46Cy1rHbQ92uuLXa/giphy.gif"/>

Research Assistant is a powerful Chrome extension that leverages the Gemini AI API to transform how you process information online. Perfect for researchers, students, and professionals, it instantly summarizes lengthy texts into concise, meaningful insights.

## ✨ Features

- 🤖 **AI-Powered Summarization**
  - Utilizes Gemini AI for intelligent text analysis
  - Generates concise, accurate summaries
  - Maintains context and key points

- 🎯 **Chrome Integration**
  - Seamless browser integration
  - One-click activation
  - Works on any web page

- 🎨 **Intuitive Interface**
  - Clean, modern design
  - Easy-to-use controls
  - Responsive layout

- ⚡ **High Performance**
  - Fast processing
  - Efficient backend
  - Optimized API calls

## 🛠️ Tech Stack

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://img.shields.io/badge/Backend-Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot"/><br>
        <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/Frontend-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/><br>
        <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/><br>
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/API-Gemini_AI-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Gemini AI"/><br>
        <img src="https://img.shields.io/badge/Testing-Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman"/>
      </td>
    </tr>
  </table>
</div>

## 🚀 Setup Guide

### Prerequisites
- Java 17 or higher
- Chrome Browser
- Gemini AI API Key
- Maven

### Backend Setup
```bash
# Clone the repository
git clone https://github.com/abdulazeez1718/research-assistant.git

# Navigate to backend directory
cd research-assistant/backend

# Install dependencies
mvn install

# Configure application.properties
# Add your Gemini AI API key
spring.gemini.api.key=your_api_key_here

# Run the application
mvn spring-boot:run
```

### Extension Setup
1. Open Chrome and navigate to `chrome://extensions/`
2. Enable "Developer mode"
3. Click "Load unpacked"
4. Select the `frontend` directory from the cloned repository

## 📝 Configuration

Create `application.properties` in `src/main/resources`:
```properties
# Server Configuration
server.port=8080

# Gemini AI Configuration
gemini.api.key=your_api_key_here
gemini.api.url=https://api.gemini.ai/v1

# Logging Configuration
logging.level.root=INFO
logging.level.com.research.assistant=DEBUG
```

## 🔧 Usage

1. Navigate to any webpage with text content
2. Click the Research Assistant extension icon
3. Select the text you want to summarize
4. Click "Summarize" button
5. View your concise summary!

## 🌐 API Endpoints

```
POST /api/v1/summarize
GET /api/v1/health
GET /api/v1/status
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

Abdulaziz - [LinkedIn](https://www.linkedin.com/in/abdulazeez-kimsanbayev-67a842255) - abdulazizkimsanbayev1718@gmail.com

Project Link: [https://github.com/abdulazeez1718/research-assistant](https://github.com/abdulazeez1718/research-assistant)

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" width="100%"/>
</div>