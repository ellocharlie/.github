## What This PR Does

<!-- Describe what this PR changes and why. Be specific — "update code" is not a description. -->

Closes #

## Type of Change

- [ ] Bug fix (non-breaking change fixing an issue)
- [ ] New feature (non-breaking change adding functionality)
- [ ] Breaking change (fix or feature that changes existing behavior)
- [ ] Documentation update
- [ ] Content (blog post, case study, changelog entry)
- [ ] CI/CD or infrastructure change
- [ ] Refactor (no behavior change)
- [ ] Dependency update

## What Changed and Why

<!-- Walk through the key changes. If the diff is large, explain the structure so reviewers know where to look first. -->

## How It Was Tested

<!-- Describe how you tested these changes. "Ran the test suite" is a start — be more specific about what you verified. -->

- [ ] `bun test` passes
- [ ] `bun run validate` passes (content repo only)
- [ ] Manual verification: (describe what you tested manually)
- [ ] No applicable tests (explain why)

## Checklist

**Before submitting:**

- [ ] I have read `CONTRIBUTING.md`
- [ ] I have read `CLAUDE.md` for this repo
- [ ] I have read `AGENTS.md` (if this PR is AI-assisted or agent-generated)
- [ ] My code follows the existing style and conventions in this repo
- [ ] This is a single logical change (no bundled unrelated changes)
- [ ] Commit messages follow conventional commit format
- [ ] I have added or updated tests for logic changes
- [ ] All tests pass locally
- [ ] I have updated documentation where applicable
- [ ] I have not hardcoded any secrets, tokens, or credentials
- [ ] I have not introduced new dependencies without discussion

**For content PRs:**

- [ ] Frontmatter is complete and valid (`bun run validate` passes)
- [ ] All claims are factual and cited where appropriate
- [ ] Voice and tone follows `MEMO.md` guidelines
- [ ] `seo.canonical` is set and correct
- [ ] No features are promised that are not currently shipped

**For `ellocharlie-engine` changes:**

- [ ] `workspace.yaml` updated if any org-level config changed
- [ ] Agent configs updated if agent behavior changed
- [ ] `bun run index:build` run after agent config changes

## KPI / OKR Reference

<!-- If this PR implements work against a measurable target in workspace.yaml, reference it here. -->

- [ ] Not directly tied to a KPI/OKR
- [ ] Tied to: (e.g., `cx.nps_target`, `content.blog_cadence`, Q2 OKR: "Ship Phase 1 CX platform")

## Agent Declaration

<!-- If this PR was created with AI assistance, complete this section. If fully human-authored, you may delete it. -->

- [ ] This PR was generated or significantly assisted by an AI agent
- [ ] A human has reviewed the **complete diff** before submission
- [ ] The changes solve a real, specific problem (not speculative improvements)
- [ ] No fabricated content, hallucinated functionality, or invented metrics
- [ ] The AI agent that assisted is identified: ________________
