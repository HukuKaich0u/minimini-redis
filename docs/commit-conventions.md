# Commit Conventions

Format:

```text
<type>: <日本語の説明>
```

例:

```text
docs: 日本語READMEを分離
build: tokioとmini-redis依存を追加
chore: Cargoプロジェクトを初期化
```

使う可能性のある type:

- `feat`: 機能追加、仕様追加
- `fix`: バグ修正、不正挙動の修正
- `docs`: README、設計メモ、各種ドキュメント
- `refactor`: 挙動を変えない整理
- `test`: テスト追加、修正、整理
- `build`: 依存関係、`Cargo.toml`、ビルド設定
- `chore`: 雑多な保守作業
- `ci`: CI、ワークフロー
- `perf`: パフォーマンス改善
- `style`: フォーマット、空白、見た目だけの調整
- `revert`: 変更の取り消し

機能を消す時:

- バグ修正のために消すなら `fix`
- 内部整理で消すなら `refactor`
- 仕様変更として消すなら `feat`
- 設定や依存の都合で消すなら `build` か `chore`

このリポジトリでは、type は英語、`:` の後ろは日本語で書く。
