# このリポジトリについて

Redmine の開発に利用するためのリポジトリです。

## CI の実行

- push すると **テスト** と **Linter** が自動で実行されます。

## master ブランチについて

- `master` ブランチは、[redmine/redmine](https://github.com/redmine/redmine) の `master` ブランチと（一部ファイルを除いて）同期しています。
- 同期は GitHub Actions ワークフローにより、**月〜金 JST 08:00** に自動実行されます。
- 必要に応じて、手動でワークフローを実行することも可能です。
- ⚠️ **`master` ブランチには直接変更を加えないでください。**
