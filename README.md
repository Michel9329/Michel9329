# Michel Dimitri

**Web, Shopify & Custom App Developer · AI Agent Engineer**

I run [Sharkcode](https://sharkcodestudio.com), a small web studio: websites, online shops and custom web apps for small businesses in Italy, Spain and the United States. From 2022 to 2025 I also led web and e-commerce development at Gilbi, a digital agency working between Miami and Italy. I take on the technical side of projects for agencies and companies too, remote.

Since 2026 I work with a system of AI agents that I designed and built on Claude Code. Brand, copy, legal pages, code and quality checks go through specialized agents; I decide what gets built, write the rules they follow and check every page on a phone and on a desktop before it reaches a client. Six sites went into production this way in 2026.

## Open source

Client code is private. These repositories are the parts of the system, and the tools built next to it, that can be separated from client data.

- [sharkcode-os](https://github.com/Michel9329/sharkcode-os): how the system is built, with its pipeline, agents, hooks and memory. A page without code.
- [claude-code-guardrails](https://github.com/Michel9329/claude-code-guardrails): hooks that deny a Claude Code tool call when it breaks a project rule, so the rule does not depend on the model remembering it. Node.js, no dependencies.
- [humanizer-it](https://github.com/Michel9329/humanizer-it): a Claude Code skill for Italian text that should not read as machine-written.
- [pinna](https://github.com/Michel9329/pinna): visual feedback on websites. A reviewer clicks a point of a staging site and leaves a comment pinned there. Cloudflare Workers, Hono, D1, R2, Vue 3, with unit tests and browser tests on three engines.
- [image-review-portal](https://github.com/Michel9329/image-review-portal): image approval with versions, comments pinned to a point and a set number of sign-offs. Cloudflare Workers, Hono, D1, R2.
- [gdpr-scanner](https://github.com/Michel9329/gdpr-scanner): a Worker that opens a site in a headless browser and reports trackers firing before consent, Google Fonts loaded from the CDN and missing privacy pages. It runs behind the privacy check of the [free site audit](https://sharkcodestudio.com/en/strumenti/audit) on the studio's website. Cloudflare Workers, Browser Run, TypeScript.
- [aion2-build-guide](https://github.com/Michel9329/aion2-build-guide): a side project. Game build guides generated from data, with a consistency check and a mutation test. Node.js, Python.

Everything here is built with Claude Code, designed and reviewed by me.

## Client work

Some of the sites that are live:

- [metalogopedia.it](https://metalogopedia.it): speech therapy practice. Brand, photos, copy and video, then the site in Astro, Sanity and Tailwind on Cloudflare, in Italian and English.
- [auravivaseniorliving.it](https://auravivaseniorliving.it): residential community for the elderly near Rome. Name and brand, Astro site on Cloudflare with a private area, business email and legal pages.
- [exteristorante.it](https://exteristorante.it): restaurant site moved from WordPress to Astro on Cloudflare with the same design, plus a private area for the owner.
- [allevamentobarboncinimaatilayla.it](https://allevamentobarboncinimaatilayla.it): poodle kennel. Five languages, React and Vite with GSAP animations, served by Cloudflare Workers.
- [lindorug.com](https://lindorug.com): Shopify rug store in six languages. Monthly retainer from July 2025 to December 2026, and a new theme built on Impact that is not live.
- [sharkcodestudio.com](https://sharkcodestudio.com): the studio's own site in three languages, moved from Webflow to Astro on Cloudflare, with the free audit tool.

Also: digital wedding invitations with guest RSVP (React, TypeScript, Tailwind, Supabase with Row Level Security), already used for weddings. Those sites belong to the couples, so there are no links.

## Stack

- **Languages:** TypeScript, JavaScript, Liquid, PHP, Python, SQL
- **Websites:** Astro, React, Vue, Tailwind CSS, GSAP, Sanity
- **E-commerce:** Shopify (Liquid themes, metafields and metaobjects, GraphQL Admin API), Klaviyo
- **Infrastructure:** Cloudflare (Workers, Pages, D1, R2, KV, Durable Objects), Supabase, Vercel
- **AI:** Claude Code (sub-agents, skills, hooks), MCP servers
- **Tests:** Vitest, Playwright

I work in Italian, English and Spanish. [LinkedIn](https://www.linkedin.com/in/michel-dimitri) · info@sharkcodestudio.com
