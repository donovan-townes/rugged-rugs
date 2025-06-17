# Rugged Rugs – Marketing Site
> “Rugs that Last” – Durable wholesale carpets in custom sizes.

## 1. Goal ✅
Launch a single-page, fast-loading marketing site that converts visitors into leads via a contact form.

## 2. Content Outline ✅
- **Hero**  
  - Headline: “Rugs that Last”  
  - Sub-head: Wholesale retailer of durable, high-quality rugs.  
  - Primary CTA button → “Get a Quote”
- **Three Value Propositions**  
  1. Durable & High Quality  
  2. Big & Assorted Inventory  
  3. Custom Sizes Available
- **Contact Section**  
  - Form fields: Name · Email · Phone · Description  
  - Secondary CTA: “Tell us what you need!”
- **Footer** (minimal)  
  - Location, hours, social links

## 3. Tech Stack
| Layer | Choice | Why |
| ----- | ------ | --- |
| Framework | **Next.js 15** (App Router) | Built-in SEO & edge rendering |
| Styling | Tailwind CSS | Rapid, utility-first layout |
| Forms | React Hook Form → EmailJS (v1) | No backend needed for MVP |
| Hosting | Vercel | CI/CD out of the box |

## 4. MVP Acceptance Criteria
- Deploys in < 1 s Time-to-First-Byte on Vercel.
- Lighthouse ≥ 90 (Performance, Accessibility, Best-Practices, SEO).
- Contact form sends email to `orders@ruggedrugs.test` and shows “Thank you” toast.
- Page passes axe accessibility scan with zero critical issues.

## 5. Stretch Goals (v2+)
- CMS (Sanity) for easy copy edits.
- Postgres + Prisma to store leads.
- Customer testimonials slider.
- i18n (ES, FR).

## 6. Getting Started
```bash
pnpm install
pnpm dev      # localhost:3000
