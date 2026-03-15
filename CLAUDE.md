# toy-admiral-test

E2E テスト用のトイプロジェクト。vibe-admiral の統合テストに使用。

## 技術スタック

- TypeScript (Node.js)

## ディレクトリ構成

```
src/
  index.ts    メイン
```

## コマンド

| Purpose | Command |
|---------|---------|
| Type check | npx tsc --noEmit |

## 実装レイヤー順序

1. src/ (ソースコード)

## 競合リスクエリア

- src/index.ts (共有エントリポイント)
