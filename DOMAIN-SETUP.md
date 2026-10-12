# Custom domain: majere.austenaa.eu
austenaa.eu is Thomas's own domain. The registrar is Domene AS (domene.no) and DNS is on Cloudflare.
1. In Cloudflare, under austenaa.eu → DNS, add a CNAME record: `majere` → `tussienorway.github.io`. Set Proxy status to **DNS only** (grey cloud) so that GitHub can issue the certificate.
2. Merge this PR, then go to Settings → Pages, check that the custom domain is majere.austenaa.eu, and tick "Enforce HTTPS".
Until DNS works, the github.io URL redirects to a domain that doesn't resolve, so merge only after the record exists.
