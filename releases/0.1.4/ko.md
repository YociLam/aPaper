# aPaper 0.1.4

[English](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/en.md) · [简体中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/zh-Hans.md) · [繁體中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/zh-Hant.md) · [日本語](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/ja.md) · [한국어](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/ko.md)

알림을 나중에 읽고 좁은 창에서도 문서를 계속 읽을 수 있습니다. 메인 창을 다시 열 때 연구 작업 공간을 복원하는 동작도 개선했습니다.

## 새 기능

- **멀티미디어 알림.** 클라이언트와 표시 언어에 맞춰 알림을 보낼 수 있습니다. 패널은 서식 있는 텍스트, 이미지, 링크와 동작 버튼을 지원하며 동영상 링크는 브라우저에서 열립니다.
- **나중에 읽기.** 사용 중에는 아일랜드에 알림이 잠시 나타납니다. 알림이나 오른쪽 아래 종 아이콘을 눌러 내용을 확인하세요. 업데이트 버튼이 있으면 종 아이콘은 그 위에 표시됩니다. 저장된 미확인 알림은 다음 실행 시 오프라인에서도 열립니다. 이전 알림을 읽어도 새 알림은 계속 받을 수 있습니다.
- **커뮤니티 초대.** 중국어 간체 및 번체 인터페이스의 앱 정보 화면에 aPaper QQ 그룹 초대와 QR 코드를 추가했습니다.

## 개선 사항

- **창 너비에 맞춘 읽기.** 창을 좁히면 왼쪽 문헌 사이드바가 먼저 닫히고, 두 단 읽기가 한 단으로 바뀐 뒤 오른쪽 패널이 닫힙니다. 창을 넓히면 이전 구성이 역순으로 복원됩니다. 전환에는 수동 조작과 같은 애니메이션을 사용합니다.
- **Dogzee 기본 모델.** Paper Mentor, Research Assistant, Knowledge Steward는 추론 강도가 중간인 GPT 6.2 Sol을 기본으로 사용합니다.

## 오류 수정

- **긴 메시지 작성.** 포인터를 입력창 위에 두면 대화 위치를 유지한 채 초안만 스크롤할 수 있습니다. 전송 후에도 조절한 입력창 높이를 유지합니다.
- **작업 공간 복원.** Dock 또는 빠른 연구에서 메인 창을 다시 열면 작업 공간과 알림 버튼이 복원됩니다. 선택 사항인 도우미 설정의 설치나 검증에 실패해도 작업 공간에 들어갈 수 있습니다.
- **추론 강도 호환성.** 모델 서비스가 선택한 추론 강도를 거부하면 같은 모델에서 지원하는 다른 강도로 다시 시도합니다. 처음 성공한 설정을 기억해 이후 같은 유형의 요청에 사용합니다.

## 다운로드 및 설치

0.1.1, 0.1.2, 0.1.3에서 0.1.4로 바로 차등 업데이트할 수 있습니다. 차등 패키지를 적용할 수 없으면 전체 업데이트 패키지를 사용할 수 있습니다. 0.1.0에서는 아래 DMG로 수동 업데이트하세요.

macOS 14.6 이상을 사용하는 Apple Silicon Mac에서 [DMG를 다운로드](https://github.com/YociLam/aPaper/releases/download/v0.1.4-b1010/aPaper.dmg)하고 열어 aPaper를 응용 프로그램 폴더로 드래그하세요. 수동 업데이트 시 aPaper를 종료한 후 기존 앱을 교체하세요. [설치 안내](https://github.com/YociLam/aPaper/blob/main/INSTALL.md)를 참고하세요.

## 전체 변경 기록

[버전별 변경 기록](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md)을 확인하세요.
