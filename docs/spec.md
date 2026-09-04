🛠️ Especificação Técnica (Tech Spec) - Digital Gardens Logbook

Este documento descreve o modelo de dados da aplicação Digital Gardens Logbook, responsável pelo gerenciamento de usuários, anotações pessoais e publicações compartilhadas na Área de Convivência.

O sistema permitirá que cada usuário possua sua própria conta e crie anotações contendo data, título, conteúdo e configuração de privacidade. As anotações poderão ser mantidas privadas ou compartilhadas publicamente com outros usuários através da Área de Convivência.

1. Modelo de Dados (Diagrama ER)

Abaixo está o Diagrama Entidade-Relacionamento (DER) que representa a estrutura do Digital Gardens Logbook.

erDiagram
    USUARIO ||--o{ ANOTACAO : "possui"

    USUARIO {
        integer id PK "Identificador único do usuário"
        string nome "Nome ou apelido do usuário"
        string email "Endereço de e-mail"
        string senha "Credencial de acesso"
    }

    ANOTACAO {
        integer id PK "Identificador único da anotação"
        integer usuarioId FK "Referência ao autor da anotação"
        date data "Data da anotação"
        string titulo "Título da anotação"
        string conteudo "Conteúdo da anotação"
        string privacidade "Status de privacidade"
    }
2. Dicionário de Dados
Usuário

Responsável por armazenar os dados necessários para identificação e autenticação dos usuários do sistema.

id: Identificador único do usuário.
nome: Nome ou apelido utilizado pelo usuário.
email: Endereço de e-mail utilizado para identificação e login.
senha: Credencial utilizada para autenticação do usuário.

O sistema permitirá que um visitante realize seu cadastro e, posteriormente, utilize suas credenciais para acessar as funcionalidades privadas da plataforma.

Anotação

Responsável por representar um registro criado por um usuário no diário digital.

Cada anotação será vinculada ao usuário que a criou e poderá ser mantida privada ou compartilhada na Área de Convivência.

id: Identificador único da anotação.
usuarioId: Identificador do usuário responsável pela anotação.
data: Data em que a anotação foi registrada.
titulo: Título utilizado para identificar a anotação.
conteudo: Texto contendo os pensamentos, experiências ou acontecimentos registrados.
privacidade: Define se a anotação é privada ou pública.
Exemplo

Uma anotação cadastrada no sistema poderá possuir os seguintes dados:

{
    "id": "1",
    "usuarioId": "5",
    "data": "2026-09-04",
    "titulo": "Um dia especial",
    "conteudo": "Hoje foi um dia importante para mim...",
    "privacidade": "publica"
}

Quando a anotação possuir o status privada, ela ficará disponível somente para o próprio usuário.

Quando possuir o status publica, ela poderá ser exibida na Área de Convivência, permitindo que outros usuários visualizem o título, conteúdo, autor e data da publicação.

3. Regras de Dados

O relacionamento entre as entidades será definido da seguinte maneira:

Um usuário pode possuir várias anotações.
Cada anotação pertence a um único usuário.
Uma anotação pode possuir apenas um status de privacidade por vez.
Anotações privadas não devem aparecer na Área de Convivência.
Anotações públicas podem ser visualizadas por outros usuários.
O autor pode alterar posteriormente a privacidade de uma anotação.
Quando uma anotação pública for alterada para privada, ela deverá deixar de aparecer na Área de Convivência.
4. Funcionalidades Relacionadas aos Dados

O sistema deverá permitir:

Cadastro de novos usuários;
Login e controle de acesso;
Criação de anotações;
Visualização das próprias anotações;
Visualização de uma anotação específica;
Edição de anotações;
Exclusão de anotações;
Definição de anotações como públicas ou privadas;
Alteração da privacidade das anotações;
Publicação de anotações na Área de Convivência;
Visualização das publicações compartilhadas por outros usuários.
5. Versões das Tecnologias
HTML5
CSS3
JavaScript
Bootstrap
jQuery
Node.js
NPM
Git
GitHub
Tecnologias ainda não definidas
Back-end: a definir.
Banco de dados: a definir.
API fake: a definir.
API pública: a definir.
Plugin jQuery: a definir.
