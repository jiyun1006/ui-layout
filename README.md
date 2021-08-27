>### UI 감 익히기 위한 저장소     


<br>

- 디자인 툴 : `figma`   

- 에디터 : `vscode`   

- css : `node-sass`    

- scripts를 이용해서 sass파일을 css로 자동 컴파일하게 만들어야 편리하다.   

```json
{
    // 생략

    "scripts": {
    "sass": "node-sass -wr styles/main.scss ./style.css" // -wr : 디렉토리의 변화를 살펴라 
  },
}
```

(진행되는 대로 추가예정)
