分叉自https://github.com/andrewyng/translation-agent

使用教程：
## Getting Started

To get started with `translation-agent`, follow these steps:

### Installation:
- The Poetry package manager is required for installation. [Poetry Installation](https://python-poetry.org/docs/#installation) Depending on your environment, this might work:

```bash
pip install poetry
```

- A .env file with a OPENAI_API_KEY is required to run the workflow. See the .env.sample file as an example.
```bash
git clone https://github.com/darkbIue/translation-agent.git
cd translation-agent
poetry install
poetry shell # activates virtual environment
```
### Usage:

```python
python utils.py
```

