# GitHub Pages 公開手順

## 1. リポジトリ作成

GitHubで新規リポジトリを作ります。

おすすめ名：

```text
shihou-yobi-ronbun-mobile-reader
```

## 2. ファイルをアップロード

このフォルダの中身を、リポジトリ直下にそのまま置きます。

必須：

```text
index.html
README.md
.nojekyll
assets/
```

## 3. Pages設定

リポジトリで以下を開きます。

```text
Settings → Pages
```

設定：

```text
Source: Deploy from a branch
Branch: main
Folder: /root
```

Save後、数十秒〜数分でURLが発行されます。

## 4. スマホ確認チェック

- トップ画面が出る
- 学習インデックスのジャンプが動く
- 科目ページへ移動できる
- カードを開閉できる
- 条文引用が表示される
- 条文候補・漏れチェックタグが開ける
- 横断検索が動く
- 最終QAが見られる

## 5. 更新方法

最新版HTMLを作ったら、`index.html` を差し替えてコミットします。  
GitHub Pagesは自動で更新されます。


## アイコンについて
- favicon は `assets/icons/favicon.ico` を参照します。
- iPhone のホーム画面追加では `assets/icons/icon-180.png` が使われます。
- `manifest.webmanifest` を同梱しているので、そのまま GitHub Pages に公開できます。
