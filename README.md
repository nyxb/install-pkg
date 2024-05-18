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

## License

[MIT](./LICENSE) License © 2021 [Dennis Ollhoff](https://github.com/nyxb)
