# Portfólio de automações

Projetos que desenvolvi na área de operações e backoffice financeiro, para reduzir trabalho manual em conciliação, cobrança e gestão de documentos. O código não está aqui porque pertence à empresa. Este repositório descreve o que cada projeto faz.

## Portal interno
Portal web para a equipe registrar ideias e solicitações de melhoria, acompanhar o status de cada uma, publicar comunicados e acessar os dashboards. Tem perfis de acesso e uma trilha de aprendizado em Python.

Tecnologias: Python, Flask, SQLite, HTML, CSS, JavaScript.

## Pipelines e dashboards
- **Conciliação de repasses:** rotina diária que busca dados em uma API externa, cruza com o banco interno e gera um dashboard e um resumo para revisão.
- **Dashboard de conciliação:** compara valores esperados e recebidos por mês e por parceiro, e gera um boletim periódico.
- **Dashboard de documentos:** acompanha a situação de contratos e atendimentos.
- **Liquidação antecipada:** conciliação diária que classifica os casos por regras e prepara o arquivo de entrada para um robô de baixa.
- **Painel de melhorias:** mostra as horas economizadas por área e as automações em andamento.

## Robôs e ferramentas
- Download automático de arquivos de um servidor externo, com aviso quando chegam arquivos novos
- Consultas automatizadas em portais e sistemas (curva de parcelas, valor presente, garantias, propostas, empréstimos)
- Busca e download de documentos em lote
- Baixa de parcelas e estorno de movimentações
- Alteração de dados em contratos
- Reserva de margem
- Digitação automática de contratos
- Extração de campos de PDF para planilha
- Validação de contratos em lote
- Unificação de planilhas

## Ferramentas
Python (pandas, Playwright, openpyxl, pdfplumber), SQL, Excel VBA, PowerShell, Flask, HTML, CSS, JavaScript.
