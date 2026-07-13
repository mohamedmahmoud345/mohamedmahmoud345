# Hi, I'm Mohamed 👋

Backend Developer specializing in **ASP.NET Core**, Clean Architecture, and CQRS — recently graduated (HTI '26), building production-grade backend systems with a focus on performance and testability.

```
Languages   : C#, Go, JavaScript
Backend     : ASP.NET Core, CQRS (MediatR), EF Core, JWT, FluentValidation
Databases   : SQL Server, Redis
DevOps      : Docker, GitHub Actions, Azure
Testing     : xUnit, Testcontainers
```

## 🚀 Featured Projects

### [ShortLink](https://github.com/mohamedmahmoud345/ShortLink) — Polyglot URL Shortener
Splits write-heavy admin operations (ASP.NET Core) from read-heavy redirects (Go) to isolate hot-path latency from the CQRS/EF Core pipeline.
- Cache-Aside pattern in Go — **4.3ms median / 7.6ms P95** latency
- Load tested with k6 (10 VUs, 10s) — **2,063 redirects/sec**, 100% success
- 61 integration tests via Testcontainers (SQL Server + Redis), CI on every PR
- Fully containerized: multi-stage Dockerfiles, 4-service Docker Compose

### [E-Commerce Platform API](https://github.com/mohamedmahmoud345)
Clean Architecture backend with CQRS across Products, Orders, and Cart domains.
- JWT auth with role-based authorization (Admin/Customer)
- Order lifecycle, payment validation, stock enforcement in domain models
- Deployed to Azure App Service + Azure SQL Database


## 📈 Stats
~150 LeetCode problems solved · Open-source contributor ([spiderly](https://github.com/filiptrivan/spiderly) PR #234)

## 📫 Reach me
[mmahmoud.swe@gmail.com](mailto:mmahmoud.swe@gmail.com) · [LinkedIn](https://linkedin.com/in/mohamed-mahmoud-957214249)
