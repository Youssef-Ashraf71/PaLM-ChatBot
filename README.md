# 🤖 PalmBot App

Welcome to the PalmBot App! 🎉 This is a simple chat application built using HTML, CSS, and JavaScript, allowing you to have conversations with a chatbot powered by the [Palm API](https://developers.generativeai.google/). The chatbot responds to your messages by generating customized responses based on the provided prompts.

Please note that this chat app responds to each individual user request, providing prompt-based responses rather than maintaining accumulative context like ChatGPT.

## 💻 Live Demo
[PaLMBot](https://palm-chat-bot.vercel.app/)

## ✨ Features

- 💬 Enter prompts and send them to the chatbot.
- ⚡️ Chatbot generates responses based on your prompts using the Palm API.
- 📝 View the conversation history in the chat window.
- 📋 Copy chatbot responses to the clipboard with ease.
- 🌓 Switch between light mode and dark mode themes to suit your preferences.

## 🚀 Getting Started

To run the chat app locally, follow these simple steps:

1. Clone the repository or download the source code.
2. Open the project directory in your code editor.
3. Launch a live server to serve the files. You can use tools like Visual Studio Code's [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) or any other web server of your choice.
4. Access the chat app through the provided local server URL.

```
 http://localhost:3000
```

## 💡 Usage

1. 👉 Type your message in the chat input box.
2. ⏰ Press Enter or click the send button to send your message.
3. 💬 The chatbot will generate a response based on your message and display it in the chat window.
4. 📋 You can copy the chatbot's response to the clipboard by clicking the "content_copy" button next to the response.
5. 🌗 You can switch between light mode and dark mode themes by clicking the "light_mode" or "dark_mode" button.

## ⚙️ Configuration

To configure the API key for the chat app, replace the `API_KEY` constant in the `palmbot.js` file with your valid Palm API key.

```javascript
const API_KEY = "YOUR_API_KEY";
```

Please ensure that you have a valid API key from the Palm API provider.
You can get yours from [PaLM API](https://developers.generativeai.google/)

## 🚧 Limitations

- The chat app only responds to individual user requests and doesn't maintain context or provide accumulative responses like ChatGPT.
- The chatbot's functionality relies on the Palm API. Any issues or limitations with the API may affect the chatbot's performance and responsiveness.

## 📄 License

This project is licensed under the [MIT License](LICENSE.txt).

## 🙏 Acknowledgements

- The chat app was built using HTML, CSS, and JavaScript.
- The design and styling of the chat app were inspired by various chat interfaces and UI patterns.

## 🆘 Troubleshooting

If you encounter any issues or have questions about the chat app, please feel free to reach out
<br><br>
<a href="https://twitter.com/yoyobunt" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="yoyobunt" height="30" width="40" /></a>
<a href="https://linkedin.com/in/yousssef-ashraf-a76633238" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="yousssef-ashraf-a76633238" height="30" width="40" /></a>
