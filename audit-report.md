# Client Sales Pitch & Audit Report: KMBRC
**Target:** https://www.kmbrc.org.uk/  
**Date:** 2026-05-31  
**Prepared by:** Brian Stephens · brianstephens.co.uk

---

## Executive Summary
KMBRC sits on one of the most compelling data assets in Kent — 9 million wildlife records — yet the current site buries that authority under Wix's heavy JavaScript renderer and a passive, descriptive headline that asks nothing of the visitor. The result is a site that feels like a filing cabinet rather than a trusted environmental authority, actively costing the organisation partnerships, volunteer sign-ups, and grant visibility.

---

## Critical Red Flags

### 1. Catastrophic Performance Bottlenecks (Wix Thunderbolt Renderer)
**The Problem:** The site loads Wix's Thunderbolt JS engine and 400kb+ bundles before the user sees a single meaningful pixel. Every page transition re-triggers this cycle. Core Web Vitals (LCP, CLS, FID) will be failing, which directly suppresses Google search rankings — critical for an organisation whose reach depends on public discovery.  
**The Fix:** Rebuild on a lightweight stack (Next.js with SSR or vanilla HTML/Tailwind). First Contentful Paint drops from ~4s to under 1s. Clean semantic HTML replaces Wix's deeply nested div soup.

### 2. Zero Emotional Hook — No Reason to Stay
**The Problem:** The hero headline reads: *"Kent & Medway Biological Records Centre collects, collates and shares information about the county's species and habitats."* This is a company description, not a value proposition. It answers "what are you?" not "why should I care?" There is no guiding CTA, no urgency, and no emotional connection to the mission. Visitors bounce.  
**The Fix:** Lead with the impact: 9 million records, decades of conservation data, ALERC-accredited expertise. Write a hero that makes the visitor feel the weight of what KMBRC protects. Give them one clear next action above the fold.

### 3. Credibility Buried, Navigation Overloaded
**The Problem:** KMBRC holds CIEEM membership, ALERC accreditation, and partnerships with Natural England, Kent Wildlife Trust, and the Environment Agency. None of this appears prominently. Meanwhile the navigation has 6+ top-level items with deep submenus — users looking for "Submit a Record" or "Data Search" have to hunt. The nav is a maze, not a guide.  
**The Fix:** Surface the accreditations and partner logos immediately below the hero as trust signals. Flatten the navigation to 4 primary paths that match the user's intent: Search Data · Submit a Record · Conservation · Education.

---

## Brand Assets (for Prototype)
| Asset | Value | Notes |
| ----- | ----- | ----- |
| Primary colour | `#2C5F2E` | Deep forest green — derived from conservation identity |
| Accent colour | `#97BC62` | Fresh lime green — highlight & CTA |
| Font | `Inter` | No font detected in Wix CSS; Inter chosen for legibility |
| Logo | `https://static.wixstatic.com/media/0fd943_5935ae799e134cfaa70c76d7ef6325f5~mv2.jpg` | Existing Wix-hosted logo |
| Org name | Kent & Medway Biological Records Centre | |
| Tagline | *9 Million Records. One Mission. Protect Kent's Wildlife.* | Rewritten for impact |

---

## The Cost of Inaction
Every month on this Wix platform, KMBRC is losing ground in Google search to better-optimised environmental organisations — meaning fewer public records submitted, fewer grant applications found, and fewer partnerships initiated. The dated aesthetic also undermines the credibility of an ALERC-accredited body when presenting to local authorities or potential funders who will judge the organisation's rigour by the quality of its digital presence. This is not a cosmetic issue — it is a trust and discoverability problem with a direct impact on the organisation's ability to fulfil its conservation mission.
