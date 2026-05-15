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
 - Parte 3: [`trabalho_parte_3.ipynb`](https://colab.research.google.com/drive/1hEyU_ZOznnrKBU1QNXfpk1lcm9K8rqBl?usp=sharing)
     - Carregamento do dataset de letras limpas;
     - Preparação dos documentos tokenizados;
     - Treinarmento de um modelo Word2Vec;
     - Geração de vetores de documentos pela média dos vetores das palavras;
     - Cálculo de similaridade por cosseno entre músicas;
     - Busca de músicas similares por consulta textual;
     - Busca de músicas similares a uma música específica;
     - Visualização de similaridades com heatmap e PCA.
- Parte 4: [`trabalho_parte_4.ipynb`](https://colab.research.google.com/drive/1YwDTObziyMIa-Ss36OEixf2uFA3QjVqK?usp=sharing)
    - a
- Parte 5: [`trabalho_parte_5.ipynb`](https://colab.research.google.com/drive/1wLVAJnq_wjeQsuJjZmNHPs2KGmVdg_A-?usp=sharing)
    - a
- Parte 6: [`trabalho_parte_6.ipynb`]()
    - a
