# Processamento de Linguagem Natural
Repositório criado para as aulas de Processamento de Linguagem Natural (PLN) da FURB. 

# Trabalho 1
Esse projeto visa a análise sentimental de letras de músicas brasileiras com base em gênero. Foram coletadas, no total, 100 músicas:
- 5 gêneros musicais:
    - MPB;
    - Rock;
    - Sertanejo;
    - Funk;
    - Rap.
 - 50 artistas (10 por gênero);
 - 2 letras por artista.

Todas as letras foram armazenadas no arquivo `songs.csv`.

Esse projeto tem fins 100% educacionais e voltados para o aprendizado.

## Notebooks
- Parte 1: [`trabalho_parte_1.ipynb`](https://colab.research.google.com/drive/1Fl-Y2HXOUr3jPxRMdVbEX982mTO-JKal?usp=sharing)
    -  Etapa de coleta;
    -  Busca de artistas através da API do MusicBrainz;
    -  Extração das letras através de web scraping do letras.com.br;
    -  Resultado: dataset `songs.csv`.
- Parte 2: [`trabalho_parte_2.ipynb`](https://colab.research.google.com/drive/1_j_S8dMcLlNJUxlp6epSbiNkdEs63cvY?usp=sharing)
    - Limpeza textual avançada;
    - Tokenização;
    - Stemming;
    - Lemmatização;
    - Remoção de stopwrods customizadas;
    - Vetorização com Bag of Words e TF-IDF;
    - Busca por similaridade por tema e por música;
    - Visualizações com heatmap e PCA.
