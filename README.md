# ChatGPT VSCode Extension

This is a Visual Studio Code extension for ChatGPT that was built using only ChatGPT and 5 beers.
The `README.md` file for this extension was generated by ChatGPT.

## Features

- Login with your ChatGPT access token
- Ask ChatGPT any question and supply source code from your current file/selection
- Ask ChatGPT to refactor your code and explain the changes
- Ask ChatGPT for help explaining code
- Ask ChatGPT for help troubleshooting code

![Small Demo](/images/demo.gif "Demo")

## Usage

To use the extension:
Open the VS Code Command Palette and Type "ChatGPT: Login", this will prompt you for your access token.

You can grab it from the [ChatGPT website](https://chatgpt.com), after logging in and copying the value from `application -> cookies -> session-token`.

*Once you're logged in, you can ask ChatGPT any question and supply source code from your current file/selection.*

The commands are:
- `ChatGPT: Ask ChatGPT` (will provide a prompt for you to ask a question)
- `ChatGPT: Why is my code broken?`
- `ChatGPT: Explain this code`
- `ChatGPT: Refactor this code`


## Installation

To install the extension, follow these steps:

1. Open Visual Studio Code
2. Click on the Extensions icon in the left sidebar
3. Search for "ChatGPT VSCode plugin"
4. Click on the Install button to install the extension
5. Click on the Reload button to activate the extension

## Support
If you need help using this extension, please open an issue on the GitHub repository for this extension.

## Credits

- [ChatGPT](https://www.openai.com/products/chatgpt/) - The large language model trained by OpenAI that was used to generate this README file
- [Yeoman](https://yeoman.io/) - The code generator used to scaffold the extension project
- [VS Code Extension Generator](https://github.com/Microsoft/vscode-generator-code) - The Yeoman generator for creating VS Code extensions
