# Intellects
INTEL-UNNATI-2024

## Introduction
Ollama is an open-source software that serves as a powerful and user-friendly platform for running LLMs on your local machines. It acts as a bridge between the complexities of LLM technology and the desire for an accessible and customizable AI experience.
At its core, Ollama simplifies the process of downloading, installing, and interacting with a wide range of LLMs, empowering users to explore their capabilities without the need for extensive technical expertise or reliance on cloud-based platforms.Instead of spending hours on downloading and installing the LLM , ollama helps to download and interact with the LLM easily.

## Key Features and Functionalities
Ollama boasts a comprehensive set of features and functionalities designed to enhance the user experience and maximize the potential of local LLMs.

## Model Library and Management
Ollama provides access to a diverse and continuously expanding library of pre-trained LLM models, ranging from versatile general-purpose models to specialized ones tailored for specific domains or tasks. Downloading and managing these models is a seamless and streamlined process, eliminating the need to navigate complex model formats or dependencies.

## Effortless Installation and Setup
One of Ollama’s standout features is its user-friendly installation process. Whether you’re a Windows, macOS, or Linux user, Ollama offers intuitive installation methods tailored to your operating system, ensuring a smooth and hassle-free setup experience.

## Customization and Fine-tuning
Ollama offers users a wide range of customization options, allowing them to fine-tune LLM parameters, modify settings, and adapt the models’ behavior to meet their specific requirements and preferences. This flexibility enables optimal performance and encourages experimentation with different model configurations.

## Interactive User Interfaces
While Ollama provides a command-line interface for advanced users, it also offers user-friendly graphical interfaces through seamless integration with popular tools like Open WebUI. These interfaces enhance the overall experience by providing intuitive chat-based interactions, visual model selection, and parameter adjustment capabilities.

## Offline Access and Privacy
One of the key advantages of running LLMs locally with Ollama is the ability to operate entirely offline, without the need for an internet connection. This not only ensures uninterrupted access and productivity but also addresses privacy concerns by keeping your data securely within your local environment.

# Getting Started with Ollama

## Installation and Setup

Embarking on your Ollama journey is a straightforward process, designed to cater to users with varying levels of technical expertise. The installation process is well-documented and supported across multiple platforms, ensuring a seamless experience regardless of your operating system of choice.

### Windows Installation

For Windows users, Ollama offers a user-friendly installer that streamlines the setup process. Simply follow these steps:

1. Visit the official Ollama website and navigate to the “Downloads” section.
2. Download the latest version of the Ollama Windows installer.
3. Run the downloaded installer and follow the on-screen instructions to complete the installation process.
4. Once installed, Ollama will be readily available on your Windows machine.

### macOS Installation

If you’re a macOS user, Ollama provides a dedicated installer tailored to your platform:

1. Visit the official Ollama website and navigate to the “Downloads” section.
2. Download the latest version of the Ollama macOS installer.
3. Run the downloaded installer and follow the prompts to complete the installation.
4. Upon successful installation, you’ll find Ollama available on your macOS system.

## Downloading LLM Models

Once you’ve identified the model that best suits your needs, downloading it is a straightforward process within Ollama:

1. Launch the Ollama application on your machine.
2. Navigate to the “Model Library” section within the Ollama interface.
3. Browse through the available models and select the one you wish to download.
4. Click on the “Download” button next to the chosen model.
5. Ollama will initiate the download process, fetching the model files from the respective repository.
6. Wait for the download to complete. The time required may vary depending on the model size and your internet connection speed.
7. Upon successful download, the model will be available for use within Ollama.

It’s important to note that some models may have specific hardware requirements, such as a minimum amount of RAM or the presence of a GPU. Ensure that your machine meets the recommended specifications for the chosen model to ensure optimal performance.

## Running and Interacting with LLMs

With Ollama installed and your desired LLM model downloaded, you’re ready to dive into the exciting world of local LLM interaction. Ollama provides multiple avenues for engaging with these powerful AI models, catering to different user preferences and requirements.

### Command-Line Interface (CLI)

For users who prefer a more traditional and streamlined approach, Ollama offers a robust command-line interface (CLI) that allows you to interact with LLMs directly from your terminal or console.
## Launching the CLI

To launch the Ollama CLI, follow these steps:

1. Open your terminal or console application.
2. Navigate to the directory where Ollama is installed using the appropriate command (e.g., `cd /path/to/ollama`).
3. Type the following command: `ollama run [model_name]`
4. Replace `[model_name]` with the name of the LLM model you wish to run (e.g., `ollama run llama2`).
5. Once the command is executed, the Ollama CLI will initialize and load the specified LLM model, preparing it for interaction.

### CLI Commands and Options

The Ollama CLI offers a range of commands and options to enhance your experience and provide greater control over the LLM interaction:

- `/help` or `/?`: Displays a list of available commands and their descriptions, helping you navigate the CLI’s functionality.
- `/temperature [value]`: Adjusts the temperature parameter, controlling the randomness and creativity of the LLM’s responses.
- `/top_k [value]`: Sets the top-k sampling value, determining the number of tokens the LLM considers when generating responses.
- `/stop`: Stops the current LLM session and returns to the command prompt.

These are just a few examples of the available commands and options. Refer to the Ollama documentation or use the `/help` command within the CLI for a comprehensive list and detailed explanations.

## Web User Interface (UI)

While the CLI offers a powerful and efficient way to interact with LLMs, some users may prefer a more visual and intuitive experience. Ollama addresses this need by seamlessly integrating with various web-based user interfaces (UIs) developed by the community.

### Steps to Activate the Web-Based UI (Example for llama3 model)

1. Launch Ollama and load the llama3 model:

2. Clone the UI repository from GitHub:
```bash
https://github.com/ivanfioravanti/chatbot-ollama.git
```

3. Navigate into the cloned repository:

4. Locate the `.env` file in the folder. View its content using: 
```bash
more .env.local.example
```

6. Edit the `.env.local.example` file using the nano text editor: 
```bash
nano .env.local.example
```

8. Add the following detail to the `.env.local.example` file:
```bash
OLLAMA_HOST=http://0.0.0.0:11434
```

7. Install dependencies using npm:
```bash
npm ci
```

8. Start the development server to launch the web UI:
```bash
npm run dev
```


## Fine-Tuning the LLM Model

To fine-tune the LLM model, follow these steps:

1. Navigate to the folder named `chatbot-ollama`.

2. Add the fin-tuned file `fine-tuned-model`.

3. Create an intellects model using a specified Modelfile:
```bash
ollama create intellects -f ./Modelfile
```
Replace `./Modelfile` with the path to your actual Modelfile.

5. Place the necessary fine-tuning contents into `modelfile`.

6. Copy the fine-tuned contents to your model:
```bash
Copy fine-tuned-model intellects
```

8. Run your chatbot using the command: 
```bash
ollama run intellects
```

#ChatBot-Photo
![Chatbot-photo](https://github.com/user-attachments/assets/8f73e9f2-a6ca-4ce9-99b7-d367b1460cbd)

#ChatBot-Demo
https://github.com/user-attachments/assets/9315a4d0-5373-4235-9300-3372dd65b458

THANK YOU
~INTELLECTS
