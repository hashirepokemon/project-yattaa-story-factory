# Project Yattaa Story Factory

日本語学習者向けの短い物語を、一定の品質と世界観で制作・管理するためのリポジトリです。

物語本文、学年別漢字、ふりがな、イラスト、Pinterest投稿、Patreon掲載用コンテンツを、共通のルールとワークフローに沿って扱います。

## 目的

- 読みやすく、楽しく、最後まで読める日本語の物語を作る
- 語彙・漢字・ふりがなの難易度をコントロールする
- 作品ごとの文章、ビジュアル、公開素材の品質を揃える
- 制作からレビュー、公開、保管までの状態を明確にする

## まず読むもの

1. [FOUNDATION.md](FOUNDATION.md) — プロジェクトの目的、読者、価値観
2. [docs/STORY_RULES.md](docs/STORY_RULES.md) — 物語の執筆ルール
3. [docs/FURIGANA_RULES.md](docs/FURIGANA_RULES.md) — ふりがなのルール
4. [docs/ART_STYLE_GUIDE.md](docs/ART_STYLE_GUIDE.md) — イラストのスタイル
5. [docs/QA_CHECKLIST.md](docs/QA_CHECKLIST.md) — 公開前の確認項目
6. [docs/PUBLISHING_WORKFLOW.md](docs/PUBLISHING_WORKFLOW.md) — 制作・公開フロー

## ディレクトリ構成

```text
project-yattaa-story-factory/
├── assets/
│   ├── approved-style-reference/  承認済みの画風リファレンス
│   ├── backgrounds/               背景素材
│   └── characters/                キャラクター素材
├── data/                          学年別漢字データ
├── docs/                          制作・公開ルール
├── stories/
│   ├── ready-for-review/          レビュー待ち
│   ├── published/                 公開済み
│   ├── rejected/                  不採用
│   └── archive/                   保管済み
└── templates/                     物語・投稿用テンプレート
```

## 基本ワークフロー

1. テンプレートから物語を作成する
2. ストーリー、漢字、ふりがな、ビジュアルを確認する
3. `stories/ready-for-review/` に移してレビューする
4. 承認後、公開用コンテンツを作成する
5. 公開済み作品を `stories/published/` に移す

詳細は [docs/PUBLISHING_WORKFLOW.md](docs/PUBLISHING_WORKFLOW.md) に記載します。

## 運用原則

- 迷った場合は [FOUNDATION.md](FOUNDATION.md) の目的と価値観を優先する
- ルールに例外が必要な場合は、作品内だけで処理せず関連ドキュメントを更新する
- 承認前の素材を「承認済み」として扱わない
- 公開前に必ずレビューとQAを行う

## 現在の状態

初期セットアップ中です。各ルール、テンプレート、漢字データは順次整備します。
