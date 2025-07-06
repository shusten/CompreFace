# EcogroundFace

EcogroundFace é uma aplicação de reconhecimento facial que permite detecção, cadastro e verificação de rostos por meio de uma API REST.

## Funcionalidades

* Detecção de rostos em imagens
* Cadastro de rostos em coleções
* Verificação e comparação facial
* API simples e intuitiva
* Interface web para gerenciamento

## Requisitos

* Docker e Docker Compose

## Como executar

1. Clone este repositório:

```bash
git clone git@github.com:seu-usuario/CompreFace.git
cd CompreFace
```

2. Suba os containers com Docker Compose:

```bash
docker-compose up -d
```

3. Acesse a interface web em:

```
http://localhost:8000
```

4. A API estará disponível por padrão em:

```
http://localhost:8000/api
```

5. Para parar os serviços:

```bash
docker-compose down
```

Pronto! O sistema estará em execução e pronto para ser usado.

