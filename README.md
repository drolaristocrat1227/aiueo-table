# あいうえお表 音声アプリ

ひらがな・カタカナの五十音表をタップすると音声で読み上げる学習Webアプリです。

## 機能

- **五十音表**（清音・濁音・半濁音・拗音）をグリッド表示
- **ひらがな／カタカナ**をワンタップで切り替え
- **文字タップで音声読み上げ**（Web Speech API）
- **ローマ字表示**のON/OFF切り替え
- **レスポンシブ対応**（PC・スマートフォン）

## ローカルで開く方法

`index.html` をブラウザで直接開くだけで動作します。

1. `index.html` をダブルクリック
2. または、ブラウザのアドレスバーにファイルをドラッグ＆ドロップ

> **注意**: 音声読み上げには Chrome / Safari / Edge の最新版を推奨します。

## 公開方法

### GitHub Pages

1. GitHubにリポジトリを作成し、`index.html` をプッシュ
2. リポジトリの **Settings → Pages** を開く
3. Source を **Deploy from a branch** → **main** → **/ (root)** に設定して Save
4. 数分後に `https://<ユーザー名>.github.io/<リポジトリ名>/` でアクセス可能

### Netlify Drop

1. [https://app.netlify.com/drop](https://app.netlify.com/drop) を開く
2. `index.html` が入ったフォルダをドラッグ＆ドロップ
3. 自動的にURLが発行される

### Cloudflare Pages

1. Cloudflare ダッシュボードで **Pages → Create a project** を選択
2. GitHubリポジトリを接続、またはダイレクトアップロード
3. ビルド設定は不要（静的HTMLのため）
4. デプロイ後にURLが発行される
