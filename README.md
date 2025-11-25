# WebXR オセロ - Quest2対応

WebXR対応の3Dオセロゲームです。Quest2などのVRヘッドセットで遊べます！

## 🎮 遊び方

### Quest2でのアクセス方法

1. Quest2のブラウザを開く
2. GitHub PagesのURLにアクセス：
   ```
   https://p72.github.io/1125webxr/
   ```
3. 「Enter VR Mode」ボタンをクリックしてVRモードに入る
4. ゲームを開始！

**注意**: GitHub Pagesが有効化されている必要があります（下記の設定手順を参照）

### ゲームモード

- **VS COM**: コンピューターと対戦（難易度：Easy / Normal / Hard）
- **VS Player**: 2人対戦モード
- **VR Mode**: Quest2などのVRヘッドセットで没入体験
- **AR Mode**: AR対応デバイスで拡張現実体験

## 🚀 GitHub Pagesへのデプロイ

### 現在のリポジトリ

- リポジトリ: `https://github.com/p72/1125webxr`
- GitHub Pages URL: `https://p72.github.io/1125webxr/`

### GitHub Pagesの設定手順

1. GitHubリポジトリのページを開く: `https://github.com/p72/1125webxr`
2. 上部の **Settings** タブをクリック
3. 左メニューの **Pages** をクリック
4. **Source** セクションで：
   - 「Deploy from a branch」を選択
   - **Branch** で `main` を選択
   - **Folder** は `/ (root)` のまま
5. **Save** をクリック

数分待つと、`https://p72.github.io/1125webxr/` でアクセス可能になります。

### 初回セットアップ（既に完了済み）

```bash
git init
git add .
git commit -m "Setup GitHub Pages for Quest2 deployment"
git branch -M main
git remote add origin https://github.com/p72/1125webxr.git
git push -u origin main
```

## 📝 注意事項

- WebXR APIはHTTPS環境でのみ動作します
- GitHub Pagesは自動でHTTPS証明書を提供するため、追加設定は不要です
- Quest2のブラウザからHTTPSのURLにアクセスする必要があります
- GitHub Pagesの設定後、サイトが公開されるまで数分かかる場合があります
- 初回デプロイ時は最大10分程度かかることもあります

## 🛠️ 技術スタック

- Three.js (WebGL 3Dレンダリング)
- WebXR API (VR/AR対応)
- 純粋なHTML/CSS/JavaScript（ビルド不要）

## 📄 ライセンス

このプロジェクトは自由に使用・改変できます。

