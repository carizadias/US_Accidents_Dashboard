# US Accidents Dashboard🚗

Este projeto é um dashboard interativo que analisa dados de acidentes nos EUA. Utiliza visualizações gráficas para explorar padrões e insights nos dados.

## Conteúdo do Projeto

- [Visão Geral](#visão-geral)
- [Demonstração](#demonstração)
- [Configuração do Ambiente](#configuração-do-ambiente)
- [Execução do Projeto](#execução-do-projeto)
- [Bibliotecas Utilizadas](#bibliotecas-utilizadas)
- [Dados Utilizados](#dados-utilizados)
- [Contribuições](#contribuições)
- [Licença](#licença)

## Visão Geral

Este projeto consiste em um dashboard de visualização de dados que utiliza Python com Streamlit para construir uma interface amigável. As principais funcionalidades incluem:

- Visualizações interativas de acidentes por estado, severidade, hora do dia e condições meteorológicas.
- Filtros para selecionar estados e anos específicos.
- Métricas de desempenho como total de acidentes, severidade média e número de estados afetados.

## Demonstração

Inserir uma captura de tela ou GIF mostrando o dashboard em ação.

## Configuração do Ambiente

Para configurar o ambiente de desenvolvimento:

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```
2. Instale as dependências necessárias:

   ```bash
   pip install -r requirements.txt
   ```
## Execução do Projeto
```bash
streamlit run dashboard.py
```
Irá abrir automaticamente uma pagina do seu browser predefinido, caso não acontecer clique no endereço localhost que aparecerá no terminal, por exemplo:http://localhost:8501.

## Bibliotecas Utilizadas

- Pandas
- Altair
- Plotly
- Streamlit

## Dados Utilizados
[Kaggle- US Accidents 2016-2023](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
Os dados de acidentes utilizados neste projeto foram obtidos a partir do dataset US Accidents disponível no Kaggle. O dataset original é composto por informações abrangentes sobre acidentes de trânsito ocorridos nos Estados Unidos. Abaixo estão alguns detalhes importantes sobre o dataset:

Período de Coleta: Os dados cobrem acidentes de trânsito registrados desde fevereiro de 2016 até março de 2023.
Número de Registros: O dataset contém mais de 7 milhões de registros de acidentes, tornando-o um recurso valioso para análise e visualização.
Atributos Disponíveis: Cada registro de acidente inclui uma ampla gama de atributos, como:

- ID: Identificador único do acidente.
- Severity: Severidade do acidente em uma escala de 1 a 4.
- Start_Time: Data e hora de início do acidente.
- End_Time: Data e hora de término do acidente.
- Start_Lat e Start_Lng: Latitude e longitude do local do acidente.
- Description: Descrição textual do acidente.
- State: Estado onde o acidente ocorreu.
- Temperature(F): Temperatura.
- Weather_Condition: Condição climática no momento do acidente.
Outros atributos relacionados às condições de visibilidade, tipo de estrada, presença de obras, entre outros.

## Dashboard em Streamlit:

Veja o dashboard em ação no [YouTube](https://www.youtube.com/watch?v=uwg72l_kC8M):

[![Dashboard](https://img.youtube.com/vi/uwg72l_kC8M/0.jpg)](https://www.youtube.com/watch?v=uwg72l_kC8M)



## Contribuições
Contribuições são bem-vindas! Para sugestões de novas funcionalidades, melhorias ou correções de bugs, abra uma issue ou envie um pull request.

