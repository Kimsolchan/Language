# HTML 기본 태그 정리
- HTML은 마크업 언어며 , 마크업 언어는 태그들로 이루어져 있다 
- HTML 문서는 HTML 태그로 작성된다

<br />

## 기본적인 HTML 구조
![HTML 시작](https://user-images.githubusercontent.com/108924832/180205298-7ace1292-6d8f-451c-ae88-77834d82ebe6.PNG)

<br />

## 결과
![test 화면](https://user-images.githubusercontent.com/108924832/180205847-80692e11-d3f0-47a5-a807-bcaa70ea8808.PNG)

<br />

## HTML 태그(tag)
- 각각의 태그는 웹페이지의 디자인 , 기능..등등을 결정하는데 사용한다
- HTML 태그는 태그 이름을 꺾쇠 괄호(<>)로 감싸서 표현한다
```
<tag name> </ tag name>
```
- <tag name>   : tag 시작
- </ tag name> : tag 종료


### HTML 기본적인 태그 정리
```
<!DOCTYPE>
```
- 현재의 문서를 HTML 문서임을 선언한다

<br />

```
<html>
```
- HTML의 시작을 알리며 , 태그안에 웹페이지에 표시할 내용을 작성한다

<br />

```
<head>
```
- HTML의 속성을 정의한다

<br />

```
<html lang="en">
```
- 문서를 html로 시작, 언어를 영어로 설정한다

<br />

```
<meta charset="utf-8">
```
+ html 파일의 인코딩을 알려주는 태그 
  + 브라우저에게 text 를 어떻게 표현하라는지 알려준다
  + "utf-8" : 화면에 text를 한글로 표시해달라는 것
  + 위 태그가 없으면 한글, 특수문자 들이 깨져서 나올 수 있으므로 필수요소다

<br />

```
<title>
```
- 페이지 명 설정

![ex title](https://user-images.githubusercontent.com/108924832/180211624-b6900124-0e38-453f-9352-f3fa55e7b5ff.jpg)

<br />

```
<body>
```
- html 문서의 본문의 시작과 종료를 알려준다 
- 웹 화면에 실질적으로 보여지는 것들을 담는 것

<br />

```
<p>   
```
- 문단과 문단 사이를 구분할 때 사용한다 
- html은 특별한 지시를 하지 않으면 문단을 구분하지 않고 한 문장으로 취급한다

<br />

### 리스트 태그 , a 태그
```
<ul> / <ol>
<li>
```
- ul : 순서가 없는 리스트를 만들 때 사용한다
- ol : 순서가 있는 리스트를 만들 떼 사용한다 
- li : ul , ol 태그 사용시 리스트 내용에 담길 아이템을 만들 때 사용한다

<br />

```
<a>
```
- 하이퍼링크(또는 링크)를 사용해서 이동할 페이지 또는 이동할 위치를 지정할 때 사용한다

