# Folder Bot — 테스트 빌드

Mac mini 호스트 + PWA 클라이언트. 소스: https://github.com/dave-jin/rondo

## 설치 (Mac mini, GUI 로 연 터미널에서)
```bash
curl -fsSL https://raw.githubusercontent.com/dave-jin/rondo-releases/main/folderbot/install.sh | bash
folderbot init "/Users/dave/Library/CloudStorage/Dropbox-Cbsjin/진대연 (Dave)/PARA"
folderbot start
```
직접 받기: [folderbot-0.1.0.tgz](https://raw.githubusercontent.com/dave-jin/rondo-releases/main/folderbot/folderbot-0.1.0.tgz) · [sha256](https://raw.githubusercontent.com/dave-jin/rondo-releases/main/folderbot/folderbot-0.1.0.tgz.sha256)

## 원격에서 열기
호스트가 뜨면 주소와 6자리 코드가 보입니다. 같은 tailnet 의 폰·맥북 브라우저에서 `http://<미니 Tailscale IP>:7373` → 코드 입력.
HTTPS·폰 푸시: 미니에서 `tailscale serve --bg 7373` 뒤 `https://mac-mini.<tailnet>.ts.net` 를 홈 화면에 추가.

| 버전 | 날짜 | 비고 |
|---|---|---|
| 0.1.0 | 2026-09-12 | 첫 테스트 빌드 — S1~S10 핵심 경로. Codex·macOS 셸·Dropbox 해시는 다음 |
