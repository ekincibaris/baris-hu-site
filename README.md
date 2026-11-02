# baris.hu

Source of my personal bilingual (English / Hungarian) CV website: **[baris.hu](https://baris.hu)**

A single static page, hosted on AWS:

```
Route 53 → CloudFront (AWS WAF, ACM) → private S3 bucket (Origin Access Control)
```

The infrastructure behind it is managed with Terraform in a separate repository:
**[baris-hu-terraform](https://github.com/ekincibaris/baris-hu-terraform)**

## What's here

- `index.html`: the whole site, in both languages
- `assets/`: self-hosted fonts, icons, flags and the social preview image
- `ekinci_muhammed_baris_cv.pdf`: my CV

## Built with

HTML · CSS · Amazon S3 · Amazon CloudFront · AWS WAF · Route 53 · ACM · Terraform

Fonts: [Inter](https://rsms.me/inter/) and [Fira Code](https://github.com/tonsky/FiraCode) (SIL Open Font License) ·
Icons: [Phosphor](https://phosphoricons.com/) (MIT)
