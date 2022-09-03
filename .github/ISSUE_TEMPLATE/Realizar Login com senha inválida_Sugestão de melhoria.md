**Solicitação de melhoria**
 | :---------------------------: |
Realizar Login com senha inválida, mudar resposta;

#### Ao realizar Login com senha inválida, de acordo com a API ele deve responder status code 400, Bad Request, porém realizando o teste percebe-se que o status code retornado é 401, Unauthorized, o que faz total sentido pois se está errado a senha não deve autorizar;
A sugestão seria, nos devolver o status code 401 Unauthorized ou mudar na documentação e adicionar este código como passível de resposta;

**Tela Printada com a sugestão:**
![image](https://user-images.githubusercontent.com/102266911/188258620-9d1c1d4b-8c4a-431b-988f-fbe7348034f3.png)
