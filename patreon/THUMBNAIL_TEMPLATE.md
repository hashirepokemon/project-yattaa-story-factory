# AP Japanese Studio Thumbnail Template

Patreonのサムネイル、Tier Cover、記事内画像を一貫させるための基準です。Project Yattaaの `docs/ART_STYLE_GUIDE.md` を優先し、この文書でPatreon向けの具体仕様を補います。

## 目標

一般の学習者や保護者にも受け入れられる、シンプルでかわいく、人が作った温度のある画像にします。情報を詰め込みすぎず、小さい表示でも記事のテーマが分かることを優先します。

## 基本スタイル

- 手描きの色鉛筆、薄いガッシュ、穏やかな紙の質感
- 少し不均一な線と自然な余白
- 平面的で、濃淡と陰影は少なめ
- 一枚につき主なモチーフは一つ、補助モチーフは二つまで
- 人物やキャラクターは、記事に本当に必要な場合だけ使う
- キャラクターなしでも、日本語学習と「やったね」の達成感が伝わる構成を優先する
- 文字は大きく短くし、スマートフォンの縮小表示でも読めるようにする

## 配色

基本色:

- Warm cream: `#FFF8EE`
- Pastel coral: `#F28C8C`
- Soft pink: `#F7B7C3`
- Muted teal: `#4F9DA6`
- Soft yellow: `#F4D77A`
- Text brown: `#5A3F3A`

一枚の主要色は三色程度に絞ります。セピア、ネオン、強い黒、過度なグラデーションを避けます。

## モチーフ

内容に合わせて少数を選びます。

- open notebook / workbook
- pencil / speech bubble / microphone
- one sakura petal
- small check mark or gentle celebratory line
- map pin / local object / cultural detail
- teacher note / rubric card

桜、鳥居、富士山などを同時に並べて「日本らしさ」を過剰に演出しません。文化的テーマは、記事で扱う具体的な一要素から選びます。

## 画像内文字

原則として、背景・イラストを生成した後に文字を配置します。画像生成時に文字を含める場合は次を守ります。

- タイトルは4〜7語を目安にする
- 正確な文字列をプロンプトへ引用する
- 余分なコピー、意味のない日本語、透かしを禁止する
- 生成後に綴り、日本語表記、句読点を確認する
- 誤字がある画像は公開しない

## 構図

- LandscapeのPatreonカバーを基本とする
- 文字と主役を中央の安全領域へ置く
- 端に重要な文字や顔を置かない
- 左または中央にタイトル、右下に小さなモチーフなど、視線の順序を明確にする
- 背景は単純にし、記事カード上で読めるコントラストを確保する

## AI感を抑える

避けるもの:

- 滑らかすぎる3D、プラスチックのような質感
- 強い光沢、映画的照明、過剰な被写界深度
- 大量の小物、花、星、紙吹雪
- 不自然な手、意味不明な文字、崩れた小物
- アニメキャラクターを毎回中心に置くこと
- 既存作品、企業ロゴ、著作権キャラクターの模倣
- 「完璧すぎる」左右対称と、均一すぎる線

## 標準プロンプト

```text
Use case: ads-marketing
Asset type: Patreon post thumbnail, landscape
Primary request: [記事のテーマが一目で分かる一つの場面]
Style: genuinely human hand-drawn colored pencil and light gouache, slightly uneven lines, limited flat color, minimal shading
Composition: one main motif, one or two supporting details, generous negative space, readable at thumbnail size
Palette: warm cream, pastel coral, muted teal, soft yellow
Text: "[短い正確なタイトル]" または no text
Avoid: AI gloss, photorealism, 3D, gradients, excessive detail, crowds, mascots unless required, extra text, watermark, copyrighted characters
```

## 保存と承認

- ファイル名: `YYYY-MM-DD-short-topic-v01.png`
- 生成元、最終プロンプト、使用記事を記録する
- 不採用画像を承認済みフォルダに置かない
- Patreonへアップロードする前に、内容、文字、AI破綻、サイズを確認する
- Save / Update / Publishはユーザー確認後に行う
