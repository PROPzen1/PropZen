# identity

Customer and dealer accounts: OTP login, roles, profiles, sessions (active sessions screen, log out other sessions).

**Owns tables:** accounts, account_roles, customer_profiles, dealer_profiles, sessions

**Inside `internal/`:** web (endpoints), domain (business rules), persistence (database access)

Other modules may only use what this folder exposes at its top level, never anything inside `internal/`.
