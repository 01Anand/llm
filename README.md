# Prerequisites
# Setting Up Your Development Environment for AI Projects 

Basic understanding of the command line.

# 1. Install VS Code (Visual Studio Code):

VS Code is a free, powerful, and versatile code editor that's perfect for AI development.
 # Download: 
 Go to the official VS Code website: https://code.visualstudio.com/
 # Installation: 
 Follow the installation instructions for your operating system.
# Essential Extensions: (optional)
Python: (Microsoft) - For Python development.
Jupyter: (Microsoft) - For working with Jupyter Notebooks.
GitLens: (Eric Amodio) - For enhanced Git capabilities.
(Optional) Any other extensions you find useful for your specific project.
# 2. Install Miniconda:

Miniconda is a lightweight distribution of Conda, a package and environment manager. It allows you to create isolated environments for your projects, preventing dependency conflicts.
Download: Go to the Miniconda website: https://docs.conda.io/en/latest/miniconda.html
Installation: Choose the appropriate installer for your operating system and follow the instructions.
Create a Conda Environment:
Bash
<code > conda create -n llm python=3.13 
 Replace myenv with your environment name and 3.13 with desired python version
conda activate myenv
</code >
#  3. Install Ollama:

Ollama allows you to run open-source large language models locally.
Download and Install:
macOS: https://ollama.ai/download (Simple installer)
Linux:
Bash
curl -fsSL https://ollama.com/install.sh | sh
Windows: (Preview) Follow instructions on the Ollama website.

# Workshop

# Run your first model:

<code> #Bash
ollama run llama3 </code >

This will download and run the llama3 model. You can then interact with it in your terminal.
Accessing Ollama within VS Code:
Ollama runs as a service in the background. You can interact with it via the command line or through Python libraries.
To use it in a python script, you will need to install its python library. 


<code >
#Bash
 pip install ollama</code >


