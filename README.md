# Website Creator Web App

A React-based web application that generates a complete website for you using OpenAI API.  
You provide a description of the website you want, and the app creates HTML, CSS, and JavaScript code for it.  

You can see all the generated code clearly, copy it easily, and instantly preview the live website inside the app.

---

## Features

- Input your website requirements or idea in natural language.
- Uses OpenAI API (GPT) to generate HTML, CSS, and JavaScript code.
- Displays all generated code (HTML, CSS, JS) in separate sections for easy reading and copying.
- Provides a live preview of the generated website instantly.
- Simple and user-friendly interface built with React.
- Helps you quickly prototype or create basic websites with minimal effort.

---

## Technologies Used

- React (JavaScript)
- OpenAI API (GPT-4 or GPT-3.5)
- HTML, CSS, JavaScript (generated code)
- CSS for styling the app UI
- Axios or Fetch API to interact with OpenAI API

---

## Getting Started

### Prerequisites

- Node.js (v16+)
- npm or yarn
- OpenAI API key ([Get yours here](https://platform.openai.com/signup))
- MongoDB Atlas account ([Create free account](https://www.mongodb.com/cloud/atlas))
- MongoDB Compass (optional, for GUI database management) ([Download here](https://www.mongodb.com/products/compass))

## .env file details

-PORT = 8080
-MONGODB_URL=mongodb+srv://name:<your_password>@cluster0.vwg6szt.mongodb.net/login
-JWT_SECRET = Choose a secret key
-OPENROUTER_API_KEY = Your Open AI API key



### Installation

1. Clone this repository

```bash
git clone https://github.com/CodePandaAkhilesh/WebBuilder.git
create .env
cd WebBuilder
npm install ( do this in both frontend and backend )
npm i concurrently ( frontend )
npm run dev 
