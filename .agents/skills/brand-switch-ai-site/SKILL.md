---
name: brand-switch-ai-site
description: Use this skill when switching an AI tools project to a new brand, new domain, new model keyword, or fresh AI trend site. It plans and updates homepage SEO, routes, footer, sitemap, canonical URLs, prompt pages, model pages, tool pages, and style pages.
---

# Brand Switch AI Site Skill

## Purpose

This Skill helps builders launch or reshape lightweight AI tool sites.

It was created for [IMGTO](https://imgto.io), an image-to-everything AI tools brand focused on Image to Video AI workflows.

Use this Skill when the task involves:

- changing brand name
- changing domain
- changing homepage keyword
- launching a fresh model keyword site
- creating AI tool pages
- creating model pages
- creating prompt pages
- creating style or effect pages
- updating footer links
- updating sitemap
- updating canonical URLs
- planning SEO routes

## Default strategy

A good AI tool site should not rely on a homepage only. Build a small system of useful pages:

- homepage
- workspace pages
- model pages
- tool pages
- video tool pages
- prompt library pages
- prompt pack pages
- style pages
- comparison pages
- pricing page

Every indexable page should be useful on its own.

## Site types

### Image to Video site

Use when the homepage should focus on image-to-video workflows.

Example homepage:

```text
Title: Image to Video AI Generator | IMGTO
H1: Image to Video AI Generator
Description: Turn images into videos, animations, product clips, and social ads with IMGTO AI tools.
```

### Model keyword site

Use when the homepage targets a fresh model keyword.

Example:

```text
Title: Grok Image 1.5 AI Image Generator | Brand
H1: Grok Image 1.5 AI Image Generator
```

### All in one AI tool site

Use when the homepage targets a brand and a broad AI tool platform.

Example:

```text
Title: Brand AI Image & Video Generator
H1: Brand AI Image & Video Generator
```

### Tool keyword site

Use when the entire site focuses on one tool category.

Example:

```text
Title: AI Photo Enhancer | Brand
H1: AI Photo Enhancer
```

## Brand brief format

Ask the user for missing values only when required. Infer safe defaults when possible.

```yaml
brandName: IMGTO
domain: https://imgto.io
siteType: image-to-video-site
mainKeyword: Image to Video AI Generator
mainSlug: image-to-video
tagline: Image to Everything
homepageTitle: Image to Video AI Generator | IMGTO
homepageH1: Image to Video AI Generator
homepageDescription: Turn images into videos, animations, product clips, and social ads with IMGTO AI tools.
defaultWorkspace: video
defaultVideoMode: image-to-video
primaryCTA: Create Image to Video
secondaryCTA: Explore Image Tools
primaryPromptPage: /prompts
enabledWorkspaces:
  - image
  - video
  - music
enabledModels:
  - gpt-image-2
  - nano-banana-2
  - nano-banana-pro
  - grok-imagine
  - seedance-2-fast
enabledTools:
  - image-to-video
  - text-to-video
  - ai-animation-generator
  - image-upscaler
  - background-remover
  - photo-enhancer
  - image-to-prompt
promptCategories:
  - Product Visuals
  - Poster Design
  - Portrait
  - Character Consistency
  - Infographic
  - Reference Edit
```

## Route strategy

Keep core model and tool routes flat when possible.

Good flat routes:

```text
/image-to-video
/text-to-video
/ai-video-generator
/image-to-animation
/ai-animation-generator
/gpt-image-2
/grok-imagine
/seedance-2-fast
/image-upscaler
/background-remover
/photo-enhancer
/photo-restoration
/image-converter
/headshot-generator
/ai-body-shake
/video-face-swap
/video-translate
/pricing
```

Workspace routes:

```text
/image
/video
/music
```

Do not redirect `/image` to `/ai-image-generator`.
Do not redirect `/video` to `/ai-video-generator`.

If `/ai-image-generator` or `/ai-video-generator` exists, make it a hub page, not a duplicate workspace page.

Use directories for page families:

```text
/prompts/product-visuals
/prompts/poster-design
/styles/photo-to-sketch
/styles/action-figure-generator
/apps/product-video
/use-cases/social-media-video
```

## Page templates

### Homepage

Required sections:

1. Hero
2. Main workspace or generator
3. Explore tools
4. Models
5. Video tools
6. Image tools
7. Prompt tools
8. Showcase
9. How it works
10. FAQ
11. Footer

For IMGTO-style sites, the homepage should focus on Image to Video first.

### Tool page

Required sections:

- exact H1
- short value proposition
- upload or input area
- settings
- generate button
- results area
- showcase
- how to use
- use cases
- related tools
- FAQ
- self canonical

### Video tool page

Use for:

```text
/image-to-video
/text-to-video
/image-to-animation
/ai-animation-generator
/ai-body-shake
/video-face-swap
/video-translate
/video-watermark-remover
```

Add responsible use notes where needed.

For watermark tools:

```text
Only upload videos you own or have permission to edit.
```

For face tools:

```text
Upload only photos or videos you own or have permission to use.
```

### Model page

Use for:

```text
/gpt-image-2
/grok-imagine
/nano-banana-2
/seedance-2-fast
```

Required sections:

- H1: `{Model Name} Generator`
- model description
- model-specific workspace or CTA
- what it is best for
- prompt examples
- related models
- related tools
- FAQ
- self canonical

### Prompt library page

Prompt cards should use consistent fields:

- title
- use case
- prompt text
- model suggestion
- category
- copy action
- use this prompt action

Remove low-quality prompt fields:

- phone numbers
- marketplace prices
- unrelated bios
- random metadata
- unsafe personal data

### Prompt pack page

Use for:

```text
/prompts/product-visuals
/prompts/poster-design
/prompts/character-consistency
```

Required sections:

- H1
- intro
- 10 to 20 prompts
- copy action
- use this prompt action
- related prompt packs
- related tools
- FAQ

### Style or effect page

Use for:

```text
/styles/photo-to-sketch
/styles/action-figure-generator
/styles/coloring-page
/styles/product-photo-generator
```

Required sections:

- H1
- short description
- upload or prompt entry
- examples
- prompt gallery
- how to use
- related styles
- related tools
- FAQ
- self canonical

Avoid trademark-heavy page names unless the user explicitly accepts that risk.

## Footer rules

Footer is an SEO distribution layer.

Use one consistent footer across indexable pages.

Recommended groups:

```text
Product
  Image to Video
  Video Workspace
  Image Workspace
  Pricing

Video Tools
  Image to Video
  Text to Video
  AI Video Generator
  Image to Animation
  AI Animation Generator
  AI Body Shake
  Video Face Swap
  Video Translate
  Video Watermark Remover

Image Tools
  Photo Enhancer
  Image Upscaler
  Background Remover
  Photo Restoration
  Image Converter
  AI Headshot Generator
  Image to Prompt

Models
  GPT Image 2
  Nano Banana 2
  Nano Banana Pro
  Grok Imagine
  Gemini Omni
  Seedance 2
  Seedance 2 Fast

Prompts
  Prompt Library
  GPT Image 2 Prompts
  Nano Banana Prompts

Resources
  History
  Docs
  Blog
  Contact

Legal
  Terms
  Privacy
  Refund
  Cookies
```

Do not link unfinished pages from the footer.

## Sitemap rules

Only finished canonical pages go into sitemap.

Include:

- homepage
- finished model pages
- finished tool pages
- finished video tool pages
- finished prompt pages
- finished style pages
- pricing

Exclude:

- empty pages
- coming soon pages
- noindex pages
- duplicate pages
- test pages
- query URL pages
- unfinished music pages

## Canonical rules

Every indexable page needs a self canonical.

Do not canonical `/image` to `/ai-image-generator` unless they are duplicates and the user chose that URL as canonical.

Preferred:

```text
/image = workspace page with self canonical
/video = workspace page with self canonical
/ai-video-generator = hub page with self canonical
/image-to-video = SEO tool page with self canonical
```

Parameter URLs should not become indexable pages.

Preferred handling:

- redirect to a clean URL
- or canonical to a clean page

## Metadata rules

Each indexable page must have:

- title
- description
- canonical
- Open Graph title
- Open Graph description
- Open Graph URL
- one H1

Title patterns:

```text
{Keyword} | {Brand}
{Model Name} Generator | {Brand}
{Tool Keyword} | {Brand}
{Prompt Pack Keyword} | {Brand}
```

Avoid:

- vague titles
- keyword stuffing
- duplicate templates
- old brand names
- unrelated model names

## Safety and quality rules

Avoid launching pages focused on:

- celebrity impersonation
- copyrighted character style names
- official brand or logo misuse
- body shaming transformations
- misleading watermark removal claims

Sensitive tools need responsible use language.

## Execution steps

1. Inspect config, routes, footer, sitemap, metadata helpers, and page registries.
2. Plan files to modify, pages to create, pages to exclude from sitemap, and footer updates.
3. Update central config first.
4. Update homepage keyword and hero.
5. Update model and prompt pages.
6. Update footer and navigation.
7. Update sitemap and canonical URLs.
8. Run checks.
9. Report changed files, new routes, sitemap changes, and unresolved issues.

## Done checklist

- Brand name is consistent.
- Domain is consistent.
- Homepage title and H1 match the main keyword.
- Footer links only finished pages.
- Sitemap contains only finished canonical URLs.
- No private code or secrets are exposed.
- Prompt examples are clean.
- Responsible use notes are present when needed.
