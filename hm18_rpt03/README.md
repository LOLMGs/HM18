## HM18의 홈페이지 V3
- Best 3 Movie 클릭시 나오는 이미지 3개 를 각각 마우스를 올리면 사진이 바뀜 <br>
(onmouseover, onmouseout  을 이용)
- Best 3 Movie 예고편 부분 모두 window.open()으로 링크를 변경해주었다.
- Best 3 Movie 와 Best 3 Country 를 클릭한후 콤보박스,라디오박스를 클릭해 다른 페이지로 <br>
이동하는것도 JS 의 onchange를 이용한 것임.
- X-Max 파티 초대장에 이 글씨를 클릭해주세요!! 라는 문구를 추가하고 글씨를 클릭하면 문구가 나오게 했음. <br>
(alert를 이용)
- HM18's Calculator 부분에 간단한 곱셈 퀴즈게임을 추가하였다.
- Hm18's daily life 부분에 time table 글씨와 daily lfe 글씨를 클릭하면 이동하겠냐고 묻는 문구 추가.
- 즐겨찾는 사이트 링크를 클릭하면 이동하겠냐고 묻는 문구를 추가.
- 홈페이지 메인 하단 우측에 현재시간,날짜,요일 이 나오게 추가했다. (초단위로 시간이 변경됨)
- 온도관리(IOT) 부분에 이미지를 클릭하면 이미지가 바뀜(5개)
- 온도관리(IOT) 부분 이미지를 oncontextmenu로 소스보기나 이미지 다운로드를 금지함.
- 온도관리(IOT) 부분에 적용 버튼을 누르면 적용되었다고 알려준다. (alert를 이용)
- Who is Hm18? 글씨에 마우스클릭을하거나 마우스휠을 움직이면 이벤트를 발생시킴.
- who is Hm18? 들어와서 이름 : ( )  등등 ( ) 부분을 클릭하면 글씨가 색깔이 바뀌고 커지게 추가함.
- 동호회 모집안내 - 동호회 정보 - 동호회 소개 부분에 마우스를 올리면 배경색을 바꾸는 이벤트를 추가하였음.
- 동호회 가입 에 제출하기 버튼을 누르면 제출되었다고 알려줌.(alert를 이용)
- 홈페이지 메인에 로그인 버튼을 누르면 로그인이 되었을때의 느낌의 화면으로 넘어가도록 추가함

# V2에서 추가된 html 파일 ( 시작파일은 hm18_rpt03.html ) 
- hm18_fancy_calc.html
- hm18_login_succes.html

# 느낀점
> 이번 Javascript 를 공부하면서 향후에 홈페이지를 건드리게 된다면 JS부분이 매우 중요하다는것을 <br>
> 알게되었고 아직 추가하고 수정하고 보완해야할 부분이 많은 홈페이지를 내가 직접 만들어보고 <br>
> CSS 로 디자인하고 JS 로 코딩을 해보며 좋은 프로젝트를 만들게 되어서 뿌듯하고 <br>
> 한학기 동안 열심히 잘 배운것 같다!. 

## 모두 한 학기동안 고생하셨습니다.

<hr>

## HM18의 홈페이지 V2
- Semantic tag로 화면 layout 구성 하였다. header, nav, section, aside, footer 
- 타이틀을 hm18 : 나는 누구인가? 로 설정하였고 [HM18's Homepage]를 클릭하면 who is hm18? 과 연결된다.<br>
홈페이지 hm18_rpt02.html 를 실행해도 초기화면은 who is hm18? 이다.
- CSS3 스타일을 응용하여 리스트로 가로 메뉴를 만들었다.
- 메뉴에 있는 글씨를 클릭하면 홈페이지 중앙부분에 iframe 를 이용하여 메뉴에 있는 내용을 볼수있다.
- whi is hm18? 부분에 li 에 이미지를 넣어서 나타내었다. 각종 애니메이션과 style 이용해서 색상변경함.
- 나의 하루를 table,th,td 을 이용해 추가하고 Time Table 글씨를 눌러 나의 시간표도 table,th,td 을 이용해 만들었다. <br>
각종 애니메이션과 style 이용해서 색상변경함.
- My Best 3 중 영화,여행 2개를 선택하여 추가했고 datalist 를 통해 영화,여행 을 선택하거나 그림을 선택하면 이동함<br>
영화 부분에 주연의 목록을 datalist 를 이용해서 추가했음. 그리고 줄거리는 details 를 이용해 펼쳐볼수 있음.<br>
그리고 li 에 이미지를 넣어서 나타내었다. 각종 애니메이션과 style 이용해서 색상변경함.
- 동호회 모집 form 을 추가하였고 Web form,fieldset tag 를 사용하여 동호회 모집 정보,가입하기 등을 추가하였고<br>
details 를 이용해 펼쳐서 볼수있게 하였음. 그리도 동호회 부분의 style 는 hm18_style.css 파일을 이용해 나타내보았다.<br>
각종 애니메이션과 style 이용해서 색상변경함.
- 온도관리(IoT) 메뉴를 추가하여 온도와 습도를 조절할수있는 input 을 만들었다. details 를 이용해 펼쳐볼수 있다.<br>
각종 애니메이션과 style 이용해서 색상변경함.
- wk07 에 만든 X-MAS card 를 메뉴에 추가하였다. wk07 폴더안 README.md 참고
- wk07 에 만든 X-MAS card 를 바탕으로 초대장을 만들었고 Table 을 이용해 나타내었다. 각종 애니메이션과 style 이용해서 색상변경함.
- 홈페이지 좌측 부분에는 즐겨찾는 사이트를 새창에 나올수있게 링크를 걸어서 즐겨찾기를 만들어보았다.<br>
 각종 애니메이션과 style 이용해서 색상변경함.
- 홈페이지 우측 부분에 login form 을 만들어 보았고 그 밑에 iframe 를 통해 코로나 확진자수를 볼수있는 사이트를 연결하였다. <br>
각종 애니메이션과 style 이용해서 색상변경함.
- 홈페이지 하단에 HM18 20182572 이정호 나의 이름을 표시했고 각종 애니메이션과 style 이용해서 색상변경함.
- 각종 글씨는 style 를 이용해 color, background 를 이용해 배경색과 글씨색을 설정하였다. 
- 각종 애니메이션은 @keyframes 와 animation ,hover, transform, translate, focus 등을 이용해 움직이게했다.<br>
(마우스를 올리면 색상변경, 이동, 커짐 등등)
- 각종 그림 및 음악은 media folder 에 저장하였고 영상은 link로 처리해서 연결하였다.

# 추가된 html 파일 ( 시작파일은 hm18_rpt02.html )
- hm18_best3country.html
- hm18_best3movie.html
- hm18_club.html
- hm18_club_info.html
- hm18_club_join.html
- hm18_Crime_city.html
- hm18_daily.html
- hm18_Germany.html
- hm18_Germany2.html
- hm18_Germany3.html
- hm18_info2.html
- hm18_IOT.html
- hm18_rpt02.html
- hm18_Spain.html
- hm18_Spain2.html
- hm18_Spain3.html
- hm18_Thailand.html
- hm18_Thailand2.html
- hm18_Thailand3.html
- hm18_timetable.html
- hm18_x-mas_card.html
- hm18_x-mas_invitation.html
- hm18_Your_wedding.html

# 추가된 css 파일
- hm18_style.css
> 동호회 부분에 css 파일을 만들어서 style 에 불러와 보았다.

# 느낀점
> 이번 홈페이지 V2 를 만들면서 진짜 홈페이지 같은 느낌으로 최대한 만들고 색배치를 해보았으며 나만의 홈페이지를 열심히 만들어 보았다.<br>
> 그리고 각종 애니메이션, 그리고 스타일시트를 이용하면서 다양하게 꾸며보고 아름답게 꾸밀수가 있었다. 내 홈페이지를 만들면서 완성된 모습을보고 뿌듯했고<br>
> 수업을 듣고 배우면서 V3 도 열심히 잘 만들어 봐야겠다.
