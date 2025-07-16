# CLAUDE.md

This file serves as a common guide for working with the claude code (claude.ai/code).

## Conversation Method
- 会話は日本語で行うこと

## Web Search
Use gemini CLI instead of built-in WebSearch tool:
```
bash gemini --prompt "WebSearch: <query>"
```
Always use this command for web searches.
実装中に解決できないことがあれば、まずはこのコマンドを使って情報を検索すること。

## コード内のログやコメントについて
- ログやコメントは日本語で記述すること

## ユーザー指定のタスクリストについて
- ユーザーが指定したmarkdownのタスクリストを実行する場合、完了したタスクにチェックを付けること
