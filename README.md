# portfolio

순수 HTML/CSS/JS로 만든 개인 포트폴리오. 빌드 도구 없이 GitHub Pages로 바로 배포합니다.

## 구조

```
index.html      메인 페이지 (소개, 기술, 프로젝트, 경력, 연락처)
css/style.css   스타일 (라이트/다크 모드 자동 대응)
js/script.js    모바일 메뉴 토글, 연도 자동 표시
assets/         이력서 PDF, 이미지 등
```

## 콘텐츠 채우기

`index.html`에서 `[대괄호]`로 표시된 부분과 이름/링크(GitHub, LinkedIn, email)를 실제 내용으로 교체하세요.
이력서 PDF는 `assets/resume.pdf`로 넣으면 "이력서 다운로드" 버튼이 바로 동작합니다.

## GitHub Pages 배포

1. 이 저장소를 GitHub에 push
2. 저장소 Settings → Pages → Source에서 `main` 브랜치, `/ (root)` 선택 후 저장
3. 몇 분 후 `https://<username>.github.io/<repo>` 에서 확인 가능

로컬 미리보기: `index.html`을 브라우저로 열거나 `python3 -m http.server` 실행 후 접속.
