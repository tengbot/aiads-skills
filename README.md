# AIADS Skills

Ad creation skills for AI agents.

Built for [AIADS.IM](https://aiads.im), an AI Ads Generator for UGC video ads, product videos, hooks, scripts, translations, and ad creative variations.

## What this is

AIADS Skills is a public kit of prompts, Codex-style Skills, ad templates, and SEO page templates for building AI ad creative tools.

It is designed for builders who want AI agents to help create:

- UGC video ad hooks
- product video ad scripts
- URL to video ad briefs
- product image to ad video storyboards
- TikTok, Reels, Shorts ad angles
- localized ad scripts and captions
- creative variation sets
- AI ad landing pages

## Built for AIADS.IM

AIADS.IM is an AI ad creative production platform.

Main site:

- [https://aiads.im](https://aiads.im)

The product direction is simple:

```text
Input product -> Generate ad creatives
```

The workflow:

```text
Product image / URL / description / script / reference ad
-> ad angle
-> hook
-> script
-> storyboard
-> video
-> captions
-> voiceover
-> creative variations
-> download
```

## What is included

- AI ad creation Skills
- Hook generation prompts
- UGC ad script templates
- Product video ad templates
- Ad brief templates
- Storyboard templates
- Creative variation templates
- SEO page templates for AI ad tools
- Route, footer, sitemap, and canonical rules
- Responsible AI ad page guidelines

## What is not included

This repository does not include the private AIADS product codebase.

It does not include:

- model provider integrations
- API keys
- payment logic
- credit logic
- database schema
- auth logic
- private prompt database
- user data
- deployment secrets

The real product code should stay private.

## Quick start

Use the ad creation Skills when building or reshaping an AI ad tool site.

```text
Use the aiads-skills workflow.

Brand brief:
brandName: AI Ads
domain: https://aiads.im
mainKeyword: AI Ads Generator
homepageTitle: AI Ads Generator for UGC & Product Videos | AI Ads
homepageH1: AI Ads Generator
homepageDescription: Create UGC video ads, product videos, hooks, thumbnails, translations, and ad variations for TikTok, YouTube, Instagram, Facebook, and X.

Create or update:
/
/ad-video-generator
/product-image-to-video
/url-to-video
/ugc-video-ads
/product-video-generator
/ai-hook-generator
/ai-ad-script-generator
/ad-translation
/pricing

Do not touch payment, database, API keys, or private product logic.
```

## Repository structure

```text
.agents/skills/aiads-site-skill/SKILL.md
.agents/skills/hook-skill/SKILL.md
.agents/skills/ad-script-skill/SKILL.md
prompts/
templates/
examples/
docs/
```

## Why this exists

A lot of AI ad tools fail because they only ship a generic video generator. Real ad workflows need focused creative steps:

- ad angle
- hook
- script
- storyboard
- product video
- UGC style
- captions
- CTA
- localized variants
- batch creative variations

This kit gives AI agents a repeatable way to create useful ad creative assets without turning the product into a pile of thin SEO pages.

## Responsible marketing note

Use these templates to create useful ad drafts and creative variations.

Do not promise:

- guaranteed viral results
- guaranteed ROI
- guaranteed conversions
- guaranteed sales

Use safer language:

- designed for faster creative testing
- helps generate draft ad creatives
- helps create multiple creative angles
- helps localize ad assets
- helps produce ad variations

## Links

- AIADS.IM: [https://aiads.im](https://aiads.im)
- Main keyword: AI Ads Generator
- Core workflow: Input product -> Generate ad creatives
