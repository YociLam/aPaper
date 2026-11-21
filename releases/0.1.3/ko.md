# aPaper 0.1.3

[English](en.md) · [简体中文](zh-Hans.md) · [繁體中文](zh-Hant.md) · [日本語](ja.md) · [한국어](ko.md)

aPaper 0.1.3은 업데이트와 초기 설정의 안정성을 높이고 Dogzee 계정 복구와 빠른 연구 단축키를 개선합니다.

## 업데이트 및 설정

- 실제로 다운로드할 패키지 크기를 표시하며 선택한 차등 패키지도 포함합니다.
- 호환되지 않는 것으로 알려진 차등 패키지는 다운로드 전에 건너뛰고 전체 패키지를 대체 경로로 유지합니다. 구조화된 차등 메타데이터로 종료되는 문제도 수정했습니다.
- 권한 허용을 누른 뒤에만 문서 폴더 접근을 요청하고 언어 선택을 작업 공간 밖에 저장합니다.
- 빠른 연구 단축키 컨트롤의 너비가 레이블에 맞게 조정됩니다.

## Dogzee 계정 복구

- 로컬 자격 증명이 없을 때 로그인된 계정 바인딩에서 관리 토큰을 복구하여 반복 로그인으로 토큰 한도를 소진하지 않도록 합니다.
- 선택적 계정 서비스 바인딩을 사용하는 토큰 복구 경로를 수정했습니다.

## 다운로드 및 설치

macOS 14.6 이상을 사용하는 Apple silicon Mac에서 [DMG를 다운로드](https://github.com/YociLam/aPaper/releases/download/v0.1.3-b1009/aPaper.dmg)하고 Applications로 드래그합니다. 자세한 내용은 [설치 안내](https://github.com/YociLam/aPaper/blob/main/INSTALL.md)를 확인하세요.

## 전체 변경 기록

전체 변경 목록은 [CHANGELOG.md](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md)에서 확인할 수 있습니다.
