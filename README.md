# @fringeworks/constants

`@fringeworks/constants` is a library some will find handy, providing well-typed shared constants.

**[日本語のREADMEはこちら](./README.ja.md)**

> [!WARNING]
> This package is no longer maintained. 0.9.0 is the final version.\
> Its constants have moved to [`@fringeworks/types`](https://www.npmjs.com/package/@fringeworks/types).

## Migration

| `@fringeworks/constants` | Replacement                                |
| ------------------------ | ------------------------------------------ |
| `ToStringResult`         | `ToStringResult` from `@fringeworks/types` |
| `TypeOfResult`           | `TypeOfResult` from `@fringeworks/types`   |
| `SYMBOL_UNDEFINED`       | None (removed). Define your own symbol     |
| `SYMBOL_NULL`            | None (removed). Define your own symbol     |
| `SYMBOL_EMPTY`           | None (removed). Define your own symbol     |

```sh
npm uninstall @fringeworks/constants
npm install @fringeworks/types
```

```ts
// Before
import { ToStringResult, TypeOfResult } from '@fringeworks/constants';

// After
import { ToStringResult, TypeOfResult } from '@fringeworks/types';
```

## License

MIT
