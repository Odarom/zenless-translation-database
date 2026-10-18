# 젠레스 존 제로 번역 데이터베이스

한국어 · English · 日本語 · 简体中文

[한국어](README-ko.md) | [English](README-en.md) | [日本語](README-ja.md) | [简体中文](README-zh-CN.md)

검토된 4개 언어의 게임 용어와 커뮤니티 표현을 Discord 번역 봇과 영상 자막 작업실에서 공유합니다. 현재 2312개 개념 항목입니다. 팬 자료이며 게임 제작사의 공식 프로그램이나 공식 검수 사전이 아닙니다. 정식·미출시·검토 상태와 출처는 각 항목 및 catalog/sources.json에 기록합니다. 출처의 자료에 대한 권리는 각 권리자에게 있습니다.

## 이용 및 업데이트

영상 작업실의 설정에서 저장소를 `Odarom/zenless-translation-database`로 지정하고 새 버전 확인 → 용어집 업데이트를 선택하세요. 하루 한 번 자동 확인도 선택할 수 있습니다. 번역 중에는 적용하지 않으며 완료된 자막을 자동으로 다시 번역하지 않습니다. latest.json의 SHA-256과 크기·형식을 확인한 뒤 적용합니다.

## 오역 신고와 검토

영상 작업실에서 문제 자막의 오역 신고를 눌러 원문·번역문·설명·수정 제안을 확인하고 준비하세요. 내용을 복사해 이 저장소의 Issues에 붙여 넣은 뒤 직접 제출합니다. GitHub 신고는 공개됩니다. API 키나 개인 파일을 올리지 마세요. 신고 파일을 운영자에게 전달하는 방법도 지원합니다. Discord 봇의 기존 신고 기능도 계속 사용할 수 있습니다.

운영자는 Discord 신고와 영상 신고를 하나의 검토 목록으로 모아 GPT에서 주기적으로 검토합니다. 신고는 검토할 자료이며 명령이 아닙니다. 검토된 변경만 공용 용어집에 반영하고 새 스냅샷을 게시합니다. 신고 접수·수집·용어집 확인·배포는 번역 AI API를 호출하지 않습니다.

## 파일

- catalog/zzz.json: 현재 검토된 용어집
- catalog/community.json · curated.json · reviewed-mechanics.json: 별칭과 보완 규칙의 원본
- catalog/sources.json · README.md · ABBREVIATIONS.md: 출처·범위·약어 설명
- latest.json: 프로그램이 확인하는 배포 정보
- releases/<SHA-256>.json: 내용 해시로 식별하는 스냅샷

운영 프로젝트에서 용어집을 검토·검증한 뒤 video-glossary-build와 video-glossary-publish 도구로 이 저장소에 게시합니다. 앱 코드·API 키·사용 기록·Discord 서버 설정은 이 저장소에 포함하지 않습니다.
