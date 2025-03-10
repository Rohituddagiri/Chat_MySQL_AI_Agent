# Chat_MySQL_AI_Agent

![image info](chat-mysql.png)


# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/Rohituddagiri/Chat_MySQL_AI_Agent.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n chatSQLAgent python=3.10 -y
```

```bash
conda activate chatSQLAgent
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone credentials as follows:

```ini
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
LANGCHAIN_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
LANGCHAIN_TRACING_V2 = true
```

```bash
# Finally run the following command
streamlit run app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- LangSmith
- Streamlit
- OpenAI GPT 3.5
- Mistral
- MySQL

