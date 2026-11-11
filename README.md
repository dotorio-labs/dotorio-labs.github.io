# dotorio.com

Dotorio Labs 앱 소개, 개인정보처리방침, 앱 원격 설정, AdMob `app-ads.txt` 를 담는 정적 사이트 (GitHub Pages, 빌드 없음).

| 경로 | 내용 |
| --- | --- |
| `/` | 앱 목록 |
| `/apps/<앱>/` | 앱 소개·웹 앱 (요격왕, LyricSync) |
| `/privacy/<앱>.html` | 개인정보처리방침 — 스토어 등록 URL |
| `/config/<앱>/*.json` | 앱이 받아가는 원격 데이터 (세율, 명절 일정, 단어 목록 등) |
| `/app-ads.txt` | AdMob 판매자 인증. 스토어의 개발자 웹사이트를 `https://dotorio.com` 으로 둔다 |

`/apps/` 는 `/` 로 넘어간다. 예전 주소 `portfolio.dotorio.com/{apps,privacy}` 는 이쪽으로 넘겨준다.
`portfolio.dotorio.com/config/*` 는 이미 설치된 앱 버전이 쓰므로, 모든 앱이 새 주소로 업데이트될 때까지 그대로 둔다.
