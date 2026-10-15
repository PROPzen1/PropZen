# leads

Customer enquiries to dealers: idempotency key, 7-day repeat check, rate limits, delivery tracking, dealer inbox.

**Owns tables:** leads

**Inside `internal/`:** web, domain, persistence, jobs (delivery, re-queue leads stuck in new)

Other modules may only use what this folder exposes at its top level, never anything inside `internal/`.
