# git command

git 기본 명령어 정리
---
- git 을 사용 하는 이유
- 분산 버전 관리 시스템
- 기능 단위 기능 변화량의 병렬적 버전 관리를 위해

---

```bash
터미널 명령어
```

# status
상태표시

```bash
git status
```
현재 git 상태를 표시

## init
.git 생성
```bash
git init
```
- 현재 위치에 `.git` 폴더를 생성

## add
working directory => staging area

```bash
git add .
```
- 지금 폴더의 것을 다 올린다 (지정도 가능하지만 지금은 다올림)

## commit
staging area => .git directory


```bash
git commit
```
- .git에 보내기
(메시지 입력 단계가 있음)
(일반적으로 변화사항에 대한 메모)
staging area에 올라간 내용을 스냅샷 찍기

```bash
git commit -m "메시지 내용"
```
- 메시지 단계를 축약 할 수 있음


