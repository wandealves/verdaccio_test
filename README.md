# verdaccio_test

Test Verdaccio

docker-compose up --build

# Login

Username: jpicado Password: jpicado

# Operações básicas

## Execute:

npm set registry http://localhost:4873/

## Para cadastrar um usuário basta executar:

npm adduser --registry http://localhost:4873/

## Caso você precise deslogar:

npm logout --registry http://localhost:4873/

## Já se precisar logar novamente:

npm login --registry http://localhost:4873/

## Para alterar a senha do usuário atualmente logado:

npm profile set password --registry http://localhost:4873/

## Publicando um pacote

npm publish --registry http://localhost:4873/

## Baixando/instalado o pacote

npm install --registry http://localhost:4873/ @exemple/hello-world

## Despublicar um pacote ou versão do Registro NPM

npm unpublish --registry http://localhost:4873/ @exemple/hello-world@1.0.0

## Já para despublicar o pacote como um todo, basta executar:

npm unpublish --registry http://localhost:4873/ @exemple/hello-world -f
