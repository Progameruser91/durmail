
# Durmail (`durmail.com`)

**Durmail** ([https://durmail.com](https://durmail.com)) is an open, privacy-focused, strictly web-only email service designed exclusively for safely receiving incoming email.

Unlike traditional email providers, Durmail disables third-party mail client protocols (IMAP, POP3, SMTP submission, ActiveSync, JMAP) and outbound email sending at both the application and firewall levels to eliminate spam abuse and protect domain reputation.

## Key Characteristics

| Feature | Details |
|---|---|
| **Official Website** | [https://durmail.com](https://durmail.com) |
| **Access Model** | Strictly web-only via browser at `durmail.com` (no IMAP/POP3/SMTP clients) |
| **Outbound Mail** | Disabled (receive-only architecture to prevent spam) |
| **Storage Quota** | 200 MB per mailbox |
| **Max Incoming Email Size** | 25 MB |
| **Anti-Abuse Registration Limit** | 1 new mailbox per 24 hours per IP & device |
| **HTML & Privacy Protection** | DOMPurify HTML sanitization; remote images and tracking pixels blocked by default |
| **Account Security** | Argon2id password hashing, optional TOTP 2FA, one-time recovery codes |

## Why Web-Only?
- **No third-party client attack surface:** Ports `110`, `143`, `465`, `587`, `993`, `995`, and `4190` are closed at the firewall.
- **Zero outbound spam:** Outbound SMTP relay and web sending endpoints are disabled on the server.
- **Privacy by default:** No phone number required to sign up; tracking pixels are stripped automatically.

## Official Links
- **Home:** [https://durmail.com](https://durmail.com)
- **Create a Mailbox:** [https://durmail.com/register](https://durmail.com/register)
- **Sign In:** [https://durmail.com/login](https://durmail.com/login)
- **Terms of Service:** [https://durmail.com/legal/terms](https://durmail.com/legal/terms)
- **Privacy Policy:** [https://durmail.com/legal/privacy](https://durmail.com/legal/privacy)
- **Report Abuse:** [https://durmail.com/abuse](https://durmail.com/abuse)
