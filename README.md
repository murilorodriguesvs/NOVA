# Automação de Dados e Dashboard de Carteira com Node.js e Power BI

## Descrição

Este projeto tem como objetivo automatizar a coleta e atualização de dados financeiros a partir de downloads diários de planilhas via portal web, integrando esses dados em dashboards interativos desenvolvidos no Power BI. A automação reduz drasticamente o trabalho manual, aumenta a confiabilidade dos dados e proporciona análises atualizadas e dinâmicas para a tomada de decisão no mercado financeiro.

---

## Problema

Antes deste projeto, a atualização dos relatórios financeiros dependia de processos manuais para baixar planilhas, consolidar dados e alimentar relatórios no Power BI, o que demandava muito tempo e apresentava risco elevado de erros humanos.

---

## Solução

- Desenvolvimento de um bot em Node.js que realiza login no portal da servicer, navega por pop-ups e modais, e baixa automaticamente as planilhas diárias.
- Organização automática dos arquivos baixados em pastas por data e operação.
- Integração dessas bases no Power BI para criação de dashboards com indicadores financeiros essenciais, como fluxo de caixa, inadimplência e carteira de recebíveis.
- Uso de Power Query para transformação e modelagem dos dados dentro do Power BI.

---

## Arquitetura da Solução

