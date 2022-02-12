
<p align="center">
<a href="https://www.docker.com/" target="_blank" rel="noopener noreferrer">
    <img width="70" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/docker/docker.png" alt="Docker Logo">
</a>
<a href="https://hyperf.io" target="_blank" rel="noopener noreferrer">
    <img width="70" src="https://cdn.jsdelivr.net/gh/hyperf/hyperf/docs/logo.png" alt="Hyperf Logo">
</a>
</p>

<p align="center">
  <a href="https://www.php.net"><img src="https://img.shields.io/badge/php-8.0-brightgreen.svg?maxAge=2592000" alt="Php Version"></a>
  <a href="https://github.com/swoole/swoole-src"><img src="https://img.shields.io/badge/swoole-4.6.7-brightgreen.svg?maxAge=2592000" alt="Swoole Version"></a>
</p>

# Docker Hyperf

Simple docker base to start a new project with [Hyperf](https://github.com/hyperf/hyperf) + [MariaDB](https://mariadb.org/) + [Redis](https://redis.io/)

## Getting Started

### Dependencies

* Docker

### Installing

* We using the [Makefile](https://www.gnu.org/software/make/manual/make.html) to automate the steps 

This command will install hyperf/hyperf-skeleton project via Composer, you will need to answer some Hyperf questions and after that the packages will be installed

```
make create-project
```

This command will build and start the necessary containers

```
make start
```

This command show the logs from containers

```
make logs
```

Check if everything is going well acessing this URL

```
http://localhost:9501/
```

The result should be like that


```
{
  "method": "GET",
  "message": "Hello Hyperf."
}
```