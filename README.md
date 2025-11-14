# Análise de Logs de Experimento de Usuário (Teste A/B)

## 📋 Descrição / Resumo Executivo
Este projeto analisa logs de eventos de usuários em um experimento (A/B testing) para entender padrões de comportamento e a eficácia de diferentes versões (grupos). O conjunto de dados contém eventos como "MainScreenAppear", "PaymentScreenSuccessful", etc., com timestamps e identificadores de grupo. A análise visa identificar qual grupo apresenta melhor desempenho em métricas de conversão e engajamento, fornecendo insights para decisões de produto e experiência do usuário.

## 🎯 Objetivos
* Comparar a taxa de conversão (evento de pagamento bem-sucedido) entre os grupos de experimento
* Analisar a sequência de eventos dos usuários para entender o funil de conversão
* Identificar padrões temporais nos logs (horários/dias de maior atividade)
* Segmentar usuários por comportamento e grupo experimental
* Avaliar a significância estatística das diferenças entre grupos

## 📊 Metodologia e Ferramentas
* **Linguagem de Programação:** Python
* **Bibliotecas Principais:** pandas, numpy, plotly, matplotlib, seaborn, scipy
* **Ferramentas de Visualização:** Plotly Express, Matplotlib, Seaborn
* **Ambiente:** Jupyter Notebook

## 🗃️ O Conjunto de Dados
* **Fonte:** Dados internos de logs de experimento (anonimizados)
* **Descrição:** Logs de eventos de usuários em um aplicativo, com informações de evento, ID do dispositivo, timestamp e grupo de experimento
* **Período:** Os dados são de 25 de julho de 2019 (conforme as primeiras entradas)
* **Tamanho e Escopo:** 244.126 registros, 4 colunas originais

## 🔍 Análise Exploratória de Dados (EDA)
* **Tratamento de Dados:** Conversão de timestamp para datetime, extração da data, renomeação de colunas para maior clareza
* **Estatísticas Descritivas:** Contagem de eventos por tipo, distribuição entre grupos, análise temporal
* **Descobertas Iniciais:** Padrões de sequência de eventos, comparação inicial entre grupos de experimento

## 📈 Modelagem & Resultados (Se Aplicável)
* **Técnica Utilizada:** Testes de hipótese (qui-quadrado, t-test) para validar diferenças significativas entre grupos
* **Resultados Obtidos:** [A ser preenchido com resultados específicos da análise]
* **Insights dos Resultados:** [A ser preenchido com conclusões sobre qual grupo performou melhor e por quê]

---

## 🚀 Como Executar este Projeto

### Pré-requisitos
* Python 3.7+
* Gerenciador de pacotes pip

### Instalação
1. Clone o repositório:
    ```bash
    git clone https://github.com/[seu-usuario]/analise-logs-experimento.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd analise-logs-experimento
    ```
3. Crie e ative um ambiente virtual (opcional):
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    # ou
    venv\Scripts\activate  # Windows
    ```
4. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

### Execução
* Abra o Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
* Execute as células do notebook `notebook_projeto_sprint11.ipynb` em ordem.

## 📄 Licença
Este projeto é para fins educacionais.

## 🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

---

*Este projeto foi desenvolvido como parte do portfólio de Análise de Dados. Feedback é sempre apreciado!*
