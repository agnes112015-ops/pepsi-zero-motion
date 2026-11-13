# Pepsi Zero Sugar — 30s Motion Spot

브라우저에서 바로 재생되는 30초 모션그래픽 광고 (16:9, HTML + GSAP).

- `index.html` — 재생 페이지 (클릭해서 재생, 스페이스바 재생/정지, 진행바 탐색, 전체화면)
- `audio.mp3` — 배경음악 + 보이스오버 믹스
- `pepsi_zero_ad.mp4` — 렌더링된 영상 파일

## GitHub Pages로 공개하기

1. 이 폴더의 파일을 저장소 루트에 올립니다.
2. 저장소 **Settings → Pages → Branch: `main` / `(root)`** 저장.
3. 잠시 후 `https://<아이디>.github.io/<저장소>/` 에서 재생됩니다.

> 로컬에서 `index.html`을 더블클릭하면 브라우저 정책상 오디오가 막힐 수 있습니다. `python -m http.server`로 열거나 Pages에서 확인하세요.

## 크레딧

- 모션/타이포: HTML + [GSAP](https://gsap.com)
- 음악: 직접 합성한 오리지널 트랙
- 보이스: Microsoft Edge 신경망 TTS (ko-KR-HyunsuMultilingualNeural)
- 폰트: Archivo Black, League Gothic, Space Mono, Noto Sans KR (Google Fonts)

※ 비공식 팬메이드/포트폴리오 작업물입니다. Pepsi는 PepsiCo, Inc.의 상표입니다.
