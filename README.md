# ead_js_alura_typescript

> Projeto referente a [este](https://cursos.alura.com.br/course/typescript-evoluindo-javascript), [este](https://cursos.alura.com.br/course/typescript-avancando-linguagem) e [este](https://cursos.alura.com.br/course/typescript-tecnicas-boas-praticas) cursos.

1. Crie o ambiente
```sh
docker-compose up -d
```
> Caso queira, ao final da configuração, pare o Docker com ``docker-compose down``

2. Baixe as dependências
```sh
docker-compose exec app npm i
```
> Caso queira, ao final da configuração, pare o Docker com ``docker-compose down``

## Execução

1. Suba o ambiente
    - Caso recém tenha feito a **configuração inicial** e o ambiente continue rodando, tudo certo.
    - Do contrário, suba o ambiente novamente: ``docker-compose up -d``

2. Inicie o servidor
```sh
docker-compose exec app npm start
```

3. Acesse ``localhost:3000``

> Para acessar o container use ``docker-compose exec app bash`` ou execute os scripts diretamente pelo Docker ``docker-compose exec app npm start``
