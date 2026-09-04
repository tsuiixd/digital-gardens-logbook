# 📄 Product Requirements Document (PRD) - Digital Gardens Logbook

## 1. Visão Geral e Objetivo

Registrar pensamentos, experiências e acontecimentos do dia a dia é uma forma de organizar ideias, refletir sobre experiências pessoais e acompanhar momentos importantes ao longo do tempo.

Entretanto, o registro de um diário tradicional geralmente é uma atividade individual e privada, o que limita a possibilidade de compartilhar experiências, reflexões e aprendizados com outras pessoas.

Diante desse cenário, o projeto **Digital Gardens Logbook** tem como objetivo criar uma plataforma de diário digital que permita aos usuários registrar suas experiências e pensamentos de maneira organizada, além de oferecer um espaço para interação e compartilhamento entre os integrantes da comunidade.

O sistema permite que cada usuário possua sua própria conta e crie anotações contendo uma data, título e conteúdo. Essas anotações podem ser mantidas de forma privada ou compartilhadas na **Área de Convivência**, permitindo que outros usuários tenham acesso aos textos publicados.

A plataforma busca unir a experiência de um diário pessoal com a ideia de uma comunidade digital, na qual os usuários podem compartilhar reflexões e conhecer diferentes experiências através dos textos publicados por outras pessoas.

O projeto foi pensado para pessoas que desejam manter um registro digital de suas experiências e, ao mesmo tempo, participar de um ambiente onde possam compartilhar pensamentos de maneira simples e organizada.

---

## 2. Atores do Sistema

* **Visitante:** Usuário que ainda não possui uma conta e pode acessar as páginas públicas do sistema, conhecer a proposta da plataforma e realizar seu cadastro.

* **Usuário:** Pessoa que possui uma conta registrada no sistema e pode criar, visualizar e gerenciar suas próprias anotações, além de acessar a Área de Convivência e visualizar textos compartilhados por outros usuários.

* **Autor:** Usuário responsável por uma determinada anotação publicada no sistema. Pode definir se sua anotação será privada ou compartilhada na Área de Convivência.

> Um mesmo usuário pode exercer simultaneamente os papéis de **Usuário** e **Autor**, dependendo da ação realizada no sistema.

---

## 3. Histórias de Usuário e Escopo

Abaixo estão as funcionalidades descritas sob a perspectiva dos usuários finais do Digital Gardens Logbook.

### 🔐 Épico 1: Autenticação e Acesso

* **US01 - Cadastro:** Como um visitante, quero criar uma conta no Digital Gardens Logbook, para poder utilizar os recursos de diário da plataforma.

  * *Critérios de Aceitação:* O sistema deve solicitar os dados necessários para criação da conta e validar as informações antes de concluir o cadastro.

* **US02 - Login:** Como um usuário cadastrado, quero inserir minhas credenciais para acessar minha conta no Digital Gardens Logbook.

  * *Critérios de Aceitação:* O sistema deve validar as credenciais informadas antes de permitir o acesso à conta.

* **US03 - Controle de acesso:** Como um usuário, quero que as funcionalidades relacionadas às minhas anotações estejam disponíveis somente após realizar o login, para manter meus registros protegidos.

* **US04 - Encerramento da sessão:** Como um usuário, quero sair da minha conta, para impedir que outras pessoas utilizem minha sessão em um dispositivo compartilhado.

---

### 📔 Épico 2: Diário e Anotações

* **US05 - Criar anotação:** Como um usuário, quero criar uma nova anotação, para registrar meus pensamentos, experiências e acontecimentos.

  * *Critérios de Aceitação:* O sistema deve permitir informar a data, o título e o conteúdo da anotação antes de salvá-la.

* **US06 - Informações da anotação:** Como um usuário, quero registrar a data, título e conteúdo de uma anotação, para organizar melhor meus registros pessoais.

* **US07 - Visualizar minhas anotações:** Como um usuário, quero visualizar minhas anotações, para consultar os registros que já realizei.

* **US08 - Visualizar uma anotação:** Como um usuário, quero abrir uma anotação específica, para ler seu conteúdo completo.

* **US09 - Editar anotação:** Como um usuário, quero editar uma anotação existente, para corrigir informações ou atualizar seu conteúdo.

* **US10 - Excluir anotação:** Como um usuário, quero excluir uma anotação, para remover registros que não desejo mais manter.

  * *Critérios de Aceitação:* O sistema deve solicitar uma confirmação antes de excluir permanentemente uma anotação.

---

### 🔒 Épico 3: Privacidade das Anotações

* **US11 - Anotação privada:** Como um usuário, quero manter uma anotação privada, para registrar pensamentos que não desejo compartilhar com outras pessoas.

  * *Critérios de Aceitação:* Anotações definidas como privadas não devem aparecer na Área de Convivência.

* **US12 - Compartilhamento de anotação:** Como um usuário, quero tornar uma anotação pública, para compartilhar meu texto com outros integrantes da comunidade.

  * *Critérios de Aceitação:* Uma anotação marcada como pública deve estar disponível para visualização na Área de Convivência.

* **US13 - Alteração de privacidade:** Como um usuário, quero alterar o status de privacidade de uma anotação, para decidir posteriormente se desejo mantê-la privada ou compartilhá-la.

---

### 🌱 Épico 4: Área de Convivência

* **US14 - Acessar Área de Convivência:** Como um usuário, quero acessar a Área de Convivência, para conhecer os textos compartilhados por outros usuários.

* **US15 - Visualizar publicações:** Como um usuário, quero visualizar as anotações públicas da comunidade em formato de feed, para acompanhar as experiências e reflexões compartilhadas.

* **US16 - Identificação do autor:** Como um usuário, quero saber quem publicou uma anotação, para identificar o autor do texto que estou lendo.

* **US17 - Visualização da data:** Como um usuário, quero visualizar a data de publicação ou registro de uma anotação, para compreender quando aquela experiência foi registrada.

* **US18 - Ler publicação:** Como um usuário, quero visualizar o título e o conteúdo de uma publicação, para conhecer a experiência ou reflexão compartilhada por outro usuário.

* **US19 - Carregamento de publicações:** Como um usuário, quero carregar novas publicações na Área de Convivência, para continuar visualizando conteúdos compartilhados pela comunidade.

---

### ✍️ Épico 5: Gerenciamento das Publicações

* **US20 - Publicar anotação:** Como um usuário, quero publicar uma anotação na Área de Convivência, para compartilhar meu texto com outros usuários.

* **US21 - Retirar publicação:** Como um autor, quero deixar uma anotação pública novamente privada, para interromper seu compartilhamento com a comunidade.

  * *Critérios de Aceitação:* Após alterar o status para privado, a anotação não deve mais aparecer na Área de Convivência.

* **US22 - Gerenciar minhas publicações:** Como um autor, quero controlar quais das minhas anotações estão disponíveis publicamente, para decidir quais conteúdos desejo compartilhar.

---

### 📝 Épico 6: Nova Anotação

* **US23 - Acessar formulário de anotação:** Como um usuário, quero acessar uma página específica para criar uma nova anotação, para registrar meus pensamentos de maneira organizada.

* **US24 - Informar data:** Como um usuário, quero informar a data da minha anotação, para manter meus registros organizados cronologicamente.

* **US25 - Informar título:** Como um usuário, quero adicionar um título à anotação, para identificar rapidamente o assunto registrado.

* **US26 - Escrever conteúdo:** Como um usuário, quero escrever o conteúdo da minha anotação, para registrar minhas experiências e pensamentos.

* **US27 - Definir privacidade:** Como um usuário, quero escolher se minha anotação será pública ou privada, para controlar quem poderá visualizar meu texto.

* **US28 - Salvar anotação:** Como um usuário, quero salvar minha anotação, para manter meu registro disponível no diário.

---

### 🌿 Épico 7: Experiência e Navegação

* **US29 - Página inicial:** Como um visitante, quero visualizar uma página inicial que apresente o Digital Gardens Logbook, para entender a proposta da plataforma antes de criar uma conta.

* **US30 - Navegação entre páginas:** Como um usuário, quero navegar facilmente entre o diário e a Área de Convivência, para acessar as diferentes funcionalidades da plataforma.

* **US31 - Acesso ao cadastro:** Como um visitante, quero encontrar uma opção para criar minha conta na página inicial, para começar a utilizar o sistema.

* **US32 - Acesso ao login:** Como um visitante ou usuário, quero encontrar uma opção para realizar login, para acessar minha conta.

* **US33 - Interface responsiva:** Como um usuário, quero utilizar o sistema em diferentes tamanhos de tela, para acessar minhas anotações tanto em dispositivos móveis quanto em computadores.

---

## 4. Escopo do Projeto

O **Digital Gardens Logbook** terá como funcionalidades principais:

* Cadastro de novos usuários;
* Login e controle de acesso;
* Criação de anotações pessoais;
* Registro de data, título e conteúdo;
* Visualização das próprias anotações;
* Edição de anotações;
* Exclusão de anotações;
* Definição de anotações como públicas ou privadas;
* Compartilhamento de anotações na Área de Convivência;
* Visualização das publicações de outros usuários;
* Identificação dos autores das publicações;
* Navegação entre o diário pessoal e a Área de Convivência;
* Interface responsiva para dispositivos mobile e desktop.

---

## 5. Fora do Escopo

Para manter o projeto dentro do escopo definido, algumas funcionalidades não fazem parte da versão inicial da aplicação:

* Sistema de mensagens privadas entre usuários;
* Sistema de seguidores ou amizades;
* Curtidas e reações nas publicações;
* Comentários nas anotações;
* Notificações em tempo real;
* Aplicativo nativo para Android ou iOS;
* Compartilhamento automático das publicações em redes sociais;
* Sistema avançado de edição de texto;
* Integração com serviços externos de armazenamento de imagens.

Essas funcionalidades podem ser consideradas futuramente, caso o projeto seja expandido.

---

## 6. Fluxo Principal do Sistema

O funcionamento básico do Digital Gardens Logbook pode ser representado pelo seguinte fluxo:

1. O visitante acessa a página inicial do Digital Gardens Logbook.
2. O visitante pode criar uma conta ou acessar uma conta existente.
3. Após realizar o login, o usuário pode acessar as funcionalidades privadas da plataforma.
4. O usuário pode criar uma nova anotação informando data, título e conteúdo.
5. Ao criar a anotação, o usuário pode definir se ela será **privada** ou **pública**.
6. Anotações privadas ficam disponíveis somente para o próprio usuário.
7. Anotações públicas são disponibilizadas na **Área de Convivência**.
8. Outros usuários podem acessar a Área de Convivência e visualizar os textos compartilhados.
9. O autor pode posteriormente editar sua anotação ou alterar sua configuração de privacidade.
10. Caso uma publicação seja alterada para privada, ela deixa de aparecer na Área de Convivência.

---

## 7. Protótipo e Interface

O protótipo inicial do **Digital Gardens Logbook** foi desenvolvido utilizando o **Stitch**, sendo utilizado como referência visual para a implementação da aplicação.

O protótipo contempla as principais telas do sistema:

* **Login:** Tela destinada ao acesso de usuários cadastrados.
* **Cadastro:** Tela para criação de uma nova conta.
* **Página Inicial:** Apresentação da proposta do Digital Gardens Logbook e acesso às principais funcionalidades.
* **Nova Anotação:** Formulário utilizado para criação de novos registros no diário.
* **Área de Convivência:** Feed com as anotações públicas compartilhadas pelos usuários.

A interface foi planejada para apresentar uma identidade visual inspirada em elementos naturais e na ideia de um **jardim digital**, representando o crescimento e desenvolvimento das ideias registradas pelos usuários.

---

## 8. Considerações Finais

O **Digital Gardens Logbook** tem como principal objetivo proporcionar um espaço digital para que pessoas possam registrar suas experiências e pensamentos, mantendo seus próprios diários e, quando desejarem, compartilhando parte desses registros com uma comunidade.

A combinação entre **diário pessoal** e **Área de Convivência** permite que a plataforma tenha tanto um caráter individual quanto social. O usuário mantém controle sobre seus registros e decide quais experiências deseja tornar públicas.

Dessa forma, o projeto busca criar um ambiente simples, organizado e agradável para **registrar pensamentos, cultivar ideias e compartilhar experiências**.
