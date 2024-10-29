# Docker Compose do meu Site Interface-Netflix

Este projeto é uma simulação do site da Netflix, configurado para ser executado em um container Docker com Apache.
Os arquivos HTML,CSS e js do site podem ser encontrados no link: _https://github.com/PetersonPHC/Interface_Netflix_

---

## A Estrutura dos diretórios na VM
Estrutura dos diretórios para compreensão do mapeamento dos volumes do arquivo [docker-compose.yml](https://github.com/PetersonPHC/Docker-compose-apache-desafio-DIO/blob/main/docker-compose.yml)
```Tree-of-Directories 
data/
├── compose
│   ├── meu-compose-netflix
│   │   ├──  docker-compose.yml
├── site-clone-netflix/
│   │   ├── index.html
│   │   ├── style
│   │   │   └── *
│   │   ├── js/
│   │   │   └── *
│   │   ├── Imagens/
│   │   │   └── *
```

## Deploy do Container
### 1. Pré-requisitos
- Docker e Docker Compose instalados.

### 2. Construir e Executar o Container
Para subir o container com Apache e hospedar o site, execute:

```bash
docker-compose up -d
```

### 3. Acessar o Site
Após a execução, o site estará acessível em [http://localhost:8080](http://localhost:8080).



## Tecnologias Utilizadas
  - Docker
  - Docker Compose
  - Imagem Docker -> Apache HTTP Server (httpd)
