## Descrevendo bug 
Cadastra um usuário com senha fraca, apenas um caracter, exemplo: (".", "5", "~"), e não deveria;

### Etapas para reproduzir o comportamento:

1. De acordo com a Documentação, criamos uma collection com verbo POST;
2. Em seguida, vamos copiar um body de cadastro de usuário conforme a documentação da API, com a senha propositalmente errada como citado a cima;
3. Na aba SEND somente dar um clique;

### Comportamento esperado:
Ele nos responde com status code 201 Created, porém não deveria; 
No conceito deveria nos responder com status code 400 Bad Request e não cadastrar;

### Print Tela:
![image](https://user-images.githubusercontent.com/102266911/188257588-d974054c-1e59-43eb-94d3-0470c1bc2f00.png)

**Desktop:**
 - Browser: Chrome;
 - Versão: 21H2;
