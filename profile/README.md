<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/lockup-dark.svg">
    <img src="assets/lockup-light.svg" alt="Argon Labs" height="88">
  </picture>
</p>

**Argon Labs builds developer infrastructure for AI agents and the data they touch.**

## Projects

| Project | What it is |
| --- | --- |
| [Argon](https://github.com/argon-lab/argon) | MongoDB sandboxes for AI agents, with Git for MongoDB underneath: fork a real database per agent run, review what changed, merge or discard. MIT. |
| [argon-agents](https://github.com/argon-lab/argon-agents) | Python SDK for Argon. |
| [benchmarks](https://github.com/argon-lab/benchmarks) | Reproducible measurements and walkthroughs behind our published numbers. |
| [homebrew-tap](https://github.com/argon-lab/homebrew-tap) | Homebrew formula for the Argon CLI. |

Install the Argon CLI:

```bash
brew install argon-lab/tap/argonctl                  # macOS or Linux
npm install -g argonctl --allow-scripts=argonctl     # anywhere with Node.js 24
pip install argon-agents                             # the Python SDK
```

More at [argonlabs.tech](https://argonlabs.tech). Security reports: security@argonlabs.tech ([policy](https://github.com/argon-lab/.github/blob/main/SECURITY.md)).
