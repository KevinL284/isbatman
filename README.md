# isbatman

Este repositório contém uma pipeline de aprendizado de máquina que utiliza transfer learning com TensorFlow para reconhecer imagens e identificar se um personagem é o Batman ou não.

## Visão geral

O objetivo do projeto é criar um classificador de imagens capaz de distinguir o Batman de outros personagens, objetos ou pessoas. Para isso, seguimos as etapas abaixo:

1. **Coleta de Dados**  
   Utilizamos web scraping para buscar e coletar imagens de Batman e de outras classes para compor o dataset inicial.

2. **Limpeza e Filtragem**  
   As imagens coletadas foram filtradas manualmente para remover itens irrelevantes ou de baixa qualidade, garantindo um conjunto de dados mais limpo e adequado para o treinamento.

3. **Treinamento com Transfer Learning**  
   Usamos TensorFlow e técnicas de transfer learning para treinar um modelo de classificação, aproveitando pesos de modelos pré-treinados que já reconhecem características gerais em imagens.

4. **Treinamento do Modelo**  
   O modelo foi treinado por 50 épocas para maximizar sua capacidade de reconhecer o Batman em imagens.

## Observações

- O modelo ainda necessita de mais dados para alcançar um desempenho satisfatório.
- Futuramente, pretendemos expandir o dataset e melhorar o processo de filtragem automática.

## Como utilizar

1. Clone o repositório:
   ```bash
   git clone https://github.com/KevinL284/isbatman.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o pipeline:
   ```bash
   python main.py
   ```

## Requisitos

- Python 3.8+
- TensorFlow
- Bibliotecas listadas em `requirements.txt`

## Contribuição

Sinta-se à vontade para abrir issues ou pull requests para sugerir melhorias, reportar bugs ou contribuir com novos dados para o projeto.

---

Feito com ☕ por [KevinL284](https://github.com/KevinL284)
