# AutoGen with Chainlit

Example integration of [AutoGen](https://microsoft.github.io/autogen/) with Chainlit.

https://github.com/Chainlit/cookbook/assets/494686/c5d608bd-7480-42cc-b21f-74989d52fd8c

## Setup

1. Optional: create your python virtual environment and activate it.

2. Install the dependencies:

```
pip install chainlit pyautogen
```

3. Copy the `.env.sample` file into a new `.env` file. Replace the `api_key` value with your own OpenAI API key.

4. Run the Chainlit app with `chainlit run app.py`. You can change the initial AutoGen prompt in the `app.py` file.
