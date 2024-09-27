# DocBot - A Python-Based Chatbot

**DocBot** is a simple chatbot designed to answer Python programming queries using basic natural language processing (NLP) techniques. This project serves as an introduction to chatbot development and demonstrates fundamental NLP concepts like tokenization, cosine similarity, and response generation.

## Features
- Greeting recognition and response
- Python-related query handling
- Cosine similarity for finding relevant responses
- Basic conversation flow with exit commands

## Prerequisites
- Python 3.x
- Google Colab (for easy setup and execution)

## Required Libraries
- `nltk`
- `scikit-learn`
- `newspaper3k`

## Installation
1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook.
3. Copy and paste the provided code into a Colab cell.

## Usage
1. Run the cell containing the code.
2. The chatbot will initialize and prompt you for input.
3. Type your questions or greetings.
4. To exit the conversation, type any of the following: `exit`, `bye`, `quit`, `break`, or `thank you`.

## How It Works
- The chatbot uses a predefined corpus of Python-related text.
- User input is tokenized and compared to sentences in the corpus.
- Cosine similarity is used to find the most relevant responses.
- The bot constructs a response based on the most similar sentences.

### Limitations
- The bot's knowledge is limited to the provided corpus.
- It may not understand complex or ambiguous queries.
- Response generation is based on text similarity, which may sometimes lead to irrelevant answers.

### Future Improvements
- Expand the knowledge base.
- Implement more sophisticated NLP techniques.
- Add the ability to learn from conversations.
- Improve context understanding and maintenance.

### Contributing
This is a learning project, but contributions, suggestions, and feedback are welcome! Please feel free to fork the repository and submit pull requests.

### License
This project is open-source and available under the MIT License.

### Acknowledgments
- Thanks to the NLTK and scikit-learn communities for their excellent libraries.
- Inspired by various online tutorials and courses on chatbot development.

### Sample Conversation

```bash
DocBot: I am Python researcher Student Bot or Doc Bot for short. I will answer your queries about python discussion. If you want to exit, type bye.
User: Hi
DocBot: hello
User: What is Python?
DocBot: Python is a high-level, general-purpose, and very popular programming language which was created by Guido van Rassum and released in 1991. Python programming language (latest Python 3) is being used in web development, Machine Learning, Mathematics, and System Scripting.
User: bye
DocBot: Chat with you later!
---

Happy chatting with DocBot!

