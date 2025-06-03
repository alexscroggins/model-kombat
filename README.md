# Model Kombat

A fun, interactive Jupyter notebook where you choose two fictional characters and see them argue funny topics — powered by OpenAI and Anthropic APIs.

Each character speaks in their own comedic voice. ChatGPT comes up with the topic, and then the models go back and forth in a live-streamed showdown.

## Setup Instructions

### 1. Clone the repo and set up a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 2. Get your API keys

You’ll need API access from both OpenAI and Anthropic:

- 🔑 **OpenAI API Key**:  
  https://platform.openai.com/account/api-keys

- 🔑 **Anthropic API Key**:  
  https://console.anthropic.com/settings/keys

Both platforms offer prepaid pricing. I suggest purchasing $5 in credits as this will last for quite a while in a project like this. Once you’ve created accounts and added billing, you can copy your keys from the respective dashboards.

### 2. Add your API keys

Create a `.env` file in the root directory of the project with this format:

```
OPENAI_API_KEY=sk-your-openai-key
ANTHROPIC_API_KEY=sk-your-anthropic-key
```

Then source it:

```bash
source .env
```

### 3. Run the notebook

Open the notebook file (`Main.ipynb`) in VSCode and run it.

Choose your fighters, click **FIGHT**, and watch the chaos unfold.

## Features
- Choose your figher: pick from classic movie & television characters or add your own.
- Absurd, hilarious, character-driven topics.
- Live-streamed responses.
- Automatic saving of transcripts with character names and timestamp.