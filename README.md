# Health Chatbot 🏥💬

A modern, responsive health chatbot application built with Node.js, Express, and MySQL. This application provides AI-powered health consultations using the Groq API, with user authentication and chat history features.

## Features ✨

- **User Authentication**: Secure signup and login system with password hashing
- **AI Health Consultation**: Powered by Groq API for intelligent health-related responses
- **Chat History**: Store and retrieve previous conversations
- **Responsive Design**: Modern UI that works on desktop and mobile devices
- **Real-time Messaging**: Instant chat interface with typing indicators
- **Personalized Experience**: User-specific chat history and suggestions

## Tech Stack 🛠️

- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **AI Integration**: Groq API
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Authentication**: bcrypt for password hashing
- **Environment**: dotenv for configuration

## Prerequisites 📋

Before running this application, make sure you have:

- Node.js (v14 or higher)
- MySQL Server
- Groq API key

## Installation & Setup 🚀

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd health-chatbot
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the application**
   ```bash
   npm run dev
   ```

4. **Access the application**
   - Open your browser and navigate to `http://localhost:3000`

## Usage 📱

1. **Sign Up/Login**: Create a new account or login with existing credentials
2. **Start Chatting**: Type your health-related questions in the chat interface
3. **View History**: Access your previous conversations in the History tab
4. **Get Suggestions**: Receive personalized health suggestions based on your chat history

## API Endpoints 🔗

- `POST /api/register` - User registration
- `POST /api/login` - User login
- `GET /api/auth-status` - Check authentication status
- `POST /api/logout` - User logout
- `POST /api/chat` - Send chat message and get AI response
- `GET /api/chat-history` - Retrieve user's chat history
- `GET /api/health-suggestions` - Get personalized health suggestions

## Database Schema 🗄️

The application uses two main tables:

- **Users**: Stores user authentication information
- **Chats**: Stores chat messages and AI responses

## Security Features 🔒

- Password hashing using bcrypt
- Session-based authentication
- Input validation and sanitization
- Environment variable protection
- SQL injection prevention

## Contributing 🤝

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Features

- **User Authentication**: Secure login/signup system with password hashing
- **AI Health Assistant**: Powered by Groq API with health-specific query filtering
- **Text & Voice Input**: Support for both text and voice-based interactions
- **Chat History**: Persistent storage of all conversations
- **Personalized Suggestions**: AI analyzes chat history to provide tailored health advice
- **Responsive Design**: Modern, mobile-friendly interface
- **Health Query Filtering**: Only responds to health-related questions

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **AI API**: Groq API (Llama 3 8B model)
- **Voice Input**: Web Speech API
- **Authentication**: bcryptjs, express-session

## Prerequisites

Before running this application, make sure you have:

1. **Node.js** (v14 or higher) - [Download here](https://nodejs.org/)
2. **MySQL** (v8.0 or higher) - [Download here](https://dev.mysql.com/downloads/)
3. **Groq API Key** - [Get it here](https://console.groq.com/)


## Usage Guide

### Getting Started

1. **Sign Up**: Create a new account with username and password
2. **Login**: Use your credentials to access the chatbot
3. **Start Chatting**: Ask health-related questions in the chat interface
4. **Voice Input**: Click the microphone button to use voice input
5. **View History**: Switch to the History tab to see past conversations

### Supported Health Topics

The chatbot can help with:

- **Physical Health**: Headaches, pain, fatigue, cold symptoms, allergies
- **Mental Health**: Stress, anxiety, depression, mood issues
- **Lifestyle**: Sleep problems, diet, exercise, hydration
- **Student-Specific**: Study stress, exam anxiety, concentration issues
- **General Wellness**: Healthy habits, self-care, preventive measures

### Example Queries

- "I have a headache, what should I do?"
- "I'm feeling stressed about exams"
- "How can I sleep better?"
- "I'm always tired, any suggestions?"
- "What are some healthy eating tips for students?"

## Project Structure

```
ai-student-health-chatbot/
├── public/
│   ├── index.html          # Main HTML file
│   ├── styles.css          # CSS styles
│   └── script.js           # Frontend JavaScript
├── server.js               # Express server
├── groqService.js          # Groq API integration
├── database.sql            # Database schema
├── package.json            # Dependencies
├── .env                    # Environment variables
└── README.md              # This file
```
