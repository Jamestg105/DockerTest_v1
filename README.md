# DockerTest

Este projeto é um exercício de estrutura de microsserviços usando Docker. Ele contém dois serviços: um em Node.js e outro em Python (Flask).

## Descrição do Projeto

- **Service 1**: Implementado em Node.js, responde na porta 3000.
- **Service 2**: Implementado em Python Flask, responde na porta 5000.

## Pré-requisitos

- Docker instalado
- Docker Compose instalado
- Phyton e Node.js instalados
- Servidor local Linux instalado
- VM para rodar Servidor
- Rede configurada entre Host e Guest
- Portas liberadas
  
## Estrutura 
```
DockerTest/
├── docker-compose.yml
├── service1/
│   ├── Dockerfile
│   ├── index.js
│   └── package.json
└── service2/
    ├── Dockerfile
    ├── app.py
    └── requirements.txt
```
