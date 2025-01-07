# Bridging Data Divides Workbook

This repo accompanies the Bridging Data Divides CAS Essay, providing a hands-on workbook and notebook examples that demonstrate the concepts discussed—such as retrieval-augmented generation, embeddings, and structured outputs. It’s designed to help actuaries and data professionals explore practical ways to unify and analyze unstructured data, apply AI techniques to real-world scenarios, and integrate these insights into existing insurance workflows.

## Setup

1. Make sure you have Python >= 3.9 installed. If you're on a work computer, you may need admin privileges to install Python.

You can check you have python by running:
```bash
python --version
```

2. Install the required packages:

Mac/Linux:
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Windows:
```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook
```

4. Open the notebook in your browser.

## API Keys:

This notebook uses an OpenAI-based implementation for simplicity. You will need an OpenAI API key that you can get from [here](https://platform.openai.com/api-keys). You can paste that key into the notebook in the cell that starts with `os.environ["OPENAI_API_KEY"] = "YOUR_API_KEY"`. Make sure to replace `YOUR_API_KEY` with your actual API key and uncomment the line (remove the `#` at the beginning of the line).

## Hosted Colab Version:

For those who don't want to setup Python, you can use the hosted Colab version of the notebook. Note this does require a Google account and it may be blocked by your company's security policies.

[Open In Colab](https://colab.research.google.com/drive/15uvMEzytBbf65HBhjh82-mHDTK6GnYt5)

