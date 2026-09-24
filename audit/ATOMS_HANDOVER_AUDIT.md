# Atoms Handover Audit — Fast Track

Date: 2026-09-25
Status: IN PROGRESS

## Immediate objective
Recover the Atoms source, preserve the original, produce a clean build, update public corporate/product content, and prepare an indexable deployment without publishing unsupported claims.

## Confirmed in export
- React 18 + TypeScript + Vite frontend.
- Spanish/English corporate content and routes.
- robots.txt and sitemap.xml.
- Schema.org / JSON-LD implementation layer.
- Prerender tooling is declared in the frontend dependencies.
- Corporate entity documents for DCT Invent, Momentum Systems, Huizhou Duran Creative, Lidafeng, Fuhe Chuangxing and Hong Kong M2M.
- Product documents for Instaflash, V16 IoT, My Cluster, Operational Mobility and Connected Worker.
- SEO/entity/Knowledge Graph/LinkedIn/external-authority/content roadmaps.
- 36 photo-review assets.
- Atoms architecture/progress documentation.

## Blocking / risk items already identified
1. Domain/contact data must be made definitive before production metadata and sitemap are trusted.
2. Ownership percentages and legal relationships remain evidence-controlled; do not publish `owns` relationships.
3. Amy/Liu Qiuping exact public title remains pending.
4. Huizhou Lidafeng sensitive registry fields flagged by management must remain unpublished.
5. Public product architecture must use current My Cluster Google/Gemini/Google Maps context; Azure material is legacy.
6. Photo-review assets must not be treated as public merely because they are under a frontend public directory.
7. robots.txt is not access control.
8. Structured data must match visible public content.
9. Search Console/Bing/indexing evidence must be verified after deployment.

## Fast-track sequence
- [x] Create governed repository `Momentumsystems1/presencia`.
- [x] Verify full Atoms source export exists.
- [ ] Preserve original export under archive/atoms.
- [ ] Recover source under website/.
- [ ] Run clean lint/build.
- [ ] Update corporate/product source-of-truth content.
- [ ] Audit routes, canonical, hreflang, JSON-LD, robots and sitemap.
- [ ] Remove/protect non-public review assets.
- [ ] Produce staging deployment.
- [ ] Management review.
- [ ] Production deployment.
- [ ] Submit/verify indexing and external entity signals.

## Publication rule
CODE ≠ PRODUCT VISION ≠ CORPORATE FACT ≠ STRATEGIC HYPOTHESIS.

Nothing becomes a public corporate fact merely because it exists in the Atoms export.
