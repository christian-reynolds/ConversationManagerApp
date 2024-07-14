
# ConversationManagerApp

This is a Python project for managing conversations with a long-term memory feature. It is designed to interact with a language model API and handle the context of the conversation efficiently.

## Features

- Manages context of conversations with a maximum token limit.
- Summarizes entries when the context exceeds the token limit.
- Stores key information in long-term memory.
- Constructs prompts for interacting with a language model.
- Provides a simple command-line interface for user interaction.

## Requirements

- Python 3.7 or higher
- Required Python packages (can be installed using `pip`)

## Setup

1. **Clone the repository**:
   ```sh
   git clone https://github.com/christian-reynolds/ConversationManagerApp.git
   cd ConversationManagerApp
   ```

2. **Create a virtual environment**:
   ```sh
   python -m venv venv
   ```

3. **Activate the virtual environment**:
   - On Windows:
     ```sh
     .\venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```sh
     source venv/bin/activate
     ```

4. **Install the dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. **Run the conversation manager**:
   ```sh
   python conversation_manager.py
   ```

2. **Interact with the AI**:
   - Type your messages after the `You:` prompt.
   - The AI will respond with its messages prefixed with `AI:`.

## File Structure

```
ConversationManagerApp/
├── .gitignore
├── README.md
├── conversation_manager.py
├── requirements.txt
└── venv/
```

- `conversation_manager.py`: The main script containing the `ConversationManager` class.
- `requirements.txt`: File to list the project's dependencies.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `README.md`: This file.

## Example

```sh
You: Hello, AI!
AI: Hello! How can I assist you today?
```

## Contributing

Feel free to submit issues or pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License.

