
# NLP - Pré-processamento de Texto

Este pipeline de pré-processamento foi construído com base no seguinte artigo: [Um Pipeline de Pré-Processamento de Dados Textuais em Português para Análise de Redes Sociais](https://sol.sbc.org.br/index.php/stil/article/download/31163/30966/).

Outras fontes de consulta:
- [https://drive.google.com/file/d/1aQ4hQ_wyuaePL32rlrPpkuO7GiqwqGAC/view](https://drive.google.com/file/d/1aQ4hQ_wyuaePL32rlrPpkuO7GiqwqGAC/view)
- [NLP for Beginners: Cleaning & Preprocessing Text Data](https://medium.com/data-science/nlp-for-beginners-cleaning-preprocessing-text-data-ae8e306bef0f)
- [Ferramentas para Processamento de Linguagem Natural em Português](https://medium.com/turing-talks/ferramentas-para-processamento-de-linguagem-natural-em-portugu%C3%AAs-977c7f59c382)
- [NLP para Iniciantes: Lematização](https://medium.com/@guilherme.davedovicz/nlp-para-iniciantes-lematiza%C3%A7%C3%A3o-d3f723fa9ee3)

## Configuração

Antes de executar o pipeline, **certifique-se de que o Python está instalado em seu sistema**. Em seguida, faça o download do corpus utilizado através do seguinte link: [https://zenodo.org/records/12761179](https://zenodo.org/records/12761179)

1. Crie um ambiente virtual Python:
```bash
python -m venv .venv
```

2. Ative o ambiente virtual criado:
- Em um terminal bash:
```bash
source .venv/bin/activate
```
- Em um terminal Powershell:
```powershell
.venv\bin\Activate.ps1
```

3. Instale os pacotes Python necessários:
```bash
pip install -r requirements.txt
```

4. Pegue o dataset baixado e mova-o para uma pasta chamada `data/`. Ela deve estar na raiz deste projeto.

## Melhorias futuras
- Utilizar um dicionário léxico para obter uma núvem de palavras mais significativa.
