
# Random CAT Image Viewer
 Vite project that demonstrates how to use Axios instances to fetch images from different public APIs (cat).

# Features

Fetches random cat images from The Cat API
.

Uses Axios instance for clean API calls.

React hooks (useState, useEffect) to manage state and lifecycle.

Fully customizable — you can swap out APIs for dogs, space images, or anything else.

# Project structure

<img width="1024" height="1536" alt="ChatGPT Image Sep 8, 2025, 11_26_40 AM" src="https://github.com/user-attachments/assets/508f1125-3e21-4b37-a67f-e380fd3951d6" />

# Installation & Setup

Run these commands in your terminal (PowerShell):
### 1. Create a React project with Vite
npm create vite@latest random-animal-app

### Choose: React + JavaScript

cd random-animal-app

### 2. Install dependencies
npm install

### 3. Install Axios
npm install axios

# code of Axios.json file
import axios from "axios";

const api = axios.create({
  baseURL: "https://api.thecatapi.com/v1",
  timeout: 8000,
});

export default api;

# To run this app
npm run dev

# Screen Shorts

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/d251c702-72cd-4d1d-b0bb-f4cbe181575c" />

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/560ca525-4a43-4e4a-bc56-3456fbd20f2c" />
