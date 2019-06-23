# Como iniciar um projeto em node.

Abre o prompt de comando na pasta desejada e digita
```
npm init -y
```

Segundo passo é criar um arquivo chamado "index.js"

O terceiro passo que temos que faze é ir no documento chamado "package.json" e ir no valor "sript" e adicionar mais um.
```
"roda": "node ./index.js"
```


O quarto passo é que temos que digitar o nome do script no terminal da forma:

```
npm run roda
```

Atenção caros amigos, caso o comando seja um default (e.g., start) não precisa colcar "run".


# Como adicionar bibliotecas ao node

Para adicionas basta usar o package manager (fisk?). Segue o exemplo:

```
npm install nome_do_package
```