# shared

Small cross-cutting pieces every module uses. Keep it small: business logic belongs in a module, not here.

- `security/` — token checks, current-user lookup
- `redis/` — Redis connection and helpers
- `web/` — common error responses
- `config/` — app-wide settings

**Owns tables:** none
