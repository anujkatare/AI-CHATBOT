 # AI-CHATBOT

This project is a simple AI-powered chatbot and image generator web app using Node.js, Express, and Hugging Face and DeepSeek APIs.

## Features

- Chatbot interface using OpenAI or Hugging Face APIs
- AI image generation from text prompts
- Real-time messaging with Socket.IO (optional)
- Modern HTML/CSS frontend

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- Hugging Face API key (for image generation)

### Installation

1. Clone the repository:
    

2. Install dependencies:
    ```
    npm install
    ```

3. Create a `.env` file and add your Hugging Face API key to brog.html :
    ```
    HF_TOKEN=your_huggingface_api_key
    ```
4. Create a `.env` file and add your deepseek free API key from openrouter to shezzy.html :
    ```
    Authorization =  your_deepseek_api_key
    ```

5. Start the server:
    ```
    node server.js
    ```

6. Open your browser and go to [http://localhost:3000](http://localhost:3000)

## Project Structure

```
AI-CHATBOT/
├── public/
│   ├── index.html
│   ├── brog.html
│   └── ... (other static files)
├── server.js
├── package.json
└── README.md
```

## Usage

- Enter a message in the chatbot to get a response.
- Enter a prompt in the image generator to create an AI image.

## License
@anujkatare
