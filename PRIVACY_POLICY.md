# Yumi V2 – Privacy Policy  
_Last updated: **14 June 2025**_

> This Privacy Policy explains **how Yumi’s Dev Team** (“**YS**”, “**we**”) collects, uses and safeguards personal data when you interact with the **Yumi Sugoi** Discord bot and the dashboard at <https://bot.guttakrutt.org> (the “Service”).  
> We are based online and can be reached via our official Discord server: <https://discord.gg/YK2rFqpayn>.

---

## 1. Who is the data controller?  

**Yumi’s Dev Team (YS)**  
Primary contact: <https://discord.gg/YK2rFqpayn>

---

## 2. What data do we collect & why?

| Category | Examples | Purpose | Retention | GDPR basis* |
|----------|----------|---------|-----------|-------------|
| **Account identifiers** | `user_id`, `guild_id`, 18 + & Premium roles | Authenticate, enforce age gates, manage subscriptions | Until opt-out or guild exit | Contract (Art. 6 b) |
| **Message content** | Text you send in `/talk` threads or persona builder | Generate AI replies, run safety filter | **30-day rolling window** | Contract |
| **Vector embeddings** | Numeric vectors from each message | Short-term memory, nightly on-prem LoRA fine-tune | 30 days | Legitimate interest (Art. 6 f) |
| **Feedback & usage** | `/feedback good/bad`, token counts, latency | Analytics & rate-limiting | 30 days | Legitimate interest |
| **Web session data** | OAuth token, IP, user-agent | Secure dashboard login, anti-abuse | Session + 24 h | Contract |
| **Billing metadata** | Patreon/Ko-fi pledge ID & tier | Grant Premium role | Active subscription + 90 days | Contract |

\*GDPR Article 6 legal basis.

We **never** collect real names, e-mails or payment-card numbers.

---

## 3. AI training & opt-in

Every 24 hours we fine-tune a small **LoRA adapter** on our own server using the most recent **opt-in** messages. Opt-out users are excluded.  
The adapter **never leaves our infrastructure**.

---

## 4. Your rights & controls

| Right | How to exercise | Response time |
|-------|-----------------|---------------|
| **Access / export** | `/yumi memory export` | Instant DM |
| **Erase & stop logging** | `/yumi memory optout` or Dashboard → Data & Privacy → *Delete & Opt-out* | ≤ 60 s |
| **Rectification / restriction / portability** | Contact us in the Discord server | ≤ 30 days |

---

## 5. Cookies

Dashboard sets **one HTTP-only session cookie** (`next-auth.session-token`). No third-party or tracking cookies.

---

## 6. Data sharing

* We **do not sell** personal data.  
* Minimal sharing with:  
  * **Discord** – message delivery & role assignment.  
  * **Ko-fi / Patreon** – pledge web-hooks.  
  * **Law enforcement** – only if legally required.

All third-parties are GDPR-compliant.

---

## 7. Storage & transfers

All databases and LLM servers run on a privately-managed VPS located in the EEA; we do not transfer personal data outside the EEA.

---

## 8. Security measures

* AES-256 encryption at rest, TLS 1.3 in transit.  
* Role-based access; keys rotated every 90 days.  
* Bot token stored in Docker secrets, never in git.  
* All team accounts secured with Discord & GitHub **2FA**.

---

## 9. Children’s privacy

The Service is **not directed to children under 13**. Users under 18 may not access `flirty_companion` or any 18 + channel. We delete data inadvertently collected from minors.

---

## 10. Policy changes

Updates will be posted in the `#announcements` channel and logged at the top of this file.  
Continued use after the “Last updated” date = acceptance.

---

## 11. Contact

Privacy questions? Join our Discord: <https://discord.gg/YK2rFqpayn>

---

_By using Yumi V2 you acknowledge that you have read and understood this Privacy Policy._
