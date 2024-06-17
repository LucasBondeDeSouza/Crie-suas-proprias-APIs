# O que torna uma API RESTful?

## 1 - Usar Métodos HTTP
A regra número um para tornar uma API RESTful é que ela use métodos HTTP padrão.

### Exemplo Prático
Considere uma API de gerenciamento de usuários que segue os princípios RESTful:

- **GET /usuarios**: Retorna uma lista de usuários.
- **GET /usuarios/1**: Retorna os detalhes do usuário com ID 1.
- **POST /usuarios**: Cria um novo usuário.
- **PUT /usuarios/1**: Atualiza as informações do usuário com ID 1.
- **DELETE /usuarios/1**: Remove o usuário com ID 1.

## 2 - Ter um formato de dados padrão
A próxima regra é que ele provavelmente deve ter um formato de dados padrão com o qual responderá. Isso significa algo como o formato JSON, a Notação de Objetos JavaScript, ou algo com XML.

## 3 - Client-Server (Cliente-Servidor)
A próxima regra é que clientes e servidores em APIs RESTful são completamente separados. Eles não estão no mesmo sistema ou no mesmo arquivo e podem enviar mensagens uns aos outros por meio de uma rede. Para fazer solicitações e também para receber respostas.