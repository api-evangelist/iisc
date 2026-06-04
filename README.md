# Indian Institute of Science Bangalore (iisc)

The Indian Institute of Science (IISc) Bangalore is India's premier research-intensive university, founded in 1909 and ranked #211 in the QS World University Rankings 2025. This repository catalogs IISc's confirmable public developer/API footprint as an [APIs.json](https://apisjson.org) profile. IISc does not run a centralized public developer portal; its machine-readable surface is primarily open-access academic infrastructure — the ePrints@IISc institutional repository and the DSpace-based ETD@IISc theses repository, both OAI-PMH compliant.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/iisc/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=iisc-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, Institutional Repository, OAI-PMH, India

## APIs

- **ePrints@IISc OAI-PMH** — OAI-PMH metadata interface for IISc's open-access research repository (EPrints, standard `/cgi/oai2` path). Docs: https://eprints.iisc.ac.in/information.html
- **ETD@IISc OAI-PMH** — OAI/ETD-MS compliant theses-and-dissertations metadata interface (DSpace). Docs: https://etd.iisc.ac.in/

## Plans, Rate Limits, and FinOps

- Plans / Pricing: [plans/iisc-plans-pricing.yml](plans/iisc-plans-pricing.yml)
- Rate Limits: [rate-limits/iisc-rate-limits.yml](rate-limits/iisc-rate-limits.yml)
- FinOps: [finops/iisc-finops.yml](finops/iisc-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://iisc.ac.in/
- Library: https://library.iisc.ac.in/
- GitHub: https://github.com/IISc
- LinkedIn: https://www.linkedin.com/school/indian-institute-of-science/
- Review: [review.yml](review.yml)

## Notes

Verification caveats (reviewed 2026-06-03): the official website (200) and library site (200) resolve cleanly. The ePrints@IISc repository and its OAI endpoint return HTTP 403 behind an Azure Application Gateway that blocks automated requests — the repository is real and documented (Registry of Open Access Repositories, IISc pages) but its OAI endpoint could not be programmatically verified. ETD@IISc returned HTTP 502 at review time. The `github.com/IISc` org exists but has no public repositories; only lab-level orgs (cni-iisc, csl-iisc, val-iisc) publish open source. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
