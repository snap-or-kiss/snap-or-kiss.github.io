# snap-or-kiss.github.io

`https://snap-or-kiss.github.io/` 로 게임을 서빙하는 저장소다.

- 게임 본체는 [snap-or-kiss/frontend](https://github.com/snap-or-kiss/frontend)의 `main`이다. 거기서 개발한다.
- 이 저장소의 `index.html`은 10분마다(그리고 수동 실행 시) frontend의 `index.html`을 복사해 커밋한다. 직접 고치지 않는다.
- 바로 반영하려면 Actions 탭에서 "Sync game from frontend"를 Run workflow 한다.
