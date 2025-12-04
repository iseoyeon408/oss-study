🔹 1. Git이란?

Git은 소스 코드의 변경 이력을 관리하는 **분산 버전 관리 시스템(DVCS)**입니다.

✔ 주요 특징

분산형: 각 개발자 컴퓨터에 전체 저장소 기록 보관

버전 관리: 코드 변경 이력 추적

브랜치/병합(Merge): 다양한 기능을 독립적으로 개발하고 쉽게 통합

속도 빠름: 로컬 저장소 기반으로 대부분의 작업 처리

🔹 2. Git 기본 개념
✔ 저장소(Repository)

로컬 저장소: 개인 컴퓨터에 있는 저장소

원격 저장소: GitHub 등 서버에 있는 저장소

✔ 영역 구성

Working Directory(작업 공간)

Staging Area(임시 저장 공간)

Repository(저장소)

✔ Git 기본 명령어
명령어	설명
git init	새 Git 저장소 생성
git clone URL	원격 저장소 복제
git add 파일명	변경사항을 스테이징
git commit -m "메시지"	저장소에 기록
git status	저장소 상태 확인
git log	커밋 이력 조회
git push	로컬 → 원격 저장소 업로드
git pull	원격 → 로컬 저장소 업데이트
git branch	브랜치 목록/생성
git merge	브랜치 병합
🔹 3. GitHub이란?

GitHub은 Git 저장소를 서버에 관리할 수 있는 클라우드 협업 플랫폼입니다.

✔ 주요 기능

원격 저장소 관리

Pull Request(PR)

Issue로 작업/버그 관리

Fork & Star

Actions(CI/CD 자동화)

🔹 4. 브랜치(Branch) 전략
✔ 브랜치란?

코드의 독립적인 작업 공간. 새로운 기능 개발, 버그 수정 등에 사용.

✔ 대표 브랜치 전략

Git Flow

main / develop / feature/* / release / hotfix

GitHub Flow

main + feature 브랜치, PR 기반

Trunk-Based Development

최소한의 브랜치, 자주 병합

🔹 5. Pull Request(PR)

GitHub에서 협업 시 핵심 기능.

✔ PR의 목적

코드리뷰 받기

팀원 간 승인 과정

테스트 자동화 연결 가능

✔ PR workflow

브랜치 생성

작업 후 커밋

GitHub에 push

PR 생성

코드리뷰

Merge

🔹 6. 협업 Workflow
✔ 일반적인 협업 과정

저장소 Fork 또는 Clone

기능 브랜치 생성

코드 작성 & 커밋

원격 브랜치 push

Pull Request 생성

리뷰 및 수정

병합 후 브랜치 삭제

🔹 7. 오픈소스 참여 절차

관심 프로젝트 찾기

Issue 확인

로컬 환경 설정

Fork → clone

기능 개발

PR 제출

Maintainer의 리뷰 반영

🔹 8. Git & GitHub에서 자주 발생하는 문제들
문제	원인	해결 방법
충돌(conflict)	다른 브랜치와 수정 부분이 겹침	수동으로 수정 후 commit
push 거부	원격에 새 커밋이 있음	git pull --rebase 후 push
PR 자동 merge 실패	충돌 존재	충돌 해결 후 다시 push
