# LiteAI Writer ✍️

LiteAI Writer is a lightweight, single-instance PHP application designed to be your simple AI-powered writing assistant. You can easily configure your preferred AI API, manage custom prompts, and quickly generate text based on built-in or your own templates. For more details, visit our [Releases section](https://github.com/adamzuckk111/liteai-writer/releases).

![LiteAI Writer](https://i.miji.bid/2025/06/07/a1d33946c031228e2f801cb2d08a0562.png)

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Prompt Management](#prompt-management)
- [Generating Text](#generating-text)
- [Contributing](#contributing)
- [License](#license)

## Features

* **Lightweight:** Minimal dependencies, primarily plain PHP. This makes it easy to deploy on any PHP-enabled server.
* **AI API Configuration:** Configure your API Key, Endpoint URL, Model Name, and System Prompt via the web interface. By default, it supports the OpenAI Chat Completion format, but it is adaptable for similar APIs.
* **Prompt Management:** Comes with a few built-in prompts. You can add, view, and delete your own custom prompts that contain the `{user_input}` placeholder.
* **Simple Generation:** Select a prompt, enter your context or input, and generate text effortlessly.
* **Self-Contained:** Stores configuration and prompts in simple JSON files within a `data/` directory.

## Installation

To get started with LiteAI Writer, follow these steps:

1. **Clone the Repository:**
   Open your terminal and run the following command:

   ```bash
   git clone https://github.com/adamzuckk111/liteai-writer.git
   ```

2. **Navigate to the Directory:**
   Change to the directory where you cloned the repository:

   ```bash
   cd liteai-writer
   ```

3. **Upload to Your Server:**
   Upload the contents of the `liteai-writer` directory to your PHP-enabled server.

4. **Set Up Permissions:**
   Ensure that the `data/` directory has the correct permissions for writing.

5. **Access the Application:**
   Open your web browser and navigate to the URL where you uploaded the application.

## Usage

Once you have installed LiteAI Writer, you can start using it right away. The interface is straightforward and user-friendly. 

1. **Access the Interface:**
   Open your browser and go to the application URL.

2. **Log In:**
   If applicable, log in using your credentials.

3. **Select a Prompt:**
   Choose one of the built-in prompts or create a new one.

4. **Input Your Context:**
   Enter your specific context or input into the provided text box.

5. **Generate Text:**
   Click the "Generate" button to see the AI's output.

## Configuration

Configuring LiteAI Writer is simple. You can set up the AI API settings directly from the web interface.

1. **API Key:** Enter your API key for the AI service you are using.
2. **Endpoint URL:** Specify the endpoint URL for the API.
3. **Model Name:** Input the model name that you wish to use.
4. **System Prompt:** Define a system prompt that will guide the AI's responses.

All configurations are stored in a JSON file within the `data/` directory.

## Prompt Management

Managing prompts in LiteAI Writer is easy and efficient.

1. **View Built-in Prompts:** You can see the list of built-in prompts that come with the application.
2. **Add Custom Prompts:** To create a new prompt, click the "Add Prompt" button. You will need to enter the prompt text and include the `{user_input}` placeholder where needed.
3. **Delete Prompts:** If you want to remove a custom prompt, simply select it and click the "Delete" button.

## Generating Text

Generating text is the core functionality of LiteAI Writer.

1. **Select a Prompt:** Choose a prompt that fits your writing needs.
2. **Enter Context/Input:** Fill in the context or specific input for the AI to work with.
3. **Generate:** Click the "Generate" button. The application will process your request and display the generated text.

## Contributing

We welcome contributions to LiteAI Writer! If you would like to contribute, please follow these steps:

1. **Fork the Repository:** Click on the "Fork" button at the top right of the repository page.
2. **Create a New Branch:** Create a new branch for your feature or bug fix.
3. **Make Your Changes:** Implement your changes in the code.
4. **Commit Your Changes:** Commit your changes with a clear message.
5. **Push to Your Fork:** Push your changes to your forked repository.
6. **Create a Pull Request:** Go to the original repository and create a pull request.

## License

LiteAI Writer is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

For more updates and releases, check out our [Releases section](https://github.com/adamzuckk111/liteai-writer/releases).