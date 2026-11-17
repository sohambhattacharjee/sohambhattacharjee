# Soham Bhattacharjee

I'm a principal software engineer working on e-commerce checkout, payments, and order orchestration. I focus on what happens when a checkout gets interrupted, a payment processor times out, or an order workflow has to retry.

I'm exploring how agentic commerce protocols can make buyer authorization explicit when an agent checks out on someone's behalf.

## Upstream pull requests

- [Temporal's Go order management reference app](https://github.com/temporalio/reference-app-orders-go/pull/137) — integration test for recovering an order after a worker restarts without creating a duplicate.
- [Hyperswitch's Saleor payment app](https://github.com/juspay/hyperswitch-saleor-payment-app/pull/98) — fix for a payment status lookup that failed before reaching the processor.

## Projects

- [Payment failover tests](https://github.com/sohambhattacharjee/payment-failover-tests) — deterministic fixtures for processor timeouts, backup routing, and reconciliation.
- [Checkout currency tests](https://github.com/sohambhattacharjee/checkout-currency-tests) — executable checks for quote preservation and partial refund reconciliation when exchange rates change.
- [Limited-release recovery tests](https://github.com/sohambhattacharjee/limited-release-recovery-tests) — a fixture for detecting duplicate or missing orders after an interrupted product launch.
- [Agentic software factory study](https://github.com/sohambhattacharjee/agentic-software-factory-study) — a staged experiment in AI-assisted maintenance of a [synthetic legacy order management application](https://github.com/sohambhattacharjee/brownfield-agentic-migration).

## Writing

- [Web Payments – Deep Dive](https://www.linkedin.com/pulse/web-payments-deep-dive-soham-bhattacharjee) (2019) — lessons from integrating Google Pay through the Payment Request API.
- [Payment Request API](https://www.linkedin.com/pulse/payment-request-api-soham-bhattacharjee) (2018) — an introduction to browser-based checkout.
