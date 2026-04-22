# Git 한눈에 정리

## 개념
- **Git**: 버전 관리 시스템
- **Repository**: 저장소
- **Commit**: 변경 기록 저장
- **Branch**: 작업 분기

## 기본 흐름

add → commit → push


## 주요 명령어
```bash
git init              # 저장소 생성
git clone URL         # 복제

git add .             # 변경 추가
git commit -m "메시지" # 저장

git push origin main  # 업로드
git pull origin main  # 가져오기

git status            # 상태 확인
git log               # 기록 확인