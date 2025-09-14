# NLP - Text preprocessing

This preprocessing pipeline was built based on the following paper: [Um Pipeline de Pré-Processamento de Dados Textuais em Português para Análise de Redes Sociais](https://sol.sbc.org.br/index.php/stil/article/download/31163/30966/).

## Setup

Prior to running the pipeline, **make sure your system has Python installed**. Then, download the corpus used through the following link: [https://zenodo.org/records/12761179](https://zenodo.org/records/12761179)

1. Create a python virtual environment:
```bash
python -m venv .venv
```

2. Activate the previously created virtual environment:
- In a bash terminal:
```bash
source .venv/bin/activate
```
- In a Powershell terminal:
```powershell
.venv\bin\Activate.ps1
```

3. Install the required Python packages:
```bash
pip install -r requirements.txt
```

4. Take the downloaded dataset and move it to a folder called `data/`. It must be at the root of this project.

