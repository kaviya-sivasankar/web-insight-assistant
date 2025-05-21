# Web Insight Assistant 🔍

**Web Insight Assistant** is a Chrome Extension connected to a Spring Boot backend that helps users quickly get AI-powered summaries for any selected web content — all using Gemini AI.

It started out as a simple idea:  
_What if I could highlight content on any page and get an instant summary without switching tabs?_

That’s what this project does.

---

## 🌟 Key Features

- Summarize any selected web content instantly
- Works as a browser extension — no need to leave the tab
- Uses Spring Boot + Gemini AI behind the scenes

---

## 🧑‍💻 Tech Stack

| Frontend (Chrome Extension) | Backend (Spring Boot API) |
|-----------------------------|----------------------------|
| HTML, CSS, JS               | Java 17, Spring Boot 3     |
| Chrome Extensions API       | Gemini AI (Google API)     |

---

## 🛠 How to Run This Project

### 🧩 Frontend - Chrome Extension

1. Go to `chrome://extensions`
2. Turn on **Developer Mode**
3. Click **Load Unpacked**
4. Select the `Research-Assistant-Extension` folder

The extension will now be visible in your Chrome toolbar.

---

### ⚙️ Backend - Spring Boot

1. Navigate to the `websearch` folder
2. Create a file:  
   `src/main/resources/application.properties`


3.Add your Gemini API Key to it:
GEMINI_API_KEY=your_api_key_here

4.Open a terminal and run:
./mvnw spring-boot:run
✅ The backend will start at http://localhost:8080

### 📸 Demo

#### 🧠 Summary Panel in Action

<img src="https://github.com/user-attachments/assets/389a7b53-daa0-42c9-9e7b-3d950a059375" width="420" height="380"/>



<img src="https://github.com/user-attachments/assets/66382b07-7482-40a4-a22a-691df223aa21" width="420" height="380"/>




