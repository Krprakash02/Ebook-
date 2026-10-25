# Verification log

Honest status of every external claim. **Nothing in this log has been verified by a human.** The sandbox used to draft this could run web searches but could not open the websites themselves (DNS errors for nist.gov, cisa.gov), so every item below rests on search-result summaries and must be checked against the primary page.

| ID | Claim (where used) | Evidence seen | Risk if wrong | Action before publication |
|---|---|---|---|---|
| V-01 | 23andMe: attackers appeared to reuse credentials exposed elsewhere; profile data of millions exposed via a relatives feature (Ch. 1) | News summaries (ABC, TechRadar, TechCrunch). Reports noted the cause and scale were stated differently over time; the company and critics disagreed on blame. | Defamation/accuracy | Read the company's own statements and a court/regulator document if available. Keep wording hedged ("reported", "disputed"). Remove numbers unless verified. |
| V-02 | NIST SP 800-63B-4: 15-character minimum when a password is the only factor, 8 when used within MFA; no other composition rules; blocklist of common/compromised passwords (Ch. 1, Ch. 2) | Search summary quoting the official NIST text. The chapter currently states this only in general terms. | Wrong numbers | Read the final publication. Confirm status (final), date, exact SHALL/SHOULD wording. Confirm "no forced periodic change" wording before using it. |
| V-03 | CISA: unique passwords with a password manager, enable MFA on email/financial/shopping/social accounts (Ch. 1) | Search summary of cisa.gov/secure-our-world pages. | Low | Open pages; capture exact titles and dates. |
| V-04 | NPCI ended P2P UPI collect requests from 1 Oct 2025 (Ch. 22) | News reports only (The Week/PTI, Outlook, ETV Bharat, CSR Journal), citing an NPCI circular dated 29 July 2025. Merchant collect requests reported to continue. Earlier cap of ₹2,000 per transaction reported. | **High.** Chapter 22 depends on it, and rules may have changed in the year since. | Obtain the NPCI circular and FAQ. Re-check for changes through October 2026. |
| V-05 | 1930 helpline and cybercrime.gov.in for reporting financial cyber fraud; reporting quickly improves chances of freezing funds (Ch. 1, closing) | Secondary pages (Vikaspedia, Moneylife, state police notice). One older news report said the helpline was sometimes unreachable. | Medium (readers act on it in a crisis) | Confirm on the official portal; add a fallback instruction (bank's fraud line, local police). Do not state specific time windows (e.g. "within 4 hours") unless the official source says so. |
| V-06 | RBI 2017 circular: zero liability for third-party breaches if reported within 3 working days; limited liability afterwards; customer bears loss if negligent (e.g., shared credentials) until reporting; bank bears loss after reporting (Ch. 1, 21, 25) | Search summaries of the circular. Conflicting figures between secondary sources (₹25,000 vs. ₹5,000/₹10,000 tables). | **High.** Easy to misstate. | Read the circular and any later amendments. Present as "rules exist; time matters; check your bank's policy", not as a guarantee. |
| V-07 | Platform "built-in password managers are free" (Ch. 1) | Common knowledge; no source retrieved. | Low | Cite Google/Apple documentation, or soften. |

## Process rules going forward
1. No statistic enters a chapter unless retrieved from a primary source and listed in `05-references.md`.
2. Real incidents are `DOCUMENTED INCIDENT [n]`; invented stories are `HYPOTHETICAL EXAMPLE`.
3. Any helpline, portal, circular, or setting is re-checked on the day of final export.
4. A human reviewer signs off each chapter before the "reviewed" label is used anywhere.

## Added with Part I

| ID | Claim (where used) | Evidence seen | Risk if wrong | Action before publication |
|---|---|---|---|---|
| V-08 | Have I Been Pwned is a free service by Troy Hunt that reports which known breaches included an email address (Ch. 3) | HIBP About page and encyclopedia entries in search results | Low | Open the page; confirm wording and that the service is still free and operating. |
| V-09 | CISA described SMS/voice codes as among the weakest MFA forms and recommended FIDO/WebAuthn phishing-resistant MFA (Ch. 4) | Bulletin title plus secondary summaries (Bricker, Infosecurity, Security Boulevard); fact sheets dated Oct 2022 | Medium | Read CISA's fact sheet itself; check whether newer guidance exists. |
| V-10 | NIST (Feb 2024) says FIDO authenticators are the most common widely available phishing-resistant authenticators (Ch. 4 table) | Search summary only | Medium | Read the NIST document. |
| V-11 | Passkeys replace passwords using device-held private keys and biometric/PIN unlock (Ch. 4) | Kaspersky/Malwarebytes only | Medium | Cite FIDO Alliance and platform vendors' docs. |
| V-12 | Google Password Manager has a "Password Checkup" (Ch. 3) | 2019-era news coverage | Medium (features and names change) | Verify on Google's help pages; check Apple/Android equivalents. |
| V-13 | NIST 800-63B-4: 15-character minimum for password-only logins (Ch. 2); discourages forced periodic changes (Ch. 2) | Summary quoting the official text for the 15-character minimum; periodic-change wording seen only in secondary sources | Medium | Read the final publication; adjust wording to exact SHALL/SHOULD language. |
| V-14 | General recommendations stated without citation: use passphrases of 4+ unrelated words generated randomly; keep a written note at home rather than carried; family-sharing/profile features instead of sharing logins; free built-in password managers exist (Ch. 2, 5) | Common security practice; no source retrieved | Low–Medium | Find supporting official guidance or label as author's recommendation. |
| V-15 | Fictional characters in Ch. 1–5 are not real people; "Dhoni", "Chennai Super Kings" appear only as fandom references in a fictional example (Ch. 2) | n/a | Low (brand/person names) | Consider replacing with a generic team to avoid any implied association. |
