# 조선의 하루

조선시대 신분제를 소재로 한 모바일 미니게임 MVP입니다.

## GitHub Pages 배포

1. GitHub에서 새 Repository를 만듭니다.
   - 예: `joseon-day`
   - Public으로 설정
2. 이 폴더의 `index.html`을 Repository 최상위에 업로드합니다.
3. GitHub Repository에서:
   `Settings` → `Pages`
4. `Build and deployment`에서:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Save를 누릅니다.
6. 잠시 후 GitHub가 제공하는 Pages 주소로 접속합니다.

예상 주소:
`https://사용자이름.github.io/joseon-day/`

## 구조

joseon-day/
├── index.html
├── assets/
└── README.md

현재 MVP는 외부 서버나 데이터베이스가 필요 없는 단일 HTML 게임입니다.
