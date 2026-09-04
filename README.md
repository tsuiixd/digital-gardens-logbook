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

🌐 **Site em Produção** - GitHub Pages  
**Pendente**

## 💻 Tecnologias e Dependências

**Framework CSS - Bootstrap:** O Bootstrap será utilizado como framework CSS para a construção da interface, oferecendo responsividade, componentes prontos, suporte a interações com JavaScript e uma estrutura consistente para o desenvolvimento das páginas.

**Stitch:** Utilizado para a criação do protótipo e esboço das interfaces da aplicação, permitindo visualizar as principais telas e fluxos antes da implementação.

---

# 📖 Checklist | Indicadores de Desempenho (ID) dos Resultados de Aprendizagem (RA)

## RA1 - Utilizar Frameworks CSS para estilização de elementos HTML e criação de layouts responsivos

- [ ] **ID 01** - Prototipa interfaces adaptáveis para no mínimo os tamanhos de tela **mobile e desktop**, usando ferramentas de design tradicionais (Figma, Quant UX ou Sketch) ou IA (Stitch).
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

- [ ] **ID 15** - Configura ambiente com **Node.js e NPM** para gerenciamento de pacotes e dependências.
- [ ] **ID 16** - Utiliza **boas práticas de versionamento** no Git/GitHub (branch `main` ou branches específicos, uso de `.gitignore`).
- [ ] **ID 17** - Mantém um **README.md** padronizado, conforme template da disciplina, com checklist preenchido.
- [ ] **ID 18** - Organiza arquivos do projeto de forma modular, seguindo padrão de exemplo fornecido.
- [ ] **ID 19** - Configura **linters e formatadores** (ESLint, Prettier) para manter qualidade e padronização do código.

## RA4 - Aplicar bibliotecas de funções e componentes em JavaScript para aprimorar a interatividade de páginas web

- [ ] **ID 20** - Utiliza **jQuery** para manipulação do DOM e interatividade (eventos, animações, manipulação de elementos).
- [ ] **ID 21** - Integra e configura um **plugin jQuery** relevante (ex.: jQuery Mask Plugin) ou outra biblioteca de funções.

## RA5 - Efetuar requisições assíncronas para uma API fake e APIs públicas, permitindo a obtenção e manipulação de dados dinamicamente

- [ ] **ID 24** - Realiza requisições assíncronas para **APIs públicas reais** (OpenWeather, ViaCEP etc.), exibindo os dados e tratando erros.
- [ ] **ID 22** - Realiza requisições assíncronas para uma **API fake** (ex.: JSON Server) para persistir dados de um formulário.
- [ ] **ID 23** - Realiza requisições assíncronas para uma **API fake** para exibir dados na página.

---

**Digital Gardens Logbook — Registre seus pensamentos, compartilhe experiências.**
