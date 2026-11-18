# RE:BIRTH 画像LP プレビュー

C案修正版の確定原稿に基づく画像LP。写真は黄色みを加える前の素材を使用し、リアボーテは支給スクリーンショットのロゴを切り抜いて配置。下部のブランド名は黒文字。

1セクション1画像（幅1080px）。動画・予約ボタン・FAQ・アクセスはHTML。予約ボタンは4か所＋固定ボタン。

## 画像・動画ファイル

- `images/IMG_8528.webp`
- `images/bg-gold.jpg`
- `images/bg-rose.jpg`
- `images/bg-wave.jpg`
- `images/logo-rebirth-t.png`
- `images/movie-first.jpg`
- `images/movie-loop.mp4`
- `images/section-01.webp`
- `images/section-02.webp`
- `images/section-03.webp`
- `images/section-04.webp`
- `images/section-05.webp`
- `images/section-06.webp`
- `images/section-07.webp`
- `images/section-08.webp`
- `images/section-09.webp`
- `images/section-11.webp`

## お悩みセクション差し替え

②はアップロードされた images/50代女性の自然な美しさ.png を使用。従来の section-02.webp は比較用として保持。

## 3つのこだわり差し替え

⑤は images/RE_BIRTHの3つのこだわり.png を使用。画像に含まれない確定原稿の締め文はHTMLで直下に保持。

## お客様の声差し替え

⑥は images/紅薔薇と金彩のお客様の声.png を使用。予約ボタンはHTMLのまま維持。支給画像の2件目末尾では、確定原稿の音符記号が省略されています。

## FV差し替え

images/真紅の薔薇が彩る贅沢フェイシャル.png を使用。画像自体は改変せず、CSSで上から1300px相当まで表示。画像内ボタンを隠し、その下に本物のHTML予約ボタンを配置。上部には支給ロゴ帯を追加。

## 顔・首・肩・デコルテのケア差し替え

③は images/rebirth-real-treatment-section.png を使用。

## セクション08差し替え

images/rebirth-owner-section.png を使用。

## お客様の声の色味・FAQ

⑥はCSS saturate(.95)で彩度のみ約5%抑制。元画像を保持。FAQは支給の「深紅と金彩の上質FAQ.png」を参考に赤帯・金枠へ変更し、確定原稿を編集可能なHTMLとして維持。

## サロン案内更新

images/赤と金の優雅なサロン案内.png の上部写真・装飾をCSSで表示。住所・駅・送迎・駐車場・営業時間・定休日は既存の確定原稿をHTMLのまま保持し、赤・金・クリーム色で整形。

## 写真の修正

⑤のカウンセリング写真は支給原本をそのまま再配置して section-05-original-photo.webp に書き出し。人物の再生成なし。⑨は既存の組版から施術サムネイルだけを暖色に調整した section-09-warm-treatment.webp に更新。

## プロフィールとアクセスの文字調整

⑧は section-08-readable.webp。本文の行分けを維持し、文字を太く大きく中央揃えに再組版。写真は既存素材をそのまま使用。アクセスは富雄駅と最終受付時刻の前に改行を指定。

## 初回体験のご案内：支給画像へ差し替え

⑨を「温かなフェイシャル施術の4ステップ.png」に更新。支給画像を加工せず使用し、予約ボタンは従来のHTMLを維持。

## 画像容量の軽量化

使用画像を同じ解像度のWebP（品質92、ロゴは可逆圧縮）に変換。元画像は保存し、容量が減った画像のみ参照先を変更。参照画像合計 16046643 bytes → 2499737 bytes。FVの優先読み込みと下部画像の遅延読み込みを維持し、動画は表示位置の300px手前まで通信を延期。

## カウンセリング写真の修正画像

⑨のWebPを支給の修正版へ差し替え（823×1910、再圧縮なし）。旧版は末尾-OLD.webpで保持。画像URLの更新識別子によりキャッシュを更新。

## 元のカウンセリング写真を直接配置

⑨の写真枠に支給原本 counseling-source-original.png をHTMLで重ねて配置。ファイルは原本と同一で、画像生成・顔補正・再圧縮なし。CSSで表示枠にトリミング。
