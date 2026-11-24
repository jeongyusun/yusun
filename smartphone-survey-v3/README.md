# 2030 스마트폰 브랜드 조사 (v3)

설문 및 관리자 분석 도구. 실제 응답은 Vercel private Blob에 저장하며 GitHub에는 포함하지 않습니다.

- 설문: https://sogang-smartphone-survey-v3.vercel.app/
- 관리자: https://sogang-smartphone-survey-v3.vercel.app/admin
- 팀원별 링크: `?team=1` ~ `?team=4`
- 검토용: `?test=1`

Vercel에서 비공개 Blob 저장소를 연결하고 `BLOB_READ_WRITE_TOKEN`, `SURVEY_ADMIN_KEY` 환경 변수를 설정해야 합니다. GitHub Pages는 서버 API를 실행하지 않으므로 실제 응답 수집에는 Vercel 배포가 필요합니다.
