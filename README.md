# Oh-Shit: Curated OSINT Toolkit Reference

`Oh-Shit` is a community-maintained directory of open-source intelligence (OSINT) resources for legitimate security research, investigations, journalism, due diligence, and incident response support.

This repository is a **reference collection**, not an automation framework. It helps analysts quickly discover useful tools by category.

## Purpose and Scope

This project is intended to:

- Curate practical OSINT resources in one place.
- Improve discoverability using categorized, consistently formatted lists.
- Provide concise context on what each tool is useful for.
- Encourage responsible, legal, and ethical investigation practices.

Out of scope:

- Bypassing access controls or terms of service.
- Doxxing, stalking, harassment, or unlawful surveillance.
- Any misuse of breached data or personal information.

## Responsible, Legal, and Ethical Use

Use this repository only for authorized and lawful purposes.

- Follow local laws, platform terms, and your organization’s policy.
- Minimize collection of personal data and respect privacy rights.
- Verify findings with multiple sources before taking action.
- Treat high-risk categories (breach/leak/identity-related) with extra caution.

See [`RESPONSIBLE_USE.md`](/RESPONSIBLE_USE.md) for detailed guidance.

## Repository Structure

```text
.
├── README.md
├── RESPONSIBLE_USE.md
├── CONTRIBUTING.md
└── utils/
    ├── companies_leaks.md
    ├── dating.md
    ├── db_breach.md
    ├── documents.md
    ├── domains.md
    ├── emails.md
    ├── maps.md
    ├── osint_tools.md
    ├── others.md
    ├── people_search.md
    ├── phone_number.md
    ├── reverse_image.md
    ├── reverse_video.md
    ├── search_engines.md
    ├── social_media.md
    └── usernames.md
```

## Category Index

Each category file includes a normalized table with:

- **Tool**: resource or platform name
- **URL**: primary link
- **Access**: `Free`, `Freemium`, `Paid`, or `Unknown`
- **Notes**: short use context and caveats

| Category | Description |
| --- | --- |
| [Usernames](/utils/usernames.md) | Username and alias discovery across platforms. |
| [People Search](/utils/people_search.md) | Public-record and people-discovery resources. |
| [Social Media](/utils/social_media.md) | Social platform investigation and profile analysis. |
| [Search Engines](/utils/search_engines.md) | General and specialized search engines/operators. |
| [Reverse Image](/utils/reverse_image.md) | Reverse-image lookup and visual verification tools. |
| [Reverse Video](/utils/reverse_video.md) | Video metadata, archive, and contextual lookup resources. |
| [Phone Numbers](/utils/phone_number.md) | Phone lookup and caller-identification resources. |
| [Emails](/utils/emails.md) | Email verification, enrichment, and format discovery. |
| [Domains](/utils/domains.md) | Domain, WHOIS, technology, and infrastructure research. |
| [Documents](/utils/documents.md) | Public document and publication search resources. |
| [Database Breach](/utils/db_breach.md) | Breach exposure checks and credential monitoring resources. |
| [Maps](/utils/maps.md) | Geospatial, map, and location research resources. |
| [Companies and Leaks](/utils/companies_leaks.md) | Corporate intelligence and leak-oriented sources (use responsibly). |
| [OSINT Tool Collections](/utils/osint_tools.md) | Meta-directories and curated OSINT indexes. |
| [Others](/utils/others.md) | Supporting utilities that do not fit one primary category. |
| [Dating](/utils/dating.md) | Public-facing dating profile discovery resources (high-privacy domain). |

## How to Use This Repository

1. Start from the category index above.
2. Open a category file and scan the **Notes** column for quick fit.
3. Validate tool availability and jurisdictional constraints before use.
4. Cross-check results with independent sources.

## Contribution Guidelines

Contributions are welcome. Please read [`CONTRIBUTING.md`](/CONTRIBUTING.md) before opening a pull request.

When adding or updating entries, include:

- Clear category placement.
- Concise description and realistic access label.
- Neutral language (avoid promotional claims).
- Caution notes when a tool can be misused.

## Maintenance and Status

- This is a community-curated list and may include stale links over time.
- Tool access models may change without notice.
- Maintainers prefer small, focused updates with clear rationale.

## License and Attribution

No repository license file is currently present. Until a license is added, treat contributions as shared for repository use under standard GitHub visibility expectations.

Tool names, logos, and trademarks belong to their respective owners.
