# 隠れキッチン 提案用デモ

## 参考サイト（2026-09-29調査、文章・写真・ロゴの転用なし）
- https://www.kantenpp.co.jp/garden/himawari — 冒頭に店名・写真。紹介→おすすめ→貸切→団体→店舗情報の5ブロック。団体予約・アクセスが主導線。白地、茶・緑、読みやすい文字と広い余白。料理と営業時間の整理を採用し、本案では道順を冒頭にも追加。
- https://youshokuno-otogiya.com/ — 冒頭に店内写真・店名・予約。紹介→メニュー→こだわり→お知らせ→猫の間→店舗情報→予約→Instagramの8ブロック。予約が最優先。白と木の茶色、柔らかな文字、ゆったりした余白。予約・駐車場・支払いの見つけやすさを採用し、本案は電話と地図を固定表示。
- https://merci-waiwai.com/ — 冒頭に料理写真・店名・電話・営業時間。お知らせ／SNS→こだわり→料理→メニュー→店舗情報・地図の5ブロック。電話とメニューが主導線。濃茶・赤・白、太い見出し、情報量の多い構成。セットとメインの分離を採用し、本案は淡色で項目を絞り読みやすくした。
- 必須情報をランチの内容・価格・量・予約、営業時間・定休日、道順・駐車場、個室・子連れ対応と整理。地域参考のひまわり亭は住宅街の一軒家と完全一致しないため、他2店で一軒家の文法を補った。評判はRetty／食べログ等の検索結果を補助参照し、順位や点数は掲載しない。

## 素材
Pexelsの無料素材を取得しローカル同梱。すべてイメージ写真表記あり。実店舗・実料理の写真ではない。
- eggs.jpg: ID 6944030 / Vlada Karpovich / https://www.pexels.com/photo/a-close-up-shot-of-a-bowl-of-eggs-and-kitchen-utensils-6944030/
- vegetables.jpg: ID 5033529 / Luis Kuthe / https://www.pexels.com/photo/red-tomato-beside-green-vegetable-on-brown-wooden-table-5033529/
- tea.jpg: ID 8634224 / aysenurhamra / https://www.pexels.com/photo/a-cup-of-tea-on-the-table-8634224/
取得URLは https://images.pexels.com/photos/<ID>/pexels-photo-<ID>.jpeg?auto=compress&cs=tinysrgb&w=1200 。200KBを超える2枚はJPEGを再圧縮。

## 内容と実装
- 店名・住所・電話・営業時間は依頼情報を使用。口コミの傾向は紹介文として明示し、具体的な内容・料金は要確認を併記。
- 番地と営業日の食い違い、ソース・量・個室・予約・駐車場・支払いを要確認表示。
- noindex、viewport-fit=cover、safe-area対応固定バー。telリンクは指定番号で外部リンク記号なし。Googleマップは指定URLを保持。
- HTML/CSSのみ。フォームや不要なJavaScriptは追加せず、電話での問い合わせに一本化。
- Google Fonts・地図埋め込みはオンライン接続を利用。写真は相対パスで同梱。地図が読み込めない場合にも外部マップリンクを表示。
- ユーザー指定に従いGitHub Pagesを使用（AGENTS.mdのデフォルトCloudflareより優先）。

## 公開・検証メモ
375pxで横はみ出しなし、固定ボタン高さ48px、電話リンク・全写真のキャプション・番地の要確認表記を確認。Pexels素材はすべて200KB以内（紅茶は800px幅に縮小）。GitHub非公開リポジトリではプラン制限でPages設定が拒否され、公開設定への変更はユーザー承認待ち。
