# Git Flow 정리 (조금 자세하게)

## 1. Git Flow란?
- Git 브랜치를 체계적으로 나눠서 개발하는 전략
- 협업할 때 충돌을 줄이고, 배포를 안정적으로 관리하는 방식

---

## 2. 핵심 브랜치 구조

### main (또는 master)
- 실제 배포용
- 항상 안정된 코드만 존재

### develop
- 다음 버전 개발 통합 브랜치
- 기능들이 합쳐지는 중심 공간

---

## 3. 보조 브랜치

### feature
- 새 기능 개발용
- 예: `feature/login`, `feature/signup`
- 작업 후 develop에 merge

```bash
git checkout -b feature/login
```
---
## release
- 배포 직전 테스트/수정용
- develop -> release -> main으로 이동
---
## hotfix
- 배포된 main에서 긴급 수정
- 버그 발생 시 바로 수정
---
## 4. 전체 흐름
## 기능 개발 흐름
main → develop → feature → develop → release → main
## 긴급 수정 흐름
main → hotfix → main + develop
---
## 5. 작업 순서 
1) 새 기능 시작
- git checkout develop
- git checkout -b feature/기능명
2) 작업 후 저장
- git add .
- git commit -m "기능 추가"
3) develop으로 병합
- git checkout develop
- git merge feature/기능명
4) 배포 준비
- git checkout -b release/v1.0
5) 최종 배포
- git checkout main
- git merge release/v1.0
---
## 6. 핵심 요약
- main: 배포용
- develop: 개발 중심
- feature: 기능 개발
- release: 배포 준비
- hotfix: 긴급 수정
---
## 7. 한 줄 이해

기능은 feature에서 만들고, develop에 모아서, release 거쳐 main으로 감