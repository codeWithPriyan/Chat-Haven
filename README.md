# 🌟 Chat Haven  

**Chat Haven** is a lightweight, intuitive application designed for seamless and human-like conversations. It leverages the power of OpenAI's ChatGPT API to provide an engaging and natural chat experience. Built with a React frontend and an Express server, the app ensures a smooth and responsive interface for all users.  

---

## 📚 Table of Contents  

1. [Features](#features)  
2. [Prerequisites](#prerequisites)  
3. [Installation](#installation)  
4. [Usage](#usage)  
5. [Contributing](#contributing)  
6. [License](#license)  

---

## 🌟 Features  

- **Interactive Chat Interface**: Offers a clean and user-friendly design for chatting.  
- **OpenAI-Powered**: Integrates with OpenAI's ChatGPT API for advanced conversational capabilities.  
- **Backend Proxy**: An Express server acts as a proxy, ensuring efficient communication with the API.  
- **Future Plans**:  
  - Enhanced responsiveness for various screen sizes.  
  - Advanced error handling for a seamless experience.  

---

## 📋 Prerequisites  

Before starting, make sure you have the following installed:  

- **Node.js** (v14 or higher)  
- **npm** (v7 or higher)  
- An **OpenAI API key** (Get one [here](https://platform.openai.com/signup)).  

---

## 🛠️ Installation  

Follow these steps to set up Chat Haven:  

1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/yourusername/chat-haven.git  
   ```  

2. **Navigate to the Project Directory**:  
   ```bash  
   cd chat-haven  
   ```  

3. **Install Dependencies**:  
   ```bash  
   npm install  
   ```  

4. **Configure API Key**:  
   Create a `.env` file in the root directory and add your OpenAI API key:  
   ```plaintext  
   REACT_APP_OPENAI_API_KEY=your_openai_api_key  
   ```  

5. **Run the Application**:  

   - **Backend Only**:  
     ```bash  
     npm run server  
     ```  

   - **Frontend Only**:  
     ```bash  
     npm run client  
     ```  

   - **Both Servers Concurrently**:  
     ```bash  
     npm run dev  
     ```  

The app will be available at `http://localhost:3000`. Open it in your browser to get started.  

---

## 🚀 Usage  

1. Launch the app and type a message in the input field at the bottom.  
2. Submit your message by pressing **Enter** or clicking the **Send** button.  
3. Chat Haven will fetch a response from the ChatGPT API and display it in the chat window.  
4. Continue the conversation by sending more messages—chat history is preserved for context.  

---

## 🤝 Contributing  

We welcome contributions to make Chat Haven even better!  

1. Fork the repository.  
2. Create a new branch for your changes.  
3. Make your edits or add features in the new branch.  
4. Submit a pull request with a detailed explanation of your changes.  

Your contributions will be reviewed and merged as appropriate.  

---

Welcome to **Chat Haven**—where conversations come alive!