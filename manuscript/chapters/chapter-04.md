## Chapter 4: Skipping Multi-Factor Authentication (or Choosing the Weakest Kind)

### 1. The Everyday Habit

Rahul's phone buzzes: "Turn on two-step verification?" He taps "Not now." It looks like an extra chore between him and his messages. *(Fictional.)*

### 2. Why People Make This Mistake

It feels slower, and it seems unnecessary because "my password is fine." Others worry about being locked out if they lose their phone, and that is a fair concern we will address below.

### 3. What Can Go Wrong?

A password alone is a single lock. If it is guessed, leaked, or tricked out of you, the attacker walks straight in.

**Multi-factor authentication (MFA)** adds a second proof that it is really you, such as a code from an app, a fingerprint, or a security key. Even if your password is stolen, the attacker usually still needs the second step.

### 4. How an Attacker Might Exploit It

Not all second steps are equal. At a high level:

- **Without MFA**, a stolen password is enough.
- **With codes sent by SMS**, attackers can try to trick you into reading the code out, or take over your phone number (a **SIM swap**).
- **With "approve" prompts**, an attacker who has your password can flood you with requests, hoping you tap "Approve" out of irritation or confusion. This is sometimes called **MFA fatigue**.

CISA has described SMS and voice codes as among the weakest forms of MFA, and pointed to phishing-resistant methods based on FIDO/WebAuthn as the strongest [8].

### 5. A Realistic Example

**HYPOTHETICAL EXAMPLE:** Rahul's password leaks. At 2 a.m., his phone shows seven "Approve sign-in?" prompts in a row. Half asleep, he taps "Approve" to make them stop. The attacker is in.

### 6. Warning Signs to Watch For

- Login approval prompts you did not start
- Codes you didn't request
- Your phone suddenly losing signal while you aren't travelling (possible number takeover; contact your operator)

> **RED FLAG:** If you didn't start the login, don't approve it, and change your password.

### 7. How to Protect Yourself

**Right now:** Turn on MFA for your email first, then money apps, then social media.

| Method | Strength | Note |
|---|---|---|
| None | Weakest | Password only |
| SMS / voice code | Better than nothing | Weaker against phishing and SIM swap [8] |
| Authenticator app | Stronger | Codes can still be phished |
| Passkey or security key | Strongest for most people | Resistant to phishing [9][10] |

**Over time:**
- Prefer an **authenticator app** or a **passkey** (a way to log in with your device's fingerprint, face, or PIN instead of a password) where offered [10].
- Some banking and card steps in India use SMS OTPs. Don't skip them; they protect you. Use stronger methods on your email and social accounts where they are offered.
- Save your **backup codes** somewhere safe, so losing your phone does not lock you out.
- Never read an OTP out to anyone (Chapter 21).

### 8. If You've Already Made This Mistake

1. Turn on MFA now, starting with email.
2. If you approved an unexpected prompt, change your password immediately, sign out of all other devices, and review account settings for changes.
3. If your number may have been swapped, contact your mobile operator and your bank.
4. If money moved, report through official channels (**1930**, **cybercrime.gov.in**) [5].

### 9. The 30-Second Security Fix

Open your email's security settings and switch on two-step verification.

### 10. Remember This

**Any second step beats none. A stronger second step beats a weaker one.**
