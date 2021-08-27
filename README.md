> ### UI 감 익히기 위한 저장소

<br>

- 디자인 툴 : `figma`

- 에디터 : `vscode`

- css : `node-sass`

- scripts를 이용해서 sass파일을 css로 자동 컴파일하게 만들어야 편리하다.

```json
{
    ---생략---

    "scripts": {
    "sass": "node-sass -wr styles/main.scss ./style.css"    (-wr : 디렉토리의 변화를 살펴라)

  },
}
```

- `scss-lint`를 사용하기 위해서, .scss-lint.yml 파일을 설정한다.  
  (github의 gists에 설정파일 저장해놈. _자주 쓰는 설정파일들 gists에 저장해놓기_)

  - 또한 ruby가 설치되어 있어야지, `scss-lint`를 사용할 수 있기 때문에, 미리 ruby를 설치한다.

- `preitter`도 설정파일을 만들어서 설정해준다.  
  (.preitterrc 파일을 만들어서 개인 or 팀의 컨벤션을 적어주면 깔끔하게 정리가능)

(진행되는 대로 추가예정)
