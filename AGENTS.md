# AGENTS Guidelines for This Repository

This repository contains a Next.js application located in the root of this repository. When
working on the project interactively with an agent (e.g. the Codex CLI) please follow
the guidelines below so that the development experience – in particular Hot Module
Replacement (HMR) – continues to work smoothly.

## 1. Use the Development Server, **not** `npm run build`

* **Always use `npm run dev` (or `pnpm dev`, `yarn dev`, etc.)** while iterating on the
  application.  This starts Next.js in development mode with hot-reload enabled.
* **Do _not_ run `npm run build` inside the agent session.**  Running the production
  build command switches the `.next` folder to production assets which disables hot
  reload and can leave the development server in an inconsistent state.  If a
  production build is required, do it outside of the interactive agent workflow.

## 2. Keep Dependencies in Sync

If you add or update dependencies remember to:

1. Update the appropriate lockfile (`package-lock.json`, `pnpm-lock.yaml`, `yarn.lock`).
2. Re-start the development server so that Next.js picks up the changes.

## 3. Coding Conventions

* Prefer TypeScript (`.tsx`/`.ts`) for new components and utilities.
* Co-locate component-specific styles in the same folder as the component when
  practical.

## 4. Useful Commands Recap

| Command            | Purpose                                            |
| ------------------ | -------------------------------------------------- |
| `npm run dev`      | Start the Next.js dev server with HMR.             |
| `npm run lint`     | Run ESLint checks.                                 |
| `npm run test`     | Execute the test suite (if present).               |
| `npm run build`    | **Production build – _do not run during agent sessions_** |

---

Following these practices ensures that the agent-assisted development workflow stays
fast and dependable.  When in doubt, restart the dev server rather than running the
production build.
Luxury Beauty Brand Requirements

The preferred design style is luxury Korean skincare and cosmetics.

Visual characteristics:

Soft blush pink, ivory, champagne, rose gold, and pearl color palettes
Premium glassmorphism effects used sparingly
Elegant luxury product photography
High-end beauty campaign aesthetics
Soft lighting and premium reflections
Large hero banners with editorial composition
Magazine-quality visual presentation
Premium ecommerce experience

Homepage should typically contain:

Luxury hero section
Featured products showcase
Brand story section
Ingredient highlights
Testimonials
Membership or loyalty section
Premium product collection
Trust indicators

Avoid:

SaaS dashboard layouts
Startup landing page structures
Corporate software aesthetics
Developer-focused UI
Generic Tailwind templates

The website should feel similar to a premium beauty brand campaign rather than a software product website.

The website should feel similar to a premium beauty brand campaign rather than a software product website.

### Design Reference

Primary design reference:
<img width="1536" height="1024" alt="ChatGPT Image May 29, 2026, 09_36_41 PM (1)" src="https://github.com/user-attachments/assets/d20eefe7-c269-4999-aa82-3e3f70573bc4" />


Always use this image as the primary visual inspiration for:

- Layout composition
- Color palette
- Product presentation
- Typography hierarchy
- Luxury atmosphere
- Visual storytelling
- Premium ecommerce experience

The generated design should closely match the overall quality, elegance, and realism shown in the reference image.
