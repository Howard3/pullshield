# PullShield.dev

## What is PullShield.dev?
PullShield.dev is a system aimed at reducing bad pull requests to open-source repositories. Unlike existing solutions like linters and CI tools, PullShield focuses on **global reputation checks**, **age checks**, and **custom quality rules** for contributions. 

## Why PullShield.dev?
While tools like GitHub Actions already offer robust linting and test coverage options, they don’t address the **context** of a contributor’s history, the age of their account, or the overall **quality** of the PR itself beyond code formatting. We aim to fill this gap by providing **reputation-based**, **cross-platform** checks that can integrate with GitHub, GitLab, Gitea, and more.

## How it works
PullShield is built on the idea of improving pull requests with tools beyond code formatters:
1. **Reputation Checks:** Evaluate contributors based on their history (PR merges, reviews, activity).
2. **Age Checks:** Identify newer accounts or low-activity accounts for extra review.
3. **Quality Rules:** Configurable rules that repository maintainers can set to define what makes a good PR.

We aim to be platform-agnostic and are working towards support for **GitHub**, **GitLab**, **Gitea**, and other platforms.

## How to Contribute
We need your help collecting examples of good and bad pull requests to refine our system. To contribute:
1. Submit a PR example via our Issues tab, with a link and an explanation of why it's good or bad.
2. Provide feedback on rules or checks that could improve PR quality.

## Roadmap
- Collect examples of good and bad PRs
- Implement global reputation and age checks
- Build configurable rule-based quality checks
- Ensure compatibility with multiple platforms (GitHub, GitLab, Gitea)
- Explore AI tools in later stages once we understand the full scope of the problem

