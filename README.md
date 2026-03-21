# APA Referencing & Citation (7th Ed) Skill for Claude

A Claude skill for formatting, checking, correcting, and verifying academic references and citations according to APA 7th Edition rules.

**Author:** Chuah Kee Man

## What It Does

- **Formats references** — Generates correctly formatted reference list entries and in-text citations from source details.
- **Checks and corrects** — Reviews existing references for APA 7th compliance, identifies errors, and produces corrected versions with explanations.
- **Verifies authenticity** — Uses web search to confirm references actually exist. Flags fabricated or unverifiable references and suggests close matches.
- **Converts styles** — Converts references from other citation styles (MLA, Chicago, Harvard, etc.) into APA 7th Edition.

## Supported Source Types

Books & eBooks (with/without DOI) · Edited book chapters · Journal articles (with/without DOI) · Open access articles · Conference papers & proceedings · Government reports · White papers · Published & unpublished dissertations/theses · Newspaper articles (online & print) · Magazine articles (online & print) · Webpages (with/without date) · PowerPoint slides & lecture notes · YouTube videos & channels · Films · TV series · Facebook posts · Instagram photos/videos · Tweets

## Installation

1. Download the `apa-referencing.skill` file from the [Releases](../../releases) page.
2. In Claude, go to **Settings → Profile → Custom Skills**.
3. Upload the `.skill` file.

## How to Use

Simply ask Claude to check, format, or verify any APA reference. For example:

- "Check this reference for APA 7th compliance: ..."
- "Format this as an APA 7th reference: author Sarah Chen, 2023, article titled..."
- "Are these references real or fabricated?"
- "Convert this Harvard reference to APA 7th"

## File Structure

```
apa-referencing/
├── SKILL.md                          # Main skill instructions
├── references/
│   ├── apa7-formatting-rules.md      # Detailed formatting templates for all 28 source types
│   └── APA7thEditionReferencingandCitationGuide.pdf  # Original quick guide
└── README.md
```

## Licence

This skill is shared for educational purposes. The APA formatting rules are based on the APA Publication Manual, 7th Edition, published by the American Psychological Association.
