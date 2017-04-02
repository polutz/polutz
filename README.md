# Polutz

[pt-br](https://github.com/polutz/polutz/blob/master/README.pt-br.md)
[en-us](https://github.com/polutz/polutz/blob/master/README.md)

We help Developers create awesome, tested and fast projects,
by creating and sharing easy reusable open source modules for any project.

Welcome aboard!

Don't you wanna to create a multi-language, web and mobile application,
where you can choose reusable modules like login, user report, membership roles, chat,
blog, FAQ, contact-us.... Or you can easily creat YOUR own modules! And sharing them only if you want to. 

It is totally FREE!!! 


## How to create your first project

Do you have Nodejs, Yeoman and MongoDB installed?
  - No -> [How can I setup my machine to be a real developer machine?](https://github.com/polutz/polutz/blob/master/docs/setup.md)
  - Yes! -> Go ahead!


## Create and run your first GraphQL Server

Run this code into your console to install our code generator:
```
    npm install -g generator-ptz-graphql
```

Create a project folder for your server and run this code and see the magic!
```
    yo ptz-graphql
```

It is time to RUN!
```
    npm start
```

[Teach me more about it](https://github.com/polutz/generator-ptz-graphql/blob/master/docs/contribute.md)


## Create and run your first react frontend web app

Run this code into your console to install our code generator:
```
    npm install -g generator-ptz-react
```

Create a project folder for your server and run this code and see the magic!
```
    yo ptz-react
```

It is time to RUN!
```
    npm start
```

[Teach me more about it](https://github.com/polutz/generator-ptz-react/blob/master/README.md)



## Projects using Polutz

[Freecomclub](https://github.com/angeloocana/freecomclub)



## If you love us, Download all polutz repos
```
curl "https://api.github.com/orgs/polutz/repos?page=$PAGE&per_page=100" |
  grep -e 'git_url*' |
  cut -d \" -f 4 |
  xargs -L1 git clone
```
