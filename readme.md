##ファイル構造
├── foundation Reset.cssなど土台となるCSS群
│   ├── _base.scss 色、文字の大きさ、書体、レスポンシブ
│   └── _reset.scss ブラウザの設定を解除
├── layout
│   ├── _footer.scss フッターエリアのmargin、paddingの設定
│   ├── _header.scss ヘッダーエリアのmargin、paddingの設定
│   ├── _main.scss メインエリアのmargin、paddingの設定
└── object 再利用できる小さなコンポーネントCSS群
    ├── _btn.scss ボタン
    ├── _heading.scss 見出し
    ├── _card.scss カード
    ├── _gallery.scss 画像
    ├── _margin.scss 余白
    ├── _position.scss
    └── _size.scss
