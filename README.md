# llm-usecases
A repository to showcase lean implementations of LLM use cases to solve real-world problems. 
---
### Installing the project dependencies

The projects published here are mostly written using Python 3.12 and Jupyter Notebook. Dependencies are managed through Poetry. To run these notebooks yourself, the easiest way is to install Poetry and then use it to create the specified Python environment:

1. Install Poetry
- Using pipx: `pipx install poetry`
- Using Homebrew: `brew install poetry`
- Using the official installer: `curl -sSL https://install.python-poetry.org | python3 -`

2. Clone this repository
3. In the project root, run `poetry install`
4. Activate the virtual environment Poetry created by running `poetry shell`
5. Run `jupyter notebook`
---

### Using the OpenAI API yourself

You will need to create an API key for the OpenAI API to reuse the code. You can create one here: https://platform.openai.com/api-keys. You will need to add some credits to your account as inference with OpenAI models via the API will incur minimal cost (developing the company summarizer cost me 3 cents).

Once you've generated an API key, you will need to create a .env file in the project root and paste your API key using the following syntax:
`OPENAI_API_KEY=paste_your_key_here`.

Have fun!