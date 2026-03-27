# Analise-Dados-Spotify-Projeto-Final-PretaLab

### 📺 Apresentação do Projeto
[![Assista à apresentação](https://img.youtube.com/vi/tAcTC49apwg/0.jpg)](https://www.youtube.com/watch?v=tAcTC49apwg)

*Neste vídeo, apresento a análise completa da "Anatomia do Hit", explorando como a duração e a dançabilidade influenciam o sucesso no Spotify.*


# 🎧 Anatomia do Hit: Análise Exploratória do Spotify

Este projeto foi desenvolvido como o **Projeto Final do Ciclo 15** (PretaLab), focado em Ciência de Dados e Análise Exploratória. O objetivo principal foi investigar quais características sonoras (duração, ritmo, volume) diferenciam um "Hit Global" do restante do catálogo do Spotify, com um olhar especial para o impacto da "Era do TikTok".

## 🎯 Objetivo do Projeto

Analisar se existe uma "fórmula sonora" para o sucesso e validar se os hits atuais tendem a ser mais curtos, mais dançantes e mais intensos (*loudness*) do que as músicas de baixa popularidade.

### Perguntas Norteadoras:

  * Existe uma "Janela de Ouro" de duração para as músicas de sucesso?
  * Músicas populares são necessariamente mais rápidas (BPM alto)?
  * Qual a influência da densidade lírica (*speechiness*) no topo das paradas?
  * Existe uma correlação matemática direta entre o áudio e a popularidade?

## 📊 Principais Insights

  * **A Janela de Ouro (3 a 4 min):** Os hits mundiais são extremamente padronizados. Enquanto o catálogo geral é disperso, os sucessos concentram-se rigidamente entre 3 e 4 minutos de duração.
  * **Melodia \> Fala:** O grupo de hits apresenta baixíssima taxa de *speechiness*. O mercado global favorece a melodia e a batida; faixas com muita fala (como podcasts ou faixas experimentais) raramente atingem o topo.
  * **O "Bilhete de Entrada":** A análise provou que seguir o padrão de mercado (duração curta e alta dancabilidade) é apenas o pré-requisito para competir.
  * **A Desconstrução da Fórmula:** O mapa de calor revelou que não há uma correlação linear forte entre áudio e popularidade. O sucesso é um fenômeno **sociocultural**, dependente de marketing, algoritmos e tendências virais.

## 🛠️ Tecnologias Utilizadas

  * **Linguagem:** Python 3.12
  * **Bibliotecas de Dados:** Pandas, NumPy
  * **Visualização:** Matplotlib, Seaborn
  * **Ambiente:** Google Colab / Jupyter Notebook

## 📁 Estrutura do Repositório

  * `Thais_Rodrigues_Projeto_Final.ipynb`: Notebook com todo o código Python, tratamentos de dados e visualizações.
  * `spotify_dataset.csv`: Base de dados contendo mais de 114.000 faixas e suas características acústicas.

## 🚀 Como Executar

1.  Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/analise-dados-spotify-projeto-final-pretalab.git
    ```
2.  Certifique-se de ter as bibliotecas instaladas:
    ```bash
    pip install pandas seaborn matplotlib numpy
    ```
3.  Abra o arquivo `.ipynb` no seu editor de preferência ou no Google Colab.

