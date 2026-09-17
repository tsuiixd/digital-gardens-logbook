# Especificação Técnica — Digital Gardens Logbook

## Stack e versões

| Tecnologia | Versão | Uso no projeto |
|---|---|---|
| HTML5 | — | Estrutura das páginas |
| CSS3 | — | Estilização customizada |
| JavaScript | ES6+ | Interatividade e requisições |
| Bootstrap | v5.3.8 | Framework CSS e componentes |
| jQuery | v3.7.1 | Manipulação do DOM (RA4) |
| Node.js | v22 LTS | Ambiente de desenvolvimento |
| NPM | v10 | Gerenciamento de dependências |
| Git / GitHub | — | Versionamento |
| Stitch | — | Prototipação das interfaces |

## API Pública

- **Nome:** Open-Meteo Forecast API
- **Versão:** v1
- **Base URL:** `https://api.open-meteo.com/v1/forecast`
- **Autenticação:** não requer chave
- **Formato de resposta:** JSON
- **Uso:** exibir a condição climática do dia na tela de nova anotação e
  associar esse dado ao registro criado.

## A definir

- API fake (JSON Server) — a definir na etapa de persistência
- Plugin jQuery — a definir (candidato: jQuery Mask Plugin, para o campo de data)

> O modelo de dados e as regras de negócio estão em [architecture.md](./architecture.md).
