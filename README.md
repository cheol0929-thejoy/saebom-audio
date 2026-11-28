# saebom-audio

새봄묵상 음성 파일 저장소 (GitHub Pages). 페이지는 이 주소로 재생한다:
https://cheol0929-thejoy.github.io/saebom-audio/<연도>/<YYYY-MM-DD>_<pastor|f|m>.mp3

- pastor = 신철 목사 녹음 · f / m = 페이지가 내놓는 AI 낭독(여/남) — 목사님 녹음이 없는 날 전부 + 녹음이 있어도 페이지가 여/남 버튼을 주는 날(2026-11-16, 11-19)
- 파일은 덮어쓰지 않는다. 같은 날 녹음을 바꾸면 새 이름(_v2)으로 올린다.
- SHA256SUMS = 로컬 원본(마스터)과 같은 값. manifest.json = 페이지 경로(audio/...) → 이 저장소 경로.
- 2026-11-27 이전 새봄묵상 음성은 2026-11-29 오너 지시로 내렸다.

## 연 단위 교체 규칙 (rotation)
- GitHub Pages 게시 사이트는 1 GB 를 넘을 수 없다 (docs.github.com, "GitHub Pages limits").
- 한 저장소 = 한 해. 2026년 파일은 이 저장소(saebom-audio)에 둔다. 2027-01-01 부터는 새 저장소 saebom-audio-2027 에 올리고, 이 저장소는 그대로 둔다(지난 주소가 계속 재생되도록 지우지 않는다).
- 실측 크기: 목사님 녹음 평균 약 4.6 MB/일 → 매일 녹음이면 1년 약 1.6~1.7 GB 로 1 GB 를 넘는다. 그래서 저장소 크기가 800 MB 에 닿으면 그 해 안에서도 다음 저장소(saebom-audio-<연도>b)로 넘긴다.
- 로컬 원본: Charles Jarvis\새봄묵상_백업 (목사님녹음 · artifact_YYYY-MM-DD\audio). 이 저장소는 사본이다.
