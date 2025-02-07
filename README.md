# MultiAgentBlogWriter

This project demonstrates a multi-agent approach for generating blog content using AI. It leverages the crewai library along with tools like langchain_groq to orchestrate interactions between various agents and produce coherent text outputs.

## Table of Contents

- Features
- Installation
- Usage
- Configuration
- Project Structure
- License
- Contributing

## Features

- Multi-Agent Collaboration: Integrates multiple AI agents to generate, refine, and enhance blog content.
- Flexible Integration: Uses libraries such as crewai and langchain_groq for seamless AI model interaction.
- Interactive Demonstration: A Jupyter Notebook (MultiAgentBlogWriter.ipynb) showcases the workflow.
- API Driven: Supports external APIs via configurable API keys, including SERPER and GROQ.

## Installation

Ensure you have Python 3.8 or higher installed. Install the required packages as specified in the project documentation. The project depends on packages like crewai, crewai with tools, langchain_groq, and groq. If a requirements file is available, use it to install the dependencies.

## Usage

To interact with the project, launch the Jupyter Notebook named MultiAgentBlogWriter.ipynb. The notebook demonstrates the following workflow:

- Importing the necessary libraries.
- Setting up API keys for SERPER and GROQ.
- Initializing the language model using the LLM class from crewai.
- Interacting with the model by sending prompts (for example, a greeting such as "hi") and processing the responses.

## Configuration

Before running the notebook, make sure to set up the required API keys for the respective services. This can be done by configuring your environment variables or by editing the notebook directly. The required keys include:

- SERPER_API_KEY
- GROQ_API_KEY

## Project Structure

The project is organized as follows:

- **MultiAgentBlogWriter.ipynb** – The main Jupyter Notebook demonstrating the project.
- **requirements.txt** – A list of Python dependencies.
- **README.md** – This file, providing an overview of the project.
- Additional files and configurations may be included as needed.

## License

This project is licensed under the MIT License. Please refer to the LICENSE file for further details.

## Contributing

Contributions are welcome. To contribute, follow these guidelines:

- Fork the repository.
- Make your changes.
- Submit a pull request.
- For significant changes, open an issue first to discuss your proposed modifications.

Happy coding and enjoy creating blog content with AI!
