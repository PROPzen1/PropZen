# admin

Staff accounts with email + password + two-factor login (never OTP), and the listing review queue.

**Owns tables:** admins

**Inside `internal/`:** web, domain, persistence

Other modules may only use what this folder exposes at its top level, never anything inside `internal/`.
