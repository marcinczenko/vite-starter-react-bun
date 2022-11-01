# vite-starter-react-bun

Starter for [vitejs](https://vitejs.dev) with React and:

- [tailwindcss](https://tailwindcss.com),
- [React Router](https://reactrouter.com),
- hosted fonts,
- eslint,
- typescript,
- [vitest](https://vitest.dev)

This project uses [bun](https://bun.sh) as dependency manager. It means there is no yarn, no npm stuff here.

## Quick start:

```bash
bun install
bun run lint
bun run test # watch mode
bun run test:cov # one shot with coverage
bun run dev # development server
bun run build # production
bun run preview # preview production
```
## Using with yarn

If you want to switch to yarn, everything is already setup to use yarn in compatibility mode, i.e. not using Zero-Installs but rather regular _node_modules_. To smoothly switch to yarn, run:

```bash
rm -rf node_modules # just in case when you used bun previously
yarn install
yarn dev
# ...
```

Switching to yarn can be handy if, for instance you want to use `yarn upgrade-interactive` to update dependencies. This currently cannot be (easily?) achieved with bun...

When switching back to bun, just do:

```bash
rm -rf node_modules # just in case when you used bun previously
bun install
bun run dev
# ...
```
