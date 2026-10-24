# Part I — Passwords and Account Security

## Chapter 1: Using the Same Password Everywhere

### 1. The Everyday Habit

Ananya is a second-year engineering student. Her password, `Ananya@2004`, opens her college portal, her Instagram, her streaming account, and the shopping app where her card is saved. It is easy to remember, and she has never had a problem.

Her friend Rohan uses a small twist: he adds "!" to the end for sites that demand a symbol. Same password, slightly different costume.

*(Ananya and Rohan are fictional.)*

### 2. Why People Make This Mistake

Because the alternative sounds exhausting. The average person has dozens of accounts, and human memory is not built to store dozens of unrelated, long strings.

There is also a quiet misconception at work: "Nobody would bother hacking *me*." Attackers rarely pick people one by one. They work in bulk, which is the point of the next section.

### 3. What Can Go Wrong?

Websites do get breached. When that happens, the email-and-password pairs may be leaked or sold. You cannot control how well a small forum or an old shopping site protects its data.

Reuse turns one site's failure into a failure everywhere. Your strongest account is only as safe as the weakest site where you used the same password.

Possible results: account takeover, fraudulent purchases, impersonation of you to your contacts, and, if your email falls, a chain of password resets on your other accounts.

### 4. How an Attacker Might Exploit It

At a high level: criminals take lists of leaked email-and-password pairs and use automated software to try them on other popular services. This is called **credential stuffing**, which simply means "stuffing" known logins into other sites' login pages.

It costs the attacker almost nothing. It only needs *some* people to have reused a password. If you did, you are in that group, without anyone ever having targeted you personally.

### 5. A Realistic Example

**DOCUMENTED INCIDENT [1][2]** — In October 2023, the genetic-testing company 23andMe disclosed that attackers had accessed customer accounts. Reporting at the time said the attackers appeared to have used usernames and passwords exposed in other breaches, and that data about millions of customers' profiles was then exposed through a feature that links relatives. The company's own account, and how much of the blame lay with customers versus the company's defences, was publicly disputed. Details, numbers, and cause were reported differently as the story developed, so treat the specifics as contested and read the sources.

The lesson is not "blame users." It is that one reused password can be the only door an attacker needs.

**HYPOTHETICAL EXAMPLE** — A small cricket-fan forum Ananya joined in 2021 is breached. Her email and `Ananya@2004` appear on a leaked list. Months later, someone's software tries that pair on popular services. It works on her streaming account, then on the shopping app, where saved details could be misused.

### 6. Warning Signs to Watch For

- Login alerts or password-reset emails you did not request.
- Being logged out unexpectedly.
- Unfamiliar orders, subscriptions, or devices in your account.
- Friends receiving odd messages "from you."

> **RED FLAG:** There may be *no* warning sign at all. Quiet takeovers happen. Don't wait for a signal before fixing reuse.

### 7. How to Protect Yourself

**Right now**
1. Make your **email** password unique first. Email can reset almost everything else.
2. Then your **banking, UPI, and payment apps**, then social media and shopping.

**Over time**
- Use a **password manager**: a tool that creates and stores a different strong password for each account, so you only remember one. Many phones and browsers include a free one. Your platform's official help pages explain how to use it. A paid product is not required to get this benefit.
- Prefer **long** passwords or passphrases. Length matters more than clever symbols. Current NIST guidance for service providers favours longer passwords, discourages forced composition rules, and recommends checking choices against lists of known-compromised passwords [3].
- Turn on **multi-factor authentication** (a second proof of identity, such as a code from an app) for important accounts. CISA recommends this for email, financial, shopping, and social accounts [4].

> **MYTH vs. REALITY**
> *Myth:* "Adding a number or symbol makes it a new password."
> *Reality:* Predictable tweaks are easy for attackers' software to try. A truly different password is different.

> **SECURITY TIP:** Don't aim for perfection on day one. Fix email and money-related accounts first.

### 8. If You've Already Made This Mistake

Most of us have. Work through this in order:

1. **Change the password on your email account** to a new, unique one.
2. **Change it on any account that shares the reused password**, starting with banking/UPI, then shopping, then social media.
3. **Turn on multi-factor authentication** where available.
4. **Review recent activity and signed-in devices** on key accounts and sign out of any you don't recognise.
5. **Check for unwanted changes** such as new recovery numbers, email forwarding rules, or unfamiliar linked apps.
6. **If money moved without your approval**, contact your bank immediately and report it through the official channels. In India, that means the National Cyber Crime Reporting helpline **1930** and the portal **cybercrime.gov.in** [5]. Reporting quickly can improve the chance of stopping a transfer [5]. Banks' rules on liability for unauthorised transactions depend on how fast you report [6]. (Confirm current procedures on the official sites.)

### 9. The 30-Second Security Fix

Open your email account's security settings and change its password to one you have never used anywhere else.

### 10. Remember This

**One password, one door. Reuse it, and you've handed out copies of the key.**

*Reflection:* If the weakest site you've ever signed up for were breached tomorrow, which of your accounts would be at risk?

*Diagram suggestion:* A single key opening five doors, labelled "Email," "UPI app," "Shopping," "Social," "College portal," versus five different keys. **Alt text:** "Illustration contrasting one key that opens many doors with a separate key for each door."

---

**References for this chapter:** [1]–[6], see `05-references.md`. **Verification status:** see `06-verification-log.md` (V-01 to V-06).
