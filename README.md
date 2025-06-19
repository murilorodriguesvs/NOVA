# NOVA: Núcleo de Operação, Visualização e Análise

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

## 📊 Dashboard

O Dashboard foi desenvolvido em PowerBI utilizando uma estrutura de seleção por veículo, múltipla ou única. Dividido em quatro páginas: Distribuição, Carteira, Inadimplência, Painel de Clientes, o relatório traz um visualização detalhada de cada aspecto de análise de uma carteira de investimentos.

### Distribuição

Focado em apresentar a concetração por devedor em cada um de seus aspectos:  
- Localização
- Taxa
- LTV
- Tabela de Amortização
- Índice de Correção
- Pessoa Física ou Jurídica
- Finalidade do Crédito
- Valor de Emissão
- Duration X Taxa

Nesta página, será possível destrinchar a concentração dos ativos, possível alocação em CRIs, impactos por índice de correção, análise de Duration individual, histórico de emissão por taxa e Ticket. Sua carteira está bem pulverizada? Qual o Duration de cada um de seus devedores? O cenário histórico de taxa de juros das emissões passadas é atrativo?

### Carteira

Em segundo momento, o dashboard permitirá analisar a carteira pulverizada. Consolidamos em uma página todo histórico de recebimento e de recebimento futuro da carteira e Behavior da carteira.  
Toda carteira futura é projetada em critério de elegibilidade, todo o histórico é apresentado para entender se o comportamento dos devedores: em dia, atrasado ou adiantado? 
Neste momento conseguimos entender e negociar a carteira como um único "pacote".

### Inadimplência

Talvez a análise mais importante, na página de inadimplência é destacado cada pagamento em aberto por cliente.  
Visualizações como:
- Valor em aberto por cliente, segmentando multa e mora
- Valor em aberto por faixa de atraso
- Rastro de inadimplência
- Distribuição por Elegibilidade
- Distribuição por estágoo na esteira de cobrança
- Nível de inadimplência
- Média de Atraso

### Painel de Clientes

Por fim, no painel de clientes é apresentado um resumo consolidado da carteira, em tabela, cada cliente é resumido em suas principais características, para uma análise rápida e certeira.  
Mas para ainda mais detalhes, o botão "Me Mostre Mais!" permite abrir no detalhe cada cliente, com detalhes de imagens da garantia, Big Numbers do ativo, histórico e localização.

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

![image](https://github.com/user-attachments/assets/d7a22bcd-47d2-4a9b-940c-03b9186f7aa8)
![image (1)](https://github.com/user-attachments/assets/1ffcba04-57b2-4487-a0a7-cf516f97b813)
![image](https://github.com/user-attachments/assets/e379a2cb-cdc0-4fde-88c6-e8a2d95ecefb)
![image (2)](https://github.com/user-attachments/assets/8c8808b0-8429-4f19-903f-14c8c80e7bbd)
![image (3)](https://github.com/user-attachments/assets/d02b8ca6-f7c3-458c-a544-ca9fc92ce3a3)

Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

Contato
Para dúvidas ou sugestões, entre em contato: [murilorodriguesvieira@outlook.com]

