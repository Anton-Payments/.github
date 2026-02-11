<div align="center">

# Anton Payments

**Cross-border payouts shouldn't be this hard.**

Moving money globally means stitching together fragmented rails, navigating compliance in every corridor, and hoping your fraud rules keep up. Most platforms bolt these pieces together as an afterthought.

We built Anton from scratch to solve this — a single payout API where compliance, risk intelligence, and multi-rail routing are foundational, not features you add later.

---

</div>

### What We Do

Anton is payout infrastructure. Our clients send us money; we deliver it to their recipients anywhere in the world — to bank accounts, cards, mobile wallets, or digital assets. One API call. We handle the routing, the compliance, and the risk.

**Every rail, one integration.** SWIFT, SEPA, ACH, FPS, cards, mobile money, and stablecoins. We route each payout to the optimal rail for the corridor — factoring in cost, speed, and availability — with automatic failover when a provider is down.

**Compliance is the product, not a checkbox.** Every payout is screened against OFAC, PEP, and sanctions lists before it moves. Maker-checker approvals enforce separation of duties on high-value transactions. Full audit trail on every state change. We're building to ISO 27001, SOC 2 Type II, and PCI DSS — not because we have to, but because our clients need us to.

### AI-Powered Risk Engine

Static rules catch known threats. They don't adapt, and they don't learn.

Our risk engine starts with configurable rules — velocity limits, geo-blocking, duplicate detection, sanctions screening — and layers AI on top:

- **Adaptive thresholds** — models analyze each merchant's historical patterns and propose rule adjustments. A $100K payout is normal for a merchant doing $500K/day. It's suspicious for one doing $500/day. Our engine knows the difference.
- **Behavioral risk scoring** — every payout receives a real-time risk score based on amount deviation, beneficiary novelty, geographic anomalies, temporal patterns, and velocity spikes relative to the merchant's own baseline.
- **Feedback-driven learning** — ops decisions on flagged payouts become training data. The model improves continuously. False positives go down. Catch rates go up.
- **Emerging risk detection** — AI monitors aggregate patterns across all corridors and merchants, surfacing new risks before they become incidents.

The static engine is the floor. AI is the intelligence above it. Compliance rules are never weakened — only strengthened.

### For Developers

We're developers too. The API is designed to get out of your way:

- **[API Documentation](https://docs.antonpayments.com)** — complete reference with request/response examples for every endpoint
- **[OpenAPI Spec](https://github.com/Anton-Payments/api-core/blob/main/docs/openapi.yaml)** — generate a typed client in any language
- **Idempotent by design** — safe to retry any request without creating duplicate payouts
- **Sandbox environment** — full API access with test keys, no real money moves
- **Webhooks** — real-time event notifications for every payout state change

### Security

If you discover a vulnerability, please review our **[Security Policy](https://github.com/Anton-Payments/.github/blob/main/SECURITY.md)** for responsible disclosure guidelines.

---

<div align="center">

**[Website](https://antonpayments.com)** · **[API Docs](https://docs.antonpayments.com)** · **[Contact Us](mailto:hello@antonpayments.com)**

<sub>© 2026 Anton Payments. All rights reserved.</sub>

</div>
