# Agent-Deep-Dive
Open AI's Agent SDK concepts

## Setup

Install the Python dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt
```

If you use Conda, create and activate the `aaaic` environment first:

```bash
conda create -n aaaic python=3.12
conda activate aaaic
pip install -r requirements.txt
```

## Run

Copy `.env.example` to `.env`, add your API key, then run the example:

```bash
cp .env.example .env
python 01-simple-agent.py
```
