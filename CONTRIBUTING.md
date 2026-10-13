# 개발·기여 진행

작업은 Issue에서 목표·스펙 ID·파일 범위·의존성·완료 기준을 정한다. 브랜치는 codex/<작업> 또는 feat/<작업> 등 구체적인 이름을 사용한다. PR은 사용자에게 달라지는 동작과 검증 결과부터 설명한다.

변경으로 제품 계약이 바뀌면 docs의 스펙/ADR PR을 링크한다. 데이터 PR에는 추가·변경·삭제 수, 출처, 정정 이유와 기존 ID 영향을 적는다. 제목/가수만 바꾼 콘텐츠 대량 생성은 하지 않는다.

통합 시 최신 main과 충돌을 확인하고 필요한 검증만 실행한다. 운영 배포 권한은 이미 위임돼 있으며 재확인을 기본 요구하지 않는다. 단, 현재 저장소와 Cloudflare의 실제 연결 및 자동 운영 배포 여부를 먼저 확인하고 미리보기·복구 기준을 만족해야 한다.

릴리스에는 소스 SHA·데이터 스냅샷·배포 ID·검증 결과·이전 정상 버전을 남긴다. 완료 상태는 merged/verified/shipped를 구분한다.

[제품 문서](https://github.com/jpop-today/docs) · [검증 기준](https://github.com/jpop-today/docs/blob/main/engineering/harness.md)
