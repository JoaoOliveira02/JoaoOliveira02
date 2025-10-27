![.NET](https://img.shields.io/badge/.NET-8%2F9-512BD4?logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-12-239120?logo=csharp&logoColor=white)
![SQL%20Server](https://img.shields.io/badge/SQL%20Server-DB-CC2927?logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-DB-4169E1?logo=postgresql&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-Cloud-0078D4?logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900?logo=amazonaws&logoColor=white)
![Azure%20DevOps](https://img.shields.io/badge/Azure%20DevOps-CI%2FCD-0078D7?logo=azuredevops&logoColor=white)
![MediatR](https://img.shields.io/badge/MediatR-Pattern-6DB33F)
![FluentValidation](https://img.shields.io/badge/FluentValidation-Validation-0E83CD)
![Serilog](https://img.shields.io/badge/Serilog-Logging-4E9A06)

# João Vitor Ferreira Oliveira

Desenvolvedor **C#/.NET** focado em back‑end, integrações e arquitetura limpa. Hoje atuo na **RSM Brasil** (finanças/auditoria), modernizando sistemas legados para **.NET 8/9** com **DDD + Clean Architecture + CQRS**, **EF Core**, e pipelines **Azure DevOps**. Experiência com **SQL Server** (bases grandes, procedures complexas, performance/índices/collation), **PostgreSQL**, e integrações com provedores de pagamento (**GetNet**, **eRede**). Também tenho vivência com **Azure** (App Service, VMs, Blob) e **AWS** (S3, Cognito).

---

## 🔥 Destaques Recentes

* **Novo trabalho — RSM Brasil (desde dez/2024):** migração de módulos fiscais/contábeis (ITAUDIT, TAX Analyzer) de .NET Framework 4.x para **.NET 8/9**, separação por camadas (Domain/Application/Infrastructure/Presentation) e adoção de **DDD**.
* **Desempenho & Banco:** otimização de **procedures** pesadas, correções de **collation** entre ambientes (prod vs homolog), criação de índices e revisão de planos de execução; importações de grandes volumes (SPED/ECF/EFD) e **CNAB FEBRABAN 240 e 400**.
* **Pagamentos Cartão (SG Rentals):** integração completa com **GetNet** e **eRede** (autenticação, tokenização, autorização, responses mapeados), com **ports/adapters** e injeção de dependência para alternar adquirente.
* **Observabilidade & Qualidade:** **Serilog** (enriquecimento, correlação), validações com **FluentValidation**, testes **xUnit + NSubstitute**, documentação com **Swagger**.
* **DevOps/IIS:** rotas de deploy em **Azure DevOps**, ajustes de agentes Windows, publicação em **IIS**, e gestão de conexões multi‑ambiente.

---

## 🧰 Stack & Ferramentas

* **Linguagens:** C#, SQL, JavaScript
* **.NET:** .NET 8/9, ASP.NET Core MVC/API, EF Core, Dapper, MediatR, FluentValidation, ErrorOr
* **Arquitetura:** DDD, Clean Architecture, CQRS, Repository, Unit of Work
* **Banco de Dados:** SQL Server (filegroups, collation, SPs, tuning), PostgreSQL (incl. PostGIS em dev)
* **Mensageria/Email:** SendGrid
* **Pagamentos:** GetNet v2, eRede
* **Observabilidade:** Serilog, Fiddler
* **Build & CI/CD:** Git, GitHub, Azure DevOps Pipelines
* **Cloud & Infra:** Azure (App Service, VMs, Blob), AWS (S3, Cognito), Docker (SQL/Postgres)
* **Front de Apoio:** Swagger, Postman; jQuery, DataTables, FullCalendar; X.PagedList
* **Outros:** ClosedXML/EPPlus (Excel), Postman Collections, IIS

---

## 💼 Experiência

**Desenvolvedor .NET — RSM Brasil**
*(ago/2025 — atual)*

* Modernização de sistemas fiscais (ITAUDIT, TAX Analyzer) para **.NET 8/9** com **DDD + CQRS + Clean Architecture**.
* Reestruturação de **DbContexts** e múltiplas conexões (prod/homolog/dev), otimização de **SPs** e **views**; correções de **collation** entre servidores.
* Publicação em **IIS** e monitoramento com **Serilog**.
* Importações CNAB/Sped, melhorias de performance, refactors em controllers para assíncrono e redução de acoplamento.

**Desenvolvedor Backend Júnior — SG Rentals**

* Sistema de reservas e pagamentos com integrações **GetNet** e **eRede** (autenticação, tokenização, autorização).
* **Ports/Adapters** e **DI** para selecionar adquirente por ambiente; **DDD/CQRS** e **Clean Architecture**.
* Envio de e‑mails com **SendGrid**, autenticação com **AWS Cognito**, uso de **Azure**/**AWS**.

**Desenvolvedor Júnior — Secretaria de Esporte e Lazer de SP**

* Sistemas internos com **ASP.NET Core** + **PostgreSQL/MySQL**, automações e suporte a usuários.
* Módulo **Controle de Acesso** (contagem por categoria, relatórios) e telas com **jQuery/DataTables/FullCalendar**.

---

## 🧪 Testes & Qualidade

* **xUnit** para unit tests com **NSubstitute**.
* **FluentValidation** em commands/DTOs (ex.: `CreateAirlineCommand`).
* Padrão de erros com **ErrorOr**; documentação **Swagger** e collections no **Postman**.

---

## 🧠 O que estou estudando/agregando agora

* **Blazor** para projeto de portfólio full‑stack (DDD + CQRS + PostgreSQL).
* **Tuning** de queries e diagnósticos (planos de execução, índices, bloqueios).
* **Pipelines** no Azure DevOps (melhores práticas), **IIS** e automações de deploy.
* Boas práticas para parsing/importações (SPED, CNAB 240) em .NET + SQL Server.

---

## 📌 Projetos em Destaque

* **RSM — ITAUDIT / TAX Analyzer (modernização):** migração e refatoração para **.NET 8/9**, separação em camadas, testes, logging estruturado e otimizações de banco.
* **SG Rentals — Pagamentos & Reservas:** integrações **GetNet/eRede** com adapters e DI; notificações via **SendGrid** e autenticação **Cognito**.
* **Controle de Acesso — Clube/Esportes:** registro diário por categoria, relatórios por período, front dinâmico.

> **Nota:** Muitos projetos são privados por confidencialidade. Quando possível, publico exemplos análogos e estudos no meu GitHub.

---

## 📫 Contato

* **E-mail:** [joaovitor.oliveira123@hotmail.com](mailto:joaovitor.oliveira123@hotmail.com)
* **LinkedIn:** [https://www.linkedin.com/in/joão-oliveira-640061190](https://www.linkedin.com/in/joão-oliveira-640061190)
