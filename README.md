# Dashboard de Despesas dos Senadores

Este projeto é um **dashboard interativo** desenvolvido com **Streamlit**, **Pandas** e **Matplotlib** para visualizar os valores reembolsados pelos senadores, organizados por ano e tipo de despesa.

## Funcionalidades

- Carregamento de dados a partir de um arquivo CSV.
- Agrupamento de dados por senador, ano e tipo de despesa.
- Visualização interativa dos valores reembolsados por senador.
- Gráfico geral com o total de reembolsos por senador.

## Tecnologias Utilizadas

- **Python**: Linguagem principal do projeto.
- **Pandas**: Manipulação e análise de dados.
- **Matplotlib**: Criação de gráficos.
- **Streamlit**: Desenvolvimento do dashboard interativo.

## Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone (https://github.com/hccaldas/Despesas-Senadores)>
2. Crie um ambiente virtual (opcional, mas recomendado):

  python -m venv venv
  source venv/bin/activate  # No Windows: venv\Scripts\activate

3. Instale as dependências:

  pip install -r requirements.txt

4. Coloque o arquivo CSV no diretório do projeto: Certifique-se de que o arquivo despesa_ceaps_ultimos_anos.csv está no mesmo diretório do script dashboard_despesas.py.

5. Execute o dashboard:
   streamlit run dashboard_despesas.py

6. Acesse o dashboard: Abra o navegador e acesse o endereço exibido no terminal (geralmente http://localhost:8501).

Estrutura do Projeto
.
├── [dashboard_despesas.py](http://_vscodecontentref_/0)   # Código principal do dashboard
├── [despesa_ceaps_ultimos_anos.csv](http://_vscodecontentref_/1)  # Arquivo de dados (não incluído no repositório)
├── requirements.txt        # Dependências do projeto
└── README.md               # Documentação do projeto

Exemplo de Visualização

  Gráfico Interativo: Valores reembolsados por senador, ano e tipo de despesa.
  Gráfico Geral: Total de reembolsos por senador.
  
Dependências

  As dependências do projeto estão listadas no arquivo requirements.txt. Certifique-se de instalar todas antes de executar o projeto.

Contribuição

  Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

Licença

  Este projeto está sob a licença MIT.

