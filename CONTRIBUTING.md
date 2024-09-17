### 1. Submitting PR Examples (Good, Bad, or Spam)
To help us fine-tune PullShield’s systems, we’re collecting examples of good, bad, and spam PRs. These examples will not only improve the system but will also serve as **training material** for other developers to understand what makes a good, bad, or spam pull request.

Instead of creating issues, we ask that you submit these examples via pull requests, adding them as markdown files in the `/examples` directory. Each file should follow the naming format:

`<rating>-<repository-name>-<PR-number>.md`

For example:
- good-github-actions-123.md
- bad-nodejs-456.md

1. **Fork the Repository** and clone it locally.
2. Create a markdown file in the `/examples` folder.
3. Use the following structure in your markdown file:

```markdown
## PR Title: [PR Title Here]

**Repository:** [Repository Name]

**PR Link:** [Link to the PR]

**Why is this PR Good/Bad?**
- Explanation of why this PR is a good, bad, or spam example.

**Spam/No Improvement:**
- [ ] This PR was spam or a low-quality contribution with no intention to improve the project.

**Lessons/Improvements:**
- (Optional) If applicable, suggestions for improving bad PRs or reasons why good PRs stood out.

**Training Notes:**
- How this PR example can be used as a learning opportunity for making effective pull requests (optional if the PR is marked as spam).
```
