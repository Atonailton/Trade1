# Entrerium - Robô de Análise Cripto

**Entrerium** é um robô simples e direto, feito em HTML + JavaScript, que une **análise técnica** (RSI e MACD) com **sentimento de mercado (Fear & Greed Index)**, exibindo **alertas automáticos de compra ou venda** com base nos dados mais recentes.

## Funcionalidades

- **Gráfico em tempo real** (TradingView)
- **Seleção de moeda** (BTC, ETH, DOGE)
- **Leitura de indicadores RSI e MACD** via API TAAPI.io
- **Leitura do Índice de Medo e Ganância** via API Alternative.me
- **Alertas automáticos de compra ou venda**
- Atualização automática a cada 30 segundos
- 100% responsivo e adaptado para mobile

---

## Tecnologias usadas

- HTML5 + JavaScript puro
- [TAAPI.io](https://taapi.io/) (RSI e MACD)
- [Alternative.me Fear & Greed API](https://alternative.me/crypto/fear-and-greed-index/)
- [TradingView Widget](https://www.tradingview.com/widget/)

---

## Como usar

1. Clone este repositório ou copie o código HTML.
2. Suba em um servidor (como [Vercel](https://vercel.com/)).
3. Altere sua **chave TAAPI.io** no código, se necessário:
   ```js
   const apiKey = "SUA_CHAVE_AQUI";
