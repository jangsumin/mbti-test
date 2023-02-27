# mbti-test

내 안에 숨어있는 직업캐 찾기!

## favicon

-   ico 확장자 파일이 최상위 루트에 있으면 파비콘이 바로 적용
-   만약 파비콘이 적용되지 않는다면, 아래 코드를 head 요소 내에 명시

```html
<link rel="icon" href="favicon.png" />
```

## script 태그 사용 시 유의사항

-   src 속성을 통해 가져오는 자바스크립트 파일이 또 다른 자바스크립트 파일을 참고할 때, type 속성에 `module` 명시

```html
<script type="module" defer src="./js/questions.js"></script>
```

## Open Graph & Twitter Cards

-   아래 메타 태그를 head 요소에 추가하여 웹사이트를 공유할 시에 추가 정보를 명시할 수 있음
-   sns에 웹 사이트 링크를 붙여넣으면 프리뷰로 보여주는 제목, 이미지, 설명글과 같은 것을 Open Graph라고 함
-   트위터는 Open Graph와 유사한 기능을 Twitter Cards로 제공
