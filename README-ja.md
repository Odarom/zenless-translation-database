# ZZZ翻訳データベース

[**アプリなしで用語・略語の誤りを報告**](https://github.com/Odarom/zenless-translation-database/issues/new/choose) — 入力別名、コミュニティ出力、正式名の誤り、未登録用語、適用ルールを記入できます。GitHubログインが必要で、内容とアカウント名は公開されます。個人情報・APIキー・非公開資料は投稿しないでください。Discord・動画報告と同じ一覧で確認し、送信だけでDBは変更されません。

[한국어](README-ko.md) · [English](README-en.md) · [日本語](README-ja.md) · [简体中文](README-zh-CN.md)

Discordボットと字幕スタジオで共有する **2314** 概念 · **13** 言語

## 閲覧

アプリなしで名称・略語・適用規則を確認できます。

- [**分類別一覧**](catalog/BROWSE.md)
- [名称索引](catalog/INDEX.md)
- [略語の説明](catalog/ABBREVIATIONS.md)
- [範囲・出典](catalog/README.md)

## データファイル

| File | Description |
|---|---|
| [zzz.json — Raw](https://raw.githubusercontent.com/Odarom/zenless-translation-database/main/catalog/zzz.json) | 基本4言語・追加9言語の名称と規則を含む全DB。大きいJSONのため原文表示へリンクします。 |
| [community.json](catalog/community.json) | 入力別名とコミュニティ出力 |
| [curated.json](catalog/curated.json) | 出典照合による補完名 |
| [reviewed-mechanics.json](catalog/reviewed-mechanics.json) | 確認済みの戦闘・リソース文脈規則 |
| [localizations.json](catalog/localizations.json) | 既存概念に追加した言語名 |
| [sources.json](catalog/sources.json) | 資料版・取得日時・ハッシュ |
| [latest.json](latest.json) | プログラム用更新情報 |
| [LIFECYCLE.md](catalog/LIFECYCLE.md) | 候補生成・確認・バックアップ・適用 |

## 利用・更新

画面と説明は韓国語・英語・日本語・簡体字中国語、翻訳名称は計13言語です。言語ごとの収録数は異なります。アプリの用語集更新は以後の翻訳に使い、既存字幕は自動変更しません。

[Subtitle Studio](https://github.com/Odarom/zenless-subtitle-studio/releases/latest) · [Discord](https://github.com/Odarom/zenless-discord-translator)

## 誤りを報告

[GitHub](https://github.com/Odarom/zenless-translation-database/issues/new/choose) — アプリなしで略語・正式名・未登録語・規則を報告できます。GitHubログインが必要で内容は公開されます。管理者が依頼時にアプリ・Discordの非公開報告と併せて確認します。投稿だけでDBは変わりません。

ファン制作で、制作会社の公式・監修辞典ではありません。既存の未公開資料は状態を表示し、新規の未公開語は正式実装確認後に検討します。APIキー・利用履歴・非公開報告原文は含みません。
