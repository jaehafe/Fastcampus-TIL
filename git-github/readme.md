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

`esc` 현재 상태 빠져나오기

`:q` quit

`E37: No write since last change (add ! to override)`
라는 문장은 변동 사항이 있고 저장을 안했다는 뜻

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
