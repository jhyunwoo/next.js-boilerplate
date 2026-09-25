# Next.js Boilerplate

## Features
- Next.js 14
- TypeScript
- Drizzle ORM
- Auth.js (Beta)
- Prettier
- PostgreSQL
- TailwindCSS
- Yarn PnP

## Command Line Interface
### Development
```bash
yarn dev
```

### Build
```bash
yarn build
```

### Start
```bash
yarn start
```

### Lint
```bash
yarn lint
```

### DB Push
```bash
yarn db:push
```

### DB Studio
```bash
yarn db:studio
```

## Project context and engineering approach

This boilerplate packages the recurring parts of a TypeScript web application into a maintainable starting point. It is intended for projects that require authentication and a SQL data model from the beginning rather than adding them ad hoc later.

Next.js, Auth.js, Drizzle ORM, PostgreSQL, Tailwind CSS, Prettier, and Yarn Plug'n'Play work together as the baseline. Database scripts keep generated migrations and local inspection explicit, which reduces setup drift between projects.

## Status

Reusable reference template rather than a separately deployed product.
