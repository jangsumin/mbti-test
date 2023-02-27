# mbti-test

mbti 테스트

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
