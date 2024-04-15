# coteTemplate

### 자바스크립트를 사용하여 코딩 테스트를 수행하는 데 사용할 수 있는 템플릿을 제공합니다. `scanInt()`를 숫자로, `scanString()`을 문자열로 대체하여 사용할 수 있으며 좌상단에서 우하단으로 순차적으로 읽습니다.

예를 들어 다음과 같은 input.txt 파일이 존재할 때

```
5
1 2 Str
```

다음 코드와 같이 사용할 수 있습니다.

```javascript
let a = scanInt()
let b = scanInt()
let c = scanInt()
let D = scanString()

// a 는 5 (number)
// b 는 1 (number)
// c 는 2 (number)
// D 는 'Str' (string)
```

---

### I provide a template that can be used for performing coding tests using JavaScript. You can use scanInt() for numbers and scanString() for strings, reading sequentially from the top left to the bottom right.

If you set input.txt like this

```
5
1 2 Str
```

you can interpret it as follows.

```javascript
let a = scanInt()
let b = scanInt()
let c = scanInt()
let D = scanString()

// a is 5 (number)
// b is 1 (number)
// c is 2 (number)
// D is 'Str' (string)
```
