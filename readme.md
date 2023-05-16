This sample is for a custom chatbot which is trained by your own knowledge base.

Copy your database files such as PDF, DOC and TXT to the "docs" folder.

## How to run this program:
### 1. Install Python
You need to install Python (Pip) on your computer.

Here's link: https://www.python.org/downloads

Don't forget to set PATH environment to your development device.

### 2. Install Python packages
- python -m pip install -U pip
- pip install openai
- pip install gpt_index==0.4.24
- pip install PyPDF2
- pip install PyCryptodome
- pip install gradio

You might need to install vcredist for this program to work properly.
Here's link: https://aka.ms/vs/16/release/vc_redist.x64.exe

### 3. Set your OPENAI_API_KEY as an environment value
Open "app.py" and set your own OPENAI_API_KEY.

os.environ["OPENAI_API_KEY"] = "sk-***************************"

### 4. Run this program

python .\app.py