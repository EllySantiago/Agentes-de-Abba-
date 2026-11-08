# Agentes de Abba

Esteira de agentes de IA que transforma uma ideia de projeto em um esqueleto de software revisado, passando por estações como numa linha de produção. A inspiração é o jogo de fábrica de bolos que vinha no PC: cada fase entrega uma parte do bolo e, no fim, tudo vai para a caixa.

## A ideia

São 12 agentes divididos em 4 trios. Cada agente tem um arquivo `.md` com persona, regras de comportamento (SEMPRE e NUNCA), ponto cego conhecido, critérios de parada, entrada, saída e critérios de aprovação. O objetivo é automatizar as partes repetitivas do desenvolvimento (telas, rotas e tabelas que todo projeto tem) e ter uma revisão em várias camadas antes da entrega.

Os perfis dos agentes foram inspirados em tiragens de tarot, usadas como ponto de partida criativo para personalidade e pontos cegos.

## Os trios

1. **Desenvolvimento (a massa do bolo):** Hermes (backend), Vitrúvio (frontend), Mnemósine (banco de dados)
2. **Qualidade e Segurança (o recheio):** Cérbero (segurança), Hércules (qualidade e código limpo), Clio (logs e rastreabilidade)
3. **Testes (o forno):** Galileu (testes de unidade e integração), Atlas (carga), Loki (casos de borda)
4. **Revisão e Entrega (a caixa):** Hamurabi (requisitos acadêmicos), Champollion (documentação), Noé (empacotamento final)

## Como deve funcionar

- Rodada 1: os agentes de cada trio debatem e geram um relatório com base teórica e regras de negócio, que uma pessoa revisa e repassa ao trio seguinte.
- Rodada 2: criação do protótipo com as regras revisadas.
- Cada agente tem critérios de parada verificáveis por código, para a esteira não ficar em loop.

## Estrutura do repositório

- `agentes/`: uma ficha por agente (rascunho v0.1)

## Status

Em construção. As fichas são rascunhos e ainda não há código de orquestração. Um manual detalhado virá depois.
