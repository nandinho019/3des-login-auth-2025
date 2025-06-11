# Login - auth
Estrutura de autenticação para o projeto **Login**.
## Atividade em grupo de até 3 integrantes.
- Clonar este repositório.
- Testar a api com **insomnia**.
- Estudar e documentar a estrutura do projeto.
- Detalhar e documentar as bibliotecas utilizadas.
- Documentar descrição do funcionamento utilizando **UML DA(Diagrama de Atividades)**.

## Tecnologias
- Node.js
- VsCode
- Insomnia

## Para testar
- Clonar este repositório.
- Na pasta **./api**, criar um arquivo **.env** com as seguintes **variáveis de ambiente**:
```js
SECRET_JWT=f?#cPV9]2sc"}gQhO)Yx7IT1M*zuv&;FVC(vsFAz;]n2tK:T*uH|@Ixrow3bLC+
USER=usuario@gmail.com
PASSWD=senha123
```
- Abrir com o VsCode e em um terminal cmd ou bash, executar os comandos a seguir para instalar as dependências e iniciar o servidor:
```bash
cd api
npm install
npx nodemon
```
- Testar com insomnia as rotas:
```bash
GET http://localhost:4000
POST http://localhost:4000/login
GET http://localhost:4000/posts
```