# Descrição

Este é um projeto de visualização de dados em Python usando as bibliotecas `matplotlib`, `pandas` e `seaborn`. O objetivo deste projeto é criar gráficos de barras para cada linha de um conjunto de dados, tornando mais fácil a compreensão de cada uma das linhas separadamente.

O projeto lê um arquivo CSV chamado "`habilidades.csv`" e gera um gráfico de barras para cada linha do conjunto de dados. Cada gráfico de barras contém as habilidades (colunas) e suas pontuações (valores) ordenadas em ordem descendente. As barras são coloridas em tons de verde e os valores são exibidos no topo de cada barra.

Cada gráfico é salvo como um arquivo PNG na pasta "`figs`" na raiz do projeto.

# Como baixar e usar
Para baixar e executar o projeto, siga as instruções abaixo:

- Certifique-se de ter o Python 3.6 ou superior instalado em sua máquina.
- Clone o repositório do projeto em sua máquina local usando o comando: `git clone https://github.com/marrcandre/habilidades.git`
- Instale as dependências do projeto usando o pdm, com o comando `pdm install`
- Execute o script principal do projeto usando o comando `pdm run python main.py`

Depois de seguir essas etapas, o script principal será executado e cada gráfico de barras será gerado e salvo como um arquivo PNG na pasta "`figs`". Você pode visualizar os arquivos gerados abrindo-os com um visualizador de imagens ou abrindo a pasta "figs" no explorador de arquivos.