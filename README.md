# TraumPortfolio
Github설명 당분간 이거 보면서 같이 실습해요 

git config --global user.name "이름"
git config --global user.email "깃허브 메일주소" // 매번 물어보는 귀찮음을 피하기 위해 설정.
 
mkdir ~/MyProject   // 로컬 디렉토리 만들고
cd ~/myproject      // 디렉토리로 들어가서
git init            // 깃 명령어를 사용할 수 있는 디렉토리로 만든다.
git status          // 현재 상태를 훑어보고
git add 화일명.확장자  // 깃 주목 리스트에 화일을 추가하고 or
git add .           // 이 명령은 현재 디렉토리의 모든 화일을 추가할 수 있다.
git commit -m “현재형으로 설명” // 커밋해서 스냅샷을 찍는다.
 
git remote add origin https://github.com/username/myproject.git // 로컬과 원격 저장소를 연결한다.
git remote -v // 연결상태를 확인한다.
git push origin master // 깃허브로 푸시한다.

-------------------------------------------------------------------------------------------------

html, head, title, meta, body
 

새로운 html 파일을 생성하고 html 태그를 입력하면

 

<!DOCTYPE html>                                                        //문서의 버전에 관한 정보를 나타낸다. 본 문서가 HTML5 라는 것을 명시함.
<html lang="en" dir="ltr">                                           //html 파일임을 정의. html 태그는 head 태그와 body 태그로 이루어짐.
  <head>                                                                        //메타 데이터의 집합으로 웹 페이지에 직접적으로 보이지 않는 정보임. head 태그                                                                                         는 title, meta, link, style, script 태그로 구성됨.
    <meta charset="utf-8">                                           //meta 태그는 <meta 속성="속성값" />으로 스스토 닫는 태그이기 때문에 이렇게                                                                                         나타낸다. 보기에 charset="utf-8"는 글자 깨짐에 대해 다른 언어에서도 볼수 있                                                                                          도록 표기한 것이다.
    <title></title>                                                            //title 태그는 페이지를 대표하는 내용의 제목을 넣어야 함.
  </head>
  <body>                                                                        //본문의 내용을 담는 공간이다.
 
  </body>
</html>
 

이러한 기본 형식의 태그가 생성된다.

div
 

html 문서에서 부분 또는 섹션을 정의한다.

 

div 요소는 css로 스타일을 지정하거나 JavaScript로 특정 작업을 수행하기 위해

다른 html 요소의 컨테이너로 자주 사용 된다.

<div style="background-color:lightblue">
  <h3>This is a heading</h3>
  <p>This is a paragraph.</p>
</div>

a
 

a 태그는 한 페이지에서 다른 페이지로 연결하는 데 사용되는 하이퍼 링크를 정의힌다.

a 요소의 가장 중요한 속성은 링크의 목적지를 나타내는 href 속성이다.

script
script 태그는 클라이언트 측 스크립트를 정의하는 데 사용된다.

script 요소는 스크립트 문을 포함하거나 src 특성을 통해 외부 스크립트 파일을 가리킨다.

자바스크립트의 일반적인 용도는 이미지 조작, 양식 유효성 검사 및 콘텐츠의 검사 및 콘텐츠의 동적 변경이다.

<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script>

link
link 태그는 문서와 외부 리소스 간의 링크를 정의한다.

link 태그는 외부 스타일 시트에 연결하는 데 사용된다.

<head>
  <link rel="stylesheet" type="text/css" href="theme.css">
</head>

img
img 태그는 html 페이지의 이미지를 정의한다.

img 태그에는 src(경로)와 alt(이미지를 설명하는 텍스트)의 두 가지 필수 속성이 있다.

<img src="smiley.gif" alt="Smiley face" height="42" width="42">

p
p 태그는 단락을 정의한다.

브라우저는 각 p 요소 앞뒤에 약간의 여백을 자동으로 추가한다. 여백은 css로 수정 될 수 있다.

<p>This is some text in a paragraph.</p>

span
span 태그는 문서의 인라인 요소를 그룹화하는 데 사용된다.

span 태그는 시각적으로 변경되지 않는다.

span 태그는 텍스트의 일부 또는 문서의 일부에 후크를 추가하는 방법을 제공한다.

<p>My mother has <span style="color:blue">blue</span> eyes.</p>

li , ul, ol
li 태그는 목록 항목을 정의한다.

li 태그는 정렬 된 목록(ol), 정렬된지 않은 목록(ul) 및 메누 목록(menu)에 사용된다.

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

br
br 태그는 한 줄 바꿈을 삽입한다.

br 태그는 끝 태그가 없다는 의미인 빈 태그이다.

This text contains<br>a line break.

------------------------------------------

This text contains

a line break.

style
sylte 태그는 HTML문서의 스타일 정보를 정의하는데 사용 된다.

style 요소 안에는 브라우저에서 HTML 요소를 렌더링 하는 방법을 지정한다.

각 HTML 문서에는 여러 개의 STYLE 태그가 포함될 수 있다.

<style>
h1 {color:red;}
p {color:blue;}
</style>

h1, h2, h3, h4, h5, h6
h1 에서 h6 태그는 hTML 제목을 정의하는 데 사용된다.

h1은 가장 중요한 제목을 정의한다. h6는 가장 중요하지 않은 머리글을 정의한다.

input, form
input 태그는 사용자가 데이터를 입력할 수 있는 입력 필드를 지정한다.

input 요소는 사용자가 데이터를 입력 할 수 있는 입력 컨트롤을 선언하기 위해 form 요소 내에서 사용된다.

입력 필드는 유형속성에 따라 다양한 f}으로 다양하다.

<form action="/action_page.php">
  First name: <input type="text" name="fname"><br>
  Last name: <input type="text" name="lname"><br>
  <input type="submit" value="Submit">
</form>

strong
strong 태그는 구문 태그이다. 중요한 텍스트를 정의한다.

<strong>Strong text</strong>

table, tr, th, td
table 태그는 HTML 테이블을 정의한다.

HTML 테이블은 table 요소와 하나 이상의 tr, th 및 td 요소로 구성된다.

tr 요소는 테이블 행을 정의하고 th 요소는 테이블 헤더를 정의하며 td 요소는 테이블 셀을 정의한다.

더 복잡한 HTML 표에는 caption, coㅣ, colgroup, thead, tfoot 및 tbody 요소가 포함될 수도 있다.

<table>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
</table>
