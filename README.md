# lp-preview

クライアント確認用のLPプレビュー置き場。push すると GitHub Actions が自動で GitHub Pages に公開する。

| プレビュー | URL |
|---|---|
| Good Pluck メンズアニソンD&Vプロジェクト オーディションLP（AIラフ忠実再現・画像はプレースホルダー） | https://810eigo-droid.github.io/lp-preview/goodpluck/ |
| 包丁人よしのり 宴会LP【v2・実データ版】(透かしなし) | https://810eigo-droid.github.io/lp-preview/yoshinori/ |
| 旧バージョン(v1・仮データ) | https://810eigo-droid.github.io/lp-preview/yoshinori/index-v1.html |
| v1サンプルA(全面ダーク・透かし入り) | https://810eigo-droid.github.io/lp-preview/yoshinori/index2-1.html |
| v1サンプルB(紺×白ミックス・透かし入り) | https://810eigo-droid.github.io/lp-preview/yoshinori/index3.html |

※ 各ページには `noindex` を入れてあり、検索エンジンには載らない。本公開時は本番サーバーへ移す。

## 画像ファイル名一覧 v2（包丁人よしのり・実写真）

`yoshinori/images/` に以下の名前(すべてWEBP)でアップロードすると自動で表示される。
旧 img01〜img14.webp は旧バージョン(index-v1.html / index2 / index3)用にそのまま残す。

| ファイル名 | 内容 | 実寸(受領済み) |
|---|---|---|
| photo00.webp | **FV背景(ぼかし店内・横長16:9)※未受領・AI生成予定** | 1600×900推奨 |
| photo01.webp | 店舗入口写真(FVで額装表示) | 正方形 |
| photo02.webp | 宴会風景写真(理由セクション+最終CTA背景に共用) | 1477×1108 |
| photo03.webp | コース写真(理由①・秋冬お鍋付き) | - |
| photo04.webp | 店内写真①(理由②貸切) | - |
| photo05.webp | ボトル写真(理由③) | 1403×1121 |
| photo06.webp | 人物写真(店舗紹介) | 1086×1448 縦 |
| photo07-1.webp / photo07-2.webp / photo07-3.webp | 店内写真②(店舗紹介・3枚) | 正方形 |
| photo08.webp | 春夏のコース写真 | 1086×1448 縦 |
| photo09.webp / photo10-1.webp / photo10-2.webp | 4,750円コース 3枚(スライドショー) | 縦 / - / - |
| photo11.webp / photo12.webp | 5,400円コース 2枚(スライドショー) | 正方形 / 縦 |
| photo13.webp / photo14.webp | 6,400円コース 2枚(スライドショー) | 正方形 / 縦 |
| photo15.webp | 人気料理: 刺身盛り合わせ | 1448×1086 |
| photo16.webp | 人気料理: 薩摩地鶏のタタキ | 正方形 |
| photo17.webp | 人気料理: 季節の天婦羅 | 正方形 |
| photo18.webp | 人気料理: お酒のボトル | - |
| photo19.webp | お客様の声: 40代男性・会社宴会(イラスト) | 正方形 |
| photo20.webp | お客様の声: 50代男性・接待(イラスト) | 正方形 |
| photo21.webp | お客様の声: 60代男性・日本酒好き(イラスト) | 正方形 |
| photo22.webp | お客様の声: 40代女性・歓送迎会(イラスト) | 正方形 |

計19枚。枠側を実寸の縦横比に合わせて調整済みのため、リサイズ不要でそのままアップロードしてよい。

## Good Pluck オーディションLP（goodpluck/）

`goodpluck/images/` に以下の名前で置くと自動で差し替わる（無い間はプレースホルダー表示）。

| ファイル名 | 内容 | 推奨 |
|---|---|---|
| logo.png | GPロゴ（背景透過） | 正方形・透過PNG |
| fv_visual.webp | FVの5人グループビジュアル（ラフの人物イラスト） | 縦長 約4:4.6（例 1000×1150） |
| project_city.webp | THE PROJECT用 東京タワー＋街並み | 横長 16:9 |
| producer.webp | PRODUCER用 スタジオ写真 | 横長 16:9 |
| qr.png | LINE公式アカウントQR（lin.ee/welphgP） | 正方形 |

- 応募導線はすべて `https://lin.ee/welphgP`（FV丸バッジ／ENTRYボタン／追従CTA／フッター）。
- PC表示では参考サイトと同様に右側480pxのスマホ幅カラム＋左側キャッチの構成。
- ラフの「THE PROCECT」は「THE PROJECT」に修正済み。
