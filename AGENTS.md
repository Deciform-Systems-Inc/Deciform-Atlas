# Deciform documentation guidance

This repository contains public operator guides for Deciform, a product of Deciform Systems, Inc. Pages are MDX with YAML frontmatter; navigation, branding and links live in `docs.json`.

- Write for the person using the workspace. Use concise instructions, exact UI labels and synthetic examples.
- Describe verified product behavior. Distinguish saved evidence, AI suggestions, reviewed proposals, applied model changes and operator-recorded accounts.
- Keep access requirements explicit. Client membership covers its engagements; collection responses and video joins require editing access. Links do not invite people or grant access.
- Explain practical limits: navigation drafts are held in memory, AI output needs review, and the Markdown handoff is not a complete backup or privacy export.
- Keep customer material, credentials, personal data, private links, internal identifiers, implementation notes and security findings out of this public repository.
- Link to the published Privacy, Terms and Data & AI pages. Do not invent legal commitments, retention periods, service levels or unsupported capabilities.
- Preserve the Mintlify starter attribution in `LICENSE`. Verify Mintlify configuration against its current official schema.
- Run `npx --yes mint@4.2.915 validate` and `npx --yes mint@4.2.915 broken-links` before submitting changes. Review the resulting diff; publishing remains a separate step.
