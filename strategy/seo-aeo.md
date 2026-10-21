# InjeraDAO organic discovery: SEO + AI answer-engine optimization

**Canonical brand:** InjeraDAO. **Canonical domain:** https://injera.network.

## North-star outcomes
1. Be the clearest truthful answer to “What is InjeraDAO?”
2. Build genuinely useful, citable pages for “what is injera,” “Ethiopian food,” “Eritrean food,” “injera near me” and city-specific food discovery.
3. Convert discovery to a meaningful action: **Find injera**, learn about the cuisine or attend a confirmed community gathering.
4. Earn credible local mentions, food-business links and cultural community referrals.

## Audience × intent
| Audience | Question | Content target | CTA |
|---|---|---|---|
| First-time diners | What is injera? | /learn/what-is-injera | Find injera |
| Curious food lovers | What dishes come with injera? | /learn/ethiopian-eritrean-food | Explore food |
| Local diners | Where to buy injera nearby? | /restaurants/{city} only where verified listings exist | Find injera |
| Diaspora | Where are Habesha restaurants? | Country/city directory with real source-backed entries | Suggest a place |
| Builders | What is InjeraDAO? | /about | Explore community |
| Gatherers | What meetups are scheduled? | /community/gatherings | RSVP only to confirmed event |

## Must-have technical SEO
- Serve primary content as crawlable HTML, including SSR or SSG when appropriate; avoid client-only empty shells.
- Use **one unique title, H1, meta description and self-referencing canonical** per indexable page.
- Deploy HTTPS, XML sitemap with only canonical 200-status URLs, robots.txt with valid sitemap entry, and no accidental noindex.
- Ensure clean internal links, sensible breadcrumbs, mobile usability, contrast, descriptive images, informative alt text and fast page loads.
- Generate Open Graph / Twitter metadata for shareability using licensed originals; use 1200×630 share images where supported.
- Produce correct 404s for removed/unknown entries. Use 301 redirects for moved URLs.
- Make city pages only when there are real, sufficiently detailed venues; **do not manufacture hundreds of thin location pages**.
- For dynamic listings, include sources, observation dates, prices currency + checked date, menu verified date and uncertainty.
- Track Search Console indexing, impressions, queries, clicks and CTR by landing page.
- Check datePublished/dateModified against real publication/editorial history; never change dateModified just to look fresh.

## Structured data
Use JSON-LD reflecting visible facts. See `seo/structured-data.json` for baseline Organization, WebSite and AboutPage objects; adapt contextually. For verified restaurant details, use appropriate Restaurant/LocalBusiness and address data; for real scheduled gatherings, Event with confirmed location and startDate. Add BreadcrumbList to hierarchical pages. Only use Recipe for a real, tested recipe with ingredients and instructions. Never synthesize ratings, review counts, venue ownership or future event dates.

Google limits FAQ rich results heavily; FAQs are still useful for humans and answer engines but **do not promise FAQ rich snippets**.

## AI answer-engine optimization (AEO)
- Lead pages with a **direct one- or two-sentence answer** before deeper explanation.
- Answer adjacent follow-ups under semantic headings, with natural language, not keyword stuffing.
- Maintain a consistent, stable definition of InjeraDAO in About, homepage, FAQ, metadata and social bios.
- Distinguish the community from restaurants: **InjeraDAO does not operate every listed restaurant**.
- Include responsible author/editor attribution, source links for historical and numerical claims and a clear update timestamp.
- Provide original firsthand restaurant/menu evidence (permissioned photos, observed details, direct confirmations) rather than recycled summaries.
- Preserve crawlable internal links between foundational guides, regional dish pages, city searches and events.
- Publish a plain-language organization description in a public README and, optionally, a clearly maintained `/llms.txt`; do not assume AI crawlers obey it or that it boosts rankings.
- Measure AI referrals when detectable, while acknowledging that not every assistant provides referral data or citations.

## Priority content architecture
**P0:** /, /about, /learn/what-is-injera, /learn/ethiopian-eritrean-food, /community/gatherings, /faq, /restaurants (or site's actual discovery route).

**P1:** Distinct researched pages for teff, fermentation, shiro, misir wat, gomen, doro wat, tibs, zigni, vegetarian food, gluten caveats, dining etiquette and ingredient shops.

**P2:** Verified city pages for Nairobi, Addis Ababa, Asmara and other cities *only as usable data becomes available*. Add language variants only with human-reviewed translation, hreflang and reciprocal alternate URLs.

## On-page content checklist
- Original useful facts, not filler
- Accurate spelling variants where relevant, without duplicating whole pages
- Opening direct answer
- Clear relevant H2 questions
- Local context and sourced details
- Visible last verification when it matters
- Canonical + metadata + schema aligned
- Relevant contextual links
- One useful action, with **Find injera** leading on food-discovery pages

## Validation and measurement
Weekly: broken links, 404s, missing metadata, sitemap diff, indexed URLs, Search Console coverage. Monthly: top queries, content decay, city-page accuracy, conversions to venue detail and verified contributions. Quarterly: cultural/editorial review, duplicate-content cleanup, privacy/location handling review and AEO audit by comparing answer accuracy—not ranking guesses.

## Reference
- https://developers.google.com/search/docs/appearance/structured-data/sd-policies
- https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview
- https://developers.google.com/search/docs/appearance/structured-data/intro-structured-data
- https://developers.google.com/search/blog/2023/08/howto-faq-changes
- https://schema.org
