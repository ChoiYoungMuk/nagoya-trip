# 나고야 가족여행 GitHub Pages 버전

## 파일 구성

- `index.html` 하나만 있으면 동작합니다.
- 외부 DB/서버가 필요 없습니다.
- 일정 데이터는 방문자 각자의 브라우저 localStorage에 저장됩니다.

## GitHub Pages 배포

1. 이 폴더의 `index.html`을 repository 루트에 업로드
2. GitHub repository에서 `Settings`
3. 왼쪽 메뉴 `Pages`
4. `Build and deployment`
5. Source: `Deploy from a branch`
6. Branch: `main`
7. Folder: `/root`
8. Save

잠시 후 아래 형태의 주소가 생깁니다.

```text
https://계정명.github.io/repository명/
```

## 주의

정적 웹사이트이므로 모두가 같은 데이터를 실시간으로 공유하지는 않습니다.
가족 A가 추가한 일정은 가족 A의 브라우저에만 저장됩니다.

공통 수정본이 필요하면 다음 중 하나로 확장하세요.

- Google Sheets 연동
- Firebase
- Supabase
- Flask + SQLite 서버
