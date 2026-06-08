# Brand Brief Template

Copy this brief when launching a new AI tool site or switching a project to a new brand.

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
pagesToCreate:
  - /
  - /image-to-video
  - /text-to-video
  - /ai-video-generator
  - /image-to-animation
  - /ai-animation-generator
  - /pricing
pagesToNoindex:
  - /music
notes:
  - Keep /image and /video as workspace routes.
  - Do not redirect workspace routes to hub pages.
  - Only add finished canonical pages to sitemap.
```
