# Contributing to microstack-dev

Thanks for your interest in contributing.

microstack-dev focuses on small, high-quality libraries with a clearly defined scope.
Please read this document carefully before proposing changes.

## Guiding Principles

- One library, one responsibility
- Minimal public API
- Zero dependencies by default
- TypeScript-first design
- Stability over features

Large or multi-purpose libraries will be rejected.

## Proposing a New Library

Before proposing a new library, ask:
1. Does this solve a single, well-defined problem?
2. Can v1 be implemented in under one week?
3. Can the API be explained in a short README?

If the answer to any of these is no, the proposal is likely out of scope.

Open a discussion or issue with:
- The problem being solved
- Intended users
- Minimal API sketch
- Expected scope for v1

## Pull Requests

- Keep PRs small and focused
- Avoid mixing refactors with feature changes
- Follow existing code style
- Add or update tests where applicable
- Update documentation if behavior changes

PRs that introduce feature creep or unnecessary abstraction may be closed.

## Code Style

- TypeScript preferred
- ESM-first where possible
- Clear, explicit types
- No unused exports
- No hidden side effects

## Review Process

Reviews prioritize:
- Scope control
- API clarity
- Long-term maintainability

Not all contributions will be accepted, even if technically correct.
