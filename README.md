# shopify-seo-schema-snippets
Clean JSON-LD schema snippets for Shopify to improve SEO &amp; rich results.
# 🧠 Shopify SEO Schema Snippets

A powerful, flexible, and modular set of **JSON-LD schema snippets** built specifically for **Shopify themes**. This repo helps developers and merchants implement structured data across product pages, business info, reviews, FAQs, and more — with complete control, full fallback logic, and no dependency on apps.

Whether you're building a custom Shopify theme or optimizing a live store for SEO and rich results, this is your toolbox.

---

## ✨ Why This Project?

Shopify themes often miss or bloat structured data, especially when relying on review apps or third-party integrations. That leads to:

- Invalid schema warnings in Google Search Console  
- Missed opportunities for rich results (stars, FAQs, breadcrumbs, etc.)  
- Duplicate `review` or `product` types in the DOM  

This repo fixes that with **clean**, **modular**, and **smart fallback-driven** snippets for every common schema type, ready to plug into any Shopify theme.

---

## 🗂 Folder Structure & Contents

```bash
snippets/
│
├── products/                   # All types of Product schema
│   ├── product-basic.liquid
│   └── product-with-reviews.liquid
│
├── reviews/                    # Review and AggregateRating schemas
│   ├── manual-review-schema.liquid
│   └── metafield-review-schema.liquid
│
├── business/                   # Local business & brand identity schemas
│   ├── local-business-schema.liquid
│   └── organization-schema.liquid
│
├── merchant-listing/           # Google Merchant Center-compatible product formats
│   ├── merchant-product-schema.liquid
│   └── merchant-feed-snippet.liquid
│
└── meta/                       # Non-product schemas: FAQPage, BreadcrumbList, etc.
    ├── faq-schema.liquid
    ├── breadcrumb-schema.liquid
    └── webpage-schema.liquid
