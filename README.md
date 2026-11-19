# Rodrigo Castro

Desenvolvedor full stack na [Montree Tecnologia](https://montreetecnologia.com.br/). Trabalho com .NET, Node.js (AdonisJS) e TypeScript e costumo cuidar do sistema inteiro: modelo de dados, regras de negócio, API, front-end, testes e deploy.

[Portfólio e blog](https://orodrigodev.com.br) · [LinkedIn](https://www.linkedin.com/in/rodrigoclc)

## No trabalho

Quase todo o meu código está em repositórios privados de clientes. Desde novembro de 2025 participei de 11 sistemas para clientes da Montree. Alguns deles:

- **Stoch:** único desenvolvedor de um marketplace com lojas, transportadoras, clientes e motoristas: API, painel web e app mobile num monorepo.
- **GoRisk:** único desenvolvedor de uma plataforma de gerenciamento de risco para transporte, com leitura de documentos por IA.
- **Prontuagil:** SaaS de saúde para prefeituras. Integrei o catálogo oficial de medicamentos do Ministério da Saúde (OBM e CATMAT): 5,7 mil medicamentos e 31 mil apresentações, atualizados pela API oficial.
- **Fleet Tree:** back-end de um sistema de gestão de frota multiempresa, em uso pelo cliente.
- **Infraestrutura da empresa:** por iniciativa própria, montei a observabilidade das APIs (OpenTelemetry e Grafana) e o backup automático dos bancos PostgreSQL para o S3.

## Projetos pessoais

| Projeto | O que é | Stack |
| --- | --- | --- |
| [Rastro](https://github.com/Rodrigoclc/rastro) | Observabilidade pronta para APIs AdonisJS 5, 6 e 7: biblioteca OpenTelemetry mais Collector, Grafana, dashboard e alertas num `docker compose up`. | TypeScript, OpenTelemetry, Grafana |
| [Nova](https://github.com/Rodrigoclc/Nova) | Framework HTTP orientado a objetos para TypeScript, com controllers, decorators e DTOs. Experimental. | TypeScript |
| [GitHub Shoppers](https://github.com/Rodrigoclc/GitHub-Shoppers) | Catálogo de produtos full stack, feito como desafio técnico. [Demonstração](https://github-shoppers.orodrigodev.com.br) | Node.js, React, PostgreSQL |
| Follow-up.ia | Follow-up automático no WhatsApp para corretores de imóveis. A IA escreve as mensagens; quem decide quando enviar é um motor determinístico. Em testes. | .NET, PostgreSQL |
| Sync Casa | Assistente da família no WhatsApp: listas, lembretes e agenda no grupo. Em desenvolvimento. | .NET, PostgreSQL |
| PulseStem | Adiciona um metrônomo que acompanha as mudanças de BPM de uma música. [Demonstração](https://clicktrack.orodrigodev.com.br) | Python, Flask |

Os projetos pessoais rodam numa infraestrutura própria na AWS: EC2 com Docker, imagens versionadas no GHCR e deploy por GitHub Actions.

## Stack

- **Back-end:** C#, .NET, ASP.NET, Node.js, AdonisJS, TypeScript
- **Front-end:** React, Angular, Ant Design
- **Dados:** PostgreSQL, SQL Server
- **Infraestrutura:** Docker, AWS (EC2, S3), Nginx, Caddy, GitHub Actions

## Como trabalho

Começo pelo modelo de dados e pelas regras de negócio, e só depois escrevo o código e os testes. Uso agentes de IA no dia a dia, dentro de um processo: cada tarefa é descrita antes, vira um pull request e passa por revisão e testes antes do merge.
