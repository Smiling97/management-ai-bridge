# Management AI Bridge: Project Plan

## Project Description

**Management AI Bridge** is an open GitHub-based knowledge hub that helps management scholars, educators, students, and practitioners translate GenAI capabilities into responsible, practical management work.

The project focuses on the bridge between **AI technology** and **management practice**, rather than treating GenAI as only a technical topic. It organizes applied resources around how AI can improve research, teaching, organizational analysis, decision-making, productivity, and community learning.

The project will archive Algorithm Apprentices / AOM workshop materials from 2025 and 2026, publish short tutorials, maintain a management-focused prompt library, share curated learning resources, and support discussion through GitHub.

## Implementation Structure

Use one public GitHub repository:

```text
management-ai-bridge/
  README.md
  LICENSE
  CONTRIBUTING.md

  docs/
    index.md
    about.md
    getting-started.md

    aom-workshops/
      index.md
      2025.md
      2026.md

    tutorials/
      index.md
      literature-review.md
      teaching-preparation.md
      organizational-analysis.md
      decision-support.md
      productivity-workflows.md

    prompts/
      index.md
      research-prompts.md
      teaching-prompts.md
      analysis-prompts.md
      decision-prompts.md
      productivity-prompts.md

    resources/
      index.md
      courses.md
      tools.md
      papers.md
      communities.md

    newsletter/
      index.md
      issue-001.md

    responsible-ai/
      index.md
      academic-use.md
      organizational-use.md
      limitations-and-risks.md

  .github/
    ISSUE_TEMPLATE/
      resource_submission.md
      prompt_submission.md
      correction_request.md
      tutorial_request.md
```

## Public Interface

- **GitHub Pages** will publish the website from the `docs/` folder.
- **README.md** will describe the project, audience, and contribution process.
- **CONTRIBUTING.md** will explain how community members submit prompts, tutorials, resources, and corrections.
- **GitHub Discussions** will be enabled with these categories:
  - `Announcements`
  - `AOM Workshop Follow-Up`
  - `GenAI Use Cases`
  - `Prompt Sharing`
  - `Teaching and Research`
  - `Responsible AI`
- **GitHub Issues** will handle structured submissions and maintenance tasks.
- Large files such as videos and large slide decks will be stored externally and linked from the relevant workshop pages.

## Core Content Model

Each tutorial should use this structure:

```markdown
# Title

## Purpose
What management task this helps with.

## When To Use
The practical situation where this workflow applies.

## Workflow
Step-by-step process.

## Example Prompt
Reusable prompt template.

## Output Review Checklist
How to judge whether the AI output is useful, accurate, and responsible.

## Risks
Common failure modes, bias concerns, privacy concerns, or overreliance risks.
```

Each prompt entry should use this structure:

```markdown
# Prompt Title

## Use Case
What task this prompt supports.

## Input Needed
What the user should provide.

## Prompt
The reusable prompt.

## Expected Output
What good output should look like.

## Review Criteria
How to evaluate and revise the AI response.
```

## Minimum Launch Content

The first implementation should include:

- Homepage explaining the mission and audience.
- About page describing the bridge between AI technology and management practice.
- AOM 2025 and 2026 archive pages.
- Five applied tutorials:
  - GenAI for literature review
  - GenAI for teaching preparation
  - GenAI for organizational analysis
  - GenAI for decision support
  - GenAI for productivity workflows
- Ten reusable management-focused prompts.
- One newsletter issue.
- Responsible AI guidance for academic and organizational contexts.
- GitHub issue templates for community submissions.

## Assumptions and Defaults

- Repository is public.
- Website is static Markdown served through GitHub Pages.
- No custom web app, database, or login system is needed for version 1.
- GitHub Discussions will be the primary community interaction space.
- External storage will be used for large AOM materials.
- The project name is **Management AI Bridge** unless renamed later.
