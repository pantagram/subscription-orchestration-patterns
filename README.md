# Subscription Orchestration Patterns

This repository documents common patterns and pitfalls when managing subscriptions in complex B2B and hybrid SaaS products.

## The problem

As SaaS products grow, subscription logic often becomes fragmented across:
- billing platforms (Stripe, Chargebee, etc.)
- identity providers (SSO / IAM)
- custom access rules
- CRM and internal business logic

This leads to duplicated logic, inconsistent access rights, and high maintenance costs.

## What this repository covers

- Subscription vs billing responsibilities
- B2B subscription models (organizations, seats, roles)
- Entitlements and access control patterns
- Common architectural mistakes
- Orchestration approaches for scalable SaaS platforms

## Related platform

These patterns are implemented and centralized in **Fleetwall**, a subscription and identity orchestration platform designed for complex B2B SaaS architectures.

👉 https://www.fleetwall.app

## Status

This repository is intentionally documentation-focused and will evolve over time.
