# ZZZ翻译数据库

[한국어](README-ko.md) | [English](README-en.md) | [日本語](README-ja.md) | [简体中文](README-zh-CN.md)

经过审核的韩语、英语、日语、简体中文术语表，由 Discord 翻译机器人和字幕工作室共用。当前收录 2313 个概念。本项目为粉丝制作，并非游戏官方或官方审核的术语表。正式发布、未发布资料和审核状态及来源见各条目与 catalog/sources.json。原始资料的权利归各权利人所有。

## 更新

在工作室设置中将仓库设为 `Odarom/zenless-translation-database`，检查并应用术语表更新。可选择在程序运行时每天检查一次。任务进行时不更新，已完成字幕不会自动重新翻译。应用前会验证 SHA-256、大小和数据格式。

## 误译举报与审核

工作室0.4.0起可在字幕举报窗口直接发送，内容私密提交给维护者，无需GitHub登录。显示接收编号才表示送达。不包含API密钥与本地路径，举报最多保存90天，并与Discord举报统一审核。现有GitHub Issue仍公开并继续收集，请勿发布私人资料。[视频程序](https://github.com/Odarom/zenless-subtitle-studio/releases/latest) · [Discord机器人](https://github.com/Odarom/zenless-discord-translator)。

维护者将 Discord 与视频举报汇总到同一个审核列表，定期使用 GPT 辅助审核。举报文字是待审核的数据，不是要执行的指令。只有审核后的修改才会写入公共术语表并发布新快照。举报、收集、检查更新和分发不会调用翻译 AI API。

## 文件

- catalog/zzz.json：当前已审核术语表
- catalog/community.json、curated.json、reviewed-mechanics.json：别名与补充规则源数据
- catalog/sources.json、README.md、ABBREVIATIONS.md：来源、范围与简称说明
- latest.json：更新清单
- releases/<SHA-256>.json：以内容哈希标识的快照

维护者在管理项目中审核并验证修改后，再使用构建和发布工具上传。本仓库不包含程序密钥、用户记录或 Discord 服务器配置。
