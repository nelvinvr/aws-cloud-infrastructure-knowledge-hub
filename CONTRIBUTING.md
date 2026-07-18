# Contributing and Quality Standards

This is Nelvin Robinson's personal engineering knowledge base. Suggestions and corrections are welcome, but publication decisions remain aligned with the repository's learning goals, voice, privacy boundary, and quality standards.

## Core Principles

1. **Originality:** Public content must be written in my own words.
2. **Accuracy:** Technical claims must be checked against current official AWS documentation or supported by reproducible hands-on evidence.
3. **Honesty:** Do not invent production experience, lab results, certifications, failures, or project outcomes.
4. **Confidentiality:** Never include credentials, customer information, personal data, confidential information, or proprietary resources.
5. **Engineering value:** Explain why, when, trade-offs, failure modes, and operational ownership—not only definitions.
6. **Durability:** Write for future revision and on-the-job reference, not for a short-lived social post.
7. **Quality over speed:** One validated article is more valuable than several shallow pages.

## Learning and Publishing Workflow

**Study → Explain → Practise → Document → Review → Publish**

### 1. Study

- Start with official AWS documentation and primary AWS guidance.
- Record open questions rather than hiding uncertainty.

### 2. Explain

- Explain the concept without copying a source.
- Identify the problem before describing the service.
- Compare it with the closest realistic alternatives.

### 3. Practise

- Define an objective and expected behavior.
- Build in a controlled environment.
- Validate success and, where safe, introduce a failure.
- Record evidence and complete cleanup.
- Do not expose secrets or identifying account information.

### 4. Document

- Start from [ARTICLE-TEMPLATE.md](ARTICLE-TEMPLATE.md).
- Use the correct numbered domain folder.
- Use lowercase kebab-case filenames, for example: `shared-responsibility-model.md`.
- Store original diagrams in `assets/diagrams/` and supporting images in `assets/images/`.
- Link a detailed lab from `13-hands-on-labs/` rather than overcrowding an article.

### 5. Review

Verify:

- Technical accuracy and current service names
- Security, cost, reliability, and operational implications
- Originality and confidentiality
- Links and navigation
- Honest status and difficulty
- Lab and diagram evidence
- Readability and interview usefulness
- Review date

### 6. Publish

- Create a focused branch.
- Keep the pull request limited to one article or one coherent foundation change.
- Summarize what was added, how it was validated, and any known limitations.
- Merge only after the checklist is complete.
- Update [ROADMAP.md](ROADMAP.md) in the same pull request.

## Branch Naming

Examples:

- `foundation/repository-structure`
- `article/shared-responsibility-model`
- `lab/windows-ec2-systems-manager`
- `diagram/multi-az-web-architecture`
- `review/aws-backup-2027`
- `fix/broken-navigation-links`

## Commit Guidance

Use concise, outcome-focused commit messages:

- `Add shared responsibility model article`
- `Document Windows EC2 recovery lab`
- `Update AWS Backup references`
- `Fix storage topic navigation`

Do not mix unrelated work in one commit.

## Pull Request Checklist

- [ ] Scope is clear and focused
- [ ] Content is original
- [ ] Official AWS references are current
- [ ] Architecture and experience claims are accurate
- [ ] Article template is followed where applicable
- [ ] Lab validation and cleanup are documented
- [ ] Diagrams are original
- [ ] Navigation and related links work
- [ ] ROADMAP.md is updated
- [ ] Review date is present
- [ ] No secrets or sensitive data are included

## Content Status

Use these terms consistently:

- **Planned** — approved for the backlog
- **Currently writing** — active public draft
- **Article written** — content complete but not yet published
- **Published** — reviewed and merged into the main branch
- **Needs review** — technical freshness or accuracy requires attention

## Difficulty Levels

- 🟢 **Beginner:** foundational concepts and core use cases
- 🟡 **Intermediate:** integrations, operating considerations, and architecture choices
- 🔴 **Advanced:** complex design, scale, governance, resilience, migration, or deep troubleshooting

Difficulty measures the knowledge required to use the article effectively, not the importance of the topic.

## Source Policy

Preferred source order:

1. Official AWS documentation
2. AWS Well-Architected guidance and whitepapers
3. AWS Architecture Center and official workshops
4. AWS service pricing and quotas pages
5. Reputable primary vendor documentation for integrated technologies

Secondary sources may help understanding but should not be the sole authority for technical claims.

## Corrections and Suggestions

Corrections should explain:

- The specific claim or location
- Why it may be inaccurate or unclear
- A current primary source
- The proposed correction

A correction is welcome even when it challenges an existing explanation. The purpose of this repository is to improve engineering understanding over time.

## License and Attribution

Repository content is made available under the [MIT License](LICENSE). External trademarks, screenshots, documentation, and quoted material remain subject to their owners' terms. Prefer original diagrams and paraphrased explanations with links to primary sources.

