# Atividade-Avaliativa-Individual-03
Crud usando Node

## Instalando dependências

```bash
npm i
```

## Senha do MYSQL

É necessário alterar a senha para a mesma senha do MYSQL na máquina.

```js
const con = mysql.createConnection({
    host: "localhost",
    user: "root",
    password: "senhaMYSQL" // senha do MYSQL na máquina.
});

```