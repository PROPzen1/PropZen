# plans

Dealer plans and subscriptions. Every dealer starts on Free. The single place for "is this dealer allowed to...?" checks: canDealer(dealerId, action).

**Owns tables:** plans, dealer_subscriptions

**Inside `internal/`:** web, domain, persistence

Other modules may only use what this folder exposes at its top level, never anything inside `internal/`.
