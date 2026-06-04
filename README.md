# Harbin Institute of Technology (harbin-institute-of-technology)

Harbin Institute of Technology (HIT) is a public research university in Harbin, Heilongjiang, China, founded in 1920 and overseen by the Ministry of Industry and Information Technology, with additional campuses in Weihai and Shenzhen. It is ranked #252 in the QS World University Rankings 2025. HIT does not run a formal public developer portal; its most concrete machine-readable footprint is the Elsevier Pure research portal at scholar.hit.edu.cn, which exposes a live OAI-PMH endpoint and RSS feeds.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/harbin-institute-of-technology/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=harbin-institute-of-technology-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Scholarly, OAI-PMH, China

## APIs

- **HIT Research Portal OAI-PMH** — OAI-PMH metadata harvesting for the HIT Elsevier Pure research system (PURE Persons and PURE publications sets, OpenAIRE CERIF 1.2). Base: `https://scholar.hit.edu.cn/ws/oai`. Docs: https://scholar.hit.edu.cn/en/
- **HIT Research Portal RSS Feeds** — RSS 2.0 feeds of research output and researcher profiles. Base: `https://scholar.hit.edu.cn/en/publications/?format=rss`. Docs: https://scholar.hit.edu.cn/en/

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/harbin-institute-of-technology-plans-pricing.yml](plans/harbin-institute-of-technology-plans-pricing.yml)
- Rate Limits: [rate-limits/harbin-institute-of-technology-rate-limits.yml](rate-limits/harbin-institute-of-technology-rate-limits.yml)
- FinOps: [finops/harbin-institute-of-technology-finops.yml](finops/harbin-institute-of-technology-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://en.hit.edu.cn/
- Developer Portal (research): https://scholar.hit.edu.cn/en/
- GitHub (affiliated research org): https://github.com/HITSZ-HLT
- LinkedIn: https://www.linkedin.com/school/harbin-institute-of-technology/
- Review: [review.yml](review.yml)

## Notes

All endpoints were probed live during research and no APIs or endpoints were fabricated. The Pure OAI-PMH endpoint was verified via `ListSets` (HTTP 200); the `Identify` verb returns a configuration 500, a known Pure quirk, while other verbs work. The library institutional repository (ir.lib.hit.edu.cn) returned 403 and exposes no documented public API from outside China. Affiliated GitHub organizations (e.g. HITSZ-HLT, hitsz-ids) belong to individual research groups rather than being institution-wide API publishers.

## Maintainers

- Kin Lane — kin@apievangelist.com
