<img src="./assets/header.svg" width="100%" alt="Tanin Rahman, product engineer. I build WordPress products end to end. Lately, the layer for AI agents. Open to remote roles.">

<p>
<a href="https://builtbytanin.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-c5ee5c?style=flat-square" alt="Portfolio"></a>
<a href="https://www.linkedin.com/in/taninrahman21/"><img src="https://img.shields.io/badge/LinkedIn-111316?style=flat-square" alt="LinkedIn"></a>
<a href="https://profiles.wordpress.org/taninrahman/"><img src="https://img.shields.io/badge/WordPress.org-111316?style=flat-square" alt="WordPress.org"></a>
<a href="mailto:builtbytanin@gmail.com"><img src="https://img.shields.io/badge/builtbytanin@gmail.com-111316?style=flat-square" alt="builtbytanin@gmail.com"></a>
</p>

Core developer at [bPlugins](https://bplugins.com) since 2023. I build the whole product, from the first forum question to the release after it, and lately the layer that lets AI agents work on a real WordPress site instead of guessing about it.

<br>

## The story so far

### <img src="https://img.shields.io/badge/2022-c5ee5c?style=flat-square" alt="2022" align="top">&nbsp; Learning to build

I started with Programming Hero's Complete Web Development course, then Learn with Sumit's Reactive Accelerator for React and Next.js.

My first full-stack app was [the-smart-tutor-client](https://github.com/taninrahman21/the-smart-tutor-client): React, Node/Express, Firebase Auth and Tailwind, deployed on Firebase. It was the first time I took something from an empty folder to a live URL.

### <img src="https://img.shields.io/badge/2023-c5ee5c?style=flat-square" alt="2023" align="top">&nbsp; First production code

I joined bPlugins as a plugin developer. My first Gutenberg blocks, PHP backends and React/SCSS admin UIs went out to real sites.

I also started answering the WordPress.org support threads for what I shipped. That habit taught me more about product than any course did.

### <img src="https://img.shields.io/badge/2023--2026-c5ee5c?style=flat-square" alt="2023-2026" align="top">&nbsp; Owning the whole product

My scope grew from interface work on one plugin to the full lifecycle of eight. Today I take every product through the same six steps:

<img src="./assets/lifecycle.svg" width="100%" alt="Analyse, Plan, Implement, Release, Support, Document">

- **Analyse.** Start from what users actually ask for in forum threads and feature requests, and from how competitors solve the same problem. Before building PDF Poster's 3D flipbook, I studied how Heyzine delivers that experience.
- **Plan.** Scope and approach are decided before code. I take part in product decisions, not only tickets.
- **Implement.** Gutenberg block in React, PHP 8 backend, REST endpoints, and an admin UI a stranger can use without asking.
- **Release.** Versioning, release tags, security patches, and a changelog in a consistent format.
- **Support.** I answer the forum threads myself. That is where the next round of analysis starts.
- **Document.** Plugin docs, and a `readme.txt` updated with every release so it never drifts from the code.

Along the way I took on mentoring junior developers on Gutenberg work.
<!-- FILL: one real milestone, e.g. a product you took over or built from scratch, with the year -->

| Product | What I built or changed | Installs |
|:--|:--|--:|
| [PDF Poster](https://wordpress.org/plugins/pdf-poster/) | Block integration, admin UI, 3D flipbook viewer, admin chatbot | 20,000+ |
| [Advance Custom HTML](https://wordpress.org/plugins/advance-custom-html/) | React editor, live preview, syntax highlighting | 10,000+ |
| [Document Embedder](https://wordpress.org/plugins/document-emberdder/) | Admin dashboard redesign, block UI, shortcodes, v2.3.0 | 10,000+ |
| [Timeline Block](https://wordpress.org/plugins/timeline-block/) | Layout engine, horizontal timeline, v2 | 3,000+ |
| [Document Viewer](https://wordpress.org/plugins/embed-office-viewer/) | Viewer block, settings UI, compatibility fixes | 2,000+ |
| [B Timeline](https://wordpress.org/plugins/b-timeline/) | Vertical and horizontal layouts, styling system | 2,000+ |
| [StreamCast](https://wordpress.org/plugins/streamcast/) | Player block UI, streaming embed | 1,000+ |
| [Voice Feedback](https://wordpress.org/plugins/voice-feedback/) | Built from scratch: admin UI, recording, playback | New |

<sub>These are bPlugins products built by a team. The highlights are the pieces I built or changed.</sub>

**Growing a PDF viewer into a product.** In PDF Poster I built a 3D flipbook and card-stack viewer on top of PDF.js. I also built an admin help chatbot that started as Fuse.js fuzzy search and later moved to the Gemini API.
<!-- FILL: one sentence on why you moved from fuzzy search to an LLM, and what it improved. -->
Then came a long bug-fix pass: CORS problems, iOS and Android failures, CJK font rendering and more.

<!--
Publish only after the fix has shipped.

**Auditing my own product.** I audited PDF Poster v2.5.2 for security and code quality and found serious issues: a hardcoded API key, SQL injection and missing nonce checks. They were fixed in [FILL: version]. Finding these in a product with 20,000+ installs is why I treat security as part of the feature, not a last step.
-->

### <img src="https://img.shields.io/badge/2026-c5ee5c?style=flat-square" alt="2026" align="top">&nbsp; The AI layer

AI assistants are good at talking about a site and bad at knowing anything real about it. They guess which plugin conflicts, which update is stale, what a setting is set to.

So I built **[My Site Hand](https://wordpress.org/plugins/my-site-hand/)**, my own plugin. It gives agents a proper interface instead of guesses:

- 46 actions registered through WordPress's **Abilities API**, so each one is discoverable and permission-checked
- A built-in **MCP server**, so Claude Desktop, Cursor and VS Code connect with token auth and a generated setup command
- **Site Health** results returned as structured data an agent can reason about

<!-- FILL: The decision I think about most: one real trade-off, e.g. what you chose NOT to expose to agents, or how a wrong agent action is contained, and why. -->

It is early: v1.0.0, and I'm working toward the first 100 real users.

[Source](https://github.com/taninrahman21/my-site-hand) · [WordPress.org](https://wordpress.org/plugins/my-site-hand/)

### <img src="https://img.shields.io/badge/Now-c5ee5c?style=flat-square" alt="Now" align="top">&nbsp; What I'm working on

1. Getting My Site Hand to its first 100 real users
2. Working through a TypeScript roadmap, started September 2026
3. A shared Playwright E2E setup for my plugins
4. A custom multi-role business system for a client

<br>

## Beyond WordPress

- **Full-stack JavaScript.** React, Node/Express and Firebase in [the-smart-tutor-client](https://github.com/taninrahman21/the-smart-tutor-client).
- **Laravel.** A take-home backend for a buy-now-pay-later flow: payment state machine, idempotency, webhook handling and a ledger. I used AI tools and kept the design decisions mine.
- **Client system.** Purchase, production, sales, accounts, HR and field marketing, each with its own permissions. <!-- FILL: stack, if the client allows it. -->
- **In design.** SiteVoice AI, a brand-voice-aware plugin for meta descriptions and excerpts. So far: concept, three UI mockups and the Gutenberg sidebar flow.

## How I work

**With AI.** Antigravity is my main editor.
<!-- FILL: I use it for [scaffolding / refactors / tests]. I review [capability checks, sanitization, escaping] by hand, and I don't delegate [one thing you never hand to AI]. -->

**Learning with proof.** For TypeScript I don't move on until I can predict code without an editor, explain it in my own words, build it from a blank file, and debug it without reaching for `any`.

## Tools

<p>
<img src="https://img.shields.io/badge/Gutenberg-111316?style=flat-square" alt="Gutenberg">
<img src="https://img.shields.io/badge/Block_API-111316?style=flat-square" alt="Block API">
<img src="https://img.shields.io/badge/React-111316?style=flat-square" alt="React">
<img src="https://img.shields.io/badge/JavaScript-111316?style=flat-square" alt="JavaScript">
<img src="https://img.shields.io/badge/SCSS-111316?style=flat-square" alt="SCSS">
<img src="https://img.shields.io/badge/PHP_8-111316?style=flat-square" alt="PHP 8">
<img src="https://img.shields.io/badge/WordPress_core-111316?style=flat-square" alt="WordPress core">
<img src="https://img.shields.io/badge/REST_API-111316?style=flat-square" alt="REST API">
<img src="https://img.shields.io/badge/MySQL-111316?style=flat-square" alt="MySQL">
<img src="https://img.shields.io/badge/Node.js-111316?style=flat-square" alt="Node.js">
<img src="https://img.shields.io/badge/Express-111316?style=flat-square" alt="Express">
<img src="https://img.shields.io/badge/Firebase-111316?style=flat-square" alt="Firebase">
<img src="https://img.shields.io/badge/Tailwind-111316?style=flat-square" alt="Tailwind">
<img src="https://img.shields.io/badge/MCP-111316?style=flat-square" alt="MCP">
<img src="https://img.shields.io/badge/Abilities_API-111316?style=flat-square" alt="Abilities API">
<img src="https://img.shields.io/badge/Webpack-111316?style=flat-square" alt="Webpack">
<img src="https://img.shields.io/badge/ESLint-111316?style=flat-square" alt="ESLint">
<img src="https://img.shields.io/badge/Composer-111316?style=flat-square" alt="Composer">
<img src="https://img.shields.io/badge/Git-111316?style=flat-square" alt="Git">
</p>

<p>
<img src="https://img.shields.io/badge/Learning-c5ee5c?style=flat-square" alt="Learning">
<img src="https://img.shields.io/badge/TypeScript-111316?style=flat-square" alt="TypeScript">
<img src="https://img.shields.io/badge/Playwright-111316?style=flat-square" alt="Playwright">
</p>

<br>

---

If you're hiring for a product-minded WordPress or full-stack role and want someone who ships, supports and keeps learning, let's talk.

<a href="mailto:builtbytanin@gmail.com"><img src="https://img.shields.io/badge/Say_hello_%E2%86%92-c5ee5c?style=for-the-badge" alt="Say hello"></a>
