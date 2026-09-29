# 11NETTG30

Organização da Turma **11NETT** da Pós-Graduação em **Arquitetura de Sistemas .NET** da FIAP — reúne os projetos desenvolvidos pelo grupo ao longo da pós.

---

## 📚 Projetos

### 🎮 FIAP Cloud Games (FCG)

Plataforma de games educacionais desenvolvida como Tech Challenge (Fases 1 a 4).

- **Fase 1** — API monolítica com Clean Architecture e DDD, cobrindo identidade e autenticação de usuários
- **Fase 2** — Refatoração em microsserviços orientados a eventos, com RabbitMQ, Kubernetes e observabilidade
- **Fase 3** — Implementação de API Gateway (Kong), persistência poliglota com MongoDB, camada de cache com Redis, refatoração do microsserviço de notificações para Serverless e aprimoramento da observabilidade com dashboards de métricas HTTP no Grafana

### 🤝 Conexão Solidária

MVP de plataforma de gestão de doadores e campanhas de arrecadação para uma ONG, desenvolvido como Hackathon (Fase 5).

Monolito modular em Clean Architecture (.NET 10), com dois processos deployáveis — a API (Identidade, Campanha e Doação) e um Worker de processamento assíncrono de doações — comunicação via RabbitMQ, banco Postgres único com schema por módulo, observabilidade com OpenTelemetry/Prometheus/Grafana, pipeline de CI publicando imagens no GHCR e deploy em Kubernetes.

---

## 📦 Repositórios

### FIAP Cloud Games

| Repositório | Descrição |
|---|---|
| [fcg-users](https://github.com/11NETTG30/fcg-users) | Microsserviço de usuários — cadastro, autenticação JWT RS256 e endpoint JWKS |
| [fcg-catalog](https://github.com/11NETTG30/fcg-catalog) | Microsserviço de catálogo — jogos, biblioteca do usuário e fluxo de compra |
| [fcg-payments](https://github.com/11NETTG30/fcg-payments) | Microsserviço de pagamentos — simulação de aprovação/rejeição de pagamentos |
| [fcg-notifications](https://github.com/11NETTG30/fcg-notifications) | Microsserviço de notificações — envio de e-mails transacionais via SMTP |
| [fcg-shared](https://github.com/11NETTG30/fcg-shared) | Pacotes NuGet compartilhados — abstrações de domínio, infraestrutura e contratos de eventos |
| [fcg-infra](https://github.com/11NETTG30/fcg-infra) | Infraestrutura — Docker Compose e manifestos Kubernetes |
| [fiap-cloud-games](https://github.com/11NETTG30/fiap-cloud-games) | Fase 1 — monolito de referência |

### Conexão Solidária

| Repositório | Descrição |
|---|---|
| [FIAP-Conexao-Solidaria](https://github.com/11NETTG30/FIAP-Conexao-Solidaria) | Monolito modular (API + Worker de doações), RabbitMQ, Postgres, observabilidade e deploy em Kubernetes |

---

## 🛠️ Stack Técnica

### FIAP Cloud Games

| Categoria | Tecnologia |
|---|---|
| Plataforma | .NET 10 / C# 14 |
| Persistência Relacional | PostgreSQL 18 |
| Persistência NoSQL | MongoDB 7 |
| Cache Distribuído | Redis 7 |
| Mensageria | RabbitMQ + MassTransit |
| API Gateway | Kong |
| Serverless | Azure Functions |
| Autenticação | JWT RS256 (RSA assimétrico) |
| Containers | Docker |
| Orquestração | Kubernetes (Minikube) |
| Observabilidade | OpenTelemetry · Prometheus · Loki · Tempo · Grafana |
| Distribuição de Pacotes | GitHub Packages (NuGet) |

### Conexão Solidária

| Categoria | Tecnologia |
|---|---|
| Plataforma | .NET 10 / C# 14 |
| Persistência Relacional | PostgreSQL 18 (schema por módulo, sem gateway) |
| Mensageria | RabbitMQ + MassTransit |
| Autenticação | JWT HMAC simétrico + Refresh Token rotativo |
| Containers | Docker |
| Orquestração | Kubernetes |
| Observabilidade | OpenTelemetry · Prometheus · Grafana |
| CI/CD | GitHub Actions → GitHub Container Registry (GHCR) |

---

## 👥 Integrantes

| Nome | GitHub | LinkedIn |
|---|---|---|
| Gabriel Alex | [@gaabrielalex](https://github.com/gaabrielalex) | [in/gabriel-alex-dev](https://linkedin.com/in/gabriel-alex-dev) |
| Lennon Marconato | [@lennonmarconato](https://github.com/lennonmarconato) | [in/lennonmarconato](https://linkedin.com/in/lennonmarconato) |
| Rafael Caetano | [@RafaelCaettano](https://github.com/RafaelCaettano) | [in/rafael-caettano](https://linkedin.com/in/rafael-caettano) |
| Saulo Gustavo | [@Saulo0100](https://github.com/Saulo0100) | [in/saulo-gustavo-p](https://linkedin.com/in/saulo-gustavo-p) |
| Stéphan Galan S. | [@stephankamus](https://github.com/stephankamus) | [in/stephan-galan](https://linkedin.com/in/stephan-galan) |
