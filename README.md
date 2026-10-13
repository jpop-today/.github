# jpop.today 운영 기반

[제품 소스](https://github.com/jpop-today/jpoptoday) · [스펙·설계·운영 문서](https://github.com/jpop-today/docs) · [운영 사이트](https://jpop.today)

## 이 저장소

조직 공통 개발 규칙, PR·작업 템플릿, 협업·배포 기준을 관리한다.

- [AGENTS.md](AGENTS.md)
- [CONTRIBUTING.md](CONTRIBUTING.md)
- [SECURITY.md](SECURITY.md)
- [.github/PULL_REQUEST_TEMPLATE.md](.github/PULL_REQUEST_TEMPLATE.md)
- [.github/ISSUE_TEMPLATE/task.yml](.github/ISSUE_TEMPLATE/task.yml)
- [다중 스레드 협업과 인계](https://github.com/jpop-today/docs/blob/main/operations/collaboration.md)
- [검증 하네스](https://github.com/jpop-today/docs/blob/main/engineering/harness.md)

| 저장소 | 관리 대상 |
| --- | --- |
| `.github` | 조직 운영 규칙·기여 안내·작업/PR 템플릿 |
| `docs` | 제품 스펙·ADR·검증 기준·진행과 운영 기록 |
| `jpoptoday` | 앱·데이터 처리·테스트·CI·배포 구성 |

2026-10-13 GitHub API로 이 저장소가 public임을 재확인했다. 조직 홈 소개는 루트 README가 아니라 [profile/README.md](profile/README.md)를 사용한다. 공통 커뮤니티 파일은 GitHub의 적용 조건을 따르며, 에이전트 규칙과 실행 workflow는 각 저장소에 명시적으로 둔다. GitHub Actions workflow는 실제 소스 저장소에서 실행한다.

목표는 신뢰 가능한 JPOP 노래방 검색과 고유 콘텐츠를 갖추고 AdSense 심사를 준비하는 것이다. 제품·데이터·운영 사실은 증거로 기록한다.

사용자는 일상 수정·검증·통합·배포와 여러 스레드의 협업을 위임했다. 작업마다 스펙 ID·기준 SHA·파일 담당·완료 기준을 남기고, 검증·병합·미리보기·운영 배포·AdSense 심사 상태를 구분한다. 현재 소스 이관·배포 진행 사실은 docs의 운영 기록에서 확인한다.
