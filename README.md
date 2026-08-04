# Labrys Biologics

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Labrys Biologics was a clinical-stage biopharmaceutical company founded in 2012 in San Mateo, California, developing anti-CGRP monoclonal antibody therapeutics for the prevention of chronic and episodic migraine. It was acquired by Teva Pharmaceutical Industries in 2014.

**Status: acquired / not operating.** Enrichment probes on 2026-07-19 found no developer or API surface:

- `labrysbiologics.com` and `labrysbio.com` resolve to `192.115.248.118` but serve nothing (TCP 80 and 443 closed).
- Both domains are delegated to Teva nameservers (`ns3/ns4/ns5.tevapharm.com`); registrant organization is still "Labrys Biologics".
- Mail is locked down: SPF `v=spf1 -all`, DMARC `p=reject` with reports to `dmarc.RUA@tevapharm.com`.
- No GitHub organization, no documentation host, no specs.

This profile is retained as a historical portfolio-company record rather than an API listing.

Backed by: canaan-partners

## Artifacts

- `security/labrys-biologics-domain-security.yml` — probed DNS/TLS/mail posture (`type: DomainSecurity`)
