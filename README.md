# 웹페이지 만들기 실습 
### 1. 과제 주제 설명
### 2. 주요 코드 설명
 <메뉴바>

 -사용 클래스 : nav, container, img1, left, item

 -display:flex 속성을 사용해서 로고와 메뉴1,2,3을 구성함

 -float:left 속성을 사용해서 충북대학교 로고를 메뉴 왼쪽에 줌

 -container로 코드를 감싸면서 전체 페이지의 크기가 가로는 1000px로 고정함

 -container의 margin을 상하는 0, 좌우는 auto로 주어서 가운데로 오도록 설정함

 -left클래스에서 margin-right를 auto로 주어서 메뉴들이 좌쪽으로 치우칠 수 있도록 함


 <대형 사진>

 -사용 클래스 : container, img2, content

 -메뉴바와 같은 크기의 컨테이너를 주어서 통일성 있도록 코드를 구현함

 -img2클래스에서 background-image에 url을 주고 width는 100%로 해서 container의 width에 꽉 찰 수 있도록 구현하였음
 
 -사진 위로 글씨가 보일 수 있도록 하기 위해 content클래스를 사용하였음

 <내용>

 -사용 클래스 : container2, grid-box, special1, special2, image
 -container2 클래스를 사용해서 container와 같은 넓이를 주어서 새로운 container를 만들었음
  (!! 되도록이면 container를 사용해서 위에 그림이랑 한꺼번에 넣는 것을 시도해보았는데 해결되지 않아 새로운 container2라는 클래스를 적용함 !!)
 -grid-box에서 display:grid 속성을 주어서 내용을 채워보았음
 -grid 속성에서 grid-template-columns 속성을 사용해서 열 넓이를 330px씩 줘서 삼등분씩 될 수 있도록 하였음
 -1번 맛집 탐방하기의 경우, special1 스타일에서 grid-column 속성을 span 2를 해줘서 가로로 두칸을 차지할 수 있도록 하였음
 -3번 넷플릭스 시청하기의 경우, special2 스타일에서 grid-column 속성을 span 3을 해줘서 가로로 세칸을 차지할 수 있도록 하였음
 -float:left 속성을 이용해서 3번. 넷플릭스 시청하기의 경우, 사진을 첨부하였음

 <footer부분>
 -사용 클래스 : footer 


### 3. 비고 및 고찰(알게 된 점, 어려웠던 점)
  이번주 수업을 통해서 웹페이지의 전체적인 구성들을 간략하게 만들어볼 수 있었고, 이 과정에서 레이아웃을 잡을 수 있는 코드들에 대해서 배울 수 있었습니다. 
 수업을 들으면서 flex와 grid의 세부 속성들을 실습해보면서 잘 이해하고 있다고 생각하였는데 막상 과제를 하려고하니 content를 작성하는 부분에서 flex를 써야할 지 grid를 써야할 지 둘다 써도 상관없는 건지가 헷갈렸습니다. 또 어떨 때 flex와 grid를 써야할 지 아직까지는 명확히 알지 못하는 것 같아 이것이 앞으로 수업을 들으면서 해결해가야 할 숙제가 될 것 같습니다. 또 이번 수업은 시간이 굉장히 길었던 만큼 다양하고 많은 속성들을 배울 수 있었는데요. 그럼에도 아직까지 체화되어서 자유자재로 쓸 수 있는 상태가 아니어서 더 공부를 하고 실습도 많이 해봐야 할 것 같습니다.
