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

## 🛠 Changelog (업데이트 기록)

### v1.0.1
- **Added**: `Shift + Enter` shortcut to terminate the script.
- **Improved**: Status display moved from `alert()` to Browser Tab Title.
- **Fixed**: Conflict issues while typing in input fields.
- **Fixed**: Performance issues caused by duplicate script executions.
