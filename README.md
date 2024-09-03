# open-ai-finetune

**Finetuning OpenAI models to specialize in common errors in Kubernetes**

**Overview of data:**
The data files are stored inside the data folder. Includes the raw data file, the prompt-completion file (used for fine-tuning Babbage), and the message-user-content file (used for fine-tuning GPT 3.5, will work for GPT 4o mini if a user has a tier 4 OpenAI subscription).

**Cloning the project:**
Run the following command in your Terminal/PowerShell to clone this GitHub repository to your local machine.
```
git clone https://github.com/FahimIslam731/open-ai-finetune.git
```

**Starting the project:**
I recommend setting this project up in Visual Studio Code. Please make sure you VS Code and the notebook extension installed.

Open a terminal in VS Code. Run the following command to setup a Virtual Environment:
```
python -m venv venv
```

If you are on MacOS use the following command to activate the virtual environment:
```
source venv/bin/activate
```
If you are on Windows use the following command to activate the virtual environment:
```
.\venv\Scripts\activate
```
We have provided a requirements.txt file in the github repository. To install these requirements, please run the following:
```
pip install -r requirements.txt
```
