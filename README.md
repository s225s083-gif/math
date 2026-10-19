# ばねばかり実験シミュレーター

ブラウザ上で、おもりとばねの伸びの関係を体験できるシミュレーターです。

## 公開方法（GitHub Pages）

1. GitHubで新しいリポジトリを作成します。
2. このフォルダ内の `index.html` と `README.md` をリポジトリの一番上（ルート）にアップロードします。
3. リポジトリの **Settings → Pages** を開きます。
4. **Build and deployment** の **Source** で `Deploy from a branch` を選択します。
5. Branchを `main`、フォルダを `/(root)` にして **Save** を押します。
6. 数分待つと、GitHub Pagesの公開URLが表示されます。

## 機能

- 1g・7g・10g・1tのおもりをドラッグ＆ドロップ
- ばねが伸び縮みするアニメーション
- 目盛りと伸びの連動（最大140cmの目盛り）
- 「やわらかい」「かたい」の切り替え
- 初期状態は「かたい」
- 1tをドラッグしたときの警告表示

## 設定

`index.html` のJavaScriptにある `stiffness='hard'` が、初期状態を「かたい」にする設定です。
