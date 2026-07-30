# Labrys Biologics

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
