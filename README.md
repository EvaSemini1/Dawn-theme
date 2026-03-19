# Dawn-theme

PDP Bundle Banner A/B Test — Written Spec

1. Tool Choice and Reasoning

Convert.com - Allows page-specific targeting for PDPs, supports HTML/CSS/JS variations, tracks custom events (like add-to-cart), and manages sticky sessions for returning visitors. Ideal for testing a custom Shopify section without affecting non-PDP pages and personally super easy to use.

2. Full URL Targeting Rules

Include: /products/* — all product detail pages

Exclude: /collections/*, /cart, / (homepage)

3. Traffic Split and Minimum Sample Size Estimate

Traffic Split: 50% Control / 50% Variation

Minimum Sample Size: ~1,000–1,500 PDP sessions per variation (assuming 10% baseline add-to-cart rate, 95% confidence, 80% power). Alternatively, run for ≥ 2 weeks to capture day-of-week variation.

4. Primary and Secondary Success Metrics

Primary Metric: Add-to-cart rate

Definition: # of PDP sessions with at least one add-to-cart click ÷ total PDP sessions

Secondary Metric: Revenue per session / Average Order Value (AOV)

Definition: Total revenue generated from PDP sessions ÷ total PDP sessions

Goal: Measure if the bundle banner increases engagement and revenue.

5. QA Approach Before Launch

Verify desktop and mobile rendering of the banner

Check CTA links point to the bundles collection

Confirm event tracking for add-to-cart and revenue metrics

Test responsive design: heading, subheading, product image, CTA

Ensure no layout or script conflicts with existing PDP elements

Confirm sticky sessions so returning visitors see the same variation

6. Risks / Edge Cases

Mobile vs desktop text alignment and CTA visibility

Returning visitors must consistently see the same variation

Banner image size should not slow down page load

Conflicts with other Shopify apps or scripts could affect layout or tracking