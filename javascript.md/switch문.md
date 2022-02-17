switch(평가){
    case A : A일때 코드
    case B : B일때 코드...
}

if문 일때 
if (평가==A){
    A일때 코드
}else if(평가 == B){
    B일때 코드
}

ex)
사과 : 100원
바나나 : 200원
키위 : 300원
멜론 : 400원
수박 : 500원
사고 싶은 과일을 물어보고 가격 알려주기

let fruit = prompt('무슨 과일을 사고 싶나요?');

switch(frruit){
    case '사과';
    console.log('100원 이니다.');
    break;
    case '바나나';
    console.log('200원 이니다.');
    break;
    case '키위';
    console.log('300원 이니다.');
    break;
    case '멜론';
    console.log('400원 이니다.');
    break;
    case '수박';
    console.log('500원 이니다.');
    break;
    defaut:
    console.log('그런 과일은 없습니다.');
}
