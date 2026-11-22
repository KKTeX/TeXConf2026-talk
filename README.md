# リアルタイム TeX プレビュー

TeXConf 2026（2026年11月21日）での KKTeX の発表資料です。

打鍵の瞬間に該当ページだけが変わるリアルタイムプレビューを、TeX の組版が「どこまで局所的で、どこから非局所的か」という切り分けから設計した話です。前半で箱とグルー、行分割、ページビルダ、出力ルーチンを追い、後半でエンジンの設計（行は TeX に組ませ、ページは自前のページビルダで組み直す）を説明しました。

## TeX64

この発表で扱ったリアルタイムプレビューは、[TeX64](https://tex64.com/ja)（AI 搭載の LaTeX 専用エディター）の機能です。

- [実演動画](tex64-realtime-preview-demo.mp4)（86 秒。速さには手を加えていません）

## 内容

- [realtime-tex-preview.pdf](realtime-tex-preview.pdf) — スライド（PDF、65 枚）
- [realtime-tex-preview.pptx](realtime-tex-preview.pptx) — スライド（PowerPoint）。アニメーション・画面切り替え・スピーカーノートは外してあります
- [abstract.md](abstract.md) — 発表要旨

## 発表者

KKTeX（X: [@KKTeX_LaTeX3](https://x.com/KKTeX_LaTeX3)）
