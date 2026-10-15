# listings

Creating and editing properties, the status lifecycle (only allowed transitions), expiry and renewal.

**Owns tables:** properties

**Inside `internal/`:** web, domain, persistence, jobs (nightly expiry, reminders)

Other modules may only use what this folder exposes at its top level, never anything inside `internal/`.
