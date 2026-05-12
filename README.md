![Análise de Churn](churn.jpg)
# Case Churn

Este projeto tem como objetivo validar a hipótese de aumento na taxa de churn de uma plataforma de ERP voltada para pequenas e médias empresas, identificando padrões e comportamentos que possam apoiar a equipe de negócios na tomada de decisão.

📄 [Veja a minha apresentação aqui](https://github.com/pedroisv/case-churn-eda/blob/main/CaseChurnApresentacao.pdf)
📓 [Acessar notebook completo](https://github.com/pedroisv/case-churn/blob/main/CaseChurnEDA.ipynb)
🔗 [Acessar documentação no Notion](https://pedroisv-portifolio.notion.site/An-lise-de-Churn-359ff4051196808da141f9985bd1921f)

## 📂 Conteúdo

1. [Principais Insights](#principais-insights)
2. [Recomendações](#recomendações)

## Principais Insights

- Houve um aumento significativo na taxa de churn nos períodos analisados, de 14,85% em abril para 18,51% em maio. Apesar disso, não é possível confirmar tendência de crescimento pois temos dados de apenas dois meses.
- Clientes com contrato mês-a-mês concentram o maior risco de cancelamento, com churn de 42,7%, contra 11,26% no trimestral e 2,83% no anual. A alta flexibilidade de saída está associada a essa maior taxa de cancelamento.
- O período inicial de contrato é fundamental na retenção de clientes. Dentre os clientes que cancelaram o serviço, 50% tiveram até 10 meses de contrato e 25% até 2 meses.
- O uso das funcionalidades está associado ao churn: clientes com baixo nível de utilização concentram maior número de churns em todos os módulos analisados (entre 33,5% e 41,8%), enquanto os com uso frequente apresentam taxas significativamente menores.

Mais detalhes podem ser encontrados no Jupyter Notebook associado.

## Recomendações

- Desenvolver um dashboard de monitoramento do churn para acompanhar a evolução mensal da taxa e identificar tendências com mais dados.
- Incentivar a migração para planos de maior duração (trimestral e anual), por meio de descontos, campanhas de upgrade e benefícios exclusivos.
- Fortalecer o onboarding nos primeiros meses, com foco em aumentar o engajamento e a adoção do sistema, reduzindo o risco de churn inicial.
- Aprofundar a análise com testes estatísticos para confirmar se as associações encontradas se sustentam como fatores de risco reais para o churn


📌 Desenvolvido no contexto da divisão América Latina do Airbnb.

---
