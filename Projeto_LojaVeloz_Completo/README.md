# Loja Veloz - Plataforma de Pedidos em Microsserviços

Este repositório contém o MVP da modernização da infraestrutura da Loja Veloz, migrando de um modelo manual para uma arquitetura cloud-native com Docker, Kubernetes e CI/CD.

## Estrutura do Projeto
- `api-gateway/`: Ponto de entrada das requisições.
- `pedidos-service/`: Gerenciamento de pedidos (Node.js).
- `pagamentos-service/`: Processamento de pagamentos (Python).
- `estoque-service/`: Controle de inventário (Go).
- `k8s/`: Manifestos Kubernetes.
- `terraform/`: Esqueleto de infraestrutura como código.
- `.github/workflows/`: Pipelines de CI/CD.

## Como Executar Localmente
```bash
docker-compose up --build
```
