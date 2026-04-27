# Developer Portfolio for GitHub Pages

정적 HTML/CSS로 만든 개발자 포트폴리오 템플릿입니다. 별도 빌드 없이 GitHub Pages에서 바로 배포할 수 있습니다.

## 파일 구성

- `index.html`: 포트폴리오 콘텐츠와 섹션 구조
- `styles.css`: 반응형 레이아웃과 시각 스타일

## 수정할 TODO

`index.html`에서 `TODO`로 표시된 값을 실제 정보로 교체하세요.

- 이름과 직무 소개
- 이메일 주소
- GitHub, LinkedIn, 블로그 링크
- 기술 스택
- 대표 프로젝트 3개
- 경력, 활동, 교육 이력

## 로컬 미리보기

브라우저에서 `index.html`을 직접 열면 됩니다. 간단한 로컬 서버가 필요하면 아래 명령을 사용할 수 있습니다.

```bash
python3 -m http.server 8000
```

이후 `http://localhost:8000`에서 확인합니다.

## GitHub Pages 배포

1. 변경 사항을 GitHub 저장소에 push합니다.
2. GitHub 저장소의 `Settings`로 이동합니다.
3. `Pages` 메뉴에서 배포 소스를 `Deploy from a branch`로 선택합니다.
4. 브랜치는 `main`, 폴더는 `/root`를 선택합니다.
5. 저장 후 표시되는 GitHub Pages URL에서 사이트를 확인합니다.
