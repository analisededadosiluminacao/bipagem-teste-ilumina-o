# Bipagem de Teste Driver — Zagonel

Protótipo funcional (HTML/JavaScript puro, sem servidor) para registro de testes de driver e montagem de luminárias (unidade **Iluminação**) e teste de componentes (unidade **Eletrônica**) da Zagonel.

## Como usar

Basta abrir `index.html` em qualquer navegador — funciona 100% offline, inclusive publicado aqui via GitHub Pages. Não precisa de instalação nem de servidor.

## Funcionalidades principais

- **Bipagem de teste** por unidade, com leitura de código de série e confirmação automática de peças OK
- **Conserto**: fila de defeitos, causa raiz, cronômetro, requisição de driver, reteste obrigatório antes de aprovar a peça
- **Rastreabilidade cruzada** entre Iluminação e Eletrônica (componentes apontados como causa, reincidência)
- **Dashboard** de indicadores com filtro por unidade, linha e data
- **Certificado de Aprovação** (exclusivo Iluminação): elegibilidade automática por OP, justificativa de OP parada
- **Relatório Mensal** com gráficos exportáveis como imagem, pronto pra impressão/e-mail

## Armazenamento de dados

Os dados ficam salvos localmente no navegador de cada dispositivo (IndexedDB) — nada é enviado para nenhum servidor. Para consolidar dados de tablets diferentes, use a exportação/importação de CSV disponível em Configurações.

## Status

Protótipo em desenvolvimento ativo, validado em campo. A integração definitiva ao App Zagonel (Vue 2) depende dos pontos listados na "Solicitação de Integração" (documento interno).
