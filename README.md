# 🚀 AutoPlay (v1.0.1)

![Version](https://img.shields.io/badge/version-1.0.1-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Language](https://img.shields.io/badge/language-JavaScript-yellow)

### (video-autoplay-bookmarklet)

Generic HTML5 Video AutoPlay Bookmarklet for personal automation.
브라우저 환경에서의 개인 학습 및 편의를 위한 자동 재생 북마클릿입니다.

> [!WARNING]
> This project is intended for **personal automation and educational purposes only**. The author is **not responsible for any misuse** of this tool.
> 본 프로젝트는 **개인 자동화 및 학습 목적**의 도구입니다. 본 도구 사용으로 발생하는 **모든 책임은 사용자 본인에게 있습니다.**

---

## ✨ Features (주요 기능)
- **Auto Navigation**: Automatically clicks "Next Video" buttons. (다음 영상 자동 클릭)
- **Tab Status UI**: Shows current status (`ON`/`OFF`) in the browser tab title to avoid flickering. (브라우저 탭 제목에 실시간 상태 표시)
- **Input Safe**: Automatically ignores keys while typing in `input` or `textarea`. (입력창 타이핑 시 간섭 방지)
- **One-Click Termination**: Completely stops and removes the script from the browser. (단축키를 통한 스크립트 완전 종료)
- **Duplicate Prevention**: Prevents multiple instances from running simultaneously. (중복 실행 방지 로직)

---

## ⌨️ Keyboard Shortcuts (단축키)

| Action (기능) | Key (키) | Description (설명) |
| :--- | :--- | :--- |
| **Toggle ON/OFF** | `Enter` | 스크립트 활성/비활성 토글 |
| **Terminate** | `Shift + Enter` | 스크립트 완전 종료 및 메모리 해제 |

---

## ✅ Usage (사용 방법)

1. **Get the Code**: Copy the one-liner code from the project.
   (`autoplay.js`의 한 줄 코드를 복사합니다.)
2. **Add Bookmark**: Create a new bookmark in your browser and paste the code into the `URL` field.
   (브라우저 북마크를 생성하고 'URL' 칸에 코드를 붙여넣습니다.)
3. **Activate**: Open the target video page and click the bookmark.
   (영상이 있는 페이지에서 북마크를 클릭하여 스크립트를 로드합니다.)
4. **Control**: Use `Enter` to start/stop, and `Shift + Enter` to exit.
   (`Enter`로 시작/정지하고, 업무가 끝나면 `Shift + Enter`로 종료합니다.)   

---

> [!IMPORTANT]
> **페이지 새로고침 시**: 영상이 다음 강의로 넘어가거나 페이지를 새로고침하면 브라우저 보안 정책상 스크립트가 초기화됩니다. 이 경우 **다시 한번 북마크를 클릭하고 `Enter`를 입력**해 주세요.

---

## 🛠️ Troubleshooting (문제 해결)

### 탭 제목에 퍼센트(%)가 나타나지 않고 작동하지 않나요?
사이트의 보안 벽(CORS)이 높은 경우, 스크립트가 영상이 들어있는 프레임(Iframe)을 찾지 못할 수 있습니다. 이때는 아래 단계를 따르세요.

1. `F12`를 눌러 개발자 도구를 열고 **Console** 탭으로 이동합니다.
2. 콘솔 상단의 `top`이라고 적힌 **드롭다운 메뉴(JavaScript Context)**를 클릭합니다.
3. 목록에서 비디오 플레이어 관련 항목(예: `index.html` 또는 `brightcove` 포함 항목)으로 변경합니다.
4. 그 상태에서 코드를 다시 입력하거나 북마크를 실행하세요.

---

## 🛠 Changelog (업데이트 기록)

### v1.0.1
- **Added**: `Shift + Enter` shortcut to terminate the script.
- **Improved**: Status display moved from `alert()` to Browser Tab Title.
- **Fixed**: Conflict issues while typing in input fields.
- **Fixed**: Performance issues caused by duplicate script executions.
