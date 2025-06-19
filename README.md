# Automação de Dados e Dashboard de Carteira com Node.js e Power BI

## 📄 Descrição 

Este projeto tem como objetivo automatizar a coleta e atualização de dados de carteira a partir de downloads diários de planilhas via portal web, integrando esses dados em dashboards interativos desenvolvidos no Power BI. A automação reduz drasticamente o trabalho manual, aumenta a confiabilidade dos dados e proporciona análises atualizadas e dinâmicas para a tomada de decisão no mercado capitais.  
A consolidação da carteira em um único relatório, interativo, de atualização diária e de alta confiabilidade possibilitou a redução no trabalho operacional e possibilitou o desenvolvimento de análises dos dados e estudos dos investimentos.  
O dashboard desenvolvido consolidou em um único relatório informações de carteiras de investimentos de FIDCs, CRIs, FIMs, ou qualquer outro veículo de investimento de CCIs.  Muito além do já apresentado, a estrutura pode ser replicada para diversos objetivos: centralizar a carteira dos inúmeros empreendimentos de uma incorporadora, dos diversos fundos de uma gestora ou qualquer outra construção de carteira de recebíveis.

---

## ❌ Problema

Antes deste projeto, a atualização dos relatórios dependiam de processos manuais para baixar planilhas, consolidar dados e alimentar relatórios no Power BI, o que demandava muito tempo e apresentava risco elevado de erros humanos.

---

## 🎯 Solução

- Desenvolvimento de um bot em Node.js que realiza login no portal da servicer, navega por pop-ups e modais, e baixa automaticamente as planilhas diárias.
- Organização automática dos arquivos baixados em pastas por data e operação.
- Integração dessas bases no Power BI para criação de dashboards com indicadores financeiros essenciais, como fluxo de caixa, inadimplência e carteira de recebíveis.
- Uso de Power Query para transformação e modelagem dos dados dentro do Power BI.

---

## ✅ Arquitetura da Solução
[Portal Web] → [Bot Node.js (login + download)] → [Estrutura de pastas local] → [Power BI (importação + transformação + visualização)]

## 💻 Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- [Power BI Desktop](https://powerbi.microsoft.com/)
- Power Query (M Language)
- JavaScript (ES6+)
- Git & GitHub

---

## ✅ Resultados Alcançados

- Redução de 90% no tempo gasto com atualização manual de dados.
- Minimização de erros causados por processos manuais.
- Dashboards dinâmicos e atualizados diariamente.
- Facilidade na análise de indicadores financeiros para decisões estratégicas.

---

## Como Rodar o Projeto

⏳ Em breve códigos para replicar...

## 📁 Estrutura do Repositório

## Estrutura do Repositório

/
├── src/               # Código do bot Node.js  
├── data-model/        # Arquivos Power BI (.pbix) e dicionários de dados  
├── documentation/     # Diagramas, fluxogramas e documentação extra  
├── assets/            # Imagens e recursos visuais  
├── .env.example       # Modelo de arquivo de ambiente para credenciais  
├── .gitignore         # Arquivos ignorados pelo Git  
├── LICENSE            # Licença do projeto  
└── README.md          # Este arquivo  

---

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

Imagens

Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

Contato
Para dúvidas ou sugestões, entre em contato: [murilorodriguesvieira@outlook.com]

