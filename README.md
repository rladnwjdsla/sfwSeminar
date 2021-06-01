#한림대학교 소프트웨어융합대학
---

<h1> 20185118 김우정 // HTML <h1>

  <h1><strong>WEB</strong></h1>
 <ol>
  <li><a href="HTML MANUAL.html" title="HTML" target="_blank">HTML</a></li>
  <li><a href="CSS MANUAL.html" title="CSS" target="_blank">CSS</a></li>
  <li>Javascript</li>
 </ol>

<h2><strong>HTML 사용 설명서</strong></h2>
<h3><strong>배운 태그</strong></h3>
<h4><strong>&emsp;&emsp;공백 넣기</strong></h4>
<ol>
  <li> & nbsp ☞ 스페이스바 공백 크기의 공백 </li>
  <li> & ensp ☞ nbsp보다 조금 더 넓음 </li>
  <li> & emsp ☞ ensp보다 조금 더 넓음 </li>
</ol>
<ol>
  <li> h1 ~ h6 ☞제목(HEADER), 숫자가 커질수록 글자크기 작아짐 <br></li>
  <li> strong  ☞ 글자 굵게 <br></li>
  <li> br ☞ 줄띄움(한줄) <u>닫힌 태그 존재X</u> <br></li>
  <li> p ☞단락구분 <u>닫힌 태그 존재O</u> <br></li>
  <li> u ☞ 밑줄(UnderLine) <br></li>
  <li> img ☞ 이미지 삽입(image), 크기 조정은 <u>width</u>(숫자나 %)<br></li>
     <img src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7648.png" width="25%"><br>
  <li> li ☞ 목차 표현(list) <br></li>
  <li> ul ☞ 목차의 경계표현(unordered list) <br></li>
  <li> ol ☞ 목차 자동 번호 매김(ordered list) <br></li>
  <li> title ☞ 웹의 제목 <br></li>
  <li> body ☞ 본문</li>
  <li> head ☞ 본문을 설명하는 태그</li>
  <li> html ☞ body와 head를 감싸는 태그</li>
  <li> !doctype html ☞ 웹페이지가 HTML로 만들어졌다는 것을 표현 </li>


  <li> a ☞ 하이퍼링크 표현 태그(achor)</li>
    └ href="" 하이퍼링크 삽입 <br>
    └ title="" 랑크 제목 표현 <br>
    └ target="_blank" 링크가 새창으로 열리게 하기 <br>
    └ <a href="https://www.youtube.com/" title ="유튜브" target = "blank">유튜브로 이동(예제)</a><br>
    <strong>세계 최초의 웹사이트(이미지 선택 시 링크 이동↓)</strong><br>
    &emsp;<a href="http://info.cern.ch" title="세계 최초의 웹사이트" target="_blank"><img src="j1.jpeg" width="25%"></a>

  <li> iframe ☞ 동영상 삽입 </li>
    └ autohide = 컨트롤러와 진행 표시줄 상태 지정 <u>(링크 내에 작성)</u><br>
&ensp; └ '0'  재생 후 시간이 지나도 감추지 않는다.<br>
&ensp; └ '1'  재생 후 일정시간이 지나면 모두 감춘다.<br>
&ensp; └ '2'  Default, 일정시간이 지나면 소리 조절, 재생 버튼이 보인 상태로 페이드 아웃 <br>
    └ autoplay = 자동재생 <u>(링크 내에 작성)</u> <br>
&ensp; └ '0'  Default, 사용 X <br>
&ensp; └ '1'  사용 O <br>
    └ color = 진행 표시줄 색상 지정<u>(링크 내에 작성)</u> <br>
&ensp; └ 'red'  Default, 빨강 <br>
&ensp; └ 'white'  흰색으로 지정, modestbranding(유튜르 로고 감추기)와 함께 사용할 수 없음. <br>
    └ controls = 영상 재생 시 컨트롤러의 표시 여부 지정<u>(링크 내에 작성)</u> <br>
&ensp; └ '0' 표시 X <br>
&ensp; └ '1' Default, 표시 O (Flash Player 즉시 로드)<br>
&ensp; └ '2' 표시 O (사용자가 재생했을때 Flash Player 로드)<br>
    └ disablekb = 플레이어를 키보드로 제어할 수 있을지에 대한 여부 <br>
&ensp;  └ '0' Default, 조작 가능 <br>
&ensp;  └ '1' 조작 불가능  <br>
    └ end = 영상의 재생이 끝나는 지점을 초 단위로 지정<u>(링크 내에 작성)</u> <br>
    └ fs = 전체화면 버튼 표시여부 <br>
&ensp;  └ '0' 버튼 표시 X  <br>
&ensp;  └ '1' Default, 버튼 표시 O <br>
    └ modestbranding = 유튜브 로고 표시 여부 <br>
&ensp;  └ '0' Default, 표시 O <br>
&ensp;  └ '1' 표시 X <br>
    └ rel = 영상이 끝났을 때 관련 영상 표시 여부
&ensp;  └ '0' 표시 X <br>
&ensp;  └ '1' Default, 표시 O <br>
    └ start = 영상의 재생이 시작하는 지점을 초 단위로 지정<u>(링크 내에 작성)</u> <br>
    └ list = 재생목록 지정 <br>
    └ listType = 재생목록 형태 지정 <br>
&ensp;  └ 'playlist' 재생목록의 고유 아이디를 입력하여 재생 <br>
&ensp;  └ 'search' 질의어를 입력하여 해당 검색결과를 재생목록으로 만들어 재생 <br>
&ensp;  └ 'user_uploads' 사용자 아이디를 입력하여 해당 소유자가 업로드한 영상을 재생 <br>

</ol>
<h3>웹 호스팅 사이트</h3>
[github] : https://github.com/
<br>
<h3>댓글 기능 추가 사이트</h3>
<ol>
<li><a href="https://disqus.com/"target="_blank"><strong>DISQUS</strong></a></li>
<li><a href="https://www.livere.com/"target="_blank"><strong>LiveRe</strong></a></li>
</ol>

