# Simple ChatGPT Example
### Summary
This project presents a simple example of how to use OpenAI's API in order to perform ChatGPT requests.
In this example, a variable "message" can be set with a desired request.
In order to make this project run, the user should provide an OpenAI API token (apply for one at https://platform.openai.com/api-keys) in a file called ".openaikey".
For more details and further investigations see the link in the acknowldedgements section.

### Motivation
This project is targeted at people who would like to use ChatGPT in a python world but do not know how.

### ACKNOWLEDGEMENTS
The project is a simplified version of a ChatGPT python implementation presented in:
https://github.com/openai/openai-python/blob/main/README.md

### Install/run instructions:
1. Install python >= 3.11 and the packages denoted in requirements_working_configuration.txt preferably in a virtual environment as exemplarily shown for the windows command prompt:
```
      projectfolder:> python -m venv .venv
      projectfolder:> cd .venv\Scripts
      projectfolder\.venv\Scripts> .\activate.bat
      projectfolder\.venv\Scripts> cd ..\..
      projectfolder:> python -m pip install -r requirements_working_configuration.txt
```
      Within your project folder "projectfolder" use the "python" command as long as the virtual environment is activated
      (if not working with/on the project, the virtual environment should be deactivated by executing projectfolder\.venv\Scripts\deactivate.bat).

       Important note: If you are using requirements.txt (no package versions provided) instead of requirements_working_configuration.txt, make sure to install ipykernel before (python -m pip install ipykernel). The order seems important.

2. In the programming IDE select .venv\Scripts\python.exe as kernel.
3. Create an API key at: https://platform.openai.com/api-keys and store your OpenAI API token in ".openaikey".
4. Run all code blocks in "simple_chatgpt_example.ipynb"

### Files in the repository
```
.gitignore
README.md
requirements.txt                       # list of required packages without version number
requirements_working_configuration.txt # packages covering a working configuration
simple_chatgpt_example.ipynb # main jupyter file
```