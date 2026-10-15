# search

Customer search: filters, map search, sorting, filter counts and result caching. Reads listings through a query exposed by the listings module.

**Owns tables:** none

**Inside `internal/`:** web, cache (Redis-cached results)

Other modules may only use what this folder exposes at its top level, never anything inside `internal/`.
