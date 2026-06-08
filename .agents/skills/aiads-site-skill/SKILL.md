---
name: aiads-site-skill
description: Use this skill when planning or building an AI ad creative production site. It focuses on AI ads generator pages, UGC video ads, product image to video, URL to video, ad hooks, ad scripts, ad translation, footer links, sitemap, and responsible ad page rules.
---

# AIADS Site Skill

## Purpose

This Skill helps AI agents plan, write, and audit AI ad creative production sites.

It was created for [AIADS.IM](https://aiads.im), an AI Ads Generator for UGC video ads and product video ads.

The core workflow is:

```text
Input product -> Generate ad creatives
```

Expanded workflow:

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

## Positioning

AIADS is not a general AI video platform.

AIADS is an ad creative production platform for:

- ecommerce sellers
- DTC brands
- paid media teams
- creative agencies
- affiliate marketers
- solo founders
- content marketers

## P0 pages

Start with these pages:

```text
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
```

Do not implement second-batch pages until the P0 pages are useful.

## Homepage rules

Homepage title:

```text
AI Ads Generator for UGC & Product Videos | AI Ads
```

Homepage H1:

```text
AI Ads Generator
```

Homepage description:

```text
Create UGC video ads, product videos, hooks, thumbnails, translations, and ad variations for TikTok, YouTube, Instagram, Facebook, and X.
```

Homepage must feel like an ad workspace, not a generic AI video generator.

Required inputs:

- Ad goal
- Product URL or product description
- Product image or reference media
- Target platform
- Ad format
- Model
- Duration
- Aspect ratio
- Brand voice

Required output story:

- angle
- hook
- script
- storyboard
- video
- captions
- voiceover
- variants
- download

## Page templates

### Ad video generator page

Use for `/ad-video-generator`.

Required sections:

- H1: AI Ad Video Generator
- ad workspace CTA
- input types
- ad formats
- example workflows
- related ad tools
- FAQ

Related links:

- /product-image-to-video
- /url-to-video
- /ugc-video-ads
- /product-video-generator
- /ai-hook-generator
- /ai-ad-script-generator
- /ad-translation

### Product image to video page

Use for `/product-image-to-video`.

Required sections:

- H1: Product Image to Video Ad Generator
- product image upload CTA
- selling point input
- platform selector
- duration and ratio
- product video examples
- prompt examples
- how to use
- FAQ

Do not claim full product understanding if product analysis is not implemented.

### URL to video page

Use for `/url-to-video`.

Required sections:

- H1: URL to Video Ads Generator
- URL input
- product description fallback
- manual selling point field
- platform selector
- examples
- FAQ

If automatic URL extraction is incomplete, say that users can paste a product URL and add or edit product details before generation.

Do not claim full Shopify, Amazon, or TikTok Shop support unless implemented.

### UGC video ads page

Use for `/ugc-video-ads`.

Required sections:

- H1: AI UGC Video Ads Generator
- UGC angle examples
- hook styles
- creator tone options
- video ad CTA
- FAQ

Do not claim 1000+ actors or avatar libraries unless implemented.

### Hook generator page

Use for `/ai-hook-generator`.

This page can be useful before full AI output exists.

It may include:

- hook formulas
- hook examples
- copy buttons
- product brief input
- CTA to generate ad video

Do not use coming soon copy.

### Ad script generator page

Use for `/ai-ad-script-generator`.

It should produce or demonstrate:

- hook
- body
- proof
- objection handling
- CTA
- captions
- voiceover draft

### Ad translation page

Use for `/ad-translation`.

Required sections:

- H1: AI Ad Translation
- video upload or workspace CTA
- target language
- subtitle / caption localization
- voiceover localization
- examples
- FAQ

## Footer rules

Footer should only link finished pages.

Recommended groups:

```text
Product
  AI Ads Generator
  Pricing

Ad Video Tools
  AI Ad Video Generator
  UGC Video Ads
  Product Video Generator
  Product Image to Video
  URL to Video
  Ad Translation

Creative Tools
  AI Hook Generator
  AI Ad Script Generator

Workspaces
  Ad Video Workspace
  Ad Image Workspace

Future
  Hookclaw
  MCNOS

Legal
  Terms
  Privacy
  Refund
```

Do not link unfinished pages.

## Sitemap rules

Only finished canonical pages go into sitemap.

P0 sitemap:

```text
https://aiads.im/
https://aiads.im/ad-video-generator
https://aiads.im/product-image-to-video
https://aiads.im/url-to-video
https://aiads.im/ugc-video-ads
https://aiads.im/product-video-generator
https://aiads.im/ai-hook-generator
https://aiads.im/ai-ad-script-generator
https://aiads.im/ad-translation
https://aiads.im/pricing
```

Exclude:

- coming soon pages
- empty pages
- duplicate pages
- query URL pages
- noindex pages
- pages with empty FAQ

## Safety rules

Do not promise:

- guaranteed viral results
- guaranteed ROI
- guaranteed conversions
- guaranteed sales

Use:

- designed for faster creative testing
- helps generate draft ad creatives
- helps create multiple creative angles
- helps localize ad assets
- helps produce ad variations

For face, avatar, actor, talking head, or face swap tools, include:

```text
Only upload people, images, or videos you own or have permission to use.
```

## Done checklist

- Homepage is ad-focused.
- P0 pages have unique title, description, H1, canonical, examples, FAQ, and related links.
- Footer links only finished pages.
- Sitemap only includes finished canonical URLs.
- No private product code or secrets are included.
- No false performance guarantees are made.
