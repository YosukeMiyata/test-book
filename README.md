# Test-Book

## Workspaces

```
packages
   |__ book
   |__ contracts
   |__ interface
```

### book

- test-book 中身

### contracts

- test-book 配布用のコントラクト (アクセス権を NFT 化する、など)

### interface

- test-book 購入ページ

## コマンド

ローカルで test-book の起動

```bash
npm run book:serve
```

その他各 workspace 配下`package.json`　を確認しながら以下で適宜コマンド実行

```
npm run [workspace_command] -w packages/[workspace_name]
```