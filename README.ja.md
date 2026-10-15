# @fringeworks/constants

`@fringeworks/constants` は型付けされた共通の定数を提供する、誰かにとっては便利なライブラリです。

**[English README is available here](./README.md)**

> [!WARNING]
> このパッケージはメンテナンスを終了しました。0.9.0 が最後のバージョンです。\
> 定数は [`@fringeworks/types`](https://www.npmjs.com/package/@fringeworks/types) に移りました。

## 移行方法

| `@fringeworks/constants` | 移行先                                   |
| ------------------------ | ---------------------------------------- |
| `ToStringResult`         | `@fringeworks/types` の `ToStringResult` |
| `TypeOfResult`           | `@fringeworks/types` の `TypeOfResult`   |
| `SYMBOL_UNDEFINED`       | なし（削除）。独自のシンボルを定義する   |
| `SYMBOL_NULL`            | なし（削除）。独自のシンボルを定義する   |
| `SYMBOL_EMPTY`           | なし（削除）。独自のシンボルを定義する   |

```sh
npm uninstall @fringeworks/constants
npm install @fringeworks/types
```

```ts
// 移行前
import { ToStringResult, TypeOfResult } from '@fringeworks/constants';

// 移行後
import { ToStringResult, TypeOfResult } from '@fringeworks/types';
```

## ライセンス

MIT
