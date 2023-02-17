# リリース用GitHub Actionsサンプルリポジトリ

### Repository Settings

Settings -> Actions -> General 

**Workflow permissions**
- Selected `Read and Write permissions`
- Checked `Allow GitHub Actions to create and approve pull requests`

### Usage

1. 開発用ブランチで開発を行い
2. `staging`ブランチへPRを作成し、レビュー後マージを行う
3. `production`ブランチへ自動的に、PRが作成される
4. `production`ブランチマージ前に、`staging`ブランチへマージすると、[4.]にて作成されたPRに自動的に項目が追加される
