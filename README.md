# LiveCode Editor

## 🚀 概要

HTML、CSS、JavaScriptをリアルタイムで編集・実行できるブラウザベースのコードエディターです。CodeMirrorを搭載し、プロフェッショナルな開発環境を提供します。

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ 主な機能

### エディター機能
- **📝 3ペインエディター** - HTML、CSS、JavaScript用の独立したエディター
- **🎨 シンタックスハイライト** - CodeMirrorによるコード色分け
- **⚡ リアルタイムプレビュー** - 入力と同時に結果を表示
- **💾 自動保存** - LocalStorageによる作業内容の保存

### 開発支援機能
- **🔧 自動補完** - コード入力を支援
- **📐 コード折りたたみ** - 大規模コードの管理
- **🎯 括弧の自動閉じ** - 入力ミスを防止
- **📊 行番号表示** - コードの位置を把握

### プレビュー・デバッグ
- **👁️ ライブプレビュー** - iframeによる安全な実行環境
- **🖥️ コンソール出力** - console.logの結果を表示
- **🔄 手動リフレッシュ** - プレビューの再読み込み
- **🔗 新規タブで開く** - 独立ウィンドウでの確認

### その他の機能
- **📚 6種類のテンプレート** - すぐに始められるサンプルコード
- **💾 HTMLダウンロード** - 完成したコードをファイルとして保存
- **📐 レイアウト切り替え** - 横/縦配置の選択
- **🔲 フルスクリーン** - 集中できる作業環境
- **📏 ペインリサイズ** - エディターサイズの調整

## 🛠️ 使用技術

| カテゴリ | 技術 | 用途 |
|---------|------|------|
| **エディター** | CodeMirror 5.65 | コードエディティング |
| **シンタックス** | CodeMirror Modes | HTML/CSS/JS構文解析 |
| **アイコン** | Font Awesome 6 | UIアイコン |
| **フォント** | JetBrains Mono | コード用等幅フォント |
| **フォント** | Inter | UI用フォント |
| **プレビュー** | iframe srcdoc | 安全な実行環境 |
| **通信** | PostMessage API | コンソール出力キャプチャ |
| **ストレージ** | LocalStorage | データ永続化 |

## 🚀 デモ

[🔗 ライブデモはこちら](https://se0831.github.io/livecode-editor/)

## 📦 インストール & 使用方法

### オンライン版
1. 上記のデモリンクにアクセスするだけですぐに使用開始できます

### ローカル版
```bash
# リポジトリをクローン
git clone https://github.com/SE0831/livecode-editor.git

# ディレクトリに移動
cd livecode-editor

# ブラウザで開く（Macの場合）
open index.html

# ブラウザで開く（Windowsの場合）
start index.html

# またはローカルサーバーで実行
python -m http.server 8000
# http://localhost:8000 にアクセス
```

## 📝 使い方

### 1. コードの編集
- **HTML タブ**: HTML構造を記述
- **CSS タブ**: スタイルを定義
- **JavaScript タブ**: インタラクティブな機能を実装

### 2. プレビューの確認
- コードは自動的にプレビューに反映（500ms後）
- 「実行」ボタンで即座に更新
- コンソールタブでJavaScriptの出力を確認

### 3. テンプレートの活用
利用可能なテンプレート：
- **基本HTML** - シンプルなスターター
- **Bootstrap** - Bootstrap 5フレームワーク
- **Canvas** - アニメーション付きCanvas
- **フォーム** - お問い合わせフォーム
- **CSS Grid** - グリッドレイアウト
- **アニメーション** - CSSアニメーション

### 4. ファイルの保存
- 「ダウンロード」ボタンで完成したHTMLファイルを保存
- 作業内容は自動的にLocalStorageに保存

## ⌨️ キーボードショートカット

| ショートカット | 機能 |
|---------------|------|
| `Ctrl/Cmd + Space` | コード補完 |
| `Ctrl/Cmd + /` | コメントトグル |
| `Ctrl/Cmd + F` | 検索 |
| `Ctrl/Cmd + H` | 置換 |
| `Ctrl/Cmd + Z` | 元に戻す |
| `Ctrl/Cmd + Y` | やり直し |

## 🎨 カスタマイズ

### エディターテーマの変更
CodeMirrorのテーマを変更可能：
```javascript
// 現在: monokai
// 他のオプション: default, dracula, material, etc.
```

### レイアウトのカスタマイズ
CSSで簡単にレイアウトを調整：
```css
.editor-container {
    flex: 1; /* エディターの幅 */
}
.preview-container {
    flex: 1; /* プレビューの幅 */
}
```

## 📚 テンプレートの詳細

### 1. **基本HTML**
- レスポンシブデザイン
- グラデーション背景
- モダンなタイポグラフィ

### 2. **Bootstrap**
- Bootstrap 5 CDN
- ナビゲーションバー
- レスポンシブグリッド

### 3. **Canvas アニメーション**
- パーティクルシステム
- requestAnimationFrame
- インタラクティブな描画

### 4. **コンタクトフォーム**
- フォームバリデーション
- モダンなスタイリング
- JavaScriptイベント処理

### 5. **CSS Grid**
- レスポンシブレイアウト
- グリッドエリア定義
- メディアクエリ対応

### 6. **CSSアニメーション**
- キーフレームアニメーション
- トランジション効果
- ホバーエフェクト

## 🔒 セキュリティ

- **iframe sandbox** - 安全な実行環境
- **srcdoc属性** - XSS攻撃の防止
- **PostMessage API** - 安全なフレーム間通信
- **ローカル実行** - サーバーサイドの脆弱性なし

## 📂 プロジェクト構成

```
livecode-editor/
├── index.html      # アプリケーション本体（HTML/CSS/JS統合）
├── README.md       # このファイル
└── LICENSE         # MITライセンス
```

## 🔄 今後の機能追加予定

- [ ] **エディター機能拡張**
  - 複数ファイル対応
  - Emmet展開
  - マルチカーソル編集
  - コードフォーマッター（Prettier）
- [ ] **プリプロセッサ対応**
  - Sass/SCSS
  - TypeScript
  - JSX (React)
  - Vue SFC
- [ ] **共有・コラボレーション**
  - 共有URL生成
  - リアルタイムコラボレーション
  - Gist連携
- [ ] **開発者ツール**
  - エラーハイライト
  - パフォーマンス測定
  - コードリンター
- [ ] **UI/UX改善**
  - 追加のエディターテーマ
  - カスタマイズ可能なレイアウト
  - タブインターフェース
  - ショートカットカスタマイズ

## 🤝 コントリビューション

プルリクエストは大歓迎です！大きな変更の場合は、まずissueを開いて変更内容を議論してください。

1. このリポジトリをフォーク
2. フィーチャーブランチを作成 (`git checkout -b feature/AmazingFeature`)
3. 変更をコミット (`git commit -m 'Add some AmazingFeature'`)
4. ブランチにプッシュ (`git push origin feature/AmazingFeature`)
5. プルリクエストを作成

## 📄 ライセンス

このプロジェクトはMITライセンスの下で公開されています。詳細は[LICENSE](LICENSE)ファイルをご覧ください。

## 👤 作者

**SE0831**

- GitHub: [@SE0831](https://github.com/SE0831)
- ポートフォリオ: [その他のプロジェクト](https://github.com/SE0831?tab=repositories)

## 🙏 謝辞

- [CodeMirror](https://codemirror.net/) - 高機能エディターライブラリ
- [Font Awesome](https://fontawesome.com/) - アイコンセット
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) - プログラミング用フォント
- [Google Fonts](https://fonts.google.com/) - Webフォント

## 🔗 関連プロジェクト

他のポートフォリオ作品もご覧ください：

- [📝 MarkdownPro Editor](https://github.com/SE0831/markdown-editor-pro)
- [🍅 Focus Timer App](https://github.com/SE0831/focus-timer-app)
- [📊 Sales Analytics Dashboard](https://github.com/SE0831/sales-analytics-dashboard)
- [🌤️ Weather Dashboard](https://github.com/SE0831/weather-dashboard)
- [💰 Expense Tracker App](https://github.com/SE0831/expense-tracker-app)
- [📋 Task Management App](https://github.com/SE0831/task-management-app)

---

⭐ このプロジェクトが役に立ったら、スターをお願いします！

*最終更新: 2024年8月*
