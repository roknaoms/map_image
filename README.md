# 한국사이버리터러시저널 홈페이지

한국사이버리터러시저널(KCLI) 정적 홈페이지 배포 저장소입니다.

## 배포 방식

- 사이트 파일: 저장소 루트의 `index.html`
- 배포 대상: GitHub Pages
- 임시 접속 URL: `https://roknaoms.github.io/map_image/`
- 커스텀 도메인: `http://www.kcli.ai.kr`
- 빌드 도구: 사용하지 않음

이 저장소는 `.github/workflows/deploy-pages.yml` 워크플로를 통해 루트 정적 파일을 GitHub Pages로 업로드하도록 구성합니다. 저장소 Settings > Pages에서 배포 소스가 GitHub Actions로 설정되어 있는지 확인하세요.

## 커스텀 도메인 DNS 안내

도메인 관리 화면에서 다음 DNS 레코드를 설정합니다.

| 이름 | 유형 | 값 |
| --- | --- | --- |
| `www` | `CNAME` | `roknaoms.github.io` |

DNS 전파 후 GitHub 저장소 Settings > Pages의 Custom domain에 `www.kcli.ai.kr`를 입력하고 저장합니다. HTTPS 적용은 GitHub Pages에서 DNS 확인이 끝난 뒤 Enforce HTTPS를 활성화합니다.

루트 도메인 `kcli.ai.kr`도 함께 연결하려면 도메인 제공자의 DNS 정책에 따라 GitHub Pages용 `A` 레코드 또는 `ALIAS/ANAME` 설정이 추가로 필요합니다. 현재 요청 범위의 공식 커스텀 도메인은 `www.kcli.ai.kr`입니다.

## 홈페이지 표시 정보

- 제호: 한국사이버리터러시저널
- 홈페이지: `http://www.kcli.ai.kr`
- 발행소: 서울특별시 금천구 디지털로 178 가산 퍼블릭 A동 1031호
- 발행인: 오명섭
- 편집인: 오명섭
- 발행형태: 무가

등록번호와 등록일은 등록 전까지 `등록 후 기재` 상태로 유지합니다.
