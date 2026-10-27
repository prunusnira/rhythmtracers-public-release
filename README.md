# Rhythm Tracers - Download GitHub Page

## 최신버전

![Version](https://img.shields.io/badge/RhythmTracers-v0.1.16.00-brightgreen.svg)
![Publish](https://img.shields.io/badge/Published_at-2026-10-27T11:55:55Z-blue.svg)

https://github.com/prunusnira/rhythmtracers-public-release/releases/tag/0.1.16.00

## Rhythm Tracers에 대해

- Rhythm Tracers는 BMS 형식의 파일을 플레이 할 수 있는 BMS 구동기입니다
- 통상 BMS를 4, 5, 6, 8키로 플레이 할 수 있습니다

## 특징

- 재생 디바이스로 ASIO를 사용할 수 있습니다
- 노트 이펙트 (배치) 로 사용자가 위치를 지정하는 '커스텀 랜덤' 기능이 있습니다
- 플레이 데이터를 보관하여 자신과의 실시간 1:1 대결을 해볼 수 있습니다

### 지원 형식

- U_E팩 4, 6, 8키를 지원합니다
- Aery팩 5키를 지원합니다
- 통상 BMS는 4, 5, 6, 8 어떤 형식으로도 플레이 할 수 있습니다

## 설명서

https://prunusnira.notion.site/Rhythm-Tracers-Alpha-Test-34216cef3d1647a58af6350509dfd9cc

## 최신 릴리즈 변경사항

# 설명서

https://prunusnira.notion.site/Rhythm-Tracers-34216cef3d1647a58af6350509dfd9cc

---

## 변경사항

### 판정등급 변경

- PERFECT+ → PERFECT
- PERFECT → GREAT
- GREAT → GOOD
- BAD (유지)
- MISS (유지)

일반적인 판정표기로 변경했습니다. 판정 수치나 다른 것이 달라진 것은 없습니다

### 플레이 배경 투명도 옵션 삭제

- BGA가 전체화면이 아니게 변경되었으나 한동안 삭제하지 않고 있던 옵션이었습니다

### DB 구조 변경

- 기존에 사용하던 db_xxx.sqlite를 하나로 합쳐 db.sqlite 파일 하나를 사용하도록 변경되었습니다
- 기존 데이터는 보존되지 않으므로 BMS Manager로 다시 데이터를 갱신해주셔야 합니다

### (BMS Manager) 난이도 표, 코스 관리 기능 추가

- BMS Manager 상에서 난이도 표와 코스 관리를 할 수 있도록 기능이 추가되었습니다
- 코스모드는 다음 업데이트 즈음… 추가될 것 같습니다
- 코스는 mocha repository 가입 후 다운로드 가능한 코스 json을 한 폴더에 모두 저장한 상태로 코스 갱신을 하시면 됩니다

### 플레이 필드 테마 기능 추가

- 8개의 선택 가능한 테마를 추가하였습니다
- 플레이 옵션 - UI 탭에서 플레이 필드 테마를 변경할 수 있습니다
- 싱글/더블을 따로 지정 가능합니다
- 추후 사용자가 직접 만든 테마를 사용할 수 있게 할 예정입니다

### 기타

- 키밤 이펙트가 변경되었습니다
- 게임 종료 시 이펙트가 변경되었습니다
- 옵션 화면의 화살표가 버튼 내에서 한 방향으로 치우쳐져 있던 문제를 수정했습니다

## 현재 확인된 버그

- 검색 결과에서 커서가 잘못 표시되는 문제가 있습니다. 방향키 위쪽을 눌러서 페이지를 갱신하면 제대로 돌아옵니다
- 기록이 저장되어 있지 않은 곡의 스코어 그래프와 타겟점수가 잘못 표시될 수 있습니다 (현재 점수는 정상 표시됨)
- 모드 선택에서 코스모드로 들어가지는 문제가 있습니다. 들어가지는건 문제가 아닌데 다시 나올 수가 없어서 게임을 강제 종료 해야 합니다.

---
