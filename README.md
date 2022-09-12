 <p align="center">
 <b>
   <a href="https://www.canva.com/design/DAFG4psALec/aor6IQ209bu4kQg7rgEqoQ/view?utm_content=DAFG4psALec&utm_campaign=designshare&utm_medium=link&utm_source=homepage_design_menu">Plano de testes</a> |
   <a href="https://www.canva.com/design/DAFLI2vUmDc/-OVp_0-yoz1fB1t8xG-vtg/view?utm_content=DAFLI2vUmDc&utm_campaign=designshare&utm_medium=link&utm_source=homepage_design_menu">Mapa Mental Completo</a> |
   <a href="https://www.canva.com/design/DAFK6q65orM/s4MEUz1kCaDvcJu4V38ZUw/view?utm_content=DAFK6q65orM&utm_campaign=designshare&utm_medium=link&utm_source=homepage_design_menu">Lista de casos de teste</a> |
 </b>
</p> 


<div align="center"> 
  <img align="center" alt="sprint 06 sf" height="500" style="border-radius:500px;" src="https://user-images.githubusercontent.com/102266911/187699538-be961390-0ae5-46b0-985d-376893926e50.png">  
 </div>
    
<b><h2 align="center">☺️ Olá, sejam todos muito bem vindos(as)!</h2></b>

<b><h3 align="center">Este repositório foi criado para que seja desenvolvido o Projeto Final, a sprint 06.</h2></b>

<b><h2 align="left">🖥️ Ferramentas utilizadas:</h2></b>
![logos1](https://user-images.githubusercontent.com/102266911/187693409-e5ce6ad8-e206-4f70-8a8d-4d97e0eb1131.png)
 * Sistema GITBASH para versionamento de arquivos;
 * Plataforma e ferramentas GitHub;
 * Visual Studio Code;
 * Postman para testes;
 * Newman;
 * Xmind para realizar o mapa mental;
 * Canva para desenvolver o plano de testes e as animações;
 
<b><h2 align="left">🔗 Clonar este repositório:</h2></b>
1. No seu perfil do Github, navegue até a página principal deste <b> <a href="https://github.com/tamara1908/Rocketman_Tamara_S06Final">Repositório</a>  </b>
2. Ao lado(direito) de Adicionar Ficheiro, clique no botão verde com nome de código.

![image](https://user-images.githubusercontent.com/102266911/188284699-4fc48d45-282d-4f37-8d2d-464626a726fb.png)

3. Copie a URL para o repositório.
Para clonar o repositório usando HTTPS, em "HTTPS", clique no quadradinho de copia ao lado da URL, como descrito na imagem abaixo:

 ![image](https://user-images.githubusercontent.com/102266911/188284806-371bac2c-4d55-414a-88fe-c1a6ac6275ce.png)

4. Abra o Git Bash.

5. Altere o diretório de trabalho atual para o local em que deseja ter o diretório clonado.

6. Digite git clone (clonar git) e cole a URL que você copiou anteriormente.
```sh
$ git clone https://github.com/tamara1908/Rocketman_Tamara_S06Final#readme
Pressione Enter para criar seu clone local.
```
```sh
$ git clone https://github.com/tamara1908/Rocketman_Tamara_S06Final#readme
> Cloning into `Spoon-Knife`...
> remote: Contando objetos: 10, concluído.
> remote: Compactando objetos: 100% (8/8), concluído.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

<b><h2 align="left">😵‍💫 Solucionar problemas de erros de clonagem:</h2></b>
Ao clonar um repositório, é possível que você encontre alguns erros.

**Se você não conseguir clonar um repositório, verifique se:**
* Você consegue conectar-se usando HTTPS. 
* Para obter mais informações, consulte <b> <a href="https://docs.github.com/pt/repositories/creating-and-managing-repositories/troubleshooting-cloning-errors">"Erros de clonagem por meio de HTTPS".</a>  </b>
 
 
 <b><h2 align="left">🌵 Ambientes disponíveis :</h2></b>

<table align="left">
  <tr>
    <td align="left">Online em serverest.dev<br/><a href="#online"><img alt="Texto serverest.dev" src="https://user-images.githubusercontent.com/29241659/97096352-49b1b380-1641-11eb-9b0a-5bb72e1b3882.png" height="80"></a></td>
    <td align="left">Local com NPM<br/><br/><a href="#localmente-com-npm"><img alt="Logo do NPM" src="https://user-images.githubusercontent.com/29241659/97096283-4bc74280-1640-11eb-920a-1c145b0c39d4.png" height="60"></a></td>
  </tr>
</table>

<p align="left">
 <img alt="Print do ServeRest iniciado no terminal" src="https://user-images.githubusercontent.com/29241659/97097145-fa24b500-164b-11eb-9a1f-f9cae275ec98.png" height="124">
</p>

## 📄Consumindo o ServeRest:

O ServeRest está disponível de forma [online](https://serverest.dev), no [npm](https://www.npmjs.com/package/serverest) e no [docker](https://hub.docker.com/r/paulogoncalvesbh/serverest/).

Todas essas opções possuem as mesmas rotas, regras, dados pré-cadastrados e documentação.

No ambiente online os dados cadastrados são removidos **diariamente**, enquanto que no local basta reiniciar o ServeRest.

> Prefira a opção de ambiente local caso precise que os dados não sejam alterados por outro usuário.

### 🟢 Online:

Acesse **<https://serverest.dev>** para visualizar a documentação e as rotas disponíveis.

> Essa é a melhor opção para quem não possui NPM e Docker na máquina ou não quer preocupar em gerenciar ambiente.

O ServeRest online possui monitoramento constante do status e tempo de atividade para garantir que esteja sempre disponível.
### Localmente com NPM

Execute o seguinte comando no terminal:

```sh
npx serverest
```

## ⚙️ Configuração

Para visualizar as configurações que são possíveis de serem feitas execute o comando:

```sh
npx serverest -h
```

![Informação de opções e exemplos fornecidos no terminal](https://user-images.githubusercontent.com/29241659/84348644-d45eae00-ab8b-11ea-89a4-d8cda3b32b74.png)

#### Segurança (`--nosec`)

Por default, o _ServeRest_ irá fazer as seguintes alterações no cabeçalho, que podem ser desabilitadas com `npx serverest --nosec`:

**Cabeçalhos adicionados:**
- `Strict-Transport-Security: max-age=15552000; includeSubDomains`
- `X-Content-Type-Options: nosniff`
- `X-DNS-Prefetch-Control: off`
- `X-Download-Options: noopen`
- `X-Frame-Options: SAMEORIGIN`
- `X-XSS-Protection: 1; mode=block`

**Cabeçalho removido:**
- `X-Powered-By: Express`

Utilize esse comportamento nos seus testes, validando a presença/ausência desses cabeçalhos.

> Para saber mais leia o [checklist de segurança de API](https://github.com/shieldfy/API-Security-Checklist#api-security-checklist)

---

## 🎯Direitos Autorais: 
![sprint6logo](https://user-images.githubusercontent.com/102266911/187577955-e6493788-912f-4c67-89ad-7fb77b180867.png)

### 👩🏿‍💻 Autor: 

<b><a href="https://github.com/tamara1908">Tamara Gleice</a></b>**

## 📌Créditos: 

### Agradecimento as pessoas que me apoiaram no projeto: 
* ### Matheus Locatelli (Scrum Master) a TODA Turma 04!.
   
## ✉️ Referências:
* **Algumas inspirações adquiri com a turma, especificamente com Amanda Cristina, Renan Rocha e a Cleonice Alves, com sugestões no plano de testes, compartilhamos bases de códigos e uma dose de motivação todos os dias**
* **Materiais Didáticos e Vídeos disponibilizados pela Compass desde o início**
* **Vídeo ensinando a <b><a href="https://www.youtube.com/watch?v=CMzOM2VyNLw">Padronizar Issues</a></b>**

