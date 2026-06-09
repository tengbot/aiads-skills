# CTA Variants Prompts

Prompt patterns for ad CTA testing.

Main site: https://aiads.im

## CTA batch prompt

```text
Product: {{product}}
Audience: {{audience}}
Offer: {{offer}}
Platform: {{platform}}
Funnel stage: {{funnel_stage}}
Tone: {{tone}}

Generate 30 CTA variants.
Group them by:
- soft CTA
- direct response CTA
- ecommerce CTA
- urgency CTA
- educational CTA
- creator style CTA

For each CTA, include:
- CTA text
- best use case
- risk level
- notes

Avoid fake urgency and guaranteed results.
```

## CTA localization prompt

```text
Translate and localize these CTAs for {{target_market}}.

Source CTAs:
{{ctas}}

Product: {{product}}
Platform: {{platform}}
Tone: {{tone}}

Return:
- localized CTA
- literal meaning
- local tone note
- what to avoid
```
