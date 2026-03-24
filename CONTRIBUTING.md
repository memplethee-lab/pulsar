# Contributing to pulsar

We welcome all contributions to improve pulsar! Whether you're fixing bugs, adding new tools, or improving documentation, we're glad you're here.

## Branch Naming

Please use the following naming convention for branches:

- **feat/** for new features or tools: `feat/add-ledger-entry-decoder`
- **fix/** for bug fixes: `fix/rpc-timeout-error`
- **docs/** for documentation changes: `docs/improve-readme-examples`
- **task/** for scaffolding, chores, or maintenance: `task/repo-scaffolding`

## Commit Conventions

We follow a simplified version of [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/):

- `feat: ...` for a new feature
- `fix: ...` for a bug fix
- `docs: ...` for documentation
- `chore: ...` for maintenance (e.g., updating dependencies)
- `refactor: ...` for code refactoring

Example: `feat: add get_account_balance tool`

## Pull Request Checklist

Before submitting a pull request, please ensure:

1. [ ] **Branching:** You are on a branch following the `feat/`, `fix/`, etc. prefix.
2. [ ] **Linting:** `npm run lint` passes without errors.
3. [ ] **Typecheck:** `npm run typecheck` passes with zero TypeScript errors.
4. [ ] **Testing:** `npm test` passes all unit tests.
5. [ ] **Documentation:** Any new tools are documented in `README.md`.
6. [ ] **Build:** `npm run build` succeeds and output is present in `dist/`.

## PR Reviews

- All PRs require at least one approval from a maintainer or core contributor.
- Status checks (Lint, Typecheck, Test, Build) must pass before a PR can be merged.

---

Thank you for your contribution!