# 🎯 NEATLABS™ CyberIntel Source Finder

> **Stop chasing aggregators. The best threat intelligence comes from the people doing the work.**

A free, standalone HTML tool that helps cybersecurity professionals find the right experts to follow on LinkedIn — organized by domain, filterable, and searchable. No backend. No login. No tracking. Just open the file and go.

![NEATLABS CyberIntel Source Finder](https://img.shields.io/badge/NEATLABS™-Source%20Intelligence%20v2-f0a500?style=for-the-badge&labelColor=0d1117)
![License](https://img.shields.io/badge/License-MIT-00d4aa?style=for-the-badge&labelColor=0d1117)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-4ade80?style=for-the-badge&labelColor=0d1117)
![Single File](https://img.shields.io/badge/Single%20File-HTML%20Only-4d9de0?style=for-the-badge&labelColor=0d1117)

---

## 🔥 Why This Exists

LinkedIn is the single best real-time threat intelligence source available — if you follow the right people.

When a researcher discovers a new threat actor campaign, a zero-day, or a ransomware group's infrastructure, **it goes on LinkedIn before it reaches Dark Reading, Bleeping Computer, or any aggregator**. By the time a news site publishes, you've already seen the researcher's analysis, context, and IOCs — hours or days earlier.

The problem: finding the right people across 58+ cybersecurity specialties is time-consuming and hit-or-miss. This tool solves that.

---

## ✨ Features

- **58+ hand-curated experts** across 15 cybersecurity domains
- **Domain filters** — click one or many to narrow your view
- **Quick Starter Packs** — pre-built domain combos for SOC analysts, GovSec/CMMC, OSINT, cloud, malware, ICS, and AI security
- **Live search** — search by name, organization, keyword, or specialty
- **Sort controls** — sort by recommended, A–Z, or most active
- **★ Follow List** — bookmark experts and export your list as a `.txt` file
- **LinkedIn search links** — every "Follow on LinkedIn" button runs a targeted people search, not a hardcoded profile URL that may be wrong or stale
- **Quickstart guide** — collapsible step-by-step walkthrough built into the tool
- **Leverage guide** — in-depth breakdown of how to use a curated feed for threat intel, compliance awareness, thought leadership, and more — by role
- **Disclaimer** — transparent about what the tool can and cannot verify
- **Zero dependencies** — pure HTML, CSS, and vanilla JavaScript
- **No server, no login, no tracking** — everything runs locally in your browser

---

## 🗂️ Domains Covered

| Domain | Icon | Example Experts |
|---|---|---|
| Threat Intelligence | 🎯 | Katie Nickels, John Hultquist, Dmitri Alperovitch |
| Vulnerability Research | 🔓 | Katie Moussouris, Jake Williams, James Kettle |
| Incident Response | 🚨 | Lesley Carhart, Andrew Case |
| Malware Analysis | 🦠 | Costin Raiu, Mikko Hyppönen, Marcus Hutchins |
| Ransomware Tracking | 💰 | Allan Liska, Brett Callow, Vitali Kremez |
| OSINT & Investigations | 🔍 | Nico Dekens, Michael Bazzell, Joe Gray |
| Privacy & Data Protection | 🛡️ | Eva Galperin, Matt Mitchell |
| CMMC / NIST Compliance | 📋 | Jeff Dalton, Matthew Travis, Ron Ross |
| Cloud Security | ☁️ | Chris Farris, Scott Piper, Kat Traxler |
| Application Security | 💻 | Tanya Janca, Sam Curry, Clint Gibler |
| OT / ICS Security | ⚙️ | Robert M. Lee, Dale Peterson, Joe Slowik |
| AI / ML Security | 🤖 | Gary McGraw, Johann Rehberger, Sven Cattell |
| Supply Chain Security | 🔗 | Ax Sharma, Feross Aboukhadijeh |
| Federal & Defense | 🏛️ | Jen Easterly, Mark Weatherford |
| Security Leadership | 📊 | Sounil Yu, Bruce Schneier, Wendy Nather |

---

## 🚀 Quick Start

**It's one file. Download it and open it.**

```bash
# Clone the repo
git clone https://github.com/yourusername/cyberintel-source-finder.git

# Open the tool
open cyberintel-source-finder/neatlabs-linkedin-finder.html
```

Or download the HTML file directly and double-click it. No installation, no npm, no Python server. It works completely offline once loaded (fonts load from Google Fonts on first open if you're online).

---

## 🎯 How to Use It

### Step 1 — Filter by Domain
Use the left sidebar to select one or more cybersecurity domains you care about. The expert grid updates in real time.

### Step 2 — Try a Starter Pack
Not sure where to begin? Click one of the Quick Starter Packs at the top of the content area:
- 🔥 **SOC Analyst Starter** — Threat Intel + Incident Response + Malware
- 🏛️ **GovSec & CMMC** — Compliance + Federal + Supply Chain
- 🔍 **OSINT & Investigations** — OSINT + Threat + Privacy
- ☁️ **Cloud-Native Security** — Cloud + AppSec + AI
- 🦠 **Malware & Ransomware** — Malware + Ransomware + IR
- ⚙️ **Critical Infrastructure** — OT/ICS + Supply Chain + Federal
- 🤖 **AI Security** — AI/ML + AppSec + Threat

### Step 3 — Search
Use the search bar to find experts by name, org, keyword, or topic across all fields.

### Step 4 — Bookmark with ★
Click the star on any expert card to add them to your **Follow List** in the sidebar. Cards highlight in amber when saved.

### Step 5 — Follow on LinkedIn
Click **"Follow on LinkedIn"** on any card. This opens a targeted LinkedIn people search — not a hardcoded profile URL — so you always find the right person. **Log into LinkedIn first for best results.** Verify the person's identity before following.

### Step 6 — Export
Once you've starred your picks, click **"Export as Text"** to download a clean `.txt` summary with each expert's name, role, search link, and why they're worth following.

---

## 💡 How to Leverage a Curated Expert Feed

> *The full in-tool guide covers this in depth — expand "How to Leverage This" inside the tool. Here's the summary:*

### For SOC Analysts & Threat Hunters
Your curated feed becomes an early warning system. Researchers post about active campaigns, new TTPs, and IOCs **hours or days before they hit your threat intel platform feeds**. When a new CVE drops, check if researchers in your feed have posted — they contextualize exploitability faster than NVD.

### For CISOs & Security Leaders
Your feed is your board prep. When executives ask "what should we worry about?", you draw from curated expert discourse — not vendor marketing. Track how peers are responding to regulatory changes. Use expert posts to build narratives for risk reviews and tabletop exercises.

### For Compliance & GRC Professionals
Policy and regulatory changes break on LinkedIn before they hit official channels. CMMC rule updates, NIST framework revisions, state-level privacy law changes — the people who write and enforce these rules post about them here. Following the right voices means you're never caught flat-footed.

### For OSINT Analysts & Researchers
Your feed becomes a live methodology library. The best OSINT practitioners share tradecraft openly — techniques, tools, platform-specific approaches, and case studies. When you hit a dead end in an investigation, your feed is where you find the technique that unblocks you.

### For Consultants & Fractional Executives
Your feed is your competitive intelligence layer. Understanding what practitioners are worried about helps you position services, anticipate client concerns, and demonstrate expertise in proposals. Consistent, thoughtful engagement on expert posts builds your reputation in front of the audiences that matter.

### For Thought Leaders & Content Creators
A curated expert feed is a content calendar engine. When researchers flag an emerging risk, you can add your practitioner angle. When multiple experts converge on the same topic, you know what your audience is about to care about before they ask.

### The 15-Minute Daily Routine
1. **Morning (5 min)** — Switch LinkedIn to "Most Recent." Scan Tier 1 follows for active campaigns, CVEs, policy changes.
2. **Mid-morning (5 min)** — Read bookmarked posts for substance. Does this change anything you're monitoring?
3. **Midday (2 min)** — Add a substantive comment or share with context. This is how you build presence.
4. **Weekly (3 min/day amortized)** — Synthesize the week's key themes into a short post or internal brief.
5. **Monthly** — Audit your follows. Unfollow anyone who's gone quiet or shifted to noise.

> **The compounding effect:** After 90 days of a curated expert feed with consistent light engagement, your LinkedIn algorithm learns what you care about and starts surfacing more of it. The best threat intelligence isn't a product you subscribe to — it's a network you cultivate.

---

## 🔗 How the LinkedIn Links Work

Every expert card uses a **LinkedIn people search URL**, not a hardcoded profile link:

```
https://www.linkedin.com/search/results/people/?keywords=Katie+Nickels+Red+Canary+threat+intelligence+SANS
```

This approach was intentional. Hardcoded profile URLs (`/in/username`) go stale when people change their handle, leave a company, or when a profile was never correct to begin with. Search URLs constructed from a person's name + org + known specialty consistently surface the right person at the top of results — and they stay accurate over time even as profiles change.

**Always verify the identity of any person before following them.** See the disclaimer section below.

---

## ⚠️ Disclaimer

This directory is provided by **NEATLABS™ / Security 360, LLC** for informational and educational purposes only.

- All expert listings, descriptions, and domain classifications reflect independent research and editorial judgment at the time of publication.
- **No formal relationship exists with, and no compensation has been received from, any individual or organization listed.**
- Because LinkedIn profiles, job titles, and organizational affiliations change frequently, **we cannot independently verify that every search link resolves to the correct individual at all times.**
- Search links open a LinkedIn people search — not a direct profile URL — to reduce false positives, but **you should always verify the identity, credentials, and current role of any person before following them** or treating their content as authoritative.
- Presence in this directory does not constitute an endorsement of any individual's views, opinions, or employer.
- NEATLABS™ is not affiliated with LinkedIn or Microsoft. LinkedIn® is a registered trademark of LinkedIn Corporation.

---

## 🤝 Contributing

See someone missing who belongs here? Know of a domain that should be added? Contributions are welcome.

1. Fork the repo
2. Add your expert to the `EXPERTS` array in the HTML file following the existing format:

```javascript
{
  name: "First Last",
  title: "Role, Organization",
  domains: ["threat", "ir"],           // domain IDs from the DOMAINS array
  signals: ["Signal 1", "Signal 2", "Signal 3"],
  freq: "3–4x/week",                   // posting frequency
  knownFor: "One to two sentences on what makes them worth following and what they specifically post about.",
  avatar: "FL",                        // initials
  linkedin: liSearch("First Last", "Organization keyword specialty")
}
```

3. Submit a pull request with a brief note on why this person belongs in the directory.

**Contribution guidelines:**
- Experts should be active LinkedIn posters (at least 2x/month)
- Content should be substantive and original — not primarily reshares or marketing
- Must be verifiable through public professional record (employer site, conference speaker history, published research, etc.)
- No self-nominations

---

## 📁 File Structure

```
cyberintel-source-finder/
├── neatlabs-linkedin-finder.html    # The entire tool — one file
└── README.md                        # This file
```

That's it. One HTML file. Everything is self-contained.

---

## 📄 License

MIT License — free to use, fork, modify, and redistribute. Attribution appreciated but not required.

If you build something useful with this or extend it for your organization, consider dropping a note or starring the repo. It helps more people find it.

---

## 🏢 About NEATLABS™

**NEATLABS™** is a brand of **Security 360, LLC**, a Veteran-Owned Small Business (VOSB) specializing in cybersecurity consulting, CMMC compliance, and security intelligence tooling for defense contractors and federal agencies.

This tool is offered free to the cybersecurity community as part of our commitment to accessible, practitioner-first security resources.

---

*Built by practitioners, for practitioners. No ads. No tracking. No upsell.*

**[⭐ Star this repo if it helped you build a better feed]**
