# Polutz

Nos ajudamos desenvolvedores a criarem maravilhosos, testados e rápidos projetos, pela criação e compartilhamento de modulos de fácil reaproveitamento. 

Bem vindo a bordo!

Você não gostaria de criar um projeto multi-idioma, web e mobile?
Onde você possa escolher módulos como login, relatório de usuários, permissões de acesso, chat, blog, FAQ, fale conosco... Ou você pode facilmente criar seus próprios módulos e compartilhar somente se você quiser.


É totalmente gratuito!!!

#GoOpenSource


## Como criar o seu primeiro projeto

Você possui Nodejs, Yeoman e MongoDB instalado?
  - Não -> [Como preparar minha máquina para desenvolver?](https://github.com/polutz/polutz/blob/master/docs/setup.md)
  - Sim! -> Siga em frente!


## Crie e Rode o seu primeiro servidor GraphQL

Rode esse comando no terminal para instalar nosso gerador de código:
```
    npm install -g generator-ptz-graphql
```

Cria uma nova pasta para o seu projeto de SERVIDOR. 
Entre dentro dela e rode esse comando. 
Deixe a mágica acontecer!
```
    yo ptz-graphql
```

Hora de rodar o projeto! =D
```
    npm start
```

[Quer aprender mais?](https://github.com/polutz/generator-ptz-graphql/blob/master/README.md)


## Crie e Rode o seu primeiro projeto web com React

Rode esse comando no terminal para instalar nosso gerador de código:
```
    npm install -g generator-ptz-react
```

Cria uma nova pasta para o seu projeto de FRONTEND. 
Entre dentro dela e rode esse comando. 
Deixe a mágica acontecer!
```
    yo ptz-react
```

Hora de rodar o projeto! =D
```
    npm start
```

[Quer aprender mais?](https://github.com/polutz/generator-ptz-react/blob/master/README.md)



## Projetos utilizando o Polutz

[Freecomclub](https://github.com/angeloocana/freecomclub)



## Se você nos ama, baixe todos os projetos da Polutz
```
curl "https://api.github.com/orgs/polutz/repos?page=$PAGE&per_page=100" |
  grep -e 'git_url*' |
  cut -d \" -f 4 |
  xargs -L1 git clone
```
