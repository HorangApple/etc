# Jupyter notebook

python은 data science에 강한 데 이때 많이 사용하는 툴이 Jupyter notebook이다.

### Jupyter notebook 설치

```
$ pip install jupyter
```

### 추가 확장 프로그램 설치

> 확장 프로그램은 [링크](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/index.html)를 통해 확인 가능하다.
>
> 일부 확장 프로그램은 pip 추가 설치 해야하는 경우도 있다.

(1) pip를 통한 패키지 설치

```
$ pip install jupyter_contrib_nbextensions
```

(2) JS, CSS 파일 설치

```
$ jupyter contrib nbextension install --user
```

(3) 확장프로그램 목록 확인

<http://localhost:8888/nbextensions>

- 사용중인 확장 프로그램
  - Table of Contents (필수)


### 사용법
cf. V현재 폴더에서 VS Code를 열고 싶으면 `code .`을 입력한다.

해당폴더에서 커맨드 창에 `jupyter notebook`을 입력하면 브라우저가 떠서 작동이 된다.

<img src="images/image 001j.png">

`alt+enter`이나 `shift+enter` 누르면 컴파일 후 새 cell이 생성된다. jupyter notebook은 컴파일 되는 일종의 노트라고 할 수 있다.

<img src="images/image 002j.png">

이외에도 `ctrl+enter`를 누르면 컴파일만 된다.

cell을 지우고 싶다면 해당 cell을 누르고 `esc`를 한번 누르고 `x`를 누르면 지워지고 `b`를 누르면 새로 cell이 생성된다.

'Code'모드를 'Markdown'모드로 바꾸면 Typora를 사용했던 것처럼 Markdown을 작성하면 된다. 

`ctrl+enter`를 누르면 편집모드가 끝난다.

<img src="images/image 003j.png">

'Help-User interface Tour'를 통해 사용법을 익힐 수 있다.



### 명령어 단축시키기

파일 이름 앞에 `.`을 붙이면 유닉스 시스템에서 숨김파일이 된다.

<img src="images/image 005j.png">

터미널 상의 최상위 폴더에서 vscode를 열고 `.bashrc`이름으로 파일을 작성한다.

그 내용으로 `alias jn="jupyter notebook"`을 입력을 한다. 

우리가 변수를 선언하듯이 `=`를 띄어쓰기하면 안된다. 



