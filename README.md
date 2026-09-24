[README.md](https://github.com/user-attachments/files/32195334/README.md)
# CipherX 2026: Join The Hunt & Follow The Trail

*Blue Track, Day 1 — presented by John Pavlidis*

## 🔍 Start the exercise

**[Launch the Internal Hunt Exercise](https://jpvli.github.io/cipherx-hunt/CipherX-Internal-Hunt-Exercise.html)**

A self-paced, 15-step gated investigation across ATT&CK-mapped phases (Initial Access → Exfiltration). Not a CTF — solve it solo, in a group, or take it home. Hints are available at every step, with a "show the answer" fallback if you get stuck.

Need to split the screen? Open the [telemetry logs in a new window](https://jpvli.github.io/cipherx-hunt/CipherX-Internal-Telemetry-Logs.html).

---

## Resource Links

Tools referenced in the workshop, for the external-lead walkthrough and for continued practice after the session.

**Tags:** `Free` = no signup needed for the core use case · `Freemium` = free tier/account unlocks more · `Account required` = you need to register to get useful results

### Malware Samples & Hash Lookup

- **[MalwareBazaar](https://bazaar.abuse.ch/)** — abuse.ch's malware sample repository; search by hash, tag, or family. `Free` to browse/search on the site; downloading samples or using the API needs a free Auth-Key from abuse.ch's Auth Portal.
- **[VirusTotal](https://www.virustotal.com/gui/home/upload)** — the standard multi-AV hash/file/URL lookup. `Freemium` — pasting a hash works without an account, but uploading files and avoiding rate limits benefits from a free account.

### Sandboxes (Dynamic / Behavioral Analysis)

- **[ANY.RUN](https://app.any.run/)** — interactive malware sandbox. `Freemium` — browsing/searching public reports is free with no account; submitting your own samples needs a free Community account.
- **[Hybrid Analysis](https://hybrid-analysis.com/)** — CrowdStrike Falcon Sandbox's community portal, large public report corpus searchable by hash. `Freemium` — the site is CAPTCHA-gated, so a free account (+ API key) is the practical way in.
- **[Joe Sandbox](https://www.joesandbox.com/#windows)** — another behavioral sandbox with public/community analysis. `Freemium` — free light lookups, full submissions need an account.

### C2 / Botnet Infrastructure Tracking

- **[Feodo Tracker](https://feodotracker.abuse.ch/browse/)** — abuse.ch's tracker for known botnet C2 servers (Emotet, Dridex, QakBot, etc.). `Free`, no signup.

### Ransomware Intelligence

- **[Ransomware.live](https://www.ransomware.live/ransomnotes)** — tracks ransomware group leak sites, victims, and ransom notes. `Free`, no signup.
- **[SOCRadar — Ransomware Intelligence](https://socradar.io/free-tools/ransomware-intelligence)** — free-tools module, same family as the IOC Radar tool used earlier in the workshop. `Free`, no signup.

### Dark Web & Leak Intelligence

- **[Dark Web Informer](https://darkwebinformer.com/)** — news/feed on dark web forum activity, breaches, and leaks. `Free`, no signup.
- **[Have I Been Pwned](https://haveibeenpwned.com/)** — checks whether an email/domain appears in known breach dumps. `Freemium` — single lookups are free, the API needs a paid key.

### CTI / IOC Context

- **[SOCRadar — IOC Radar](https://socradar.io/free-tools/ioc-radar)** — confirms whether a hash/domain/IP is known-malicious and adds context; used in Part 2 of the workshop. `Free`, no signup.
- **[Pulsedive](https://pulsedive.com/)** — community threat intel platform; search/enrich IPs, URLs, domains, and hashes with risk scoring. `Freemium` — lookups work with no account, a free account raises limits and unlocks extras.
- **[PhishTank](https://phishtank.org/)** — community-run database of verified phishing URLs; check a URL or browse recent submissions. `Free`, no signup to check/browse (submitting/voting benefits from a free account).

### Network & Domain OSINT / Recon

- **[MXToolbox](https://mxtoolbox.com/)** — DNS, MX, blacklist, and header lookup toolkit. `Freemium` — most lookups free, some tools/history need an account.
- **[AbuseIPDB](https://www.abuseipdb.com/)** — IP reputation and abuse-report lookups. `Freemium` — basic checks free, account needed for higher limits/reporting.
- **[ZoomEye](https://www.zoomeye.ai/)** — internet-wide device/service search engine (like Shodan/Censys). `Freemium` — limited free searches, account needed for full results.
- **[web-check](https://web-check.xyz/)** — all-in-one website recon (DNS, headers, certs, tech stack) in one report. `Free`, no signup.
- **[WhereGoes](https://wheregoes.com/)** — traces a URL's full redirect chain. `Free`, no signup.
- **[Cyscan](https://cyscan.io/)** — domain/IP scanning and recon tool. `Free`, no signup.

### Utilities

- **[Base64 Decode](https://www.base64decode.org/)** — quick base64 encoder/decoder. `Free`, no signup.

### Threat Reports & Case Studies

- **[The DFIR Report](https://thedfirreport.com/reports/)** — deep, technical writeups of real intrusions from initial access through impact, often mapped to ATT&CK. `Free`, no signup.

### Concepts & Framework References

- **[AttackIQ — Pyramid of Pain](https://www.attackiq.com/glossary/pyramid-of-pain-2/)** — glossary writeup of the Pyramid of Pain model. `Free`, no signup.

### Curated Collections

- **[start.me — Cybersecurity](https://start.me/pages/cybersecurity)** — a large curated bookmark board of security tools and resources. `Free`, no signup to view.

### Resources

- **[Pyramid of Pain Article](https://detect-respond.blogspot.com/2013/03/the-pyramid-of-pain.html)** — Full article by David Bianco on the Pyramid of Pain.
- **[HMM Article](https://detect-respond.blogspot.com/2015/10/a-simple-hunting-maturity-model.html)** — Full article on David Bianco on Hunting Maturing Model, explaining levels HM0 to HM4.
---

