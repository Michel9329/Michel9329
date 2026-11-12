# Michel Dimitri

I run [Sharkcode](https://sharkcodestudio.com), a small web studio: websites and online shops for small businesses in Italy.

I work with a system of AI agents that I designed and built with Claude Code. Brand, copy, legal pages, code and quality checks go through specialized agents; I decide what gets built, write the rules they follow and check the result before it reaches a client. The repositories below are the parts of that system that can be public, separated from client code and data.

| Repository | What it is |
|---|---|
| [sharkcode-os](https://github.com/Michel9329/sharkcode-os) | How the system is built: pipeline, agents, hooks, memory. A page without code. |
| [claude-code-guardrails](https://github.com/Michel9329/claude-code-guardrails) | Hooks that deny a Claude Code tool call when it breaks a rule, so the rule does not depend on the model remembering it. |
| [humanizer-it](https://github.com/Michel9329/humanizer-it) | A Claude Code skill for Italian text that should not read as machine-written. |
| [gdpr-scanner](https://github.com/Michel9329/gdpr-scanner) | A Cloudflare Worker that finds trackers firing before consent, Google Fonts loaded from the CDN and missing privacy pages. |
| [image-review-portal](https://github.com/Michel9329/image-review-portal) | Image approval with versions, comments pinned to a point and a set number of sign-offs. |

Everything here is built with Claude Code, designed and reviewed by me.

I work in Italian, Spanish and English. Contact: info@sharkcodestudio.com
