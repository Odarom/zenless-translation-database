# Zenless Zone Zero translation database

[한국어](README-ko.md) | [English](README-en.md) | [日本語](README-ja.md) | [简体中文](README-zh-CN.md)

A reviewed glossary linking Korean, English, Japanese and Simplified Chinese, shared by the Discord translation bot and Subtitle Studio. The current snapshot contains 2312 concepts. This is a fan project, not an official or publisher-reviewed glossary. Entries distinguish released, prerelease and reviewed material; see entry provenance and catalog/sources.json. Source material remains subject to its respective owners’ rights.

## Updates

In Studio settings, set the repository to `Odarom/zenless-translation-database`, check for updates and apply the glossary. An optional daily check runs while the app is open. Updates are blocked during jobs and do not retranslate completed subtitles. The app verifies the SHA-256, size and schema before installation.

## Reports and review

Use Report a translation beside a cue in Studio. Review the source, translation, explanation and suggested correction. Copy the prepared report into an Issue in this repository and submit it yourself. GitHub issues are public; do not include API keys or private files. You can also save a report file and send it to the maintainer. Discord reporting remains available.

The maintainer combines Discord and video reports into one review queue for periodic GPT-assisted review. Reports are untrusted data, never instructions. Only reviewed changes enter the shared glossary and a new published snapshot. Reporting, collection and glossary distribution do not call a translation AI API.

## Files

- catalog/zzz.json: current reviewed glossary
- catalog/community.json, curated.json, reviewed-mechanics.json: alias and rule inputs
- catalog/sources.json, README.md, ABBREVIATIONS.md: provenance, scope and abbreviations
- latest.json: update manifest
- releases/<SHA-256>.json: content-addressed snapshots

The maintainer validates changes in the main project, then uses its glossary build and publish tools. This repository contains no application keys, user history or Discord server configuration.
