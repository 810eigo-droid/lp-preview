# RE:BIRTH デザイン確認用

最新版7セクション原稿に対応。写真は仮枠。予約先は公式LINEの暫定リンクです。

images/ に以下のWebP画像を追加すると枠を自動置換します。hero.webp（頬・フェイスライン）、concerns.webp（女性の表情）、neck.webp（首）、decollete.webp（デコルテ）、treatment.webp（セミオーダー施術）、hands.webp（手の密着感）、owner.webp（オーナー）、offer.webp（初回体験）。画像なしでも枠を表示します。

WordPress用HTMLは非公開taf-clientの clients/rebirth/delivery/wordpress-block.html。CSSは #rebirth-lp 内に限定。画像URLはWordPressのメディアURLに変更して使用。テーマ・権限によるHTML属性の削除有無は実環境で確認が必要です。

## V1保存とセクション画像

変更前のページは `v1/index.html`、画像は `v1/images/` に固定保存。現行は画像 section01.png / section02.png を使用。FVボタンは画像上のリンク領域。復元する場合は v1/index.html を index.html に、v1/images の画像を images にコピーする。動画は外部WordPress URLのため、元動画が変更されればV1の動画も変わる。

## B案ファーストビュー（2026-11）

B案（`b/index.html`）のFVは `hero-b-headline.png`（見出し）と `hero-b-ribbon.png`（奈良・学園前リボン）を使用。どちらも `hero-b-latest.png` からの切り出し。「たるみ改善フェイシャル体験」・料金・予約ボタンはHTML文字。

## B案 動画セクション（2026-11）

01〜03の3動画と説明文を削除し、縦長動画1本＋短い説明文の `rb-b-movie` に統合。新動画が届くまで仮で video2.mp4（フェイシャル）と `movie-poster-temp.jpg`（同動画から切り出した仮の表紙）を使用。届いたら `source` のURLと `poster` を差し替える。
