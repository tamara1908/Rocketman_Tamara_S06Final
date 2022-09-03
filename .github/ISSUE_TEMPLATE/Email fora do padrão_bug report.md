## Descrevendo bug 
Cadastra um usuário com email fora do padrão e senha de apenas um caracter, e acredito que não deveria, exemplo:
{
  "nome": "tamara",
  "email": "~ç@gq.br",
  "password": ".",
  "administrador":"false"
}

### Etapas para reproduzir o comportamento:

1. De acordo com a Documentação, criamos uma collection com verbo POST;
2. Em seguida, vamos copiar um body de cadastro de usuário conforme a documentação da API, com email e senha propositalmente errados como citado a cima;
3. Na aba SEND somente dar um clique;

### Comportamento esperado:
Ele nos responde com status code 201 Created, porém não deveria; 
No conceito deveria nos responder com status code 400 Bad Request e não cadastrar;

### Print Tela:

![image](https://user-images.githubusercontent.com/102266911/188257815-c0c46bda-b191-44a2-8fda-f702e70e87c7.png)

**Desktop:**
 - Browser: Chrome;
 - Versão: 21H2;
