# How to setup your development envirioment

[pt-br](https://github.com/polutz/polutz/blob/master/docs/setup-arch-linux.pt-br.md)
[en-us](https://github.com/polutz/polutz/blob/master/docs/setup-arch-linux.md)

## Install Global Dependencies

yo => Yeoman, we use Yeoman to automaticly generate your project/code.

babel-cli => Babel is a javascript compiler. Use next generation JavaScript, today.

ts-node => Typescript execution environment for node.

```
    npm i -g yo babel-cli ts-node
```

## Install MongoDB for Arch

Start MongoDB
```
    systemctl start mongodb.service
```

## Install Docker
```
    sudo pacman -S docker
```

To start docker:
```
    sudo systemctl start docker
```

To start on system boot:
```
    sudo systemctl enable docker
```

## Install Docker Compose
```
    sudo pacman -S docker-compose
```

