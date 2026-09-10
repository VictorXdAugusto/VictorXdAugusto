## Victor Augusto Moraes Pereira

Engenheiro de software back-end. Go, microsserviços e sistemas distribuídos.

Trabalho no núcleo de uma plataforma de saúde com 13 microsserviços em produção, no serviço de
integrações com laboratórios e sistemas EHR: pipelines assíncronos com Pub/Sub, PostgreSQL,
GraphQL, Kubernetes e tracing distribuído. A parte que mais me ensina é a menos glamourosa —
incidente em produção, causa raiz, e correção com revert testado antes de rodar.

**Stack principal**

`Go` · `PostgreSQL` · `Kubernetes` · `Docker` · `GCP (Pub/Sub, GKE)` · `GraphQL / Hasura` · `OpenTelemetry` · `GitLab CI/CD`

**Alguns repositórios**

| | |
|---|---|
| [exam-processing-service](https://github.com/VictorXdAugusto/exam-processing-service) | Processamento assíncrono de exames em Go — Clean Architecture, worker pool com goroutines e channels, PostgreSQL, Docker |
| [engineer-test](https://github.com/VictorXdAugusto/engineer-test) | Geolocalização em tempo real — PostGIS para consulta geoespacial, Redis Streams para eventos, Swagger |
| [clean-architecture-golang](https://github.com/VictorXdAugusto/clean-architecture-golang) | API REST em Go com injeção de dependência via `google/wire` e worker desacoplado |

**Como eu trabalho**

Regra de negócio antes do código. Teste como gate bloqueante, não como sugestão. Produção só por
protocolo: evidência, apply idempotente, revert testado. E quem implementa não revisa.

**Contato**

[LinkedIn](https://www.linkedin.com/in/victor-augusto-moraes-pereira-46a1a0205/) · augusto9055@gmail.com
