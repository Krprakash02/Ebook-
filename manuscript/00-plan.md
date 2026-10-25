# Stage 1: Planning — *50 Ways You're Making Yourself Hackable*

**Status:** DRAFT for author review. Nothing here is "fact-checked by a human" or "publication-ready" until the verification log (`06-verification-log.md`) is cleared by a person.

**Working title:** 50 Ways You're Making Yourself Hackable
**Subtitle:** Everyday Cybersecurity Mistakes, Hidden Digital Risks, and Simple Ways to Protect Yourself Online
**Author:** Prakash Kumar (2026)

---

## 1. Table of contents (50 chapters, 10 parts × 5)

Changes from the master prompt's proposed list are marked **(refined)**. Reasons are in section 2.

### Front matter
Title page · Copyright page · Disclaimer · Introduction: "You're Probably Making More Security Mistakes Than You Think"

### Part I — Passwords and Account Security
1. Using the Same Password Everywhere
2. Choosing Passwords That Are Easy to Guess
3. Ignoring Data Breach Notices and Never Checking Whether You Were Exposed **(refined)**
4. Skipping Multi-Factor Authentication (or Choosing the Weakest Kind)
5. Sharing Passwords or Storing Them Insecurely

### Part II — Email, Messages, and Phishing
6. Logging In Through a Link Instead of Going Straight to the Site or App **(refined)**
7. Trusting Shortened Links and QR Codes Without Previewing Them **(refined)**
8. Opening Unexpected Attachments
9. Trusting a Sender's Name Without Verifying It **(refined)**
10. Replying to Suspicious Messages and Confirming Your Details **(refined)**

### Part III — Smartphones and Applications
11. Installing Apps From Outside Official Stores
12. Granting Apps Unnecessary Permissions
13. Postponing Software and Security Updates
14. Leaving Your Phone Easy to Unlock and Impossible to Find **(refined)**
15. Trusting Look-alike Apps Inside Official Stores **(refined)**

### Part IV — Social Media and Digital Identity
16. Sharing Too Much Personal Information Online
17. Accepting Unknown Friend or Follow Requests
18. Posting Travel Plans and Live Locations Publicly
19. Taking Online Quizzes and Trends That Collect Personal Details
20. Using One Email Address for Everything **(replaced: was "reusing the same public username")**

### Part V — Banking, Payments, and Online Shopping
21. Sharing OTPs, PINs, or Banking Credentials
22. Entering Your UPI PIN Without Checking What You're Approving **(refined — see note on P2P collect requests)**
23. Calling Customer-Care Numbers You Found Online **(refined)**
24. Shopping on Suspicious Websites
25. Ignoring Bank and Payment Alerts and Statements **(refined)**

### Part VI — Wi-Fi, Browsing, and Internet Habits
26. Connecting to Public Wi-Fi Without Understanding the Real Risks **(refined)**
27. Ignoring Browser Security Warnings
28. Downloading Files From Untrusted Websites and Chats
29. Overlooking Look-alike Web Addresses **(refined)**
30. Leaving Sensitive Accounts Open on Shared Devices

### Part VII — Computers, Files, and Software
31. Installing Cracked Software
32. Clicking Fake Software Update Prompts **(refined)**
33. Switching Off Security Protections Without Understanding the Consequences **(refined)**
34. Plugging In Unknown USB Drives
35. Leaving Device Storage Unprotected **(refined — was "unencrypted files")**

### Part VIII — Privacy, Backups, and Personal Data
36. Never Backing Up Important Files
37. Losing Track of Old Accounts and Unused Apps
38. Never Reviewing Privacy and Ad Settings **(refined)**
39. Giving Away or Selling Devices Without Wiping Them
40. Scattering Copies of ID Documents Across Gallery, Chats, and Photocopy Shops **(refined)**

### Part IX — Scams, Manipulation, and Human Psychology
41. Trusting Impersonators Who Claim to Be Officials or Company Staff
42. Falling for Fake Job Offers and Work-from-Home Scams
43. Trusting Unexpected Prize, Lottery, and Giveaway Messages
44. Trusting Voices and Videos Without Verification **(refined)**
45. Letting Fear, Urgency, or Curiosity Override Your Judgement **(sharpened)**

### Part X — Advanced Everyday Risks
46. Ignoring Login and Security Alerts From Your Accounts
47. Using Devices That No Longer Receive Updates **(refined)**
48. Leaving Your Home Router on Default Settings **(refined)**
49. Sharing Sensitive Information With AI Tools and Online Services
50. Assuming "It Won't Happen to Me"

### Closing sections
Self-assessment · 24-hour checklist · 7-day plan · Printable checklist · Incident quick-reference (account compromise / phishing / malware / financial fraud) · Glossary · Further reading · Conclusion · References

---

## 2. Overlap and accuracy review

| Issue | Chapters | Resolution |
|---|---|---|
| Three chapters on links | 6, 7, 29 | **6** = the *habit* of logging in via a message link. **7** = shortened links + QR codes (hidden destination). **29** = recognising look-alike domains. Each teaches a different skill. |
| Urgency covered three times | 9, 41, 45 | **9** = verifying *who* sent it. **41** = officials/staff impersonation. **45** = the *psychology* and a reusable "pause" routine. Chapters 9 and 41 must not re-explain urgency; they cross-reference 45. |
| Reuse vs. compromised | 1, 3 | Old ch. 3 duplicated ch. 1. Replaced with *breach awareness* (checking exposure, reacting to notices). |
| App chapters | 11, 15 | **11** = sideloading outside stores. **15** = fake/look-alike apps *inside* stores (fake loan apps etc.). |
| Updates | 13, 32, 47 | **13** = delaying updates. **32** = *fake* update prompts. **47** = end-of-support devices. |
| Alerts | 25, 46 | **25** = bank/payment alerts. **46** = login/security alerts from email and social accounts. |
| Storage/ID | 35, 40 | **35** = device protection (screen lock, built-in encryption). **40** = where ID copies end up (gallery, chats, photocopy shops), incl. masked-Aadhaar guidance (to be verified against UIDAI). |
| Weak premise | 20 | "Reusing a public username" is a low-impact risk; replaced with the higher-value "one email for everything" (your email is the master key to password resets). |
| Dated premise | 26 | Public-Wi-Fi advice has shifted as most sites use HTTPS. Chapter will be proportionate and **will not recommend buying a VPN** by default. |
| Dated premise | 22 | NPCI reportedly ended **P2P** UPI collect requests from 1 Oct 2025 (see verification log V-04). Chapter reframed around *reading what you approve* (merchant collect requests, QR, PIN prompts remain). |
| Proportionality | 34 | USB attacks are real but rarer for ordinary users; chapter must say so. |

Count check: 10 parts × 5 = 50, numbers 1–50 with no gaps.

---

## 3. Chapter template (every chapter)

```
## Chapter N: [Title]
### 1. The Everyday Habit
### 2. Why People Make This Mistake
### 3. What Can Go Wrong?
### 4. How an Attacker Might Exploit It        (defensive, high level only)
### 5. A Realistic Example                     (label: HYPOTHETICAL or DOCUMENTED + citation)
### 6. Warning Signs to Watch For
### 7. How to Protect Yourself                 (Right now / Over time)
### 8. If You've Already Made This Mistake     (prioritised steps; who to contact)
### 9. The 30-Second Security Fix
### 10. Remember This
```

Optional callouts (use only where they earn their place): **Myth vs. Reality**, **Red Flag**, **Security Tip**, comparison table, reflection question, diagram suggestion.

Length target: 400–600 words. If a safety step needs more room, take it.

**Labelling rules**
- Every example is tagged `HYPOTHETICAL EXAMPLE` or `DOCUMENTED INCIDENT [n]`.
- Every external fact carries a numbered citation `[n]` that resolves to `05-references.md`.
- No statistic appears without a retrieved, cited source.
- Advice avoids paid products by default; free built-in features come first.

---

## 4. Visual identity (proposal)

- **Mood:** calm, modern, trustworthy — not alarmist. No skulls, hooded hackers, or green-matrix text.
- **Palette (tokens):** deep navy `#0B1F3A` (text/headings), teal `#0E7C86` (accents), warm off-white `#FAF8F3` (page), amber `#B45309` (warnings), muted green `#1F6F43` (tips). Check contrast ratios (WCAG AA) before final.
- **Typography:** an accessible, open-licence face such as Atkinson Hyperlegible or Lexend for body; a clean sans for headings. Left-aligned, never justified. ~11 pt, line height ≈1.45.
- **Callouts:** every callout has an **icon + text label** ("RED FLAG", "SECURITY TIP", "MYTH vs REALITY"), so meaning never depends on colour alone.
- **Structure:** part-opener pages with a one-line promise; page break before each part; numbered chapters.
- **Diagrams:** simple line illustrations with captions and alt-text (e.g. "How a link's visible text differs from its real destination").

**Cover concept (original):** an everyday smartphone on a desk beside a coffee cup and keys, with a faint, stylised padlock-shaped reflection on the screen and a few unevenly-lit "cracks" in the background pattern suggesting weak points. Navy and teal palette, large title type, subtitle beneath. Commission an original illustration or use properly licensed assets only; do not imitate any existing cover.

## 5. Publication settings (Stage 5 preview)

- **EPUB 3, reflowable:** semantic headings, a navigable TOC, alt text on every image, no text baked into images, embedded fonts only if licensing permits.
- **PDF (print/screen):** 6 × 9 in (or A5 for India), 0.75 in margins, widows/orphans control, bookmarks for each chapter.
- **Tooling:** keep Markdown as the source of truth; build with Pandoc (EPUB) and a PDF engine of your choice.

## 6. Decisions needed from the author

1. ~~Author name and publication year~~ — **Decided:** Prakash Kumar, 2026.
2. ~~English spelling~~ — **Decided:** Indian English (British-style spelling, e.g. *judgement*, *organisation*), used consistently.
3. **Hindi/regional editions** later? (Affects how idioms and examples are written.)
4. **Whether to disclose AI assistance.** Many publishing platforms require it; check the rules of wherever you publish.
5. **Human reviewer:** ideally someone with security experience should review before sale.
