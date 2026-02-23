# 🧠 Case Mirante – IA Aplicada ao Agronegócio (Precificação Preditiva)
### Protótipo funcional + Discovery + Arquitetura de Solução

Este repositório contém a solução desenvolvida para o **Case de Solution Designer da Mirante**, cujo desafio consiste em conceber e tangibilizar uma ferramenta de **precificação preditiva** para apoiar compradores de leite cru na indústria de laticínios.

A entrega combina **descoberta de negócio**, **arquitetura lógica**, **simulação de IA no front-end** e um **protótipo funcional em HTML/CSS/JS**, conforme solicitado no case.

---

## 🚜 1. Contexto do Desafio

Um grande player do setor de laticínios enfrenta dificuldades para prever o preço do leite cru devido à alta volatilidade do mercado.  
Hoje, as decisões de compra são tomadas com base apenas no **histórico de preços**, ignorando fatores externos que influenciam o preço futuro.

A solução proposta busca:

- correlacionar múltiplos fatores externos  
- gerar previsões simples e explicáveis  
- oferecer recomendações de compra  
- simular cenários  
- aumentar a confiança do comprador  

---

## 🎯 2. Objetivo da Solução

Construir um **protótipo funcional** que simule um “copiloto de decisão” para o comprador, correlacionando quatro pilares:

1. **Político**  
2. **Econômico**  
3. **Climático**  
4. **Agropecuário**

A inteligência é **simulada no front-end**, reagindo às interações do usuário.

---

## 🧩 3. Arquitetura da Solução

### 🔹 Simplicidade técnica  
A solução utiliza apenas:

- HTML  
- CSS  
- JavaScript puro  

Sem backend, sem frameworks e sem dependências externas.

### 🔹 IA Simulada (Regras de Negócio)

A lógica preditiva de preço é construída com base na performance estatítica mas, o Insight IA trabalha em combinação de regras simples:

```js
🟢 Preço baixo (≤ 2,39):
Oportunidade máxima (preço baixo + troca favorável)
Oportunidade de compra (preço baixo + troca saudável)
Atenção (preço baixo mas troca crítica)
Cautela (preço baixo mas múltiplos custos altos)
Oportunidade de estoque (caso geral)

🔴🟠 Preço alto (≥ 2,80):
Alerta crítico (3+ variáveis em alta simultânea)
Pressão de custos (dólar + ração)
Inflação + câmbio (IPCA + dólar)
Alta + produtor em crise (troca crítica)
Logística pressionada (diesel alto)
Sinal de alta (caso geral)

🟢🟡 Preço normal (2,40–2,79):
Equilíbrio favorável (troca ótima + custos controlados)
Estabilidade frágil (troca crítica + custos altos)
Atenção — custos em alta
Estabilidade / Normalidade

## 🚀 Acesse o Protótipo Funcional

<p align="left">
  <a href="https://casemirante.netlify.app/" target="_blank">
    <img src="https://img.shields.io/badge/Acessar_Protótipo-00C853?style=for-the-badge&logo=google-chrome&logoColor=white" />
  </a>
</p>
