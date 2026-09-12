# Folder Bot — 설치

**전체 가이드(미니 · 맥북 · 폰)**: https://github.com/dave-jin/rondo/blob/main/docs/INSTALL.md

## 앱 (권장 — 미니·맥북 공용)
최신 DMG: https://github.com/dave-jin/rondo/releases (`desktop-v*` › `Folder Bot-<버전>-arm64.dmg`)
- 미니: 첫 화면 「이 맥에서 호스트 실행」 → PARA 루트 선택 → 메뉴바에서 페어링 코드
- 맥북: 첫 화면에 미니 주소 → 페어링 코드
- 처음 열 때 우클릭 → 열기. "손상됨" 이면 `xattr -dr com.apple.quarantine "/Applications/Folder Bot.app"`

## CLI (미니, 터미널 방식)
```bash
curl -fsSL https://raw.githubusercontent.com/dave-jin/rondo-releases/main/folderbot/install.sh | bash
folderbot init "/Users/dave/Library/CloudStorage/Dropbox-Cbsjin/진대연 (Dave)/PARA"
folderbot start   # GUI 로 연 터미널에서
```
- 호스트 tarball: `folderbot-0.2.0.tgz` (sha256 은 옆 파일)
