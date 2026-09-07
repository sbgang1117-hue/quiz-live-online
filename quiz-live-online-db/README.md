# QUIZ LIVE ONLINE — DB edition

## 온라인 배포
GitHub에 이 폴더를 올리고 Render Web Service로 연결하세요.
Build Command: `npm install`
Start Command: `npm start`
Environment Variable: `DATABASE_URL` = PostgreSQL 연결 문자열

DB가 연결되면 퀴즈는 PostgreSQL에 영구 저장됩니다. DATABASE_URL이 없으면 로컬의 data/quizzes.json을 사용합니다.


## v6 업그레이드
- 게임 HUD 및 모바일 대응 강화
- 문제 시작 3-2-1 카운트다운 연출
- 제한시간 5초 이하 긴급 타이머 연출 및 효과음
- 정답 선택/결과/최종 우승자 화면 애니메이션
- 최종 결과 우승자 강조 및 전체 순위 화면
- 음악 업로드: 파일당 최대 20MB (MP3/WAV/M4A/OGG 등)
- 서버에서도 음악 파일 크기 검증
- 대용량 음악 때문에 브라우저 localStorage가 넘치는 문제 방지
- 기존 O/X, 주관식 다중 정답, 순서 맞추기, 재접속, 실시간 주최자 답안 현황 등 기존 기능 유지
