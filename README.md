# VAD-Menlo-Team1

VAD Project - Menlo Team 1

## ブランチ戦略

- `main` — 本番ブランチ（直接pushは禁止、PRのみ）
- `feature/<issue番号>-<概要>` — 機能開発ブランチ（例: `feature/1-add-login`）
- `fix/<issue番号>-<概要>` — バグ修正ブランチ（例: `fix/2-fix-crash`）

## 開発フロー

1. Issueを作成してチケットを立てる
2. ブランチを切る: `git checkout -b feature/<issue番号>-<概要>`
3. 実装してコミット
4. PRを作成（mainへ）
5. レビュー → マージ
