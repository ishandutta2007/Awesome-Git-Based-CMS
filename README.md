# Awesome-Git-Based-CMS

## Top Git-Based CMS Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Content Versioning, Static Site Editing & Self-Hosted Git Workflows*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Git-Based CMS**. These tools provide a friendly editing interface on top of a Git repository—committing Markdown, JSON, or YAML files directly to your codebase—so non-technical editors can manage content without touching Git, while developers retain full version control and deployment simplicity.



**Examples** include Contentful, TinaCMS, Decap CMS, CloudCannon, Sanity, Strapi, Storyblok, Prismic, and Sveltia CMS (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, Git-native content workflows, and transparent editing interfaces—ideal for Jamstack sites, documentation projects, and teams that refuse database lock-in. The open-source landscape is anchored by **Decap CMS** (the established standard, formerly Netlify CMS), **Sveltia CMS** (its modern successor with active development), and **TinaCMS** (visual editing with GraphQL), with **Pages CMS** offering the simplest GitHub-focused option. **Forestry** is discontinued and should only be referenced for migration context .



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global Headless and Git-Based CMS market is estimated between **.2B and .9B**, growing rapidly at a CAGR of **~18% to 22%** toward a projected – by the mid-2030s. The sector is **highly fragmented** rather than concentrated (*winner-take-all*), marked by fierce competition among enterprise API clouds (Contentful, Sanity), open-source database-backed frameworks (Strapi), and developer-centric Git-native static site workflows (CloudCannon, TinaCMS, Decap, Keystatic). Most enterprise engineering teams maintain two or more distinct CMS solutions simultaneously to address specific editorial and engineering workflows.

## SaaS/Hosted Platforms

| Platform | Company Scale (Valuation / Revenue) | Architecture / Type | Pricing (Starting Tier) | Free Tier Limits / Free Trial Details |
| :--- | :--- | :--- | :--- | :--- |
| **[Contentful](https://www.contentful.com/)** | **.0B Valuation** (~ ARR / + funding) | API-first Headless (Cloud Database) | Starts at **/mo** (Lite / Basic Plan) | **Free forever plan**: Up to 10 users, 2 roles, 2 locales, 1 Starter Space, 100K API calls/month, and 50 GB CDN bandwidth/month |
| **[Sanity](https://www.sanity.io/)** | **~ Valuation** (~ ARR / + funding) | API-first Headless (Content Lake) | Starts at **/seat/mo** (Growth Plan) | **Free forever plan**: Up to 20 user seats (unlimited free viewers), 2 public datasets, 10,000 documents, 1M API requests/month, 5M CDN requests/month |
| **[Storyblok](https://www.storyblok.com/)** | **~ Valuation** (~ ARR /  funding) | API-first Headless (Component-based) | Starts at **.75/mo** (billed annually) or **/mo** (Growth Plan) | **Free forever plan**: 1 user seat (expandable to 2), 1 space, 100 GB traffic/month, 1M API requests/month, 2 locales, and Visual Editor access |
| **[Strapi Cloud](https://strapi.io/)** | **~ Valuation** (~ ARR /  funding) | Hosted Headless CMS (PostgreSQL / API) | Starts at **/mo** (billed annually) or **/mo** (Starter Plan) | **Free forever (Self-hosted Community Edition)**: Unlimited content and users when self-hosting; Strapi Cloud has no cloud free plan or cloud trial, but includes a **30-day trial** for self-hosted Enterprise features |
| **[Prismic](https://prismic.io/)** | **~ Valuation** (~ ARR / .4M funding) | API-first Headless (Slice Machine) | Starts at **/mo** (Starter Plan for up to 3 users) | **Free forever plan**: 1 user seat, 2 locales, 100 GB CDN bandwidth/month, unlimited API requests, and Slice Machine visual editor access |
| **[CloudCannon](https://cloudcannon.com/)** | **~ Valuation** (~.5M ARR /  funding) | Git-based CMS (Direct Git commits) | Starts at **/mo** (billed annually) or **/mo** (Standard Plan) | **21-day free trial**: Full Standard Plan features, unlimited test sites on .cloudvent.net domains, no credit card required |
| **[TinaCMS (TinaCloud)](https://tina.io/)** | **~ Valuation** (SSW Group backing / Open-core) | Git-based CMS (GraphQL + Git sync) | Starts at **/mo** (Team Plan) | **Free forever plan**: Up to 2 users, 500 assets/month, real-time visual editing, and Git sync |

## Open-Source GitHub Projects

Curated list of active, open-source Git-based content management systems, sorted descending by GitHub stargazers count:

- **[Decap CMS (formerly Netlify CMS)](https://github.com/decaporg/decap-cms)** [![GitHub stars](https://img.shields.io/github/stars/decaporg/decap-cms?style=social&color=white)](https://github.com/decaporg/decap-cms/stargazers)  
  The established open-source Git-based CMS standard. A single-page React app that provides a clean content authoring UI on top of GitHub, GitLab, or Bitbucket. Commits Markdown, JSON, and YAML directly to your repository. **Drop-in installation**: add an HTML entry point and YAML config to your static site's /admin route. Works with any static site generator (Hugo, Jekyll, Eleventy, Gatsby, etc.). MIT licensed.

- **[TinaCMS](https://github.com/tinacms/tinacms)** [![GitHub stars](https://img.shields.io/github/stars/tinacms/tinacms?style=social&color=white)](https://github.com/tinacms/tinacms/stargazers)  
  Open-source Git-backed headless CMS delivering **in-context visual live editing**—authors edit text and media directly on the rendered page. Powered by a TypeScript schema-as-code configuration and a GraphQL content layer. Ideal for modern Next.js and React stacks. Apache 2.0 licensed.

- **[Statamic Core](https://github.com/statamic/cms)** [![GitHub stars](https://img.shields.io/github/stars/statamic/cms?style=social&color=white)](https://github.com/statamic/cms/stargazers)  
  A powerful flat-file, Git-friendly CMS powered by PHP and Laravel. Content is saved as YAML front-matter files directly in your repository without requiring a relational database. Features a robust control panel, live preview, version control integration, and asset management.

- **[Prose](https://github.com/prose/prose)** [![GitHub stars](https://img.shields.io/github/stars/prose/prose?style=social&color=white)](https://github.com/prose/prose/stargazers)  
  A classic, lightweight web-based content editor specifically designed for managing Jekyll websites and Markdown documents hosted directly on GitHub. Connects via GitHub OAuth to provide a clean writing environment with live Markdown previews and syntax highlighting.

- **[Pages CMS](https://github.com/pages-cms/pages-cms)** [![GitHub stars](https://img.shields.io/github/stars/pages-cms/pages-cms?style=social&color=white)](https://github.com/pages-cms/pages-cms/stargazers)  
  A fast, GitHub-native Git-based CMS that requires zero build step or server setup. Offers a clean, minimal interface designed for personal blogs, documentation, and small business sites. Commits changes directly to your repository branches. MIT licensed.

- **[Outstatic](https://github.com/avitorio/outstatic)** [![GitHub stars](https://img.shields.io/github/stars/avitorio/outstatic?style=social&color=white)](https://github.com/avitorio/outstatic/stargazers)  
  A Git-based headless CMS tailored for Next.js (App Router and Pages Router). Provides a full-featured dashboard, rich text editor, custom schema creation, and automatic commits to GitHub repositories without external databases or third-party cloud services. MIT licensed.

- **[Sveltia CMS](https://github.com/sveltia/sveltia-cms)** [![GitHub stars](https://img.shields.io/github/stars/sveltia/sveltia-cms?style=social&color=white)](https://github.com/sveltia/sveltia-cms/stargazers)  
  A modern, lightweight successor to Decap/Netlify CMS rebuilt from scratch in Svelte. Maintains **100% configuration compatibility** with Decap's config.yml while offering faster initial load times, built-in internationalization (i18n), and an improved mobile-friendly editing UX. Works statically with Astro, Hugo, Eleventy, and Vite. MIT licensed.

- **[Jekyll Admin](https://github.com/jekyll/jekyll-admin)** [![GitHub stars](https://img.shields.io/github/stars/jekyll/jekyll-admin?style=social&color=white)](https://github.com/jekyll/jekyll-admin/stargazers)  
  The official in-browser graphical interface plugin for Jekyll sites. Runs locally or in deployment environments to let content creators author posts, manage pages, upload media files, and update front matter with automated Git tracking. MIT licensed.

- **[Keystatic](https://github.com/Thinkmill/keystatic)** [![GitHub stars](https://img.shields.io/github/stars/Thinkmill/keystatic?style=social&color=white)](https://github.com/Thinkmill/keystatic/stargazers)  
  An open-source, Git-based content management framework by Thinkmill built for Next.js, Astro, and Remix. Allows structured content definition via TypeScript schemas with local filesystem development mode and cloud/GitHub sync for production publishing. MIT licensed.

- **[Static CMS](https://github.com/StaticJsCMS/static-cms)** [![GitHub stars](https://img.shields.io/github/stars/StaticJsCMS/static-cms?style=social&color=white)](https://github.com/StaticJsCMS/static-cms/stargazers)  
  A community-maintained, modernized fork of Netlify CMS. Offers a drop-in single-page application admin interface with TypeScript support, enhanced collection configurations, and native GitHub/GitLab/Bitbucket authentication. MIT licensed.

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
