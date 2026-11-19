# プロンプト工房

日本語のチップを選ぶだけで、AIイラスト生成用の英語プロンプトが組み上がるツールです。

## 使い方

- 公開ページ: https://asuberu1979.github.io/prompt-koubou/
- カテゴリから単語チップを選ぶと、選択順にプロンプトが組み上がります（↑↓で並び替え可能）
- 出力形式は Niji / Midjourney / Stable Diffusion / Bing / ハイブリッド の5種類に対応。全形式の比較表示もあります
- アスペクト比・スタイライズの調整、主題の自由入力、ランダム組み立て、カスタム単語の追加に対応
- 組み合わせはプリセットとしてブラウザ内に保存できます

## 単語のリクエスト

追加してほしい単語があれば、[リクエストフォーム](https://docs.google.com/forms/d/e/1FAIpQLSf31G_Kbil7fL29Y0RjelZ2FvtNC0A_wctwbEfO-BNSYq4VtA/viewform) からお気軽にどうぞ。ログイン不要で送れます。週1回の見回りで確認し、汎用的なものから順次追加します。
GitHubに慣れた方は [Issues](https://github.com/asuberu1979/prompt-koubou/issues) からでも構いません。

## 仕組み

- 語彙は `assets/words.json` の1ファイルで管理しています。このファイルを差し替えるだけで語彙の追加・修正が反映されます
- 処理はすべてブラウザ内で完結し、サーバーへの送信はありません
