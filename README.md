# **Desafio Frontend Stellar**

Primeiramente, obrigado pelo seu interesse em trabalhar na Stellar!
Abaixo você encontrará todos as informações necessárias para iniciar o seu teste.

### Desafio proposto
O desafio proposto é a criação de uma página web com um formulário onde o usuário irá preencher os dados de sua conta e depois irá enviar para a API para realizar login, e em seguida, irá retornar o token de autenticação para o usuário, caso o login seja bem sucedido, e caso não seja, irá retornar uma mensagem de erro.
O usuário poderá entrar na página /produtos somente após realizar o login.

O que espera que seja feito?

- Validação do input de email e senha
- Exibição de mensagens de erro caso o usuário não seja autenticado
- Abrir o modal de sucesso após o login
- Redirecionamento para a página de erro caso o usuário tente acessar a página /produtos sem estar autenticado.
- Salvar o token de autenticação no localStorage



### 1. O usuário ira apertar em "Login" e irá abrir um modal com um formulário para preencher os dados de sua conta.
![Login](./assets/imagens/1.png)


### 2. O usuário ira preencher os dados de sua conta e irá clicar em "Logar"
![Login](./assets/imagens/2.png)
### 3. Irá abrir um modal com a mensagem "Login realizado com sucesso".
![Login](./assets/imagens/3.png)
### 4. O usuário será redirecionado para uma página de erro caso tente entrar na página /produtos sem estar logado.
![Login](./assets/imagens/4.png)

*OBS: A pagina /produtos será apenas uma página em branco.*

## Avisos antes de começar

- Caso não consiga acessar o figma, também há screenshoots do Figma na pasta assets. Você não é obrigado a seguir o layout do figma, ele é apenas uma base para que você entenda melhor o desafio proposto.

- Para a entrega do teste você precisará ter two factor habilitado na sua conta do GitHub, você poderá ver o passo a passo nesse tutorial: [Two Factor Authentication](https://help.github.com/pt/github/authenticating-to-github/configuring-two-factor-authentication).

- Com two factor habilitado, você precisa configurar a chave SSH: [Add new SSH key to your Github account ](https://help.github.com/pt/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account).

- **Para iniciar o teste, crie uma branch a partir da `master` nesse padrão de nomenclatura: dd-mm-yy/nome-sobrenome (por exemplo, 30-04-20/meu-nome)**
- **Quando finalizar o teste, crie uma PR (Pull Request) da sua branch para a master e avise o(a) recrutador(a) que o teste está finalizado.**
- Você poderá consultar o Google, Stackoverflow ou algum projeto particular na sua máquina.
- Fique à vontade para perguntar qualquer dúvida aos recrutadores.

- Fique tranquilo, respire, assim como você, também já passamos por essa etapa. Boa sorte! :)

## Figma
[Link](https://www.figma.com/file/gzIs5GonMky67OYQopwiHT/Frontend-Challenge?node-id=0%3A1)
## Tecnologias

- HTML
- CSS
- Javascript

## Começar?

- Clone este repositório: `git clone git@github.com:stellartechnologies/frontend-challenge.git`
- Abra a pasta `frontend-challenge` com o seu editor de texto favorito e comece a desenvolver o seu teste.
<br/>

### Leia com atenção! ⚠️

**1 -** Nosso desafio consiste em uma aplicação web simples, que será utilizada para testar o seu conhecimento como desenvolvedor Frontend, a fim de avaliar seu conhecimento e habilidades, é preferível que você siga o mínimo do layout proposto. Você pode implementar novas features, melhorar o design, tudo que você fizer contará pontos!

**2 -** Temos uma API mock (JSON Server) na qual você utilizará para implementar os seus serviços de CRUD. A documentação da API está disponível no formato OpenAPI, você pode importar o arquivo `api-doc.yaml` no Postman, Swagger ou qualquer outro serviço que você desejar.

**3 -** Certifique-se de revisar seu código, a modo que fique o mais organizado possível para a avaliação e entendimento dos avaliadores.

**4 -** Utilize a estrutura de pastas que achar mais adequada, bem como padrões, patterns, práticas de segurança, performance etc.

**5 -** Caso você seja JR e tenha algum receio, não se preocupe, iremos avaliar o que foi entregue, mesmo com pendências.

**6 -** O diferencial para este desafio, é o aprimoramento do mesmo, bem como implementação de boas práticas, performance e/ou estrutura.
<br/>
<br/>

### **API**

Para realizar o login, você deverá utilizar a API de autenticação, que está disponível aqui: https://stellar-mock.herokuapp.com/v1


**Rotas:** <br />
`POST: /auth`<br />
<br/>

<br/>

### **Parametros da API:**

**Usuário e senha correta:**<br />
`{"email": "joaodasilva@gmail.com", "password": "teste12345@TES"}`<br />
Resposta:<br />
`{
    "success": true,
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkpvaG4gRG9lIiwiaWF0IjoxNTE2MjM5MDIyfQ.SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV_adQssw5c"
}`

**Usuário e senha incorreta:**<br />
`{"email": "joaodasilva@gmail.com", "password": "teste12345@TES"}`<br />
Resposta:<br />
`{
    "success": false,
    "errorCode": "INVLCRED",
    "errorMessage": "Invalid email or password"}`<br />

<br/>
<br/>

**Orientações e dicas:**

- Esperamos que você consiga completar o mínimo do desafio; Mas não se esqueça, mostre o seu melhor! 😉

- Iremos avaliar cada feature, conceito, pattern, tudo o que você fizer de adicional. Tudo além do proposta contará pontos!

- Faça commits regulares. Eles são melhores do que um commit gigantesco. Gostaríamos de ver commits organizados e padronizados, então capriche neles!

### **Links úteis**:

- https://github.com/BeeTech-global/bee-stylish/tree/master/commits <br/>
- https://www.conventionalcommits.org/en/v1.0.0/

Qualquer problema por favor contate seu recruiter.

**BOA SORTE !** 😉😉😉