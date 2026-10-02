# LivingThings

여행 항공권 비교 HTML을 제공하는 정적 사이트입니다.

## Vercel 배포

1. HTML과 설정 파일을 Git 저장소에 커밋하고 push합니다.
2. Vercel에서 **Add New → Project**로 이 Git 저장소를 Import합니다.
3. **Root Directory**는 저장소 루트(`.`)로 지정합니다.
4. **Deploy**를 실행합니다.

`vercel.json`에서 Framework를 Other로 설정하고 설치 및 빌드 단계를 생략합니다.
배포 결과물 디렉터리는 저장소 루트이며, `/` 요청은
`travel-flight-comparison-2026-2027.html`로 연결됩니다.
별도 환경 변수는 필요하지 않습니다.

이후 HTML을 수정하고 Vercel에 연결된 브랜치로 push하면 자동 재배포됩니다.

설정 참고: https://vercel.com/docs/project-configuration/vercel-json
