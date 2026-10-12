# leafchat（リーフチャット）

[leafchat](https://leafchat.app) は、サイトに設置する AI サポートチャットです。登録したマニュアルや FAQ をもとに AI が訪問者の質問に答え、答えられなかった質問は担当者が会話を引き継ぎます。Claude や ChatGPT から MCP で接続すると、未回答の質問と担当者の返信をもとに、資料の修正案を作れます。

## 公開しているもの

- [cli](https://github.com/leafchat/cli)：フォルダの資料を leafchat のナレッジに同期する CLI（npm の [`@leafchat/cli`](https://www.npmjs.com/package/@leafchat/cli)）と GitHub Action（Marketplace の [leafchat knowledge sync](https://github.com/marketplace/actions/leafchat-knowledge-sync)）。pull request に同期の計画をコメントし、`main` への push で反映します

## 開発者向けの資料

- [API の仕様書](https://api.leafchat.app/api/v1/docs)（[Markdown](https://api.leafchat.app/api/v1/docs.md)・[OpenAPI](https://api.leafchat.app/api/v1/openapi.json)）
- [MCP サーバーの案内](https://api.leafchat.app/mcp.md)。公式 MCP Registry に `app.leafchat/leafchat` として載せています

## 問い合わせ

- 製品について：[相談ページ](https://leafchat.app/contact)
- CLI の不具合：[leafchat/cli の Issues](https://github.com/leafchat/cli/issues)
- 脆弱性：公開の Issue には書かず、各リポジトリの「Security」タブの「Report a vulnerability」から知らせてください
