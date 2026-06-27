# AI Resume Assistant 🚀

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

</div>

**Elevate your resume to the next level with the power of AI. Get instant analysis, data-driven feedback, and tailor your resume to any job description in seconds.**

![SmartResume Demo](https://your-link-to-image-or-gif.com/demo.gif)

---

### 📋 Table of Contents

1.  [About The Project](#-about-the-project)
2.  [Key Features](#-key-features)
3.  [Tech Stack](#️-tech-stack)
4.  [Getting Started](#-getting-started)
5.  [Environment Variables](#-environment-variables)
6.  [API Endpoints](#-api-endpoints)
7.  [License](#-license)
8.  [Contact](#-contact)

---

### 📖 About The Project

SmartResume is a full-stack MERN application designed to help job seekers gain a competitive edge. Traditional resume writing is often a guessing game. This tool removes the guesswork by leveraging AI to provide objective, actionable feedback and helps users perfectly align their resume with the specific requirements of a job posting.

---

### ✨ Key Features

* **Secure User Authentication:** JWT-based login and registration to keep user data private.
* **AI-Powered Resume Analysis:** Upload a resume to receive a detailed score, breakdown, and a list of pros and cons.
* **AI-Powered Resume Customization:** Paste a job description to have the AI rewrite and tailor your resume, highlighting relevant keywords and skills.
* **Personal Profile & History:** A user dashboard to view all past analysis and customization activities.
* **Professional & Responsive UI:** A clean, modern interface built with Tailwind CSS that works beautifully on all devices.

---

### 🛠️ Tech Stack & ML Implementation

This project is built with a modern MERN stack and heavily focuses on Machine Learning for intelligent resume processing.

#### Core Machine Learning Implementation
* **LLM Integration:** Powered by the **OpenRouter API**, enabling access to state-of-the-art Large Language Models for natural language understanding and generation.
* **Prompt Engineering:** Custom-designed prompts to analyze resume content, extract key skills, and dynamically rewrite resume sections to align with specific Job Descriptions.
* **Contextual Analysis System:** The backend processes PDF text extraction and sends structured context to the AI model to perform scoring, pros/cons generation, and tailored improvements.

#### Full-Stack Technologies
| Frontend | Backend | Database | Authentication |
| :--- | :--- | :--- | :--- |
| **React** (Vite) | **Node.js** | **MongoDB** | **JWT** |
| **Tailwind CSS** | **Express.js** | **Mongoose** | **bcrypt.js** |
| **React Router** | **PDF Parser**| | |
| **Axios** | | | |

---

### 🚀 Getting Started

This guide will walk you through setting up a local development environment.

#### Prerequisites

* **Git**: To clone the repository. [**Download Git here**](https://git-scm.com/downloads).
* **Node.js**: `v18.x` or later is recommended. [**Download Node.js here**](https://nodejs.org/en/download).

#### Installation & Setup

1.  **📂 Clone the Repository**
    ```sh
    git clone https://github.com/Itzsajidsk/resume-optimizer-pro.git
    cd smart-resume-app
    ```

2.  **⚙️ Set Up the Backend Server**
    ```sh
    # Navigate to the server folder
    cd server
    # Install all required packages
    npm install
    # Create a .env file and add your secret variables
    touch .env
    ```

3.  **🖥️ Set Up the Frontend Client**
    ```sh
    # Open a new terminal and navigate to the client folder
    cd ../client
    # Install all required packages
    npm install
    # Create a .env file and add your API URL
    touch .env
    ```

4.  **▶️ Run the Application**
    * In the **backend** (`/server`) terminal: `npm start`
    * In the **frontend** (`/client`) terminal: `npm run dev`

---

### 🔑 Environment Variables

To run this project, you will need to add the following environment variables to your `.env` files.

#### `server/.env`
```env
# The port for the Express server
PORT=8080

# Your MongoDB connection string
MONGO_URI=your_mongodb_connection_string

# A secret key for signing JSON Web Tokens
JWT_SECRET=your_super_secret_jwt_key

# Your API key from OpenRouter.ai
OPENROUTER_API_KEY=your_openrouter_api_key