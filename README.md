# FreeAI.run

[English](./README.md) | [中文](./README_zh.md) | [日本語](./README_ja.md)

Discover the best free AI tools, AI websites, and curated AI resources in one directory.  
FreeAI.run helps users find practical AI products faster, while giving founders a clearer place to submit, promote, and grow discovery through multilingual SEO pages.

Live site: [https://www.freeai.run](https://www.freeai.run)  
GitHub: [https://github.com/a136332462/FreeAI.run](https://github.com/a136332462/FreeAI.run)

## What FreeAI.run Is

FreeAI.run is a multilingual AI tools directory focused on discovery, ranking, comparison, and promotion.

It is built around four public-facing goals:

- Help users discover useful free AI tools across writing, design, video, productivity, coding, marketing, and more.
- Organize listings into SEO-friendly pages such as categories, best-of collections, monthly updates, open-source roundups, affiliate pages, and discount pages.
- Give product owners a clear submission flow with free listing and paid visibility upgrades.
- Support ongoing promotion through featured directory placements and native ad placements inside the site.

## Main Public Pages

| Page | URL | Purpose |
| --- | --- | --- |
| Home | [https://www.freeai.run/](https://www.freeai.run/) | Main landing page for AI tool discovery, search, featured exposure, and category navigation |
| Free AI Tools | [https://www.freeai.run/free-ai-tools](https://www.freeai.run/free-ai-tools) | Dedicated entry for tools with real free pricing |
| All Free AI Tools | [https://www.freeai.run/free-ai-tools/all](https://www.freeai.run/free-ai-tools/all) | Full free-priced tools listing |
| Free AI Tools by Category | [https://www.freeai.run/free-ai-tools/[slug]](https://www.freeai.run/free-ai-tools) | Category-specific free AI tools pages |
| Best AI Tools | [https://www.freeai.run/best-ai-tools](https://www.freeai.run/best-ai-tools) | Curated best AI tools collection |
| Best AI Tools by Year | [https://www.freeai.run/best-ai-tools/[year]](https://www.freeai.run/best-ai-tools) | Year-based best AI tools archives |
| New This Month | [https://www.freeai.run/new](https://www.freeai.run/new) | Latest tools added to the directory |
| Monthly Archive | [https://www.freeai.run/new/[month]](https://www.freeai.run/new) | Archive of monthly additions |
| Categories | [https://www.freeai.run/categories](https://www.freeai.run/categories) | All categories overview |
| Category Detail | [https://www.freeai.run/categories/[slug]](https://www.freeai.run/categories) | Category-specific landing pages |
| Search | [https://www.freeai.run/search](https://www.freeai.run/search) | Internal search for AI tools and websites |
| Explore | [https://www.freeai.run/explore](https://www.freeai.run/explore) | Browse by pricing model, platform, and founded year |
| Open Source | [https://www.freeai.run/open-source](https://www.freeai.run/open-source) | Open-source AI tools and software |
| Affiliate | [https://www.freeai.run/affiliate](https://www.freeai.run/affiliate) | Listings with affiliate programs |
| Discount | [https://www.freeai.run/discount](https://www.freeai.run/discount) | Tools offering discounts or promo codes |
| Product Detail | [https://www.freeai.run/product/[slug]](https://www.freeai.run/product) | SEO landing page for each tool |
| Skills Hub | [https://www.freeai.run/skills](https://www.freeai.run/skills) | Skills articles and documentation-style content |
| Skill Article | [https://www.freeai.run/skills/[slug]](https://www.freeai.run/skills) | Individual long-form article page |
| Pricing | [https://www.freeai.run/pricing](https://www.freeai.run/pricing) | Public pricing page for submit plans and advertise plans |
| Submit | [https://www.freeai.run/submit](https://www.freeai.run/submit) | Tool submission flow |
| Advertise | [https://www.freeai.run/advertise](https://www.freeai.run/advertise) | Ad creative creation and checkout flow |

## Core Product Value

- Directory SEO: category pages, free-pricing pages, best-of pages, monthly new pages, and product pages create long-tail discovery paths.
- Multilingual reach: English, Simplified Chinese, and Japanese routes are supported.
- Founder conversion: the site does not only list tools, it also turns traffic into submissions, upgrades, and ad purchases.
- Editorial structure: FreeAI.run is more than a flat list page. It combines directory pages, curated collections, content pages, and product detail pages.

## Submission Plans

FreeAI.run currently supports both free submission and paid listing upgrades.

### Free Listing

- Submit your tool for free
- Basic directory listing
- Standard visibility
- Requires a dofollow backlink in the website footer
- Manual review required
- Badge selection is supported during submission
- Daily free quota limits are enforced in the submission flow
- Current quota rule: `1` free submission per logged-in user per UTC day

### One-Time

Price: **$9.99 / lifetime**

- Featured on homepage
- Highlighted listing
- 3+ dofollow backlinks
- Permanent listing without backlink requirement
- Instant approval and immediate go-live
- Standard directory listing
- One-time payment with lifetime access
- No badge required
- Priority support
- Used as the paid fast-track option when the free daily quota is exhausted

### Monthly Promotion

Price: **$5.00 / month**

- Auto-refresh to top monthly
- Continuous homepage exposure
- Always highlighted
- 5+ dofollow backlinks
- Higher visibility across the directory
- Permanent listing without backlink requirement
- Instant approval and immediate go-live
- Included in the AI tools directory
- No badge required
- Priority support
- Marked as a popular plan on the public pricing page

### Featured Listing

Price: **$29.00 / month**

- Site-wide top banner exposure with rotation
- Premium spotlight on high-traffic pages
- Continuous homepage exposure
- Promotion across almost every page
- Featured across multiple key pages in the directory
- Strong brand visibility and consistent traffic boost
- Higher visibility across all listings
- Permanent listing without backlink requirement
- Instant approval and immediate go-live
- Included in the AI tools directory
- No badge required
- Priority support
- Higher-visibility directory exposure than standard paid listings

## Advertising and Promotion

FreeAI.run also includes a separate advertise flow for products that are already listed in the directory.

The current implementation supports:

- Choosing an existing listed product before creating an ad
- Localized ad titles, landing URLs, and short ad copy in English, Chinese, and Japanese
- Payment checkout through the same payment infrastructure used by listing upgrades
- Creative review before delivery
- User dashboard status tracking for payment, review, and campaign delivery
- Impression logging and click tracking

### Current Ad Placements

- `home_top`: homepage top banner placement
- `home_welcome_ad`: sponsored badge in the homepage hero/welcome area
- `list_mid_recommend`: sponsored card inserted into directory grids
- `product_detail_sidebar_card`: sponsored card on product detail pages

### Important Note About Ad Pricing

Advertise plans are rendered from the live pricing configuration used by the site and can be managed separately from the static repository files.  
In my verification pass, the submit-side pricing was readable directly from the live `/pricing` page, while the advertise-side plan cards were still dynamically gated behind the tab state in this environment.  
For that reason, the safest source of truth for current ad package names and prices remains the live pricing flow:

- [https://www.freeai.run/pricing](https://www.freeai.run/pricing)
- [https://www.freeai.run/advertise](https://www.freeai.run/advertise)

## Dashboard and Operations

FreeAI.run includes authenticated dashboards for both users and admins.

User-facing areas include:

- My orders
- Profile and listing management
- Advertise management
- Settings

## Content and SEO Structure

FreeAI.run is designed to rank across multiple search intents, not only for branded traffic.

Key SEO-oriented content layers include:

- Free AI tools pages
- Best AI tools pages
- Monthly new tool archives
- Category landing pages
- Product detail pages
- Open-source pages
- Affiliate program pages
- Discount pages
- Skills / documentation-style content

This structure helps the project target both high-volume keywords such as `free ai tools` and long-tail terms such as category, year, pricing-model, and product-name queries.

## Languages

The project supports:

- English
- Simplified Chinese
- Japanese

Locale behavior:

- English uses default routes without a prefix
- Chinese pages use `/zh`
- Japanese pages use `/ja`

Examples:

- English: [https://www.freeai.run/](https://www.freeai.run/)
- Chinese: [https://www.freeai.run/zh](https://www.freeai.run/zh)
- Japanese: [https://www.freeai.run/ja](https://www.freeai.run/ja)

## Who FreeAI.run Is For

- Users who want to find useful free AI tools without digging through low-quality list pages
- Founders who want more organic discovery for their AI products
- Marketers who want directory-native promotion placements
- Content operators who want a structured AI niche property with strong SEO landing-page coverage
