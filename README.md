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
[Portal Web] → [Bot Node.js (login + download)] → [Estrutura de pastas local] → [Power BI (importação + transformação + visualização)]

yaml
Copiar
Editar

---

## Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- [Power BI Desktop](https://powerbi.microsoft.com/)
- Power Query (M Language)
- JavaScript (ES6+)
- Git & GitHub

---

## Resultados Alcançados

- Redução de 90% no tempo gasto com atualização manual de dados.
- Minimização de erros causados por processos manuais.
- Dashboards dinâmicos e atualizados diariamente.
- Facilidade na análise de indicadores financeiros para decisões estratégicas.

---

## Como Rodar o Projeto

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-projeto-bidata.git
   cd seu-projeto-bidata
Instale as dependências do Node.js:

bash
Copiar
Editar
npm install
Configure suas credenciais no arquivo .env (copie do .env.example):

ini
Copiar
Editar
USERNAME=seu_usuario
PASSWORD=sua_senha
Execute o bot para baixar as planilhas:

bash
Copiar
Editar
node src/bot.js
Abra o arquivo Power BI (data-model/SeuDashboard.pbix) e atualize as conexões para carregar os dados baixados.

Estrutura do Repositório
bash
Copiar
Editar
/
├── src/               # Código do bot Node.js
├── data-model/        # Arquivos Power BI (.pbix) e dicionários de dados
├── documentation/     # Diagramas, fluxogramas e documentação extra
├── assets/            # Imagens e recursos visuais
├── .env.example       # Modelo de arquivo de ambiente para credenciais
├── .gitignore         # Arquivos ignorados pelo Git
├── LICENSE            # Licença do projeto
└── README.md          # Este arquivo
Imagens

Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

Contato
Para dúvidas ou sugestões, entre em contato: [seu-email@exemplo.com]

yaml
Copiar
Editar

---

Quer que eu te ajude a criar o `.env.example` e algum código inicial para o bot?
