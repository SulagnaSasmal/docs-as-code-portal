# Docs-as-Code Platform — Documentation Guide

An interactive, single-page documentation guide covering the complete Docs-as-Code workflow — from Markdown authoring through Git version control, CI/CD pipeline, style linting, and multi-format publishing.

## Live Demo

Hosted on GitHub Pages: `sulagnasasmal.github.io/docs-as-code-portal/`

## What's Covered

The guide is structured around the full Docs-as-Code lifecycle:

| Section | Content |
|---------|---------|
| Introduction | What Docs-as-Code is and why it matters |
| What is Docs-as-Code? | Core principles — content as source code, Git-first, CI/CD for docs |
| Quick Start Guide | Set up a working Docs-as-Code environment from scratch |
| Markdown Authoring | Syntax, frontmatter, topic types, callouts, code blocks |
| Git & Version Control | Branch strategy, PR workflow, commit conventions for docs |
| CI/CD Pipeline | GitHub Actions workflows — lint, build, test, deploy |
| Style Linting (Vale) | Configure Vale with MSTP / Google style rules |
| Multi-Format Output | HTML, PDF, OpenAPI, Postman collections |
| Deployment | GitHub Pages, Netlify, custom CDN deployment |

## Tech Stack

- Single HTML file (inline CSS + JS — zero external dependencies)
- JetBrains Mono, Outfit, Inter (Google Fonts)
- Dark and light mode support
- Sidebar navigation with JavaScript-driven section switching

## Dark / Light Mode

The page supports dark and light themes via a toggle button (◐ / ☀) in the top action bar. Theme preference persists in `localStorage`. System `prefers-color-scheme` is respected on first visit.

## Status

**Infrastructure / Documentation Guide — Complete**

| Area | Status |
|------|--------|
| Full Docs-as-Code workflow guide | Complete |
| Sidebar navigation with section switching | Complete |
| Code examples with syntax highlighting | Complete |
| CI/CD GitHub Actions workflow examples | Complete |
| Vale configuration guide | Complete |
| Dark / light theme support | Complete |
| README | Complete |

## Relationship to DocForge

This page explains the **principles and workflow** behind Docs-as-Code. The [DocForge — Documentation Center Platform](https://github.com/SulagnaSasmal/Documentation-Center-Platform) is an interactive **demo** that shows the same pipeline in action.

## Future Enhancements

- Convert to multi-page site for deeper per-topic coverage
- Live Vale linting demo (in-browser)
- Downloadable starter kit (Markdown templates + GitHub Actions workflows)
- Video walkthrough companion
