# ETL_IPTU_2025

### Visão Geral
Este repositório contém o código-fonte de um projeto universitário focado na construção de um pipeline de ETL (Extração, Transformação e Carga) para os dados do IPTU de Recife do ano de 2025.

A fonte de dados original foi previamente baixada e armazenada no Google Drive para assegurar um ambiente de desenvolvimento estável e resiliente a falhas da API externa.

## Tecnologias
O projeto foi desenvolvido utilizando as seguintes tecnologias:

* **Python**
    * **Pandas:** Para todas as etapas de manipulação e transformação de dados.
    * **Matplotlib:** Para a geração de gráficos e visualizações.
* **Google Drive:** Como plataforma de armazenamento e acesso aos dados brutos.

## Instalação
Para executar este projeto em sua máquina local, siga os passos abaixo:

1.  Certifique-se de ter o [Python](https://www.python.org/downloads/) instalado.
2.  (Recomendado) Crie e ative um ambiente virtual para isolar as dependências do projeto:
    ```bash
    python -m venv venv
    # No macOS/Linux:
    source venv/bin/activate
    # No Windows:
    venv\Scripts\activate
    ```
3.  Instale as bibliotecas necessárias usando o `pip`:
    ```bash
    pip install pandas matplotlib
    ```
