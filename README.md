# ChatGPT and LangChain integration

A command line application that uses LangChain to answer code related questions

### Installation

1. Clone this repository

```git
git clone https://github.com/pasDamola/chatgpt-langchain.git
```

2. Get your OpenAI API key

Go to the OpenAI [site](https://platform.openai.com/), Login or Sign up, then generate an API key

3. Set up your environment variable by creating a _.env_ file and inputing the key, for example:

```
OPENAI_API_KEY=myopenailuckycharm
```

3. Install the dependencies

```
pip install -r requirements.txt
```

**At this point, you can go ahead and customize the PromptTemplate in the main.py file to whatever you want**

4. Run the application

This can be done in 2 ways

- Run with the default arguments already stated in the parser arguments

```python
    python main.py
```

- Customize the _--language_ and _--task_ for example:

```python
  python main.py --language golang --task 'return a list of numbers'
```
