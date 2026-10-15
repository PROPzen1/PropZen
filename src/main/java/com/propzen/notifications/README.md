# notifications

Sends SMS and email (OTPs, lead alerts, reminders). Used by background workers.

**Owns tables:** none

**Inside `internal/`:** sms, email (provider integrations)

Other modules may only use what this folder exposes at its top level, never anything inside `internal/`.
