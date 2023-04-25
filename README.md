# Modelo forecast bitcoin

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)
[![author](https://img.shields.io/badge/author-RafaelGallo-red.svg)](https://github.com/RafaelGallo?tab=repositories) 
[![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-374/) 
[![](https://img.shields.io/badge/R-3.6.0-red.svg)](https://www.r-project.org/)
[![](https://img.shields.io/badge/ggplot2-white.svg)](https://ggplot2.tidyverse.org/)
[![](https://img.shields.io/badge/dplyr-blue.svg)](https://dplyr.tidyverse.org/)
[![](https://img.shields.io/badge/readr-green.svg)](https://readr.tidyverse.org/)
[![](https://img.shields.io/badge/ggvis-black.svg)](https://ggvis.tidyverse.org/)
[![](https://img.shields.io/badge/Shiny-red.svg)](https://shiny.tidyverse.org/)
[![](https://img.shields.io/badge/plotly-green.svg)](https://plotly.com/)
[![](https://img.shields.io/badge/XGBoost-red.svg)](https://xgboost.readthedocs.io/en/stable/#)
[![](https://img.shields.io/badge/Tensorflow-orange.svg)](https://powerbi.microsoft.com/pt-br/)
[![](https://img.shields.io/badge/Keras-red.svg)](https://powerbi.microsoft.com/pt-br/)
[![](https://img.shields.io/badge/CUDA-gree.svg)](https://powerbi.microsoft.com/pt-br/)
[![](https://img.shields.io/badge/Caret-orange.svg)](https://caret.tidyverse.org/)
[![](https://img.shields.io/badge/Pandas-blue.svg)](https://pandas.pydata.org/) 
[![](https://img.shields.io/badge/Matplotlib-blue.svg)](https://matplotlib.org/)
[![](https://img.shields.io/badge/Seaborn-green.svg)](https://seaborn.pydata.org/)
[![](https://img.shields.io/badge/Matplotlib-orange.svg)](https://scikit-learn.org/stable/) 
[![](https://img.shields.io/badge/Scikit_Learn-green.svg)](https://scikit-learn.org/stable/)
[![](https://img.shields.io/badge/Numpy-white.svg)](https://numpy.org/)
[![](https://img.shields.io/badge/PowerBI-red.svg)](https://powerbi.microsoft.com/pt-br/)

Nesse projeto de forecast modelo previsão bitcoin utlizando modelos ARIMA, SARIMA, SARIMAX como vai está o valor do bitcoin no futuro uma previsão. 
Algumas ferramentas vai ser utilizada python autoarima, statsmodels, fbprophet.

No segundo projeto modelo processamento de linguagem natural análise de sentimentos e extração de tópicos, utlizando modelo LDA para fazer extração dos textos mais comentados.

Bases de dados foi extraida site do kaggle, e uma API em python extração dos dados.


![Logo](https://img.freepik.com/fotos-gratis/o-bitcoin-dourado-nas-maos-do-correio_155003-8473.jpg?w=1060&t=st=1682440631~exp=1682441231~hmac=5045c8c71d1f049c42b2f755fc76a36c89204c383cad0dea7bfd8396e240dfe8)


## Autores

- [@RafaelGallo](https://www.github.com/RafaelGallo)


## Stack utilizada

**Machine learning:** Python, R, autoarima, statsmodels, fbprophet



## Instalação


Instalação das bibliotecas para esse projeto no python.

```bash
  conda install -c conda-forge pandas 
  conda install -c conda-forge scikitlearn
  conda install -c conda-forge numpy
  conda install -c conda-forge scipy
  conda install -c conda-forge matplotlib
  conda install -c conda-forge statsmodels
  conda install -c conda-forge fbprophet
  conda install -c conda-forge pmdarima

  python==3.6.4
  numpy==1.13.3
  scipy==1.0.0
  matplotlib==2.1.2
  statsmodels==0.13.2
  fbprophet==0.7.1
  pmdarima==2.0.0



```
Instalação do Python É altamente recomendável usar o anaconda para instalar o python. Clique aqui para ir para a página de download do Anaconda https://www.anaconda.com/download. Certifique-se de baixar a versão Python 3.6. Se você estiver em uma máquina Windows: Abra o executável após a conclusão do download e siga as instruções. 

Assim que a instalação for concluída, abra o prompt do Anaconda no menu iniciar. Isso abrirá um terminal com o python ativado. Se você estiver em uma máquina Linux: Abra um terminal e navegue até o diretório onde o Anaconda foi baixado. 
Altere a permissão para o arquivo baixado para que ele possa ser executado. Portanto, se o nome do arquivo baixado for Anaconda3-5.1.0-Linux-x86_64.sh, use o seguinte comando: chmod a x Anaconda3-5.1.0-Linux-x86_64.sh.

Agora execute o script de instalação usando.


Depois de instalar o python, crie um novo ambiente python com todos os requisitos usando o seguinte comando

```bash
conda env create -f environment.yml
```
Após a configuração do novo ambiente, ative-o usando (windows)
```bash
activate "Nome do projeto"
```
ou se você estiver em uma máquina Linux
```bash
source "Nome do projeto" 
```
Agora que temos nosso ambiente Python todo configurado, podemos começar a trabalhar nas atribuições. Para fazer isso, navegue até o diretório onde as atribuições foram instaladas e inicie o notebook jupyter a partir do terminal usando o comando
```bash
jupyter notebook
```


## Descrição projetos

| Nome              | Link base dados                                              |
| ----------------- | ---------------------------------------------------------------- |
| Bitcoin - Série temporal | [Link projeto](https://www.kaggle.com/datasets/varpit94/bitcoin-data-updated-till-26jun2021)|
| Bitcoin Tweets - NLP | [Link projeto](https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets)|

## Screenshots

![App Screenshot](https://raw.githubusercontent.com/steffmul/nextbike/master/forecast.gif)


## Roadmap

- Previsão dos bitcoin e a tendencia da moeda, modelo análise de sentimento o que pessoal está dizendo sobe as moedas.

- Extração de tópicos em textos, os sentimentos que as pessoas estão dizendo.

- Verificar a têndencia dos textos.


## Feedback

Se você tiver algum feedback, por favor nos deixe saber por meio de rafaelhenriquegallo@gmail.com

