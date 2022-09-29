## 1. 마크다운이란?

> 마크다운(Markdown)은 일반 텍스트 기반의 마크업 언어다. 일반 텍스트로 서식이 있는 문서를 작성하는 데 사용되며, 일반 마크업 언어에 비해 문법이 쉽고 간단한 것이 특징이다. HTML과 리치 텍스 서식 문서로 쉽게 변환되기 때문에 응용 소프트웨어와 함께 배포되는 README 파일이나 온라인 게시물 등에 많이 사용된다.
> URL : https://ko.wikipedia.org/wiki/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4

- 장점

1. 문법이 쉽고 간결하다.
2. 관리가 슆다.
3. 지원 가능한 플랫폼과 프로그램이 다양하다.

- 단점

1. 표준이 없다.
2. 모든 HTML 마크업을 대신하지 못한다.

## 2. 마크다운문법

### 2-1. 제목(header)

#### h1 ~ h6

- 숫자가 낮을수록 중요한 제목

```
# h1
## h2
### h3
#### h4
##### h5
###### h6
```

### 2-2. 줄바꿈 (Line Breaks)

```
1. 띄어쓰기 2번
2. <br>
```

### 2-3. 강조 (Emphasis)

> - _이텔릭_

- **두껍게**
- **_이텔릭 + 두껍게_**
- ~~취소선~~
- <u>밑줄</u>

```
_이텔릭_
**두껍게**
**_이텔릭 + 두껍게_**
~~취소선~~
<u>밑줄</u>
```

### 2-4. 목록 (List)

> 1. 순서

1. 순서
1. 순서
   1. 순서
   1. 순서
1. 순서

- 목록
- 목록
- 목록
  - 목록
  - 목록
- 목록

```
1. 순서
1. 순서
1. 순서
   1. 순서
   1. 순서
1. 순서

- 목록
- 목록
- 목록
   - 목록
   - 목록
- 목록
```

### 2-5. 링크(Links)

> <a href="https://google.com">Google</a>
> [Google](https://google.com)
> <a href="https://www.naver.com" title="네이버로가기">Naver</a>
> [Naver](https://www.naver.com "네이버로 가기")

```
<a href="https://google.com">Google</a>

[Google](https://google.com)

<a href="https://www.naver.com" title="네이버로가기">Naver</a>

[Naver](https://www.naver.com "네이버로 가기")
```

### 2-6. 이미지(images)

```
기본틀 = ! [ ] ( )
![Github](https://mblogthumb-phinf.pstatic.net/MjAxOTEyMTVfMjc4/MDAxNTc2NDE0MTAwNjg1.cp_9N4gi8GOe7idQjx6pC1LUhK9EqpIs9uArKqZq6iUg.1vF6bTjG3vJW4mb_WagZ5gh0gfwjoo2bznBTEs-tyXkg.JPEG.nilsine11202/github.jpg?type=w800)
```

![Github](https://mblogthumb-phinf.pstatic.net/MjAxOTEyMTVfMjc4/MDAxNTc2NDE0MTAwNjg1.cp_9N4gi8GOe7idQjx6pC1LUhK9EqpIs9uArKqZq6iUg.1vF6bTjG3vJW4mb_WagZ5gh0gfwjoo2bznBTEs-tyXkg.JPEG.nilsine11202/github.jpg?type=w800)

### 2-7. 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> (네이버 국어사전)

```
> 인용문
>> 중첩된 인용문
>>> 중중첩된 인용문
```

### 2-8. 인라인(inline) 코드 강조

> CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있음.

```
` ` // 백틱 기호
```

### 2-9. 블록(block) 코드 강조

> 백틱 3번 + 코드 + 백틱 3번

```
<a href="https://www.google.co.kr" target="_blank">Google</a>
```

### 2-10. 표(Table)

```
position 속성

값 | 의미 | 기본값
--|:--:|--: // : 글자 정렬
static | 기준없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모요소 | X
fixed | 뷰포트 | X
```

position 속성

| 값       |       의미       | 기본값 |
| -------- | :--------------: | -----: |
| static   |     기준없음     |      O |
| relative |    요소 자신     |      X |
| absolute | 위치 상 부모요소 |      X |
| fixed    |      뷰포트      |      X |

### 2-11. 원시 HTML(Raw HTML)

```
동해물과 <u>백두산</u>이 마르고 닳도록 <br/>
하느님이 보우하사 우리나라 만세

```

동해물과 <u>백두산</u>이 마르고 닳도록 <br/>
하느님이 보우하사 우리나라 만세

### 2-12. 수평선(Horiontal Rule)

```
---
***
___
```

---

---

---
