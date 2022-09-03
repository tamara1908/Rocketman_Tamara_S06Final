## Descrevendo bug 
Cadastra um produto com apenas um caracter, exemplo: (".", "5", "~"), e não deveria;

### Etapas para reproduzir o comportamento:

1. De acordo com a Documentação, criamos uma collection com verbo POST;
2. Em seguida, vamos copiar um body de cadastro de produto conforme a documentação da API, com o nome produto propositalmente errado como citado a cima;
3. Na aba SEND somente dar um clique;

### Comportamento esperado:
Ele nos responde com status code 201 Created, porém não deveria; 
No conceito deveria nos responder com status code 400 Bad Request e não cadastrar;

### Print Tela:
![image](https://user-images.githubusercontent.com/102266911/188257322-6ea8a40f-85cd-4773-a226-7b15def249e4.png)

**Desktop:**
 - Browser: Chrome;
 - Versão: 21H2;
