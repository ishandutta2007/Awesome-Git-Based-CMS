# Awesome-Git-Based-CMS

# Top Git-Based CMS Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Content Versioning, Static Site Editing & Self-Hosted Git Workflows*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Git-Based CMS**. These tools provide a friendly editing interface on top of a Git repository—committing Markdown, JSON, or YAML files directly to your codebase—so non-technical editors can manage content without touching Git, while developers retain full version control and deployment simplicity.

**Examples** include Contentful, TinaCMS, Decap CMS, CloudCannon, Sanity, Strapi, Storyblok, Prismic, and Sveltia CMS (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, Git-native content workflows, and transparent editing interfaces—ideal for Jamstack sites, documentation projects, and teams that refuse database lock-in. The open-source landscape is anchored by **Decap CMS** (the established standard, formerly Netlify CMS), **Sveltia CMS** (its modern successor with active development), and **TinaCMS** (visual editing with GraphQL), with **Pages CMS** offering the simplest GitHub-focused option. **Forestry** is discontinued and should only be referenced for migration context .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Contentful](https://www.contentful.com/)**  
  API-first headless CMS with a mature content modeling UI, GraphQL and REST APIs, and enterprise-grade localization. **Not Git-based**—content lives in Contentful's database, not your repository. Included here because it's commonly listed alongside Git-based tools, but it's architecturally different .

- **[TinaCMS (Cloud)](https://tina.io/)**  
  Commercial tier of the open-source TinaCMS. Offers TinaCloud for hosted content API, visual editing, and team collaboration. Free tier covers 1 user and 500 content assets/month; paid plans from $29/month . The open-source core is self-hostable.

- **[CloudCannon](https://cloudcannon.com/)**  
  Git-based CMS with visual editing, live previews, and team workflows. Connects to GitHub, GitLab, and Bitbucket. Popular for Jekyll, Hugo, and Eleventy sites. Commercial with tiered pricing. No fully open-source self-hosted option.

- **[Sanity](https://www.sanity.io/)**  
  API-first headless CMS with real-time collaboration, GROQ query language, and a customizable Studio (React-based). **Not Git-based**—content is stored in Sanity's Content Lake. Included for ecosystem context; architecturally API-first .

- **[Strapi Cloud](https://strapi.io/)**  
  Hosted tier of the open-source Strapi headless CMS. Strapi is **API-first, database-backed** (not Git-based). The open-source core is MIT licensed; the cloud tier adds managed infrastructure. Included because it's frequently compared to Git-based tools, though it serves a different architecture .

- **[Storyblok](https://www.storyblok.com/)**  
  API-first headless CMS with a visual editor and component-based content model. **Not Git-based**. Included for comparison context.

- **[Prismic](https://prismic.io/)**  
  API-first headless CMS with Slice Machine for component-driven development. **Not Git-based**. Included for comparison context.

## Open-Source GitHub Projects

- **[Decap CMS (formerly Netlify CMS)](https://github.com/decaporg/decap-cms)**  
  The established open-source Git-based CMS. A React single-page app that provides a friendly editing UI on top of GitHub, GitLab, or Bitbucket. Content is committed directly to your repository as Markdown/JSON/YAML. **Drop-in installation**: add two files (an HTML entry point and a YAML config) to your site's `/admin` path . Works with any static site generator. **Status**: mature with 18,700+ GitHub stars, but development has slowed—Sveltia CMS emerged as a modern alternative addressing longstanding issues . MIT licensed. Best for teams already using Decap or Netlify CMS that want a stable, proven solution.

- **[Sveltia CMS](https://github.com/sveltia/sveltia-cms)**  
  The de facto successor to Netlify/Decap CMS. A complete modern rewrite in Svelte, maintaining **full configuration compatibility** with Decap's `config.yml` while delivering significantly improved performance (smaller bundle, faster load), first-class i18n support, and a modern UX . Addresses 355+ issues that lingered in Decap. Framework-agnostic, works with Astro, Eleventy, Hugo, and any SSG. Self-hostable as a static single-page app. MIT licensed. **Growing adoption**: U.S. government agencies and 175+ sites migrated from Decap . Best for greenfield Git-based CMS projects and teams migrating from Decap seeking active maintenance.

- **[TinaCMS](https://github.com/tinacms/tinacms)**  
  Open-source Git-based CMS with **real-time visual editing**—editors see changes inline on the live page, not in a separate admin panel. Uses a GraphQL content API and TypeScript schema configuration. Apache 2.0 licensed. **Key trade-off**: requires Node.js in your project, which partially undoes Hugo's zero-Node simplicity—a significant consideration for Hugo users . Best for Next.js projects and teams that prioritize inline visual editing over minimal setup complexity.

- **[Pages CMS](https://github.com/pages-cms/pages-cms)**  
  A simple, free, GitHub-focused Git-based CMS. Minimal configuration, clean interface, and no build step required. Positioned as the simplest option for small projects and personal sites. Best for developers who want a lightweight editor without the full complexity of Decap or TinaCMS .

### Additional Strong Open-Source Options

- **Spaceship CMS** — MDX content management for Astro sites with GitHub integration. Best for Astro-specific documentation and blog projects .
- **FrontAid CMS** — Git-based CMS specifically for JSON files. Editors fill in content based on a defined data model, and changes are pushed to your Git repository . Best for structured data editing rather than prose-heavy content.
- **Frameworks for building custom systems**: Start with **Sveltia CMS** for new Git-based projects—it offers Decap compatibility with active development. Use **Decap CMS** if you need maximum ecosystem maturity and existing documentation. Choose **TinaCMS** when inline visual editing is non-negotiable and you accept the Node.js dependency. Use **Pages CMS** for the simplest possible GitHub-based editing workflow.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- **Git-based vs. API-first distinction matters**: Contentful, Sanity, Strapi, Storyblok, and Prismic are API-first headless CMS platforms where content lives in their databases—not in your Git repository. They're included for ecosystem context but solve a different problem than true Git-based CMS .
- **Forestry is discontinued** (shut down 2023); TinaCMS is its official successor. Do not select Forestry for new projects .
- Self-hosted Git-based CMS requires OAuth configuration with your Git provider (GitHub, GitLab, or Bitbucket) and a proxy server (like `decap-server`) for authentication .

---

**Made for Jamstack developers, content editors, documentation teams, and anyone who wants version-controlled content without a database.**  
Let's make content management more open, Git-native, and accessible.
