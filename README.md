# anywhen

> [!IMPORTANT]
> **This repository has moved.** `anywhen` now lives in the
> [**anyfamily**](https://github.com/kirilinsky/anyfamily) monorepo alongside the
> rest of the `any*` family. This copy is archived and frozen at v1 — anything
> below is kept for history only.

Dates and times into localized strings and relative phrasing. Built on native Intl, no data files.

|  |  |
| --- | --- |
| **Source** | [kirilinsky/anyfamily → packages/anywhen](https://github.com/kirilinsky/anyfamily/tree/main/packages/anywhen) |
| **Docs** | [anyfamily.site/docs/anywhen](https://anyfamily.site/docs/anywhen) |
| **Demo** | [anyfamily.site/anywhen](https://anyfamily.site/anywhen) |
| **npm** | [npmjs.com/package/anywhen](https://www.npmjs.com/package/anywhen) |

The package is still published and maintained — only the repository moved.
`npm install anywhen` works exactly as before.

## v2 changed the API

Every `any*` package now exports **exactly one name**, with the extras hanging
off it:

```diff
- anywhenParts(date)
+ anywhen.parts(date)
```

Full notes: [migrating to v2](https://anyfamily.site/docs/anywhen#migrating).

## the rest of the family

Eight micro, zero-dependency Intl tools — one function each, zero data files,
200+ locales via native `Intl`. `anywhen` · `anyamount` · `anymany` ·
`anyaround` · `anylong` · `anyplural` · `anyword` · `anylocale`, or all eight
at once via [`anyfamily`](https://www.npmjs.com/package/anyfamily).

**[anyfamily.site](https://anyfamily.site)** · ⭐ [star the monorepo](https://github.com/kirilinsky/anyfamily)

MIT © [kirilinsky](https://github.com/kirilinsky)
