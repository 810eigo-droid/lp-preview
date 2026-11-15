# RE:BIRTH LP 引き継ぎメモ（2026-11-15時点）

## ページ一覧（すべて GitHub Pages で公開中・noindex）

| ページ | URL | ファイル | 状態 |
|---|---|---|---|
| A案 | https://810eigo-droid.github.io/lp-preview/rebirth/ | `rebirth/index.html` | 変更なし（触らない） |
| B案（ピンク基調） | https://810eigo-droid.github.io/lp-preview/rebirth/b/ | `rebirth/b/index.html` | 11/12の修正依頼書（PDF）の文章・構成を反映済み |
| 色合い見本 | https://810eigo-droid.github.io/lp-preview/rebirth/gold/ | `rebirth/gold/index.html` | 赤・黒・ゴールドの冒頭のみ |
| C案（文章確認用） | https://810eigo-droid.github.io/lp-preview/rebirth/c/ | `rebirth/c/index.html` | 11/15の制作指示書の文章を組んだもの。現在の本線 |
| 動画表紙の候補 | https://810eigo-droid.github.io/lp-preview/rebirth/c/thumb-candidates.jpg | 同左 | ①〜④新動画、⑤⑥旧フェイシャル動画 |

## 現在の進め方

1. C案で文章を確定してもらう（「この内容で確定」の返事をもらう）
2. 確定後に、文字入り画像・イラストを ChatGPT で作成（プロンプトはその時点で用意）
3. 写真・画像を C案に入れて仕上げ、WordPress用HTMLに反映

## クライアントの返事待ち

- C案の文章確定
- メニュー名（仮：「たるみ悩み特化フェイシャル」／もう1案「たるみ悩み集中フェイシャル」）
- ③見出し「顔だけケアしても、フェイスラインは変わりにくい」のままでよいか
- 口コミ2件目（ハーブ＝別メニューの感想。差し替えを推奨中）
- 冒頭に「マーメイドセル」の名前を出すか（仮で小さく表示中）
- 予約カレンダーのURL（現在のボタンは https://page.line.me/954miweg ）
- 動画の見せ方：A 縦型・無音自動再生（C案の現状）／B 横長の表紙＋再生ボタン
- 動画表紙の番号（Bの場合）

## クライアントが決めた・触れないことにした点

- リアボーテの文言は原稿どおり「サロン業界をけん引する ヒト幹細胞培養液配合化粧品ブランド リアボーテ」
- 口コミの年代表記、駐車場台数・住所は確認しない（アクセスは指示書どおりの表記）
- 使用色：鮮やかな赤・ゴールド・白・黒（くすみ色なし）
- 予約ボタンは4か所＋固定ボタン、文言は「空き状況を見て予約する」で統一
- ビフォーアフター写真は使わない（Meta広告から誘導するため）

## C案で未着手のもの（破線の枠＝差し替え位置）

- 冒頭の施術写真（現在は既存の hero.webp を仮置き）
- お悩み4つのイラスト、顔・首・肩・デコルテのつながりの図
- 3つのこだわりの写真3枚、当日の流れの写真4枚
- 黄色い確認メモ3か所（公開前に削除する）

## 素材

- 動画（WordPressメディア）：https://rebirth-beauty-sakurai.com/wp-content/uploads/2026/11/re_birth-lp.mp4 （縦1080×1920・約33秒・60MB）
  - 旧動画：同フォルダの video1.mp4（デコルテ0〜30秒／首30秒〜）、video2.mp4（フェイシャル）
- `images/movie-loop.mp4`：上記を無音・540×960・1.7MBに圧縮した自動再生用（C案で使用）
- `images/movie-poster.jpg`：動画から切り出した表紙（B案・C案）
- `images/logo-gold.png`：支給ロゴ（白背景スクリーンショット）から切り抜いたRE:BIRTHロゴ。拡大すると粗い
- `images/rela-logo-white.png`：公式サイト relabeaute.com のロゴ（61×130）を6倍に拡大したもの
- `images/reaboute-products.jpg`：支給のリアボーテ商品写真
- `images/hero-b-headline.png` `hero-b-ribbon.png`：B案冒頭用に hero-b-latest.png から切り出し
- 非公開の素材・納品データ：https://github.com/810eigo-droid/taf-client/tree/main/clients/rebirth

## 未対応

- WordPress用HTML（taf-client の `clients/rebirth/delivery/wordpress-block-b.html`）は未更新。方向確定後に反映する
- 首・デコルテ・フェイシャルのサムネイル3枚（taf-client `delivery/thumbnail-review/`）はピンク系・文字入りのため、現方針では未使用
- 実機（スマホ）での動画自動再生・LINE遷移の確認

## 注意

- A案には手を加えない
- lp-preview は他案件（act-atkey など）も同じ main に push される。push 前に `git pull --rebase origin main`
