# IntelliChat AI

IntelliChat AI is a full-stack AI-powered chat application inspired by ChatGPT. It supports AI conversations, document-based querying, authentication, chat history, and a modern SaaS-style interface.

## Features

* AI chat using OpenRouter API
* Upload PDF, DOCX, and TXT files
* Authentication system
* Chat history
* Modern dark UI
* FastAPI integration
* MongoDB backend

## Tech Stack

### Frontend

* React.js
* Tailwind CSS
* Axios

### Backend

* Node.js
* Express.js
* FastAPI

### Database

* MongoDB

### AI

* OpenRouter API

## Installation

### Clone Repository

```bash
git clone <your-repo-link>
cd IntelliChat
```

---

## Backend Setup

### Server

```bash
cd server
npm install
npm start
```

### FastAPI

```bash
cd fastapi
pip install fastapi uvicorn python-multipart PyPDF2 python-docx requests
uvicorn main:app --reload
```

### Frontend

```bash
cd client
npm install
npm run dev
```

## Environment Variables

Create `.env` inside `server` folder:

```env
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret
PORT=5000
```

## Project Structure

```text
IntelliChat/
 ├── client/
 ├── server/
 ├── fastapi/
```

## Future Improvements

* Streaming responses
* Cloud chat storage
* Markdown rendering
* Syntax highlighting
* Mobile responsiveness

## Author

Monisha S
