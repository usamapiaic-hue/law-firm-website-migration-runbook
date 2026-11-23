# Law Firm Website Migration Runbook

A step-by-step runbook for redesigning, re-platforming or changing the domain of a law firm website without losing the Google rankings and calls the old site earned. Published by [Legal Web Agency](https://legalwebagency.com/).

Most traffic losses after a redesign are not caused by the new design. They come from a handful of skipped steps: old URLs that stop working, practice pages that get merged or thinned out, and a staging site that was left blocked from search engines. This runbook lists those steps in the order they should happen. For the background, read our guide to a [lawyer website redesign without losing rankings](https://legalwebagency.com/lawyer-website-redesign-without-losing-rankings/).

## Phase 1: Before anything changes

| # | Task | Why it matters |
|---|------|----------------|
| 1 | Export every URL on the current site (sitemap plus a crawl). | This is the list you will redirect. Anything missing from it can turn into a 404 later. |
| 2 | Export 12 months of Search Console pages and queries. | Shows which pages actually bring clicks, so they are protected first. |
| 3 | Record current call and form volume per month. | Gives a baseline to compare against after launch. See [conversion tracking for law firms](https://legalwebagency.com/law-firm-website-conversion-tracking/). |
| 4 | Save the current titles, meta descriptions and H1s. | Pages that rank well should keep wording close to what is working. |
| 5 | Note backlinks that point to deep pages. | Those URLs need exact redirects, not a redirect to the homepage. |
| 6 | Run a content audit. | Decide what to keep, merge, rewrite or retire. See the [law firm website content audit](https://legalwebagency.com/law-firm-website-content-audit/). |

A full pre-launch review is covered in our [law firm SEO audit](https://legalwebagency.com/law-firm-seo-audit/) guide.

## Phase 2: Building the new site

1. **Keep URLs the same wherever possible.** The safest redirect is the one you never need.
2. **Do not thin out practice area pages.** A 1,500-word page replaced by three short paragraphs and a button will usually drop. See [law firm practice area pages](https://legalwebagency.com/law-firm-practice-area-pages/).
3. **Keep attorney bios, case results and reviews.** These pages carry trust signals clients and search engines look for. See [attorney bio page content](https://legalwebagency.com/attorney-bio-page-content/) and [the case results page](https://legalwebagency.com/law-firm-case-results-page/).
4. **Carry structured data over.** LegalService or Attorney schema, FAQ markup and breadcrumbs should exist on the new templates. See [schema markup for law firms](https://legalwebagency.com/schema-markup-for-law-firms/).
5. **Block the staging site properly.** Use a password, not only a noindex tag, so a staging copy never gets indexed as a duplicate.
6. **Check mobile layout early.** Most legal searches happen on a phone. See [mobile law firm website design](https://legalwebagency.com/mobile-law-firm-website-design/).
7. **Watch page weight.** Heavy sliders and page builders often make the new site slower than the old one. Our [Core Web Vitals study of 14 law firm sites](https://legalwebagency.com/core-web-vitals-law-firm-websites/) shows the common causes.

If you are also changing platforms, compare options first in [WordPress vs Wix vs Squarespace for law firms](https://legalwebagency.com/wordpress-vs-wix-vs-squarespace-for-law-firms/) and review [law firm website hosting](https://legalwebagency.com/law-firm-website-hosting/).

## Phase 3: The redirect map

Build a spreadsheet with two columns: old URL and new URL. Rules:

- Every old URL gets a **301** redirect to the closest matching new page.
- Never send everything to the homepage. Google treats mass homepage redirects like missing pages.
- Avoid chains (A to B to C). Point A straight to C.
- Keep trailing-slash and lowercase rules consistent.
- If the domain changes, redirect at the page level and use the Change of Address tool in Search Console.

Choosing a new domain? Read [how to choose a domain name for a law firm](https://legalwebagency.com/how-to-choose-domain-name-law-firm/) before you commit.

## Phase 4: Launch day

| Check | Pass condition |
|-------|----------------|
| robots.txt | Does not contain `Disallow: /` copied from staging |
| Meta robots | No leftover `noindex` on live pages |
| Redirects | A sample of 30 old URLs returns a single 301 to the right page |
| XML sitemap | Lists only new, live, indexable URLs and is submitted in Search Console |
| Canonicals | Point to the live domain, not staging |
| Analytics and call tracking | Firing on every page, including thank-you pages |
| Click-to-call | Phone number is tappable on mobile |
| Forms | Test submissions arrive in the right inbox |

Our [law firm website launch checklist](https://legalwebagency.com/law-firm-website-launch-checklist/) has the full version.

## Phase 5: The first 90 days

- **Week 1:** Check Search Console for 404s and crawl errors every day. Fix missing redirects as they appear.
- **Weeks 2 to 4:** Expect some ranking movement. Compare clicks on the top 20 pages against the baseline from Phase 1.
- **Month 2:** If a page that used to rank has dropped and stayed down, compare its old and new content side by side. Usually something was removed.
- **Month 3:** Compare calls and forms with the same months last year. That is the result that counts.

Ongoing care is covered in [law firm website maintenance](https://legalwebagency.com/law-firm-website-maintenance/).

## When to bring in help

A migration is a good time to fix problems, but it is also when the most damage happens. If the firm depends on organic leads, have someone who has run migrations review the redirect map before launch. Our full [law firm website redesign guide](https://legalwebagency.com/law-firm-website-redesign-guide/) explains planning and budget, and [how to choose a web designer for your law firm](https://legalwebagency.com/how-to-choose-a-web-designer-for-your-law-firm/) lists questions to ask an agency.

Before and after launch, run the free [law firm website scan](https://legalwebagency.com/free-website-scan/) to check titles, H1s, schema, robots.txt, the sitemap, the mobile viewport and click-to-call, plus common bar advertising wording problems.

---

*Published by Legal Web Agency, a website design and SEO studio for law firms.*
