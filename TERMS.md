# Yumi V2 – Terms of Service
_Last updated: **14 June 2025**_

> **Important — binding agreement**  
> By installing or interacting with the **Yumi Sugoi** Discord bot or by accessing <https://bot.guttakrutt.org> (the “Dashboard”), **you agree to these Terms**.  
> If you do not agree, do not use Yumi V2.

---

## 1. Definitions

| Term | Meaning |
|------|---------|
| **Bot** | The Yumi Sugoi Discord application (client ID `…`) operated by **Yumi Dev Team** (“**YS**”). |
| **Service** | The Bot, the Dashboard, related web-hooks, APIs and documentation. |
| **User Content** | Any text, commands, persona instructions, feedback, or other material you submit to the Service. |
| **Premium** | Paid tiers offered through Ko-fi, Patreon, or other channels that grant additional features (e.g., extra persona slots). |

---

## 2. Description of the Service

* AI companion bot inside Discord, powered by a **locally-hosted Ollama LLM**.  
* Two preset personas (`companion`, `flirty_companion`) + **one free custom persona** per user (more via Premium).  
* Conversation history (30-day window) stored **locally** for memory and nightly LoRA fine-tuning.  
* Web Dashboard with OAuth2 login, analytics, persona builder, opt-out & data-deletion controls.  
* Full compliance with Discord’s Community Guidelines via an on-device safety filter.

---

## 3. Eligibility & Age Requirements

* **13 +** to use the Bot (Discord minimum).  
* **18 +** for the `flirty_companion` persona or any age-restricted channel.  
* You must maintain a Discord account in good standing.

---

## 4. Your Responsibilities

1. **Follow all laws & Discord policies.**  
2. **Prohibited content** — never submit content that is: sexual with minors, non-consensual, hateful, extremist, self-harm instructions, personally identifying someone else, or otherwise illegal.  
3. **Custom personas** — you are liable for the instructions you create; violating personas will be removed.  
4. **Security** — keep your Discord credentials safe and notify us of any unauthorised use.

---

## 5. Data Use & Privacy

| What we store | Where | Retention | Purpose |
|---------------|-------|-----------|---------|
| `user_id`, `guild_id`, age-gate role ID | MySQL (AES-256 at rest) | Until opt-out or guild exit | Identify users, enforce age gates, Premium roles |
| Message content & vector embedding | MySQL | Rolling **30 days** | Memory & on-prem LoRA fine-tune |
| Feedback + usage stats | MySQL | 30 days | Quality metrics |

* **Opt-out / delete:** `/yumi memory optout` or Dashboard → Data & Privacy.  
* **Training:** Only **opt-in** messages train the local adapter.  
* See full privacy details in `PRIVACY_POLICY.md`.

---

## 6. Payments & Premium

* Payments handled by Stripe; YS never touches your card data.  
* Refunds & disputes follow the payment platform’s own terms.  
* Lapsed subscriptions may remove Premium features.

---

## 7. Intellectual Property

* **Your Content:** you keep ownership. You grant YS a **non-exclusive, worldwide, royalty-free licence** to store, process, display, and (if not opted-out) use it to improve the Service.  
* **Our Content:** YS owns all code, models, and branding. No reverse-engineering or resale without written permission.

---

## 8. Disclaimer of Advice

The Bot’s responses are **AI-generated** and may be inaccurate.  
They do **not** constitute professional, medical, or legal advice.

---

## 9. Warranty Disclaimer

THE SERVICE IS PROVIDED **“AS IS”** WITHOUT WARRANTIES OF ANY KIND, EXPRESS OR IMPLIED.

---

## 10. Limitation of Liability

GK is **not liable** for indirect, incidental, special, consequential or punitive damages, nor for loss of profits, data, or goodwill.  
Aggregate liability is capped at **€50** or the amount you paid for Premium in the past 12 months (whichever is greater).

---

## 11. Indemnification

You will indemnify and hold YS (and contributors) harmless from any claim arising out of:

* your use or misuse of the Service;  
* your violation of these Terms or the law;  
* your User Content.

---

## 12. Termination

* You may stop using the Service at any time.  
* We may suspend or terminate your access for violations, legal requirements, or discontinuation of the Bot.  
* Sections 7 – 12 survive termination.

---

## 13. Changes to These Terms

We may update these Terms. Material changes will be posted on the Dashboard and announced in `#announcements`. Continued use after the effective date means acceptance.

---

## 14. Governing Law & Disputes

* Governed by **Norwegian law** (conflict-of-law rules excluded).  
* Disputes to be resolved in the courts of **Oslo**, unless mandatory local law provides otherwise.

---

## 15. Contact

**Yumi Development**  
Join the official Yumi Discord Server.
https://discord.gg/YK2rFqpayn

---

_By using Yumi you acknowledge that you have read, understood, and agree to these Terms._
