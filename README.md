# Repositório

Este repositório é destinado a um App feito em Javascript, tendo em vista sua utilização para anotação de notas. Além disso, a base para o desenvolvimento deste App foi o curso https://www.udemy.com/modern-javascript/.

Sua utilização é feita por intermédio de scripts que rodam webpack e babel para compilação de código em Javascript (principalmente ES6>).

É utilizado em seu armazenamento o Local Storage do Web Browser.

O App pode ser testado em http://balog-notes-app.surge.sh/



## Modo de usar

Para utilizar deste repositório, basta clona-lo e rodar os seguintes comandos dentro da pasta:

```bash
$ npm install
$ npm run dev-server
```

Rodados os comandos abaixo basta acessar a url http://localhost:8080/ para que possa ser visualizado o website.

**A porta pode variar caso ja esteja alocado a 8080**



## Desenvolvimento

Os arquivos feitos para este App foram escritos em JS, HTML e CSS.

O arquivo HTML pode ser encontrado em public/index.html.

O arquivo CSS em public/styles/styles.css.

E os arquivos não compilados podem ser encontrados na pasta src/.



## Publicação

Para efetivação do App em um Javascript compilado, basta rodar o comando abaixo:

```bash
$ npm run build
```

Feito isso, basta utilizar algum programa para direcionar para o arquivo index.html dentro da pasta public.