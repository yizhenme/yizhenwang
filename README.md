## 💻 Running Locally

Install dependencies:

```bash
pnpm install
```

Run the development server:

```bash
pnpm run dev
```

## 📄 Adding a post

Adding a post is as simple as adding a .md or .mdx file to the blog folder at the path **src/content/posts**.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                       |
| :--------------------- | :------------------------------------------- |
| `pnpm install`         | Installs dependencies                        |
| `pnpm run dev`         | Starts local dev server at `localhost:4321`  |
| `pnpm run build`       | Build your production site to `./dist/`      |
| `pnpm run preview`     | Preview your build locally, before deploying |
| `pnpm run format`      | Code formatter using prettier                |
| `npx @astrojs/upgrade` | To upgrade                                   |
