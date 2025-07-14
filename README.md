# Telecom X - Análise de Evasão de Clientes

![GitHub language count](https://img.shields.io/badge/LANGUAGES-01-green)

<img src="assets/telecomX.png" alt="Exemplo imagem">

> Este projeto consiste em uma Análise Exploratória de Dados (EDA) aprofundada para identificar os principais fatores que contribuem para a evasão de clientes (Churn) na empresa de telecomunicações TelecomX. O objetivo é fornecer insights acionáveis que possam guiar a criação de estratégias eficazes de retenção de clientes.

## Objetivo do projeto

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas para as seguintes tarefas:

- Identificar Padrões de Churn: Compreender as características de clientes que churnam versus clientes que permanecem.
- Gerar Insights Acionáveis: Derivar recomendações estratégicas baseadas em dados para mitigar a taxa de evasão e melhorar a retenção de clientes na TelecomX.
- Analisar Relações: Investigar a correlação entre diversas variáveis (demográficas, de serviço, financeiras) e a propensão ao Churn.

## 💻 Pré-requisitos

### - Python (versão 3.x)
### - Bibliotecas Python:
- pandas para manipulação e análise de dados.
- numpy para operações numéricas.
- matplotlib para visualização de dados estática.
### - Ambiente de Desenvolvimento: Google Colab (ou Jupyter Notebook).

## 🚀 Como Executar a Análise

### No Google Colab:

1. Upload do Arquivo: Faça o upload do arquivo TelecomX_Data.json para o ambiente do Google Colab (na sessão de arquivos, clique no ícone de "Upload"). Certifique-se de que ele esteja na pasta /content/.
2. Abrir o Notebook: Abra o arquivo Desafio TelecomX_BR (1).ipynb no Google Colab.
3. Executar as Células: Execute todas as células do notebook sequencialmente. O notebook está estruturado para realizar o pré-processamento, as análises e gerar os gráficos e o relatório final.

## 📊  Insights Principais (Resumo)

A análise revelou que o Churn na TelecomX é influenciado por múltiplos fatores, com destaque para:

* **Contrato e Tempo de Serviço (`tenure`):** Clientes com contratos **mensais** e com **pouco tempo de serviço** são os mais propensos à evasão. Contratos de longo prazo demonstram ser o fator de retenção mais robusto.
* **Serviço de Internet:** A **Fibra Ótica** apresenta uma taxa de Churn significativamente maior, indicando possíveis problemas de qualidade, expectativa ou suporte neste tipo de serviço.
* **Método de Pagamento:** O **Cheque Eletrônico** é um método de pagamento associado a uma alta taxa de Churn.
* **Perfis Demográficos:** Clientes **idosos**, **sem parceiro** e **sem dependentes** demonstram maior propensão a churnar.

## 🖼️ Gráficos Principais

Para ilustrar os insights mais impactantes, destacamos alguns dos gráficos gerados na análise:

### Proporção de Churn por Tipo de Contrato
*(Este gráfico demonstra claramente como clientes com contratos mensais têm uma taxa de Churn dramaticamente maior.)*
<img src="assets/Churn tipo contrato.png" alt="Exemplo imagem">

### Proporção de Churn por meses de contrato
*(Este gráfico evidencia a alta taxa de Churn entre clientes com pouco tempo de contrato e até 20 meses de contrato.)*
<img src="assets/Churn meses.png" alt="Exemplo imagem">

---

## 💡 Recomendações Estratégicas (Resumo)

Com base nos insights, algumas recomendações para a TelecomX incluem:

* **Programas de Fidelização Acelerada:** Focar em clientes novos e de contrato mensal com check-ins proativos e ofertas de migração para contratos mais longos.
* **Otimização da Fibra Ótica:** Investigar profundamente a experiência do cliente com fibra (qualidade, suporte, expectativas) e realizar ajustes.
* **Valorização de Serviços Agregados:** Integrar serviços como Suporte Técnico em pacotes base ou oferecer test-drives para aumentar a percepção de valor e "aderência".
* **Incentivos para Migração de Pagamento:** Oferecer bônus ou descontos para clientes que migram do Cheque Eletrônico para métodos de pagamento automáticos.
* **Atendimento Personalizado:** Desenvolver abordagens e ofertas segmentadas para clientes idosos e para indivíduos sem parceiro/dependentes.

## 📞 Contato

Em caso de dúvidas ou para mais informações, sinta-se à vontade para entrar em contato:

* **Seu Nome:** Lucca Santos.
* **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/lucca-masiero)
* **Email:** [e-mail](mailto:luccamasiero7@gmail.com)
