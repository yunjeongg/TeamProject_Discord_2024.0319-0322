<h1>HTML, CSS Project - Discord</h1>
HTML과 CSS를 학습한 후 웹페이지 Discord를 만들었습니다.
<br>
<br>
교재에 적힌대로 예제만 공부하는 것에서 벗어나 <br>
처음부터 끝까지 HTML로 뼈대를 구성해보고 CSS로 필요한 스타일들을 적용해 볼 수 있었습니다.
<br>
<br>

<h2>목차</h2>

- [프로젝트 소개](#프로젝트-소개)
- [디스코드를 선택한 이유](#디스코드를-선택한-이유)
- [프로젝트에서 어려웠던 점](#프로젝트에서-어려웠던-점)
- [프로젝트를 끝내고 느낀점](#프로젝트를-끝내고-느낀점)
<br>

## 프로젝트 소개
- 프로젝트 이름: Discord 4조<br>
- 개발기간: 24.03.19 ~ 24.03.22<br>
- 개발환경: HTML, CSS<br>
- 멤버구성: <br>
강지혜 - Main<br>
배윤정 - Join<br>
김한솔 - Safety, Head & Footer<br>
김병모 - Nitro<br>
<br>
<br>

## 디스코드를 선택한 이유
- 학습을 완료한 이후 가장 어렵다고 느꼈던 부분이 <br>
img태그로 삽입한 이미지의 사이즈조절과 여러 박스들을 배치하는 부분이라고 생각했었기 때문에<br>
이 부분이 다 들어있는 사이트들을 먼저 골랐고 (커피빈, 당근마켓, Netflix, Discord)<br><br>
- 그 외에는 우리가 학습한 내용을 적당히 사용해 볼 수 있는 사이트인가, 시간안에 작업하기 적당한 작업량인가를 중점에 두고 골랐고 <br>
최종적으로 Discord를 선택하게 되었다.
<br>

## 프로젝트에서 어려웠던 점
<h3>공통영역</h3>
<ol>
	<li>처음 협업하기 전 간단한 회의를 했었는데 어떤사이트를 할 것인가, 그 사이트의 어떤영역을 맡을것인가에 대해서만 회의를 하고<br>
     더 세부적인 사항은 정하지 않고 바로 개인작업에 들어갔었다.</li><br>
	<ul><li>github에 통일된 파일명으로 빈 개인작업파일을 먼저 만들고 시작하면 좋지 않았을까 생각이 들었다. 개인작업이 끝난 후 통합시에 <br>
     파일명이나 위치도 다 제각각이었고 또 공통적용사항을 각자의 개인작업파일에 넣은 경우, 공통파일링크만 넣은 경우등이 있어 <br>
     통일성이 부족했다.</li><br>
		<li>각자의 개인영역 작업 중간에 공통적으로 들어가는 head&footer 를 삽입함으로서 내 개인영역의 넓이와 높이를 공통영역에 맞추어 <br>
	   다시 바꿔줘야 하는 번거로움이 있었다.</li><br>
		<li>Discord는 font가 유료이거나 오픈소스가 아닌 부분이 많아 font를 먼저 정하지않고 개인작업을 먼저 마친 후 <br>
			다시 회의를 해서 정했었는데 해당사항을 일일이 따로 수정을 해야하는 부분도 번거로웠고, <br>
			적용된 사항도 각자 다 다른부분이 있어 완성된 사이트에 통일성이 부족한 느낌을 받았다.</li></ul><br>
	<li>발표 <br>
	 - 강사님께서 이번 발표는 시연만 하는 정도로 하면 된다고 하셔서 따로 준비를 해가지 않았었는데 발표가 끝나고 나니 <br>
	   팀원들 모두 자기영역에 대해서만 자세히 알고 다른팀원들이 작업한 영역에 대해서 이해도가 많이 떨어지는 느낌이 있었다.</li></ol><br>
<br>
<h3>개인영역</h3>
<ol>
	<li>main영역을 작성할 때 그 높이를 초기에 vh로 작성했었는데 모니터마다 해상도마다 크기가 들쭉날쭉하게 변해서 <br>
메인부분안의 콘텐츠들이 잘 주차되어 있는 경우도 있고 메인영역 바깥으로 빠져나온 경우도 있어서 이런저런크기로 바꿔보느라 시간을 많이 보냈다.</li><br>
<ul><li>결국에는 발표시에 혹시모를 깨짐문제를 방지하기 위해 메인부분의 높이를 px로 바꾸고 메인부분만 반응형웹처리를 하게되었다.</li></ul><br>
	<li>ouroffice영역에서 메인박스안에 이미지박스와 아이콘박스를 넣어 작업을 했었는데 박스가 여러개로 중첩이 되어 있는 부분도 그렇고 <br>
그 안에 수평배치, 이동효과 등 효과들마저 중첩이 되어있어서 HTML문서에서는 아이콘박스의 위치를 어디에 놓아야 하는가에 대해서, <br>
CSS문서에서는 효과의 지정위치와 값의 선택에 대해 많은 시간을 할애했다.</li><br>
	<ul><li>아이콘을 감싼 원테두리를 타원형이 아닌 정원의 형태로 만들기 위해서 내박스가 아닌 부모박스에서 테두리를 만들어야 했다.</li><br>
		<li>그 아이콘박스의 위치를 조정할 때 position: apsolute와 transform: translate로 위치지정을 했었는데<br>
그 절대값이 동일하지 않다면 먼저 transform: translate 값을 0으로 주고 position: apsolute의 값을 수정해야 한다는 걸 알게되었다.</li><br>
		<li>ouroffice영역에서 원래는 사진이 슬라이드하듯이 돌아가는 효과를 써야 하는데  <br>
	이건 Java Script의 영역이라서 이후에 배울 수 있다고 하셨다. 나중에 꼭 배웠으면 좋겠다. </li></ul><br>
	<li>이번작업을 하면서 처음과 끝에서만 백업을 하고 나머지는 시간이 날 때마다 들어가서 파일에 직업적으로 작업을 하고<br>
중간중간 commit을 할 생각을 하지 못 했던것 같다. 앞으로는 계속해서 commit하는 습관을 들여야겠다.</li></ol><br>
<br>
<br>

## 프로젝트를 끝내고 느낀점
- 처음에는 내가 이걸 다 해낼수 있을까 하는 막막함도 있었지만 끝내고 보니 하나의 프로젝트를 어떤식으로 진행해야 한다는 걸 알 수 있었고 <br>
중간중간에 내가 부족한 점을 알 수 있어서 좋았던 것 같았다.<br>
- 또 발표까지 하면서 다른 팀의 과제결과물까지 보게됐는데 배워보지 못햇던 효과라던가 괜찮아보였던 웹페이지도 있어서 <br>
나중에 해보고싶은게 생겼다는 사실에 기분이 좋았다.<br>
- 또 팀프로젝트는 개인프로젝트와 달리 앞에 팀이라는 말이 붙는것처럼 팀으로 작업을 한다는 생각, <br>
팀원들과의 소통이 중요하다는 생각이 들었다. <br>
개인프로젝트를 한다면 내 기술을 갈고닦는 것을 최우선으로 하면 되겠지만 <br>
앞으로 팀프로젝트를 한다면 팀원들과 열심히 대화를 나눠보고 싶다.<br>

