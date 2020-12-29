

## git 기초

분산버전관리시스템(DVCS)

## 0. 로컬 저장소 설정

```bash
$ git init
Initialized empty Git repository in C:/Users/fkdle/.git/
fkdle@LAPTOP-NJPBHVKS MINGW64 ~ (master)
$
```

### 기본 작업 흐름

1. add

* add 이전과 이후

```bash
$ touch a.txt
$ git status
on branch master
```

```bash
$ git add .
$ git status
On branch master

No commits yet
# 커밋이 될 변경사항
# 두번째 통에 있는 애들
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   a.txt
```

2. commit

```bash
$ git commit -m 'first commit'
[master (root-commit) 7cc7787] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 a.txt
```

* `commit`은 지금 상태를 스냅샷을 찍는다

* 커밋 메시지는 지금 기록하는 이력을 충분히 잘 나타낼 수 있도록 작성한다.
* `git log`명령어를 통해 지금까지 기록된 커밋들을 확인할 수 있다.

## 기타 명령어

### 1.status

로컬 저장소의 상태

```bash
$ git status
```

### 2. log

커밋 히스토리

```bash
$ git log
commit 7cc7787329a4612edf50dfc1d5f87c749b5045cb (HEAD -> master)
Author: sungsu <fkdleks12@naver.com>
Date:   Tue Dec 29 14:10:57 2020 +0900

    first commit
```

staging area를 사용함으로써, 파일들 각각 버전을 만들어 따로 관리 할수 있다 때문에 staging area를 사용한다.

 



