# 얼마나썼냐옹 · How Meowch 🐾

**AI 사용량을 메뉴 막대와 작업표시줄에서 한눈에.**

Claude · Codex · Antigravity의 여러 계정을 연결하고, 남은 사용량과 초기화 시각을 확인해요. macOS에서는 메뉴 막대, Windows에서는 작업표시줄 칩과 알림 영역에서 열 수 있어요.

## 다운로드

플랫폼별 최신 안정 버전이에요. 사용 중인 운영체제에 맞는 파일을 선택해 주세요. 두 플랫폼의 버전은 서로 다를 수 있어요.

<!-- howmeowch:macos:start -->
### macOS

[![macOS v0.1.0](https://img.shields.io/badge/macOS-v0.1.0-24292f?style=for-the-badge)](https://github.com/mmisman/how-meowch/releases/tag/macos%2Fv0.1.0)

[![macOS 다운로드](https://img.shields.io/badge/Download-macOS_ZIP-2ea44f?style=for-the-badge)](https://github.com/mmisman/how-meowch/releases/download/macos%2Fv0.1.0/HowMeowch-0.1.0-macos.zip)

**[HowMeowch-0.1.0-macos.zip](https://github.com/mmisman/how-meowch/releases/download/macos%2Fv0.1.0/HowMeowch-0.1.0-macos.zip)** · [릴리스 노트](https://github.com/mmisman/how-meowch/releases/tag/macos%2Fv0.1.0)

macOS 14 이상 · Apple Silicon 및 Intel
<!-- howmeowch:macos:end -->

<!-- howmeowch:windows:start -->
### Windows

[![Windows v0.1.0](https://img.shields.io/badge/Windows-v0.1.0-0078d4?style=for-the-badge)](https://github.com/mmisman/how-meowch/releases/tag/windows%2Fv0.1.0)

[![Windows 다운로드](https://img.shields.io/badge/Download-Windows_EXE-2ea44f?style=for-the-badge)](https://github.com/mmisman/how-meowch/releases/download/windows%2Fv0.1.0/HowMeowch-Setup-0.1.0-win-x64.exe)

**[HowMeowch-Setup-0.1.0-win-x64.exe](https://github.com/mmisman/how-meowch/releases/download/windows%2Fv0.1.0/HowMeowch-Setup-0.1.0-win-x64.exe)** · [릴리스 노트](https://github.com/mmisman/how-meowch/releases/tag/windows%2Fv0.1.0)

Windows 10/11 · x64
<!-- howmeowch:windows:end -->

> 설치하려면 **macOS ZIP** 또는 **Windows EXE**를 선택해 주세요. 릴리스 화면의 **Source code (zip/tar.gz)**는 공개 안내와 업데이트 정보의 스냅샷이며, 앱 설치 파일이 아니에요.

---

## macOS 설치와 처음 실행

1. 이 릴리스의 **HowMeowch-버전-macos.zip**을 다운로드하고 더블 클릭하여 압축을 풀어요. GitHub의 **Source code** 파일은 설치 파일이 아니에요.
2. **얼마나썼냐옹.app**을 **응용 프로그램(Applications)** 폴더로 옮겨요. 이전 앱이 실행 중이면 메뉴에서 종료한 뒤 교체해 주세요.
3. 응용 프로그램 폴더에서 앱을 **먼저 실행**해요. 별도 창 대신 화면 위 메뉴 막대에 표시돼요.
4. 확인되지 않은 개발자 안내로 실행이 차단된 경우, 이 저장소에서 받은 앱인지 확인한 뒤 **시스템 설정 → 개인정보 보호 및 보안(Privacy & Security)** 아래의 **그래도 열기(Open Anyway)**를 선택해요. 이어지는 안내에서 **열기**를 확인하고 macOS가 요구하면 Mac 로그인 암호를 입력해요. 해당 버튼은 실행을 시도한 뒤 나타나요. [Apple의 공식 안내](https://support.apple.com/ko-kr/102445)를 참고해 주세요.

현재 Mac 앱은 ad-hoc 서명을 사용하며 Apple 공증을 받지 않았어요. 보안 설정을 끄거나 터미널 명령을 실행할 필요는 없어요. 악성 소프트웨어 경고가 나오거나 출처를 확신할 수 없다면 실행하지 마세요.

### 계정 연결과 키체인

메뉴 막대의 **얼마나썼냐옹**을 눌러 서비스를 선택해요.

- **claude.ai 로그인:** 로그인하면 계정이 연결돼요.
- **Codex 로그인:** ChatGPT에 로그인하고 원하는 워크스페이스를 선택한 뒤 **이 계정 연결**을 눌러요.
- **Antigravity 로그인:** 기본 브라우저에서 Google 계정을 고르고 접근에 동의하면 앱으로 연결돼요.

계정을 더 연결하려면 **설정(⚙️) → 계정 추가**를 사용해요. 앱은 사용량을 조회하며, 세션과 토큰은 **macOS 로그인 키체인에 자동 저장**돼요. 키를 따로 만들거나 등록할 필요도, 쿠키를 복사해서 붙여넣을 필요도 없어요.

키체인 접근 요청이 나타나면 요청한 앱이 **얼마나썼냐옹**인지 확인한 뒤 허용해 주세요. macOS가 암호를 요구하면 해당 로그인 키체인의 암호(보통 Mac 로그인 암호)를 입력해요. 기존 키체인 항목 이름이 `claude.ai session cookie`로 표시될 수 있지만 여러 서비스의 계정을 함께 저장하는 항목이에요. ad-hoc 서명 특성상 업데이트 후 접근 승인을 다시 요청할 수 있어요. 요청을 거절해 계정이 나타나지 않거나 저장 오류가 표시되면 앱을 다시 실행해 접근 요청을 확인하고, 필요하면 계정을 다시 연결해 주세요. 키체인을 삭제하거나 암호를 공유하지 마세요.

## Windows 설치

1. 위의 **Windows EXE** 설치 파일을 내려받아 실행해요.
2. 설치 위치와 필요한 구성 요소를 확인하고 설치를 진행해요. .NET 10 Desktop Runtime과 WebView2 Runtime이 필요하며, 설치기가 상태를 확인하고 필요한 설치를 안내해요.
3. 설치가 끝나면 앱을 실행하고 계정을 연결해요. 알림 영역의 고양이 아이콘에서도 앱을 열 수 있어요.

현재 Windows 설치 파일은 Authenticode 서명이 없어 Windows 보안 경고가 나타날 수 있어요. 다운로드 출처와 파일명을 확인하고, 회사나 학교에서 관리하는 PC에서는 조직의 정책을 따라 주세요.

## 앱 업데이트

설정에서 **업데이트 확인**을 선택할 수 있어요. 하루 한 번 새 버전을 자동으로 확인하며, 다운로드와 설치는 사용자가 선택해요. 업데이트 파일의 서명을 검증한 뒤 설치해요. 업데이트 기능이 없는 개발 빌드는 위 파일로 한 번 수동 설치해 주세요.

## 도움이 필요할 때

[릴리스 목록](https://github.com/mmisman/how-meowch/releases)에서 변경 사항을 확인하거나 [문제 제보](https://github.com/mmisman/how-meowch/issues)를 남겨 주세요. 사용 중인 OS, 앱 버전, 오류 문구를 알려 주시면 도움이 돼요. 계정 이메일·쿠키·토큰·키체인 암호는 올리지 마세요.
