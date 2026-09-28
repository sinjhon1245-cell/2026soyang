# 한마음 가을 운동회 웹 안내장

인천소양초등학교 · 2026년 9월 30일(수)

## 미리 보기

`index.html`을 브라우저로 열면 됩니다. 설치나 빌드 없이 작동합니다.
안내장 2쪽이 바로 표시됩니다. 이미지를 누르면 원본 크기의 PNG가 열립니다.
각 이미지 아래의 이미지 저장 버튼으로 고해상도 PNG를 다운로드할 수 있습니다.
휴대폰에서 이미지가 열리면 길게 눌러 저장하세요.
휴대폰에서는 두 손가락으로 확대하고, 뒤로가기로 안내장에 돌아올 수 있습니다.

## GitHub Pages에 올리기

1. ZIP을 압축 해제합니다.
2. GitHub 저장소에 **이 폴더 안의 내용물**을 올립니다. 저장소의 맨 위에 `index.html`이 있어야 합니다. ZIP 자체를 업로드하지 마세요.
3. 저장소의 `Settings → Pages`로 이동합니다.
4. `Source`를 `Deploy from a branch`로 설정합니다.
5. 올린 브랜치(보통 `main`)와 `/(root)`를 선택하고 `Save`를 누릅니다.
6. 배포 완료 후 Pages 설정에 표시된 사이트 주소를 공유합니다.

공식 안내: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 파일 구성

```text
index.html                 웹 안내장
.nojekyll                  정적 파일 배포 설정
assets/
  page-1.webp              1쪽 고해상도 WebP
  page-2.webp              2쪽 고해상도 WebP
  page-1-small.webp        1쪽 모바일용 WebP
  page-2-small.webp        2쪽 모바일용 WebP
  page-1.png               1쪽 확대용 PNG
  page-2.png               2쪽 확대용 PNG
README.md                  사용 및 배포 안내
```

PNG와 고해상도 WebP는 1698 × 2400px입니다. 원본의 비율과 내용은 유지했습니다.
화면 크기에 맞는 WebP를 우선 사용하고, 지원하지 않는 브라우저에서는 PNG를 표시합니다.
외부 폰트, 외부 라이브러리, 별도 서버 및 JavaScript가 필요하지 않습니다.
모든 파일 경로가 상대 경로이므로 GitHub Pages의 하위 경로에서도 동작합니다.

이 패키지는 배포용 파일이며, 아직 온라인에 게시된 상태는 아닙니다.
