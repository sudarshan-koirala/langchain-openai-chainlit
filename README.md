# langchain-openai-chainlit
Chat with your documents (pdf, csv, text) using Openai model, LangChain and Chainlit

### Chat with your documents 🚀
- [OpenAI model](https://platform.openai.com/docs/models) as Large Language model
- [LangChain](https://python.langchain.com/en/latest/modules/models/llms/integrations/huggingface_hub.html) as a Framework for LLM
- [Chainlit](https://docs.chainlit.io/langchain) for deploying.

## System Requirements

You must have Python 3.10 or later installed. Earlier versions of python may not compile.

## Steps to Replicate 

1. Fork this repository and create a codespace in GitHub as I showed you in the youtube video OR Clone it locally.
```
git clone https://github.com/sudarshan-koirala/langchain-openai-chainlit.git
cd langchain-openai-chainlit
```

2. Rename example.env to .env with `cp example.env .env`and input the OpenAI API key as follows. Get OpenAI API key from this [URL](https://platform.openai.com/account/api-keys). You need to create an account in OpenAI webiste if you haven't already.
   ```
   OPENAI_API_KEY=your_openai_api_key
   ```

3. Run the following command in the terminal to install necessary python packages:
   ```
   pip install -r requirements.txt
   ```

4. Run the following command in your terminal to start the chat UI:
   ```
   chainlit run langchain_openai_chainlit.py -w
   ```

## Disclaimer
This is test project and is presented in my youtube video to learn new stuffs using the openly available resources (models, libraries, framework,etc). It is not meant to be used in production as it's not production ready. You can modify the code and use for your usecases ✌️

