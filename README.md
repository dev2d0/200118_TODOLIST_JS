## 200118_TODOLIST_JS

# Todo.js
**let todos = [];**<br />
todolist에 담길 배열을 선언한다.<br />

**deleteTodo(event)**<br />

**displayTodo(text)**<br />
html태그를 추가하여 todolist를 웹에서 보이게 하는 함수<br />


**handleTodoSubmit(event)**<br />

**loadTodo()**<br />

**init()** <br />

# Clock.js

**getTime()**<br />
const date = new Date();: 현재 날짜와 시간을 가지는 인스턴스를 반환한다.<br />
날짜와 시간을 각각 자바스트립트의 get data methods를 이용하여 받아오고 출력해준다. <br />

**setInterval(getTime, 1000);**<br />
1초마다 gettime함수를 호출함<br />

# Greeting.js

**doGreeting**<br />
Hello 뒤에 이름을 쓰면 <br />
Hide를 지워서 Hello를 보이게 하고<br />
Title에 hide를 지워서 글씨를 보이게한다<br />

**saveName**<br />
localStorage에 NAME_LS를 저장한다.<br />

**handleSubmit**<br />
CurrentValue애 인풋값을 넣고 doGreeting, saveName함수에 Current을 인자로 호출한다.<br />

**loadName**<br />
loadeName에 저장된 NAME_LS값을 저장하고 저장된 인자가 없으면 doGreeting을 실행함<br />


**init()**<br />

