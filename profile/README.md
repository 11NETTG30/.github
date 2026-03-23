# 11NETTG30 — FIAP Cloud Games

Organização do **Grupo 30** da Turma **11NETT** da Pós-Graduação em **Arquitetura de Sistemas .NET** da FIAP.

---

## 🎮 Sobre o Projeto

O **FIAP Cloud Games (FCG)** é uma plataforma de games educacionais desenvolvida como Tech Challenge.

- **Fase 1** — API monolítica com Clean Architecture e DDD, cobrindo identidade e autenticação de usuários
- **Fase 2** — Refatoração em microsserviços orientados a eventos, com RabbitMQ, Kubernetes e observabilidade

---

## 📦 Repositórios

| Repositório | Descrição |
|---|---|
| [fcg-users](https://github.com/11NETTG30/fcg-users) | Microsserviço de usuários — cadastro, autenticação JWT RS256 e endpoint JWKS |
| [fcg-catalog](https://github.com/11NETTG30/fcg-catalog) | Microsserviço de catálogo — jogos, biblioteca do usuário e fluxo de compra |
| [fcg-payments](https://github.com/11NETTG30/fcg-payments) | Microsserviço de pagamentos — simulação de aprovação/rejeição de pagamentos |
| [fcg-notifications](https://github.com/11NETTG30/fcg-notifications) | Microsserviço de notificações — envio de e-mails transacionais via SMTP |
| [fcg-shared](https://github.com/11NETTG30/fcg-shared) | Pacotes NuGet compartilhados — abstrações de domínio, infraestrutura e contratos de eventos |
| [fcg-infra](https://github.com/11NETTG30/fcg-infra) | Infraestrutura — Docker Compose e manifestos Kubernetes |
| [fiap-cloud-games](https://github.com/11NETTG30/fiap-cloud-games) | Fase 1 — monolito de referência |

---

## 🛠️ Stack Técnica

| Categoria | Tecnologia |
|---|---|
| Plataforma | .NET 10 / C# 14 |
| Banco de Dados | PostgreSQL 18 |
| Mensageria | RabbitMQ + MassTransit |
| Autenticação | JWT RS256 (RSA assimétrico) |
| Containers | Docker |
| Orquestração | Kubernetes (Minikube) |
| Observabilidade | OpenTelemetry · Prometheus · Loki · Tempo · Grafana |
| Pacotes Compartilhados | GitHub Packages (NuGet) |

---

## 👥 Integrantes

| Nome | GitHub | LinkedIn |
|---|---|---|
| Gabriel Alex | [@gaabrielalex](https://github.com/gaabrielalex) | [in/gabriel-alex-dev](https://linkedin.com/in/gabriel-alex-dev) |
| Lennon Marconato | [@lennonmarconato](https://github.com/lennonmarconato) | [in/lennonmarconato](https://linkedin.com/in/lennonmarconato) |
| Rafael Caetano | [@RafaelCaettano](https://github.com/RafaelCaettano) | [in/rafael-caettano](https://linkedin.com/in/rafael-caettano) |
| Saulo Gustavo | [@Saulo0100](https://github.com/Saulo0100) | [in/saulo-gustavo-p](https://linkedin.com/in/saulo-gustavo-p) |
| Stéphan Galan S. | [@stephankamus](https://github.com/stephankamus) | [in/stephan-galan](https://linkedin.com/in/stephan-galan) |
