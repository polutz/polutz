# Como configurar sua máquina de desenvolvimento

[pt-br](https://github.com/polutz/polutz/blob/master/docs/setup.pt-br.md)
[en-us](https://github.com/polutz/polutz/blob/master/docs/setup.md)


## Instalar Dependências Globais

yo => Yeoman, nos usamos Yeoman para gerar automaticamente o seu código/projeto.

babel-cli => Babel é um compilador javascript, permite você utilizar tudo o que há de novo no javascipt.

ts-node => Typescript pra executar códigos Nodejs

```
    npm i -g yo babel-cli ts-node
```

## Instalar MongoDB

### MongoDB para Windows
[documentação completa para Window](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/)

Resumo das etapas:
1- [Baixar e Instalar MongoDB](https://www.mongodb.com/download-center#community)

2- MongoDB precisa de uma pasta para salvar todos os seus dados. A pasta padrão é \data\db. Crie essa pasta rodando o comando abaixo:
```
    md \data\db
```

3- Para iniciar o MongoDB, rode o comando abaixo:
```
"C:\Program Files\MongoDB\Server\3.4\bin\mongod.exe"
```

Parabéns! Agora é só aproveitar e curtir o seu MongoDB instalado localmente =D
