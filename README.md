# Modelo Preditivo de Fechamento da IBOVESPA

Este projeto consiste em um modelo preditivo desenvolvido para prever diariamente o fechamento do índice IBOVESPA. O modelo foi desenvolvido utilizando a biblioteca Prophet e é baseado em uma série temporal de dados históricos da IBOVESPA.

## Índice
- [Descrição do Projeto](#descrição-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Avaliação do Modelo](#avaliação-do-modelo)
- [Contribuição](#contribuição)

## Descrição do Projeto
O objetivo deste projeto é criar um modelo preditivo para prever o fechamento diário do IBOVESPA. Utilizamos a biblioteca Prophet, que é adequada para a modelagem de séries temporais com sazonalidades diárias e anuais, além de considerar feriados nacionais.

## Tecnologias Utilizadas
- Python
- [Prophet](https://facebook.github.io/prophet/docs/quick_start.html)
- pandas
- numpy
- scikit-learn
- matplotlib

## Como Executar o Projeto

1. Clone o repositório:
   ```sh
   git clone https://github.com/usuario/previsao_ibovespa.git
2. Navegue até o diretório do projeto:
   ```sh
   cd seu-repositorio
3. Instale as dependências:
   ```sh
   pip install -r requirements.txt
4. Execute o script principal:
   ```sh
   python seu-script.py

## Avaliação do Modelo
O modelo foi avaliado utilizando as métricas RMSE (Root Mean Squared Error) e MAE (Mean Absolute Error), além de uma medida de acurácia. Os resultados obtidos foram:

- RMSE: 15.6218107000084
- MAE: 12.304413929815267
- Acurácia: 0.8881246458113503

## Contribuição
Se você deseja contribuir com o projeto, por favor, siga os passos abaixo:

1. Faça um fork do repositório
2. Crie uma branch para sua feature (git checkout -b feature/nova-feature)
3. Commit suas alterações (git commit -am 'Adicionei uma nova feature')
4. Faça o push para a branch (git push origin feature/nova-feature)
5. Abra um Pull Request

<p align='center'>Desenvolvido 🧩 por, Willian</p>
