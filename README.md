# Projeto de Clusterização

Este repositório contém o notebook para um projeto de clusterização de dados utilizando algoritmos de aprendizado de máquina.

## Visão Geral

O objetivo deste projeto é agrupar dados em clusters significativos com base em suas características.
## Objetivos

- Utilizar a API da OpenAI para obter embeddings dos dados, melhorando a qualidade da clusterização.
- Integrar outra API para obter dados de datas comemorativas e feriados, adicionando uma camada contextual ao processo de análise.
- Análise dos dados e cluster objetidos

## Estrutura do Projeto

- `data/`: Contém os conjuntos de dados utilizados no projeto.
- `notebooks/`: Jupyter Notebooks com o código de implementação dos algoritmos de clusterização e análise dos resultados.
- `scripts/`: Scripts Python para pré-processamento dos dados e execução dos algoritmos de clusterização. (TO DO)
- `results/`: Imagens e arquivos de resultados das análises e visualizações. (TO DO)
- `README.md`: Este arquivo de documentação.

## Requisitos

Para executar este projeto, você precisará das seguintes bibliotecas Python:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- plotly
- jupyter
- scipy
- OpenAI

Você também vai precisar de uma chave da OpenAI e uma da Calendarific


Você pode instalar todas as dependências utilizando o arquivo `requirements.txt`:

pip install -r requirements.txt


## Uso

1. Clone este repositório:

git clone https://github.com/isaccjr/LLM-Clustering.git


2. Navegue até o diretório do projeto:

cd LLM-Clustering


3. Execute os notebooks ou scripts para realizar a clusterização e visualizar os resultados. 

## Algoritmos Utilizados

- **K-means**: Um algoritmo de clusterização particional que divide os dados em K clusters com base em suas distâncias.

## Resultados

Os resultados das análises e visualizações estão disponíveis na pasta `results/`. Incluímos gráficos e métricas de desempenho para avaliar a qualidade dos clusters formados.

## Contribuição

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões para melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Para mais informações ou perguntas sobre o projeto, entre em contato:

- **Isac Soares Camara Junior**
- **Email:** isacscjr@gmail.com
- **LinkedIn:** [linkedin.com/in/isacscjr](https://linkedin.com/in/isacscjr)
- **Github:** [github.com/isaccjr](https://github.com/isaccjr)


