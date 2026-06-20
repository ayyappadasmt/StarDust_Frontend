# StarDust Frontend

A futuristic conversational AI interface featuring a galaxy-themed design, real-time streaming responses, and persistent chat sessions.

Built to provide an immersive user experience while interacting with the StarDust AI assistant.

---

## Features

- Beautiful Galaxy Background
- Streaming AI Responses
- Persistent Sessions
- Glassmorphism UI
- Real-time Message Updates
- Session Tracking
- Mobile Friendly Layout
- Fast Loading Static Deployment

---

## Preview


StarDust offers an experience similar to modern AI chat platforms with a cinematic space-inspired design.


Features include:


✔ Live response generation

✔ Conversation continuity

✔ Session IDs

✔ Interactive chat bubbles

✔ Smooth scrolling



---

## Tech Stack


| Component | Technology |
|-----------|------------|
| Frontend | HTML5 |
| Styling | CSS3 |
| Logic | Vanilla JavaScript |
| Streaming | Fetch API |
| Hosting | Netlify |
| Media | MP4 Video Background |

---

## Project Structure


```text
StarDust_Frontend/

│

├── index.html

├── netlify.toml

│

└── assets/

    └── galaxy.mp4
```



---

## Running Locally


Clone repository



```bash
git clone https://github.com/yourusername/StarDust_Frontend.git
```



Open


```text
index.html
```



or


Run



```bash
python -m http.server
```



Visit



```text
http://localhost:8000
```



---

## Backend Configuration


Update the backend endpoint inside:


```javascript
const API_BASE_URL =
"https://stardust-backend-6zjp.onrender.com";
```



Change to local backend if needed.


```javascript
const API_BASE_URL =
"http://localhost:8000";
```



---

## Deployment


Deploy easily on:


### Netlify


```bash
Drag and Drop Project Folder
```



or connect GitHub repository.



Netlify redirects are configured using:


```text
netlify.toml
```



---

## User Interface


The interface consists of:


### Header

Displays project branding.


---

### Session Manager


Tracks active conversations.


---

### Chat Window


Shows streamed AI responses.


---

### Input Box


Allows user interaction with the assistant.


---

## Future Improvements


- Markdown Rendering
- Syntax Highlighting
- Dark/Light Themes
- Voice Input
- Image Uploads
- Chat Export
- Authentication


---

## Contributors


Built as part of the **StarDust AI Conversational Platform** project.


---

## License


MIT License
