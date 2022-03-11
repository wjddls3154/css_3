# css_3
Created with CodeSandbox

![4](https://user-images.githubusercontent.com/37132897/157815186-ff962af2-1fc7-4c79-ba00-cdc425a9a0fe.JPG)
![5](https://user-images.githubusercontent.com/37132897/157815181-fa1b1e2c-fbe1-4b04-ba74-a33b968fddcc.JPG)


position: relative; : 기준점 이동 시킬 수 있다.
overflow: hidden; : 글자가 칸을 넘어가면 안보이게
cursor: pointer; : 커서 갖다대면, 버튼에 올린거마냥 커서모양 바뀌게
transition : all 0.3s : 0.3초 딜레이 준다.

.btn:before : btn 클래스의 내용앞에 무언가 추가가능
position: absolute; : absolute의 기준점은, relative를 지칭한다.relative가 없으면 최상단
z-index는 맨위로 보내기나 맨아래로보내기
height: 0px 를 줬다가, .btn:hover:before 에서 height: 130px; 를 주어서 천천히 올라오는 애니메이션처럼 만듬.
