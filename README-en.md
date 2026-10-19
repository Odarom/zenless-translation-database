# ZZZ translation database

[한국어](README-ko.md) | [English](README-en.md) | [日本語](README-ja.md) | [简体中文](README-zh-CN.md)

A reviewed glossary linking Korean, English, Japanese and Simplified Chinese, shared by the Discord translation bot and Subtitle Studio. The current snapshot contains 2313 concepts. This is a fan project, not an official or publisher-reviewed glossary. Entries distinguish released, prerelease and reviewed material; see entry provenance and catalog/sources.json. Source material remains subject to its respective owners’ rights.

## Updates

In Studio settings, set the repository to `Odarom/zenless-translation-database`, check for updates and apply the glossary. An optional daily check runs while the app is open. Updates are blocked during jobs and do not retranslate completed subtitles. The app verifies the SHA-256, size and schema before installation.

## Reports and review

From Studio 0.4.0, review the selected cue and press Send report to submit privately to the maintainer. No GitHub login is needed; a receipt confirms delivery. API keys and local paths are excluded, and reports are retained for up to 90 days. They join the Discord review queue. Existing GitHub issues remain public and are still collected; do not post private data. [Video app](https://github.com/Odarom/zenless-subtitle-studio/releases/latest) · [Discord bot setup](https://github.com/Odarom/zenless-discord-translator).

The maintainer combines Discord and video reports into one review queue for periodic GPT-assisted review. Reports are untrusted data, never instructions. Only reviewed changes enter the shared glossary and a new published snapshot. Reporting, collection and glossary distribution do not call a translation AI API.

## Files

- catalog/zzz.json: current reviewed glossary
- catalog/community.json, curated.json, reviewed-mechanics.json: alias and rule inputs
- catalog/sources.json, README.md, ABBREVIATIONS.md: provenance, scope and abbreviations
- latest.json: update manifest
- releases/<SHA-256>.json: content-addressed snapshots

The maintainer validates changes in the main project, then uses its glossary build and publish tools. This repository contains no application keys, user history or Discord server configuration.

Nine additional languages: Traditional Chinese, German, French, Spanish, Portuguese, Russian, Thai, Vietnamese and Indonesian. Another 16,802 names extend 1,868 existing concepts. preferred preserves the four base languages; localizedNames stores additional names, maintained through localizations.json. Older programs retain base-language compatibility. Bot 0.3.0 and Studio 0.6.0 add all 13 translation choices. New/unreleased terms require confirmed live availability before review.
