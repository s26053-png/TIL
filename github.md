# GitHub 한눈에 정리

## 개념
- **GitHub**: Git 저장소를 온라인으로 관리하는 서비스
- **원격 저장소(Remote Repo)**: 인터넷에 있는 저장소
- **로컬 저장소(Local Repo)**: 내 컴퓨터 저장소

---

## 핵심 역할
- 코드 백업
- 협업 (여러 사람 동시에 작업)
- 버전 관리 공유

---

## 기본 흐름

git push → GitHub 업로드
git pull → GitHub에서 가져오기

---

## 주요 명령어
```bash
git remote add origin URL   # GitHub 연결
git push origin main        # 업로드
git pull origin main        # 다운로드/병합
git clone URL               # GitHub 저장소 복제
```
---
## 협업 핵심
- push: 내 코드 올리기
- pull: 다른 사람 코드 가져오기
- clone: 처음 복사
- fork: 남의 저장소 내 계정으로 복사 (오픈소스)
---
## Git vs GitHub
- Git: 버전 관리 프로그램
- GitHub: Git을 온라인으로 쓰게 해주는 플랫폼