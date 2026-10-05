# SwapSpot earlier repository

A separate repository for the student accommodation exchange prototype.
It uses React with TypeScript and Vite.
Supabase provides the application connection.

See [`swapspot`](https://github.com/danielpuri1901/swapspot) for the other repository.
The relationship between the two code versions needs review before either is treated as the canonical application.
The repository name alone does not establish which version is complete.

User counts and other numbers in the interface are not verified product results.

## Local development

```bash
npm install
npm run dev
```

Supabase-backed features require the relevant application configuration.
Use a project you control for tests that change stored data.

## Checks

```bash
npm run lint
npm run build
```

See [`package.json`](package.json) for scripts and dependencies.
