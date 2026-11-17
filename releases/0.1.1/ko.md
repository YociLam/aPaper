# aPaper 0.1.1

[English](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/en.md) · [简体中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/zh-Hans.md) · [繁體中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/zh-Hant.md) · [日本語](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/ja.md) · [한국어](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/ko.md)


## 새 기능
- 모델 설정과 대화 입력창에서 모델별 추론 강도 프리셋을 일관되게 제공합니다.
- 연구 도표와 대화형 보기에 공통 디자인을 적용하고, 검증된 출처 발췌와 보기 상태 저장을 지원합니다.
- Library 우클릭 메뉴에서 논문을 바로 가져올 수 있습니다.

## 개선
- 대화 목록, 스트리밍 답변과 Knowledge 그래프 업데이트의 응답성을 개선했습니다.
- 결과 보기에서 이번 작업의 논문을 카드 또는 그래프 모드로 표시합니다.
- 재시작 후 계속할 수 있는 저장된 Knowledge 작업을 재개합니다. 필요한 기능이 복구되면 복구 가능한 오류를 자동으로 재시도하며, 처리 설정과 기존 지식을 유지합니다.

## 수정
- 여러 App이 같은 작업공간을 동시에 열지 않도록 하고 SQLite 트랜잭션 잠금을 유지합니다.
- Knowledge 시작 중 일시적인 오류에 제한된 복구 절차와 명확한 안내를 제공합니다.
- 실패하거나 중단된 Mentor 답변에서 질문 편집과 재시도를 복원했습니다.
- 사이드바 호버 펼치기, 정리 대화상자, 초기 설정 탐색과 권한 버튼을 수정했습니다.
- 선택적 키 이름 업데이트가 실패해도 사용 가능한 Dogzee 모델 그룹을 유지합니다.
- Research Assistant의 첨부파일 접근, 프로젝트 리소스 작업과 명령 실행의 안정성을 개선했습니다.
- Zotero 식별자나 제목으로 메타데이터를 확인하고 사용자 편집을 유지합니다.
- 이동 및 복사 대상 폴더를 계층형 메뉴로 표시합니다.
- 떠 있는 패널의 제목과 가장자리에서도 스크롤이 해당 패널 안에 머물도록 했습니다.

## 다운로드 및 설치

[macOS 버전 다운로드](https://github.com/YociLam/aPaper/releases/download/v0.1.1-b1007/aPaper.dmg) · [설치 안내](https://github.com/YociLam/aPaper/blob/main/INSTALL.md)

## 전체 변경 내역

[모든 버전의 변경 내역 보기](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md).
