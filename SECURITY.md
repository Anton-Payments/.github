# Security policy

## Reporting a vulnerability

Please don't report security issues in public GitHub issues.

Email **security@antonpayments.com** with:

- what you found and where
- steps to reproduce it
- the impact you think it has
- the name or handle you'd like credited, if any

We acknowledge reports within 2 business days and send an initial assessment within 5. You'll hear a fix timeline once we know the severity.

## In scope

- The Anton API, in production and the sandbox (`api.antonpayments.com`, `api.antonpayments.dev`)
- The merchant portal and sign-in (`app.` and `auth.` on both domains)
- Our website and the public docs (`docs.antonpayments.com`, `Anton-Payments/docs`)

## Out of scope

- Social engineering, phishing and physical attacks
- Denial of service and volumetric testing
- Vulnerabilities in third-party services or dependencies (please report those upstream)

Test against the sandbox, not production, and never against other customers' data. If you're unsure whether something is in scope, ask us first.

## Compliance

Our regulatory registrations and compliance programme are described in the [compliance statement](https://www.antonpayments.com/legal/compliance-statement/).
