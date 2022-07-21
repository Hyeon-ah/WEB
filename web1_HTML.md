+ <h1> </h1>: 글씨 굵게
+ <ol> </ol>: 1. 2. 3. 생성
+ <li> </li>: 리스트화 
+ <p> </p>: passage 만듦


1. HTML(Hypertext Markup Language)
웹페이지를 만들기 위해서는
	+ 기획을 해야 함

2. 사람과 기계가 하는 일 분리
사람이 하는 일: Code, Source, Language
기계가 하는 일: Application, App. Program, Webpage, Website
 	관점에 따라 어휘가 달라지는 것
 	webpage 만드는 언어가 HTML
 HTML 장점: 쉬움, 중요함
 PUBLIC DOMAIN: 저작권이 없음

3. 태그 특징
 tag(태그)
 	+ 닫히는 태그는 앞에 /를 붙임
 	+ 중첩 사용가능
 	ex) <strong>,<u>,</u>,</strong> 
 	+ 모든 태그를 외울 수는 없음.
 	+ 태그의 frequency를 보고 많이 사용되는 것들을 학습먼저 하자
 https://www.advancedwebranking.com/seo/html+study/

4. 태그 몇 가지 종류
	+ <h1></h1>: heading(제목)
	+ 줄바꿈 태그는 닫히지 않는 태그, 쓰는 만큼 줄바꿈 가능
 		+ ex)img, input, br, hr, meta
 	+ <p></p>: 단락표현

 
 5. CSS 맛보기
 	+ HTML과 완전히 다른 문법 가짐
 	+ 정보를 꾸며주는 CSS, 정보를 표현하는 HTML
 ```
 <p style="margin+top:45px;"> 
 ```
 p태그 위쪽에 45px만큼 여백(margin)생성

 6. 태그의 심화된 문법: attribute(속성)
	+ img: 이미지를 넣는 태그
태그 이름 만으로 정보 부족-> 새로운 문법인 **속성**
(source의 줄임말 src)
```
<img src="codin_image.jpeg" width="500">
or
<img src="codin_image.jpeg" width="100%">
```

7. 태그 간의 관계를 나타내는 표현(parent, child->부모, 자식)
```
<p>
    <a href="https://opentutorials.org">opentutorials</a>
</p>
```
위의 태그는 p 태그가 a 태그의 부모, a 태그가 p 태그의 자식이지만!
필요에 따라 달라짐

그러나, 부모 자식 관계가 고정된 태그가 있음.
	+ list(목차)의 줄임표현 li
	+ <ul> </ul>: 목록에서 다른 목록과 구분할 수 있도록 경계가 표시
	+ <ul></ul>:  unordered list의 약자
	+ <ol></ol>: ordered list의 약자

8. 문서의 구조
	+ <title></title>: 문서의 제목 지정
- 약속
	+본문을 설명하는 태그: head 태그
	+본문: body 태그
	+head 태그와 body 태그를 감싸는 하나의 태그: html 태그
	+HTML로서 만들어졌다는 것을 표현하기 위해서 문서의 시작에 <!doctype html> 코드 추가

9. HTML  태그의 여왕
anchor의 a: 링크!
	+ target="_blank"는 링크 클릭했을 때 새 창에서 페이지 열리기
	+ a 태그 안의 title: 이 링크가 어떤 내용을 담고 있는지를
툴팁으로 보여

10. Internet vs Web
<비유>
도시(인터넷) & 도시의 위의 건물 하나(웹)
도로(인터넷) & 도로 위를 달리는 자동차 한 대(웹)
운영체제(인터넷) & 하나의 앱(웹)


#쓰면-> div id 값 지정한 걸로 감
.은 class

grid --> col-sm-6(총 12를 반으로 나누어 사용하는 것!)
