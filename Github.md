### Git hub

#### 준비사항

* Github에 비어있는 저장소를 만든다.

#### 기초 명령어

##### 1. 원격저장소 설정

```bash
$ git remote add origin __url__
```

* 깃, 원격저장소를(remote)추가해줘 origin이라는 이름으로 URL!
* 설정된 원격저장소를 확인하기 위해서는 아래의 명령어를 입력한다.

```bash
$ git remote -v
```

* 설정된 원격저장소를 지우기 위해서는 아래의 명령어를 입력한다.

```bash
$ git remote rm __이름__
```

* 원격 저장소 추가하기

```bash
$ git remote add __저장소이름__ __url__
```

##### 2. 내보내기

```bash
$ git push origin master
```

##### 3. 작업순서

로컬 저장소 설정

git init - git 파일 생성

이후 작업 기본틀

git add

git commit -m '커밋메세지'

git status

git push origin master



#### 기타사항

* 기존 commit된 파일들을 다시 commit하려면 파일에 변경사항이 있어야 가능하다.
* 온라인으로 깃 로그기록  확인

```bash
$ git log --oneline
```

* commit을 하고 업로드 하면 github에서 해당 commit의 수정, 변경, 추가 내용들을 확인할 수 있다.

[커밋](https://djkeh.github.io/articles/How-to-write-a-git-commit-message-kor/)

[깃허브 특강](http://bit.ly/aiserviceb )

[좋은 메세지를 위한 영어사전](https://blog.ull.im/engineering/2019/03/10/logs-on-git.html)