# How to run 🤔?

1. Install dependencies:
   1. From root directory (Will install dependencies for all the workspaces & projects): `npm install`
2. Run Locally (From root directory):
   1. To Run all projects at once: `npm run dev`
   2. Run individual projects: `npx turbo dev --filter <project_name>`
      i.e. To run apps/web: `npx turbo dev --filter web`

---

### Apps and Packages

- `docs`: a [Next.js](https://nextjs.org/) app
- `web`: another [Next.js](https://nextjs.org/) app
- `@repo/ui`: a stub React component library shared by both `web` and `docs` applications
- `@repo/eslint-config`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `@repo/typescript-config`: `tsconfig.json`s used throughout the monorepo
