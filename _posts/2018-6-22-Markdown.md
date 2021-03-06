---
categories: Markdown
title: Markdown
---

> ### 마크다운(Markdown) 문법정리

### 제목(Heading)       *(← 글씨색깔은 어떻게 바꿀까?)*

제목문구 앞에 #을 넣어서 작성한다. *(#과 문구 띄어쓰기!)*

#의 개수에 따라 글자의 크기가 달라진다.

최대 6개까지이며 #개수가 많을수록 크기는 작아진다.

예시_ *(``` + enter 로 아래에 상자 만들었음)*

```
# Heading
### Heading
###### Heading
```
# Heading
### Heading
###### Heading



*(↑ 이 수평선은 --- 넣으면됨)*



> ### 본문(Paragraph)

본문 그대로 작성하면 된다.

```
안녕하세요. 라이언입니다.
```

------

안녕하세요. 라이언입니다

------



> ### 인용(Blockquotes)

인용은 > 를 넣어서 작성한다.

```
> 맥북이 그렇게 좋은가요? 
>> 맥북이 그렇게 좋은가요?
```

------

> 맥북이 그렇게 좋은가요?
>
> > 맥북이 그렇게 좋은가요?

------



> ### 리스트(List)

#### 순서가 없는 리스트(Unordered List)

*(↑ 제목에 들여쓰기 하고싶은데 아직 모르겠다)*

```*``` 또는 ```-``` 를 넣어서 사용한다.  tab 또는 2칸 띄어쓰기*(잘안된다)*로 중첩항목 작성 가능

```
* Frontend
  * HTML
  * CSS
  * JavaScript
    * Vue.js
     
- Frontend
  - HTML
  - CSS
  - JavaScript
    - Vue.js
```

------

- Frontend
  - HTML
  - CSS
  - JavaScript
    - Vue.js
- Frontend
  - HTML
  - CSS
  - JavaScript
    - Vue.js

------

#### 순서가 있는 리스트(Ordered List)

```
1. HTML
2. CSS
3. JavaScript
```

------

1. HTML
2. CSS
3. JavaScript

------

```
1. Frontend
	1. HTML
	2. SCC
	3. JavaScript
		1. Vue.js
2. Backend
```

------

1. Frontend
   1. HTML
   2. CSS
   3. JavaScript
      1. Vue.js
2. Backend

------

> ### 코드블록(Code Blocks)

코드블록은 1. 단어 2. 짧은 문장 3. 여러줄의 문장 으로 삽입가능하다

```
단어 : ```깃허브```
문장 : ```오늘 날씨가 참 좋네요```
여러문장 : 2018년 러시아 월드컵이 시작되었습니다. 비록 조 편성이 안타깝지만 힘을내어 기적같은 좋은 결과가 생겨났으면 좋겠습니다. :)
```

------

단어 : ```깃허브```

문장 : ```오늘 날씨가 참 좋네요```

여러문장 : ```2018년 러시아 월드컵이 시작되었습니다. 비록 조 편성이 안타깝지만 힘을내어 기적같은 좋은 결과가 생겨났으면 좋겠습니다. :)  ```

------

> ### 수평선(Horizontal Rules)

문단과 문단을 나눌때 사용하는 수평선

```
* * *
***
*****
- - -
---
```

------

------

------

------

------

------

------

> ### 강조(Emphasis)

텍스트 굵기, 기울임, 취소 등 설정

1. 굵기

```
**굵은글씨1** ,  __굵은글씨2__
```

------

**굵은글씨1**  ,  __굵은글씨2__

------

1. 기울임

```
*기울어진 글씨1* , _기울어진 글씨2_
```

------

*기울어진 글씨1* , _기울어진 글씨2_

------

1. 취소선

```
나는 ~~술을~~ 밥을 먹고 싶다
```

------

나는 ~~술을~~ 밥을 먹고 싶다

------

> ### 이미지 삽입(Images)

```
![대체 텍스트](C:\Users\YANGUK\Desktop\study\github\electrocat.jpg)
```

![electrocat](C:\Users\YANGUK\Desktop\study\github\electrocat.jpg)

> ### 링크(Links)

```
[Ryan blog](http://ryankim41.github.io "title")   * title 생략 가능
검색엔진은 [구글](https://www.google.com) [네이버](https://www.naver.com)
```

[Ryan blog](http://ryankim41.github.io "title")
검색엔진은 [구글](https://www.google.com) [네이버](https://www.naver.com)
