# practice-gh-action-ci
GitHub ActionでPR時のCIアクションを実行する

### できること

- 別のPRがある場合はエラー
- baseブランチの変更を取り込む
- CI（ビルド、テスト）
- テストレポートの公開
- CIステータスをPRにコメント

### コマンド

```shell
# パッケージをインストール
yarn

# index.tsを実行
yarn run start

# テストを実行
yarn run test

# tsファイルをビルド
yarn run build
```
