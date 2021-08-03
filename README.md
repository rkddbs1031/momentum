# JavaScript & HTML & CSS로 만든 chrome momentum 클론 코딩
01) login 및 greeting 기능
02) To Do List 기능
03) clock 기능
04) random 기능
05) openweathermap의 API를 이용하여 위치, 온도 등 제공 기능

01)greeting.js
- form에 의한 submit event가 발생할 시 localstorage에 id 정보 저장.
- localstorage에 저장되는 id 값의 유무에 따른 form과 greeting문장 show or hidden
- Date 객체를 이용하여 시간 정보를 표현.
- if문을 이용하여 시각에 따른 인사말이 변경. 
ex)12시 이전 : Good Morning ,-
- 저장된 사용자의 id(name) 삭제 가능 -> 삭제 후 페이지 reload

02)todo.js
- 해당 input박스에 입력한 value값을 localstorage에 string타입으로 저장
- 선택한 list를 삭제하기 위해 각 list에 랜덤으로 id를 지정.
- to do list 추가 및 삭제 가능

03)clock.js
- Date 객체를 이용하여 시간 정보를 표현.
- SetInteval함수로 인해 일정주기 즉 , 1초 단위로 (설정) 실행 되도록 설정.


04)background.js & quotes.js
- 배열 및 객체 생성하여 알맞는 정보들 저장
- Math.floor,Math.random()을 이용하여 랜덤으로 저장된 background이미지와 quoute들이 화면에 송출.

05)weather.js
- openweathermap의 API를 이용하여 사용자의 위치, 온도, 날씨 등 제공 기능 
-> 날씨는 추후에 이미지로 넣을 계획


