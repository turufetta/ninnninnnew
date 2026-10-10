# つるふぇったの忍者修行

ブラウザで遊べる忍者パズルゲーム。made by turufetta

## 遊び方

公開URLを開くだけでプレイできます（インストール不要）。

## GitHub Pages での公開手順

1. このリポジトリの **Settings → Pages**
2. **Source** を **Deploy from a branch** にする
3. Branch を `main`（または `master`）、folder を `/ (root)` にする
4. Save する

数分後に `https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます。

### うまく表示されないとき

- リポジトリに **`.nojekyll`** があること（Jekyll 無効化用）
- エントリが **`index.html`** であること
- リポジトリが **Public** であること（無料の Pages の場合）
- 反映まで 1〜3 分かかることがあります

## ファイル

| ファイル | 説明 |
|---------|------|
| `index.html` | ゲーム本体（画像・音声埋め込みの単一ファイル） |
| `.nojekyll` | GitHub Pages で Jekyll を使わないための指定 |
