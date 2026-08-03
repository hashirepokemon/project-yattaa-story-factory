# AP Japanese Studio Patreon Production

このフォルダは、AP Japanese StudioのPatreon記事、サムネイル、Tags、公開前QAを一貫して作るための入口です。

Codexは、毎回すべてのファイルを読みません。まずこのREADMEを読み、作業に必要なファイルだけを開きます。

## 最小読み込みルール

| 作業 | 必ず読む | 必要なときだけ読む |
|---|---|---|
| 新しい記事を書く | `PATREON_RULES.md`, `ARTICLE_TEMPLATE.md` | `TAG_TAXONOMY.md`, `THUMBNAIL_TEMPLATE.md` |
| 既存記事を整える | `PATREON_RULES.md` | `ARTICLE_TEMPLATE.md` |
| サムネイルを作る | `THUMBNAIL_TEMPLATE.md` | 記事のメタデータ |
| Tagsを追加する | `TAG_TAXONOMY.md` | `PATREON_RULES.md` |
| PaywallやAudienceを設定する | `PATREON_RULES.md` | `ARTICLE_TEMPLATE.md` |
| 公開前レビュー | `PATREON_QA_CHECKLIST.md` | 問題がある項目に対応するルール |
| Save / Update / Publish | `PATREON_RULES.md` の公開操作 | `PATREON_QA_CHECKLIST.md` |

## ファイル

- [PATREON_RULES.md](PATREON_RULES.md) — 文体、読者、Tier、Paywall、著作権、公開操作
- [ARTICLE_TEMPLATE.md](ARTICLE_TEMPLATE.md) — 記事構成と制作メタデータ
- [THUMBNAIL_TEMPLATE.md](THUMBNAIL_TEMPLATE.md) — 配色、構図、AI感を抑える画像基準
- [TAG_TAXONOMY.md](TAG_TAXONOMY.md) — 承認済みTagsと選び方
- [PATREON_QA_CHECKLIST.md](PATREON_QA_CHECKLIST.md) — 公開前の最終確認

## 作業の流れ

1. 記事の読者、Access、Language、Kanji level、AP skillを決める
2. 必要なルールだけを読む
3. オリジナルの本文を作成する
4. 無料部分とPaywall候補を確認する
5. サムネイルとTagsを準備する
6. QAを行う
7. Patreonへ入力する
8. Save / Update / Publishの直前でユーザー確認を得る
9. 公開後の最終版を制作記録へ残す

## トークンを抑える原則

- 記事作成前に、目的と読者を一文で確定する
- 同じルールを会話へ繰り返し貼らず、該当ファイルを参照する
- 画像は承認済み配色と標準プロンプトを再利用する
- Tagsは承認済み一覧から選び、新しい類義語を増やさない
- QAでは全記事を再生成せず、問題のある箇所だけ修正する
- 過去記事は全文ではなく、制作メタデータと必要な抜粋から再開する

## セキュリティとプライバシー

このリポジトリは公開されています。

- 個人名、メール、住所、学生情報、認証情報、MFAコードを保存しない
- PatreonやGoogle Driveなどの非公開URLを保存しない
- Cookie、Local Storage、閲覧履歴、画面全体のスクリーンショットを保存しない
- ローカルファイルのメタデータと画像内の個人情報を確認する
- 秘密情報を見つけた場合はコミットせず、作業を止めてユーザーへ知らせる
- 外部資料は参照元のURLと事実確認に使い、教材そのものを転載しない
