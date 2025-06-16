
# Transformer para predição de preços de ações

Esse projeto consiste em um repositório Python que usa, especialmente, PyTorch e Jupyter para a criação de um Transformer que prediz preços de ações para quatros empresas de tecnologia:

- IBM;
- Microsoft;
- Apple;
- Google.

O repositório tem 4 Dataframes embutidos, cada um com 251 valores de ações entre os anos de 2024 e 2025. A fonte dos dados é a [National Association of Securities Dealers Automated Quotations (Nasdaq)](https://www.nasdaq.com/).

## Rodando o projeto em sua máquina

Clone o projeto localmente:
```bash
  git clone https://github.com/GabrielFAlmeida/transformer-para-predicao-de-precos-de-acoes-em-Big-Techs.git
```

Entre no diretório do projeto, preferencialmente utilizando o [VSCode](https://code.visualstudio.com/):

```bash
- No VSCode acesse:
  File > Open Folder > [Pasta onde armazenou o projeto] 
```

Acesse a pasta de códigos-fonte:
```bash
  cd app
  cd src
```

Instale as dependências JupyterLab e Jupyter Notebook:
```bash
  pip install jupyterlab
  pip install notebook
```

Instale as demais dependências:
```bash
  # Numpy  
  pip install numpy

  # PyTorch 
  pip install torch

  # MatplotLib
  python -m pip install -U pip
  python -m pip install -U matplotlib

  # SciKit Learn
  pip install -U scikit-learn

  # Seaborn
  pip install seaborn

  # Scipy
  pip install scipy
```

Execute o projeto diretamente do VSCode, acessando o arquivo notebook.ipynb ou ainda, com o servidor Jupyter:
```bash
   jupyter notebook
```


## Autores

Os autores do projeto são mestrandos do Programa de Pós Graduação em Ciência da Computação (PPGCO) da Universidade Federal de Uberlândia (UFU). Caso tenha interesse, você pode se conectar através dos links a seguir: 
- [Gabriel França de Almeida](https://github.com/GabrielFAlmeida)
- [Eneia Castigo Gazite](mailto:eneiagazite@yahoo.com)


## Referências

- Dos Santos, Guilherme Galvao. MODELO DE PREDIÇÃO DE PREÇOS DE AÇÕES UTILIZANDO REDES NEURAIS ARTIFICIAIS. São Paulo. 2022
- BLUME, L.; EASLEY, D.; O’HARA, M. Market statistics and technical analysis: Therole of volume.The journal of finance, Wiley Online Library, v. 49, n. 1, p. 153– 181, 1994.
- Ghodrati, A., Samadi, B., & Gharaviri, A. (2014). Forecasting stock exchange trends using a time series model. Journal of Soft Computing and Decision Support Systems, 1(1), 6-9.
- Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., ... & Polosukhin, I. (2017). Attention is all you need. Advances in Neural Information Processing Systems, 30.
- Zerveas, G., Jayaraman, S., Patel, D., Bhamidipaty, A., & Eickhoff, C. (2021). A transformer-based framework for multivariate time series representation learning. Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining
- Wu, H., Xu, J., Wang, J., & Long, M. (2021). Autoformer: Decomposition transformers with auto-correlation for long-term series forecasting. Advances in Neural Information Processing Systems, 34
- JAIN, V.; SAINI, D.; AHLUWALIA, A. Real-time autonomous trading system.Journal of Statistics and Management Systems, Taylor Francis, v. 22, n. 2, p. 403–413, 2019.
- LeCun, Y., Bengio, Y., & Hinton, G. (2015). Deep learning. Nature, 521(7553), 436–444.
- Atsalakis, G. S., & Valavanis, K. P. (2009). Surveying stock market forecasting techniques – Part II: Soft computing methods. Expert Systems with Applications, 36(3), 5932–5941.

## Considerações e agradecimentos

Nessa seção estamos saudando e agradecendo especialmente nosso amigo de trabalho, Salomão, que nos auxiliou na jornada de concepção do modelo de predição - com as tecnologias usadas como motor para o funcionamento do trabalho.

Cabe ressaltar que essa é a primeira versão do repositório, que certamente será melhorado em possibilidades posteriores de desenvolvimento - para que o modelo se torne mais preciso e generalista.

Agradecemos a atenção dispensada pelos leitores, em especial o professor orientador da disciplina, Murillo Guimarães Carneiro. 

