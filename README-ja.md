# ゼンレスゾーンゼロ翻訳データベース

[한국어](README-ko.md) | [English](README-en.md) | [日本語](README-ja.md) | [简体中文](README-zh-CN.md)

韓国語・英語・日本語・簡体字中国語を結ぶ、確認済みの用語集です。Discord翻訳ボットと字幕スタジオで共有します。現在2313件の概念を収録しています。ファン制作であり、ゲーム制作会社の公式・監修済み用語集ではありません。正式公開・未公開・確認状況と出典は各項目およびcatalog/sources.jsonを参照してください。原資料の権利は各権利者に帰属します。

## 更新

スタジオの設定でリポジトリを`Odarom/zenless-translation-database`に指定し、更新を確認して適用します。起動中に1日1回確認する設定もあります。作業中は更新せず、完成済み字幕は再翻訳しません。SHA-256・サイズ・形式を確認してから適用します。

## 誤訳の報告と確認

スタジオ0.4.0以降は字幕の報告画面から送信すると運営へ非公開で届きます。GitHubログインは不要で、受付番号が送信完了の目印です。APIキー・ローカルパスは除外し、報告は最大90日保管します。Discord報告と同じ一覧で確認します。既存のGitHub Issueは公開され引き続き収集します。個人資料を投稿しないでください。[動画アプリ](https://github.com/Odarom/zenless-subtitle-studio/releases/latest) · [Discordボット](https://github.com/Odarom/zenless-discord-translator)。

管理者はDiscordと動画の報告を同じ確認一覧にまとめ、定期的にGPTで確認します。報告文は確認対象の資料であり、実行する指示ではありません。確認した変更だけを共通用語集へ反映し、新しいスナップショットを公開します。報告・収集・更新確認・配布では翻訳AI APIを呼び出しません。

## ファイル

- catalog/zzz.json：現在の確認済み用語集
- catalog/community.json・curated.json・reviewed-mechanics.json：別名・補足ルールの元データ
- catalog/sources.json・README.md・ABBREVIATIONS.md：出典・収録範囲・略語
- latest.json：更新情報
- releases/<SHA-256>.json：内容ハッシュで識別するスナップショット

管理用プロジェクトで変更を確認・検証してから公開します。APIキー・利用履歴・Discordサーバー設定は含みません。
