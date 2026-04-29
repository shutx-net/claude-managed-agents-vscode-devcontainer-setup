# Claude Managed Agents 開発環境ベース（TypeScript SDK）

[Claude Managed Agents](https://platform.claude.com/docs/ja/managed-agents/overview) を使って自律型エージェントを開発するためのローカル環境のベースです。

SDKはTypeScriptです。

### コアコンセプト

| 概念 | 説明 |
|------|------|
| **Agent** | モデル、システムプロンプト、ツール、MCP サーバーの定義 |
| **Environment** | パッケージやネットワークアクセスを設定したコンテナテンプレート |
| **Session** | 特定タスクを実行するエージェントの実行インスタンス |
| **Events** | アプリケーションとエージェント間でやりとりするメッセージ |

## セットアップ

```bash
npm install
```

`ANTHROPIC_API_KEY` 環境変数に API キーを設定してください。

```bash
export ANTHROPIC_API_KEY=sk-ant-...
```


## 技術スタック

- **Runtime**: Node.js (TypeScript / tsx)
- **SDK**: `@anthropic-ai/sdk` v0.91+

## 参考ドキュメント

- [Managed Agents 概要](https://platform.claude.com/docs/ja/managed-agents/overview)
- [クイックスタート](https://platform.claude.com/docs/ja/managed-agents/quickstart)
- [API リファレンス](https://platform.claude.com/docs/ja/managed-agents/sessions)
- [対応ツール一覧](https://platform.claude.com/docs/ja/managed-agents/tools)
