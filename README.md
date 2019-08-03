<p align="center">
  <a href="https://hub.docker.com/u/caggi">
    <img width="200" src="./docker.png">
  </a>
</p>

<h1 align="center">Git Docker Hub (gdh)</h1>

<div align="center">A code repository for the docker study</div>


## 🐳 Accessing the images
Images available at https://hub.docker.com/u/caggi


## 📦 gdh-php-apache

1 - Clone the repository [gdh](https://github.com/felipecaggi/git-docker-hub.git)
```bash
git clone https://github.com/felipecaggi/git-docker-hub.git
cd git-docker-hub
```

2 - Build image    
```bash
docker build --rm -f "gdh-php-apache\Dockerfile" -t gdh-php-apache:latest gdh-php-apache
```

3 - Initialize Container
```bash
docker run --rm -p 80:80/tcp gdh-php-apache:latest
```

4 - Go to localhost:80 in your browser to check the default settings and variables available on your system.


## 🔗 Links

- [Dockerfile reference](https://docs.docker.com/engine/reference/builder/)
- [Hello World com Docker](https://www.devmedia.com.br/hello-world-com-docker/40174/)
