<header>Github Markdown 살펴보기</header>  
  
<br/>   
<br/> 

# 제목(Header)

```plaintext
# 기호를 문장 맨 앞에 추가하며, #의 갯수에 따라 h1~h6까지 표시 할 수 있다.
```

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

<br/>   
<br/> 

# 문장(Paragraph)

```plaintext
기본적인 text 글은 자동으로 <p></p> 태그 처리된다.
```

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

<br/>
<br/>

# 줄바꿈(Line Breaks)
```plaintext
줄바꿈을 원하는 끝 부분에 스페이스바 2번 또는 <br/>태그를 추가하여 줄바꿈을 구현한다.
```

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

<br/>
<br/>

# 강조(Emphasis)
```plaintext
_이텔릭_  
**두껍게**  
**_이텔릭+두껍게_**  
~~취소선~~  
<u>밑줄</u> 또는 <span style ="text-decoration: underline"></span>
```
_이텔릭_  
**두껍게**  
**_이텔릭+두껍게_**  
~~취소선~~  
<u>밑줄</u>

<br/>
<br/>

# 목록(List)
```plaintext
문장 앞에 숫자. 을 붙여 리스트화 할 수 있으며, 들여쓰기를 통해 하위뎁스로 표현 가능하다.
```
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록  
        1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록  
        - 순서가 필요하지 않은 목록  
        - 순서가 필요하지 않은 목록  
- 순서가 필요하지 않은 목록

<br/>
<br/>

# 링크(Links)
```plaintext
CSS와 같은 형식으로 표현 또는 [키워드](웹주소)를 통해 구현 가능 하다. 
```

<a href="https://google.com">GOOGLE<a>  

[GOOGLE](https://google.com)  

<a href="https://naver.com" title="NAVER로 이동!">NAVER<a>  

[NAVER](https://naver.com "NAVER로 이동!")  

<br/>
<br/>

# 이미지(Image)
```plaintext
링크와 같은 형식에 !를 맨앞에 추가하여 이미지를 삽입한다.
![hero](url) = <img src="url" alt="hero">
```
![logo](https://i.postimg.cc/tJdNdgVn/hero22.png)

<br/>
<br/>

# 인용문(BlockQuote)
```plaintext
문장 앞에 '>'를 추가하여 인용문으로 표현할 수 있으며, '>' 갯수에 따라 중첩하여 사용이 가능하다.
```
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
>(네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3

<br/>
<br/>

# 인라인(inline) 코드 강조
```plaintext
단어를 `(back-tick)으로 감싸 코드 형식의 단어로 표현 가능하다.
```
예시) 
<br/>
CSS에서 background 혹은 background-image 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

<br/>
<br/>

# 블록(block) 코드 강조

```plaintext
삼중`(back-tick)과 형식을 추가하여 코드를 강조할 수 있다.
```

<br/>

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

<br/>
CSS 표현

```css
.list > li {
    position: absolute;
    top: 40px;
}
```
<br/>

Javascript 표현
```javascript
function func(){
    var a = 'AAA';
    return a;
}
```
<br/>

Git 표현

```bash
$ git init
$ git config --global core.autocrlf 'input'(mac) or 'true'(windows)
$ git config --global user.name '이름'
$ git config --global user.email '이메일주소'
$ git config --global --list

$ git status
$ git add .
$ git commit -m 'Study Markdown'
$ git log
$ git remote add origin 'url'
$ git push origin master
```

Git 이전 버전으로 한번 되돌리기
  
```bash
$ git reset --hard HEAD~1
```

Git 버전 되돌리기 취소
  
```bash
$ git reset --hard ORIG_HEAD
```
 
<br/>
plaintext 표현

```plaintext
아무 글이나 코드배경으로 사용 할 수 있는 방법이다.
```
<br/>
<br/>

# 표(Table)
```plaintext
띄어쓰기+ '|' 기호를 통해 표형태로 만들어 낼 수 있으며, 
--|:--:|--: 를 추가하여 제목행을 만들고 :으로 좌측-가운데-우측정렬을 표현
```

position 속성

값 | 의미 | 기본값  
--|:--:|--:  
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위차상 부모 요소 | X
fixed | 뷰포트 | X
<br/>
<br/>

# 원시 HTML(Raw HTML)

```css
동해물과 <u>백두산</u>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

동해물과 <span style="text-decoration: underline">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세
```

동해물과 <u>백두산</u>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

동해물과 <span style="text-decoration: underline">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세
<br/>
<br/>

# 수평선(Horizontal Rule)
```plaintext
'-', '*', '_'를 3번 연속 입력하여 수평선을 표현
예) ---, ***, ___
```

---
***
___
