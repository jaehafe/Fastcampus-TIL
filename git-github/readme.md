# git & github

---

[reference](https://freeprog.tistory.com/254)

### Mac Terminal

`~` (tiled)지금 로그인 한 사용자가 비밀번호 없이 사용할 수 있는 최상위 폴더

`pwd` print working directory

CLI(Command Line Interface)

GUI(Graphic User Interface)

`ls` list segment

`ls -a` list all

`cd` change directory

`mkdir` make directory

`cp -r ~/Documents/dev/readme.md ~/Desktop`

⇒ `~/Documents/dev/readme.md` 를 `~/Desktop`로 copy

`cp -r ~/Documents/dev/readme.md ~/Desktop`

`mv [readme.md](http://readme.md) ./README.txt` : rename from [`readme.md`](http://readme.md) to `README.txt`

⇒ 현재 폴더의 [`readme.md`](http://readme.md) 파일을

`rm server.*` server라는 이름의 확장자 모두 삭제

`rm -r public` recursion 디렉토리와 파일 모두 삭제

---

### VIM

`vi [learn-md.md](http://learn-md.md)` : vi로 파일 열기

→ I: —Insert—

#Let’s learn Markdown

VIM은 파일의 첫 상태를 기억하고 있다.

`esc`

`:q`

`E37: No write since last change (add ! to override)`

`:wq` 저장을 하고 나감

---

### Mac Terminal

`cat [learn-md.md](http://learn-md.md)`

⇒ 안에 있는 내용물을 보여줌

---

### Mark Down

## Links

[link text](http://dev.nodeca.com/)

[link with title](http://nodeca.github.io/pica/demo/)

## Images

![https://octodex.github.com/images/minion.png](https://octodex.github.com/images/minion.png)

![https://octodex.github.com/images/stormtroopocat.jpg](https://octodex.github.com/images/stormtroopocat.jpg)

## Code

Inline `code`

Indented code

```
// Some comments
line 1 of code
line 2 of code
line 3 of code

```

Block code "fences"

```
Sample text here...

```

Syntax highlighting

```
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));

```

**More Markdown is refers to here [Markdown](https://markdown-it.github.io/)**

---

github: git에 기반한 클라우드

Mac Terminal

`cd ~` 어느 dir에 있든 `~` dir로 이동됨

git

`git config —list`

![스크린샷 2022-12-13 오후 1.26.28.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0f644517-f327-4ec0-b0c3-8f5e95cf88a5/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2022-12-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_1.26.28.png)

`vi ~/ .gitconfig` : 수정

`git config —global —unset [user.email](http://user.email)` : 리셋

git config —global [user.email](http://user.email) “이메일”

lg alias 설정

`git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --”`

`git lg`, `git log` 차이

`git lg`

![스크린샷 2022-12-13 오후 1.40.55.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/42a4e8fa-b239-4892-bce4-11309c5cf65e/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2022-12-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_1.40.55.png)

`git log`

![스크린샷 2022-12-13 오후 2.01.47.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/53faf5a0-7345-4a13-94de-3b7d9225db1b/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2022-12-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_2.01.47.png)

`git clone <깃헙 repo 주소>`

`git add .`

`git commit`

i → insert 모드로 변경 후

제목과 내용 변경

![스크린샷 2022-12-13 오후 2.04.49.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1b878a75-1646-4e3d-a70c-ccde8b5aa667/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2022-12-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_2.04.49.png)

`esc` switch to normal

`:wq`

![스크린샷 2022-12-13 오후 2.07.25.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6f1eaac0-e223-4dc9-90d1-175b93dc1587/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2022-12-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_2.07.25.png)

`git lg`

![스크린샷 2022-12-13 오후 2.07.43.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/25940c51-da45-4615-84ff-e9a2b24bea77/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2022-12-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_2.07.43.png)

---

`vi [README.md](http://README.md)` : 리드미 파일을 vi로 열어서 작업

normal mode에서 `o`

![스크린샷 2022-12-13 오후 2.13.24.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/69e378bd-cc64-4c7f-b346-87233ae344b4/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2022-12-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_2.13.24.png)

[Readme.md](http://Readme.md) 파일 작성법

![스크린샷 2022-12-13 오후 2.14.43.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6a4a282a-4292-4927-9564-abecd48ff076/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2022-12-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_2.14.43.png)

`git add [README.md](http://README.md)` → `git status` 입력하고 제대로 됐는지 확인

`git commit` → VI 모드

`I`: switch to Insert 모드 → commit 제목과 내용 입력 후

`esc`: switch to normal mode

`git status`

`git push origin main`

![스크린샷 2022-12-13 오후 2.38.16.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/36f6da35-e25f-4db9-8437-67de3b1487c7/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2022-12-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_2.38.16.png)

- git add 취소 / stage 된 파일 취소 방법
  `git reset HEAD <파일 이름>`
- git commit 취소 방법
  `git log` commit 목록을 우선 확인 후
  `git reset HEAD^` commit 을 취소하고 해당 파일을 unstaged 상태로working dir에 보존

**git convention**

angular 참조

![스크린샷 2022-12-13 오후 3.21.31.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/81787acb-f82f-4150-b443-db0deaf15311/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2022-12-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_3.21.31.png)

`git lg`

![스크린샷 2022-12-13 오후 4.12.29.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/db8e9b9b-c6d0-4cde-bc90-6184d87f76d9/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2022-12-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_4.12.29.png)

HEAD: 가장 최신

`git remote add origin main`: repo주소 추가

`git remote remove origin`: repo 주소 제거

`git remote add origin <깃헙repository주소>` : 깃헙 이름을 origin으로 정함
