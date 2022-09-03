**Solicitação de melhoria**
 | :---------------------------: |
Buscar ID inexistente ou com variável de ID vazia;
GET sem ID

#### Ao buscar por Produto,Usuário ou Carrinho inexistentes ou com variável de ID vazia, ele nos devolve a resposta OK com status code 200, e lista todos os usuários/produtos/carrinhos que estão cadastrados no banco de dados.

A sugestão seria, nos devolver o status code 400 Bad Request e no body estar descrito: "não foi possível encontrar" ou "ID inexistente";


**Contexto adicional**

**Tela Printada com a sugestão:**

![image](https://user-images.githubusercontent.com/102266911/188256210-c11b33b4-90eb-4e86-a232-520652bd37f3.png)
