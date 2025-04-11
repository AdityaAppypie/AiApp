.NET Chat Interface
A modern, responsive chat interface for interacting with OpenAI's language models through a clean
and intuitive web interface.

📋 Features
Split UI Layout: Chat interface on the left, code preview panel on the right
Code Highlighting: Automatic detection and formatting of code blocks
API Integration: Seamless integration with OpenAI's Chat Completion API
Model Selection: Choose between different OpenAI models (GPT-3.5 Turbo, GPT-4)
Secure API Key Storage: Local storage of API keys with masking for security
Copy Code Functionality: Easy copying of code snippets with a single click
Responsive Design: Works on desktop and mobile devices

🚀 Getting Started
Prerequisites
A modern web browser (Chrome, Firefox, Edge, Safari)
An OpenAI API key (get one at OpenAI's website)

Installation
1. Clone this repository:
 git clone https://github.com/AdityaAppypie/AiApp.git

3. Navigate to the project directory:
bash
cd dotnet-chat-interface
4. Open the index.html file in your web browser or deploy to a web server.

💻 Usage
1. Enter your OpenAI API key in the provided field and click "Save Key"
2. Select your preferred AI model from the dropdown menu
3. Type your message in the input field and press "Send" or hit Enter
4. View the AI's response in the chat window

5. Code snippets will automatically appear in the right panel for easy viewing and copying

🔒 Security Notes
Your API key is stored in your browser's local storage for convenience
The application communicates directly with OpenAI's API from your browser
No data is stored on any server except during API communication with OpenAI

🤖 How It Works
1.
The interface captures user input and sends it to OpenAI's API
2.
The API response is parsed and displayed in the chat window
3.
Code blocks are automatically detected and displayed in both the chat and code preview panel
4.
The code preview panel allows for easier viewing and copying of code snippets
📝 License
This project is licensed under the MIT License - see the LICENSE file for details.
🙏 Acknowledgements
OpenAI for providing the API that powers the chat functionality
Contributors who help improve this interface
📞 Contact
For any questions or suggestions, please open an issue on this repository.
