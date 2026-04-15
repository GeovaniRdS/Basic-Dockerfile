# Hello, Captain!

Uma imagem Docker minimalista que exibe `Hello, Captain!` no console e encerra.

> Projeto baseado no desafio: [roadmap.sh/projects/basic-dockerfile](https://roadmap.sh/projects/basic-dockerfile)

## Requisitos

- Docker instalado e em execução

## Como Usar

**Construir a imagem:**
```bash
docker build -t hello-captain .
```

**Executar o container:**
```bash
docker run hello-captain
```

**Saída esperada:**
```
Hello, Captain!
```

## Como Funciona

O `Dockerfile` utiliza `alpine:latest` como imagem base e executa um único comando `echo` para imprimir a mensagem antes de encerrar.