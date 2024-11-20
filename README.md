# Tinder AI

A Tinder-inspired AI-powered application built with **React** and **Spring Boot**, integrating **GPT-4** and **Stable Diffusion** to generate dynamic profiles and AI-driven conversations.

## Features
- **AI-Generated Profiles**: Leverages **GPT-4** and **Stable Diffusion** to create realistic, engaging fictional profiles with custom profile pictures.
- **AI-Powered Conversations**: Provides users with chatbot interactions, showcasing **natural language processing** with unique personality traits.
- **Responsive Frontend**: Built with **React** for a seamless, modern user experience.
- **Robust Backend**: Utilizes **Spring Boot** to handle profile generation, data management, and API integration.
- **Efficient Data Management**: Stores profile data using **MongoDB**, ensuring scalability for handling large datasets.

---

## Technologies Used
- **Frontend**: React, JavaScript, Axios, React Hooks
- **Backend**: Spring Boot, GPT-4, Stable Diffusion, REST APIs
- **Database**: MongoDB
- **Deployment**: Docker, Docker Compose
- **Others**: Maven, AI Integration (OpenAI API)

---

## Project Structure
- **Frontend**: Located in the `frontend` folder. Handles the user interface, including profile browsing, swiping, and chat interactions.
- **Backend**: Located in the `backend` folder. Manages AI integrations, profile generation, and API endpoints for the frontend.

---

## Installation
### Step 1: Clone the repositories
```bash
git clone https://github.com/your-username/tinder-ai-frontend.git
git clone https://github.com/your-username/tinder-ai-backend.git
```

### Step 2: Set up the backend
1. Navigate to the `backend` directory:
   ```bash
   cd tinder-ai-backend
   ```
2. Copy the `profile.json` file (from the provided profile bundle) to the root directory.
3. Copy all images to `resources/static/images`.
4. Add your OpenAI API key in the `SPRING_AI_OPEN_AI_API_KEY` environment variable.
5. Build and run the backend:
   ```bash
   mvn clean install
   java -jar target/backend.jar
   ```

### Step 3: Set up the frontend
1. Navigate to the `frontend` directory:
   ```bash
   cd ../tinder-ai-frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

---

## Usage
1. Start both the backend and frontend servers.
2. Open the app in your browser at `http://localhost:3000`.
3. Browse AI-generated profiles, swipe, and engage in chatbot-driven conversations.

---
