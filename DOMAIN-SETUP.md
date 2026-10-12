# Custom domain: majere.thomasaustenaa.no
The DNS for thomasaustenaa.no is managed at domene.no.
1. At domene.no, under thomasaustenaa.no → DNS, add a CNAME record: `majere` → `tussienorway.github.io.`
2. Check that it resolves with `dig majere.thomasaustenaa.no CNAME`.
3. Merge this PR, then go to Settings → Pages, check that the custom domain is majere.thomasaustenaa.no, and tick "Enforce HTTPS" once the certificate has been issued.
Merge only after the record resolves. Otherwise the github.io URL redirects to a domain that doesn't exist.
