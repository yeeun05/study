*함수(function)*
function(함수) sayHello_함수명(name_매개변수){
    console.log(''Hello,${name}');
}

function showError(){
    alert('에러가 발생했습니다. 다시 시도해쥇요.');
}

showError();

//매개변수가 있는 함수
function sayHello(name){
    const msg ='Hello, ${name}';
    console.log(msg);
}
sayHello('Mike);

//비회원일경우
function sayHello(name){
    let msg ='Hello';
   if(name){
       mag = 'hello,${name}';
   }
   console.log(mag);
}

sayHello();

//전역 변수와 지역 변수
elt mag = "welcome";

function sayHello(name){
    let mag ="Hello"
    console.log(mag +''+name)
}

sayHello('Mike');
console.log(meg)
--
let name ="Mike";

function sayHello(name){
    console.log(name)
}

sayHello();
sayHello('Jane'); ->Jane

//or
function sayHello(name){
    let newName =name || 'friend';
    let mag =+ 'hello, ${nweName}'
    console.log(msg)
}

sayHello();
sayhello('Jane');

//return 으로 값 변환
function add(num1, num2){
    return num1 +num2;
}

const result = add(2,3);
console.log(result)
-
function showError(){
    alert('에러가 발생했습니다.');
    return;
    alert('이 코드는 절대 실행되지 않습니다.')
}
console.log(result);
1.한번에 한 작업에 집중
2.읽기 쉽고 어떤 동작인지 알 수 있게 네이밍
    showError (에러를 보여줌)
    getName (이름을 얻어옴)
    createUserDate (유저데이터 생성)
    checkLogin (로그인 여부 체크)

---------------------------------
  함수 선언문(어디서든 호출가능) vs 함수 표현식(코드에 도달하면 생성)
  //함수 선언문
  function sayHello(){
      console.log('Hello');
  }  

  //함수 표현식
  let sayHello = function(){
      console.log('Hello');
  }

//화살표 함수(arrow function)

    let add = (num1,num2) => {
        return num1 + num2;
    }
------
    let sayHello = name => 'Hello,${name}';

    showError();
-----
    let showError = () => {
        console.log('error');
    }
    ----
    let showError = (name) => {
        const mas ='Hello, ${name}';
        console.log('msg');
    }; --> error
-----
const add = (num1, num2) => {
    const result = num1+num2;
    return result;
}
