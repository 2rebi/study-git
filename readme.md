# Hello Git World

## git의 주요 개념
- 작업 디렉토리 (Working Directory) : 프로젝트 루트
- 준비 영역 (Staging Area, Stage/Index) : 파일 트랙킹 하기위한 준비
- 로컬 저장소 (Local Repository) : 로컬 영역에 파일 버저닝
- 원격 저장소 (Remote Repository) : 깃헙, 깃랩, 빗버킷등 원격지에 파일 버저닝

## 기본 명령어
- git init : 로컬 저장소 생성
- git status : 변화 상태
- git add : 파일 스테이지 올리기
- git commit : 버전 기록
- git log : 버전 기록 리스트
- git reset --hard : 커밋 헤드로 모든 파일 원복.
- git rm --cached : 커밋 스테이지에서 내리기.

## 제외목록 설정
- [.gitignore 파일](https://git-scm.com/docs/gitignore#_pattern_format)
- [추천 사이트](https://www.gitignore.io/)

## 원격 저장소
- 목록보기 : git remote -v 
- 추가하기 : git remote add [별칭] [주소]
- 삭제하기 : git remote rm [별칭]
- 별칭수정 : git remote rename [기존별칭] [새 별칭]
- 주소수정 : git remote set-url [별칭] [변경할주소]

## 브랜치
- 목록보기 : git branch
- 생성하기 : git branch [새 브랜치명] 또는 git branch [복사할 브랜치명] [새 브랜치명]
- 삭제하기 : git branch -d [브랜치명] 
- 이름변경(이동) : git branch -m [기존 브랜치명] [새 브랜치명]
- 전환하기 : git checkout [브랜치명]