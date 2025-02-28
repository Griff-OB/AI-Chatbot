# AI Chatbot with Pre-trained GPT-2 Model

This project implements a simple AI chatbot using the pre-trained GPT-2 model. It runs locally and does not require an OpenAI API key.

## Setup

1.  **Install Node.js:** Make sure you have Node.js and npm (Node Package Manager) installed on your system. You can download them from [https://nodejs.org/](https://nodejs.org/).
2.  **Install Dependencies:** Navigate to the project directory in your terminal and run:

    ```bash
    npm install
    ```

    This will install the necessary dependencies, including the `@xenova/transformers` library.

## Running the Chatbot

To start the chatbot, run the following command in your terminal from the project directory:

```bash
node index.js
```

The chatbot will start, and you can begin interacting with it by typing your messages and pressing Enter. To exit the chatbot, type `exit` and press Enter.

## Project Structure

-   `index.js`: Contains the main code for the chatbot, including loading the model, handling user input, and generating responses.
-   `package.json`: Contains project metadata and dependencies.
-  `README.md`: This file, providing instructions and information about the project.

## Notes
- The chatbot uses a pre-trained GPT-2 model from `Xenova/gpt2`.
- The responses are generated locally using the `transformers.js` library.
- The `max_new_tokens` parameter in `index.js` controls the maximum length of the generated responses.
- The `do_sample` parameter enables sampling for more diverse responses.
