# cheonyeon0316.github.io

GitHub Pages 허브입니다. 이 저장소의 `site/` 아래에 정적 프로젝트를 추가하면 한 사이트에서 공개할 수 있습니다.

## 프로젝트 추가

1. `site/projects/<project-slug>/` 폴더를 만들고 그 안에 `index.html`을 둡니다.
2. `site/index.html`에 프로젝트 링크를 추가합니다.
3. `main` 브랜치에 푸시하면 GitHub Actions가 사이트 전체를 배포합니다.

프로젝트 주소는 `https://cheonyeon0316.github.io/projects/<project-slug>/` 형태입니다.

## 배포

`.github/workflows/pages.yml`이 `site/`를 GitHub Pages로 배포합니다. 저장소를 만든 뒤 Settings → Pages → Build and deployment에서 Source를 **GitHub Actions**로 설정해야 합니다. 워크플로가 최초 실행되면 사이트가 공개됩니다.

