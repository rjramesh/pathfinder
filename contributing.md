# Contributing to Pathfinder

Welcome, and thank you for your interest in contributing to Pathfinder!

The easiest way to do so is to open issues for questions, bug reports and areas
where documentation is lacking.

At this stage the code and documentation is still in a pretty rough shape, so
finding a place to contribute actual code can be difficult. If you do feel like
tackling an open issue, please do comment on the issue or open a PR. We are
happy to guide you through the process.

## Pull-requests

Keeping these points in mind will increase the odds of a successful PR:

- Keep the PR small.
- Have an accurate description of your changes and intentions with the PR.
- Code comments should describe the **why** and not the **how**.
- New features should have reasonable tests.
- Ensure CI is happy. CI will run automatically when the PR is opened. This includes checks checks for
  - formatting (`cargo fmt`)
  - linting (`cargo clippy`)
  - testing (`cargo test`)
- We (loosely) follow the [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.
- Commit messages should be sensible and descriptive.
- No extra merge commits in the PR. This usually only occurs if you've merged another branch into your PR branch. You should use `git rebase` instead.
