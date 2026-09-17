# 🌿 Digital Gardens Logbook

Sistema web desenvolvido para funcionar como um **diário de bordo digital**, permitindo que cada usuário registre pensamentos, experiências, acontecimentos e reflexões por meio de anotações pessoais.

O **Digital Gardens Logbook** também possui uma **Área de Convivência**, funcionando como um feed onde os usuários podem compartilhar seus textos com a comunidade. Dessa forma, além de manter seus próprios registros, cada pessoa pode conhecer as experiências e reflexões de outros usuários.

O projeto foi pensado para proporcionar um espaço simples e agradável para **escrever, organizar e compartilhar experiências**, unindo a proposta de um diário pessoal com uma área de interação entre usuários.

## 👨‍💻 Autor

**Leandro Rangel Gadens Zevierzicoski**

## 📚 Documentação do Projeto

Para entender as regras de negócio, o escopo e a arquitetura técnica da aplicação, consulte os documentos abaixo:

📄 **[Product Requirements Document (PRD)](./docs/prd.md)** - Visão geral, atores e histórias de usuário.

🛠️ **[Especificação Técnica (Tech Spec)](./docs/architecture.md)** - Arquitetura técnica e estrutura do projeto.

🎨 **[Design (Protótipo da página](https://stitch.withgoogle.com/projects/16391617503745330697)** - Telas interativas da aplicação.

🌐 **Site em Produção** - GitHub Pages  
**Pendente**

## 💻 Tecnologias e Dependências

**Stitch:** Utilizado para a criação do protótipo e esboço das interfaces da aplicação, permitindo visualizar as principais telas e fluxos antes da implementação.

**Framework CSS - Bootstrap v5.3.8:** escolhido pelo sistema de grid de 12 colunas com breakpoints prontos, que atende diretamente ao requisito de layout responsivo mobile e desktop. Traz os componentes já previstos no protótipo (navbar, cards, formulários e modais) e inclui o JavaScript dos componentes interativos no próprio bundle, sem depender de bibliotecas externas como o jQuery. O repositório oficial é ativo e mantido, e a licença MIT é compatível com projetos de código aberto.

**API Pública — Open-Meteo:** utilizada para buscar as condições climáticas do dia e associá-las às anotações do usuário, enriquecendo cada registro com o contexto do momento em que foi escrito. Foi escolhida por ser gratuita e não exigir chave de autenticação, o que simplifica o consumo no front-end; por ter CORS habilitado, permitindo requisições diretas do navegador sem proxy; e por ser um serviço ativo, com documentação clara e histórico de disponibilidade confiável.

---

# 📖 Checklist | Indicadores de Desempenho (ID) dos Resultados de Aprendizagem (RA)

## RA1 - Utilizar Frameworks CSS para estilização de elementos HTML e criação de layouts responsivos

- [x] **ID 01** - Prototipa interfaces adaptáveis para no mínimo os tamanhos de tela **mobile e desktop**, usando ferramentas de design tradicionais (Figma, Quant UX ou Sketch) ou IA (Stitch).
- [ ] **ID 02** - Implementa layout responsivo com **Framework CSS** (Bootstrap, Materialize) usando **Flexbox ou Grid** do próprio framework.
- [ ] **ID 03** - Implementa layout responsivo com **CSS puro**, usando Flexbox ou Grid Layout.
- [ ] **ID 04** - Utiliza **componentes prontos** de um Framework CSS (ex.: card, button) e componentes JavaScript do framework (ex.: modal, carousel).
- [ ] **ID 05** - Cria layout fluido usando **unidades relativas** (vw, vh, %, em, rem) no lugar de unidades fixas (px).
- [ ] **ID 06** - Aplica um **Design System consistente** (cores, tipografia, padrões de componentes) em toda a aplicação.
- [ ] **ID 07** - Utiliza **Sass (SCSS)** com ou sem framework, aplicando variáveis, mixins e funções para modularizar o código.
- [ ] **ID 08** - Aplica **tipografia responsiva** (media queries mobile first) ou **tipografia fluida** (função `clamp()` + unidades relativas).
- [ ] **ID 09** - Aplica técnicas de responsividade de imagens usando **CSS** (`object-fit`, containers com unidades relativas).
- [ ] **ID 10** - Otimiza imagens usando formatos modernos (**WebP**) e carregamento adaptativo (`srcset`, `picture` ou parâmetros do Cloudinary).

## RA2 - Realizar tratamento de formulários e aplicar validações customizadas no lado cliente

- [ ] **ID 11** - Implementa **validação HTML nativa** (campos obrigatórios, tipos, limites de caracteres) com mensagens de erro/sucesso no lado cliente.
- [ ] **ID 12** - Aplica **expressões regulares (REGEX)** para validações customizadas (e-mail, telefone, datas, etc.).
- [ ] **ID 13** - Utiliza elementos de seleção em formulários (**checkbox, radio, select**) para coleta de dados.
- [ ] **ID 14** - Implementa leitura e escrita no **Web Storage** (`localStorage`/`sessionStorage`) para persistir dados localmente.

## RA3 - Aplicar ferramentas para otimização do processo de desenvolvimento web

- [x] **ID 15** - Configura ambiente com **Node.js e NPM** para gerenciamento de pacotes e dependências.
- [x] **ID 16** - Utiliza **boas práticas de versionamento** no Git/GitHub (branch `main` ou branches específicos, uso de `.gitignore`).
- [x] **ID 17** - Mantém um **README.md** padronizado, conforme template da disciplina, com checklist preenchido.
- [ ] **ID 18** - Organiza arquivos do projeto de forma modular, seguindo padrão de exemplo fornecido.
- [x] **ID 19** - Configura **linters e formatadores** (ESLint, Prettier) para manter qualidade e padronização do código.

## RA4 - Aplicar bibliotecas de funções e componentes em JavaScript para aprimorar a interatividade de páginas web

- [ ] **ID 20** - Utiliza **jQuery** para manipulação do DOM e interatividade (eventos, animações, manipulação de elementos).
- [ ] **ID 21** - Integra e configura um **plugin jQuery** relevante (ex.: jQuery Mask Plugin) ou outra biblioteca de funções.

## RA5 - Efetuar requisições assíncronas para uma API fake e APIs públicas, permitindo a obtenção e manipulação de dados dinamicamente

- [ ] **ID 24** - Realiza requisições assíncronas para **APIs públicas reais** (OpenWeather, ViaCEP etc.), exibindo os dados e tratando erros.
- [ ] **ID 22** - Realiza requisições assíncronas para uma **API fake** (ex.: JSON Server) para persistir dados de um formulário.
- [ ] **ID 23** - Realiza requisições assíncronas para uma **API fake** para exibir dados na página.

---

**Digital Gardens Logbook — Registre seus pensamentos, compartilhe experiências.**
