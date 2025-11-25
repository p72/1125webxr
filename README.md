# WebXR オセロ - Quest2対応

WebXR対応の3Dオセロゲームです。Quest2などのVRヘッドセットで遊べます！

## 🎮 遊び方

### Quest2でのアクセス方法

1. Quest2のブラウザを開く
2. GitHub PagesのURLにアクセス：
   ```
   https://[username].github.io/[repo-name]/
   ```
3. 「Enter VR Mode」ボタンをクリックしてVRモードに入る
4. ゲームを開始！

### ゲームモード

- **VS COM**: コンピューターと対戦（難易度：Easy / Normal / Hard）
- **VS Player**: 2人対戦モード
- **VR Mode**: Quest2などのVRヘッドセットで没入体験
- **AR Mode**: AR対応デバイスで拡張現実体験

## 🚀 GitHub Pagesへのデプロイ

### 1. GitHubリポジトリにプッシュ

```bash
git init
git add .
git commit -m "Initial commit: WebXR Othello game"
git branch -M main
git remote add origin https://github.com/[username]/[repo-name].git
git push -u origin main
```

### 2. GitHub Pagesの設定

1. GitHubリポジトリのページを開く
2. **Settings** > **Pages** に移動
3. **Source** でブランチを選択（通常は `main`）
4. **Save** をクリック

数分待つと、`https://[username].github.io/[repo-name]/` でアクセス可能になります。

## 📝 注意事項

- WebXR APIはHTTPS環境でのみ動作します
- GitHub Pagesは自動でHTTPS証明書を提供するため、追加設定は不要です
- Quest2のブラウザからHTTPSのURLにアクセスする必要があります

## 🛠️ 技術スタック

- Three.js (WebGL 3Dレンダリング)
- WebXR API (VR/AR対応)
- 純粋なHTML/CSS/JavaScript（ビルド不要）

## 📄 ライセンス

このプロジェクトは自由に使用・改変できます。

