# CNN 합성곱 시뮬레이터

이미지가 숫자가 되고, 필터를 지나 특징이 되기까지 — CNN(Convolutional Neural Network)의 동작 원리를 단계별로 시각화하는 교육용 웹 시뮬레이터입니다.

## 배포 (Deploy)

단일 HTML 파일이므로 별도 빌드 과정 없이 정적 호스팅으로 바로 배포됩니다.

### GitHub Pages
1. 이 저장소를 GitHub에 push
2. **Settings → Pages → Source**를 `main` 브랜치 / `/ (root)`로 설정
3. `https://<사용자명>.github.io/<저장소명>/` 에서 접속

### Netlify
1. Netlify에서 **Add new site → Import an existing project**로 이 저장소 연결
2. Build command 없음, Publish directory는 `/` (root)
3. 자동 배포 완료

## 파일 구조

- `index.html` — 시뮬레이터 본체 (모든 스타일·스크립트 포함)
- `README.md` — 이 문서

## 라이선스

교육용으로 자유롭게 사용 가능합니다.
