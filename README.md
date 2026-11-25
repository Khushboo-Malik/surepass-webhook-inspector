# Verification Webhook Inspector (concept for Surepass)

Unofficial concept by Khushboo Malik. Sample data only, not affiliated with Surepass.

A small dev-console view for teams integrating KYC APIs: each verification call with its webhook timeline, a plain-language reason and next step for each failure, and a replay that shows duplicate webhook deliveries being ignored (dedupe on request_id + event type).

Live: https://khushboo-malik.github.io/surepass-webhook-inspector/

Plain HTML + JS. Based on what I learned building KYC APIs on AWS at 1StopKYC and an idempotent Stripe webhook pipeline at Efficient Capital Labs.
