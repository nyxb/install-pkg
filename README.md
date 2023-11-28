# install-pkg

[![NPM version](https://img.shields.io/npm/v/@nyxb/install-pkg?color=a1b858&label=)](https://www.npmjs.com/package/@nyxb/install-pkg)

Install package programmatically. Detect package managers automatically (`npm`, `yarn`, `bun` and `pnpm`).

```bash
npm i @nyxb/install-pkg
```

```ts
import { installPackage } from '@nyxb/install-pkg'

await installPackage('vite', { silent: true })
```

## Sponsors

<p align="center">
  <a href="https://cdn.jsdelivr.net/gh/nyxb/static/sponsors.svg">
    <img src='https://cdn.jsdelivr.net/gh/nyxb/static/sponsors.svg'/>
  </a>
</p>

## License

[MIT](./LICENSE) License © 2021 [Anthony Fu](https://github.com/nyxb)
