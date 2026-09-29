# Agent Handoff: Management AI Bridge

## Project Mission

Management AI Bridge is a GitHub Pages knowledge hub that translates GenAI capabilities into responsible management research, teaching, organizational analysis, decision support, and productivity workflows.

The project should remain focused on the bridge between AI technology and management practice. Do not turn it into a general AI news site or a technical ML engineering tutorial site.

## Current Architecture

- Public site content lives in `docs/`.
- GitHub Pages is configured to publish from the `main` branch and `/docs` folder.
- Jekyll config lives at `docs/_config.yml`.
- Shared page layout lives at `docs/_layouts/default.html`.
- Site styling lives at `docs/assets/css/style.css`.
- GitHub issue templates live in `.github/ISSUE_TEMPLATE/`.
- Planning documents live at the repository root.

## Content Model

Tutorials should include:

- Purpose
- When To Use
- Workflow
- Example Prompt
- Output Review Checklist
- Risks

Prompt pages should include:

- Use Case
- Input Needed
- Prompt
- Expected Output
- Review Criteria

Responsible AI guidance should be included wherever prompts or tutorials could affect research quality, teaching, privacy, decision-making, or organizational consequences.

## Editing Principles

- Preserve the management-wide framing.
- Avoid splitting content into separate Strategy, OB, or Management silos unless the user explicitly asks.
- Prefer practical workflows over abstract descriptions.
- Keep language clear for nontechnical management scholars and practitioners.
- Link large files externally instead of committing them to the repository.
- Do not commit secrets, access tokens, private workshop files, unpublished research data, student data, or confidential organizational information.
- Keep Markdown pages simple and compatible with GitHub Pages/Jekyll.

## Deployment Notes

The current expected GitHub Pages URL is:

```text
https://smiling97.github.io/management-ai-bridge/
```

The current `docs/_config.yml` uses:

```yaml
baseurl: "/management-ai-bridge"
```

If the repository name changes, update `baseurl` to match the new repository name.

## Validation Checklist

After edits, check:

- All Markdown pages have YAML front matter if they are under `docs/`.
- Navigation links still work with `relative_url`.
- The homepage links to the main content sections.
- New prompts include review criteria and risks.
- New tutorials include workflow steps and responsible-use cautions.
- No large media files or private data were added.
- GitHub Pages source remains `main` branch and `/docs` folder.

## Recommended Maintenance Workflow

1. Review new issues and discussion posts.
2. Convert accepted submissions into Markdown pages.
3. Keep resource pages current and remove dead links.
4. Add newsletter issues as dated Markdown files.
5. Update workshop archive pages when new AOM materials are available.
6. Run a local or static link/content check before committing.
7. Push changes to GitHub and verify the published site.

## Known Constraints

- Jekyll was not installed in the original local environment, so rendered local builds may not be available unless Ruby/Jekyll is installed.
- Large slide decks and videos should be stored externally.
- GitHub Discussions must be enabled manually in the GitHub repository settings.
