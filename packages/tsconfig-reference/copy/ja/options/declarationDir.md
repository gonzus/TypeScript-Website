---
display: "Declaration Dir"
oneline: "Set the root directory for d.ts files to go"
---

型定義ファイルが出力されるルートディレクトリを設定します。

```
example
├── index.ts
├── package.json
└── tsconfig.json
```

次の`tsconfig.json`は:

```json
{
  "compilerOptions": {
    "declaration": true,
    "declarationDir": "./types"
  }
}
```

`index.ts`に対応するd.tsファイルを`types`フォルダへ配置します:

```
example
├── index.js
├── index.ts
├── package.json
├── tsconfig.json
└── types
    └── index.d.ts
```
