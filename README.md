# mta-sts.pz.com.au policy host

Serves the MTA-STS policy for pz.com.au via GitHub Pages.

Policy file: `.well-known/mta-sts.txt` → https://mta-sts.pz.com.au/.well-known/mta-sts.txt

- mode: testing (flip to `enforce` + max_age 604800 after 1-2 weeks of clean TLS-RPT reports)
- After ANY policy change, bump the `id=` in the `_mta-sts.pz.com.au` TXT record (Cloudflare)
- Deployed 2026-09-04 by GruBot per Paul directive; procedure: botpedia operations/email-authentication-playbook.md
