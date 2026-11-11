### Ryan Corazza Alvarenga

Desenvolvedor backend. Construo sistemas com regra de negócio de verdade: pedidos, pagamentos, saldo, relatórios. Trabalho com Java/Spring Boot, TypeScript/Node e Python, sempre com PostgreSQL, testes automatizados e CI.

[Portfólio](https://ryancorazza.vercel.app) · [LinkedIn](https://linked.in/ryancorazza)

---

### Projetos em destaque

**[Naquela Mesa](https://github.com/aishiteirai/naquela-mesa)** · [demo](https://naquela-mesa.vercel.app)
Cardápio digital e gestão de pedidos para restaurantes. Cada loja tem uma página pública e um painel de operação com fila de pedidos em tempo real, comanda para impressora térmica, avisos por WhatsApp e métricas.
- Preço calculado no servidor e pedido gravado em transação
- Código organizado por domínio (`orders`, `catalog`, `auth`, `audit`), 13 migrations versionadas
- Testes unitários, de integração contra Postgres e e2e com Playwright, todos no CI
- `Next.js` `TypeScript` `PostgreSQL` `Drizzle` `Better Auth` `Vercel`

**[everythingispdf](https://github.com/aishiteirai/everythingispdf)**
Serviço web que converte documentos e imagens em PDF (LibreOffice headless + Pillow).
- Rate limit compartilhado em Redis, cabeçalhos de segurança, healthcheck
- Docker Compose, Gunicorn, ruff, pip-audit e testes rodando no CI
- `Python` `Flask` `Redis` `Docker`

**[YIPE](https://github.com/aishiteirai/yipe-personal-finance)**
Gestão de finanças pessoais: transações, faturas de cartão, orçamento por categoria, extrato e importação/exportação.
- Valores em `BigDecimal`, schema versionado com Flyway, DTOs com MapStruct
- Testes de service, repository e controller
- `Java 21` `Spring Boot` `Spring Security` `JPA` `Flyway` `Thymeleaf`

**[Simulador OSI](https://github.com/aishiteirai/simulador-osi)**
Simulador das sete camadas do modelo OSI, com topologia de rede, roteamento e segmentação. Projeto em equipe de seis pessoas.
- `Python`

---

### Stack

**Backend:** Java, Spring Boot, TypeScript, Node.js, Python, Flask
**Dados:** PostgreSQL, Redis, JPA/Hibernate, Drizzle, Flyway
**Qualidade e entrega:** JUnit, Vitest, Playwright, GitHub Actions, Docker
