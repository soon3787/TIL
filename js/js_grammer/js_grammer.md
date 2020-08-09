## 자바스크립트(JavaScript)란?
자바스크립트(JavaScript)는 객체(object) 기반의 스크립트 언어입니다.
HTML로는 웹의 내용을 작성하고, CSS로는 웹을 디자인하며, 자바스크립트로는 웹의 동작을 구현할 수 있습니다.
자바스크립트는 주로 웹 브라우저에서 사용되나, Node.js와 같은 프레임워크를 사용하면 서버 측 프로그래밍에서도 사용할 수 있습니다.

## 자바스크립트의 특징
1. 자바스크립트는 객체 기반의 스크립트 언어입니다.
2. 자바스크립트는 동적이며, 타입을 명시할 필요가 없는 인터프리터 언어입니다.
3. 자바스크립트는 객체 지향형 프로그래밍과 함수형 프로그래밍을 모두 표현할 수 있습니다.

##  자바스크립트 문법
자바스크립트의 실행문은 세미콜론(;)으로 구분됩니다.
```
예) var x = 10;
var result = x + 3;
```
자바스크립트는 대소문자를 구분합니다.
자바스크립트에서 변수나 함수의 이름, 예약어 등을 작성하거나 사용할 때에는 대소문자를 정확히 구분해서 사용해야 합니다.
```
예) var javascript = 10; // 변수 javascript와 JavaScript는 서로 다른 두 개의 변수로 인식됨.
var JavaScript = 20;
Var Script = 30; // 변수의 선언은 var 키워드로만 할 수 있으면 Var는 동작하지 않음.
```

## 리터럴(literal)
리터럴은 직접 표현되는 값 그 자체를 의미합니다.
```
예) 12            // 숫자 리터럴
"JavaScript"  // 문자열 리터럴
'안녕하세요'  // 문자열 리터럴
true          // 불리언 리터럴
```
## 식별자(identifier)
식별자는 변수나 함수의 이름을 작성할 때 사용하는 이름을 의미합니다.
자바스크립트에서 식별자는 영문자(대소문자), 숫자, 언더스코어(_) 또는 달러($)만을 사용할 수 있습니다.

## 식별자 작성 방식
1. Camel Case 방식이란 식별자가 여러 단어로 이루어질 경우에 첫 번째 단어는 모두 소문자로 작성하고, 그다음 단어부터는 첫 문자만 대문자로 작성하는 방식입니다.
2. Underscore Case 방식은 식별자를 이루는 단어들을 소문자로만 작성하고, 그 단어들은 언더스코어(_)로 연결하는 방식입니다.
```
예) var firstVar = 10;           // Camel Case 방식
function my_first_func {     // Underscore Case 방식
    var firstLocalVar = 20;  // Camel Case 방식
}
```

## 키워드(keyword)
자바스크립트에서는 몇몇 단어들을 특별한 용도로 사용하기 위해 미리 예약하고 있습니다.
이렇게 미리 예약된 단어들을 키워드(keyword) 또는 예약어(reserved word)라고 합니다.
```
예) var firstVar = 10;      // var는 변수의 정의를 위해 예약된 키워드입니다.
function myFirstFunc {  // function은 함수의 정의를 위해 예약된 키워드입니다.
    var secondVar = 20; // var는 변수의 정의를 위해 예약된 키워드입니다.
}
```


## 주석(comment)
주석(comment)이란 코드 내에 삽입된 일종의 설명문입니다.
주석은 작성자나 다른 개발자가 나중에 코드를 수정할 때 참고할 수 있으며, 웹 페이지 개발 시 디버깅에도 사용됩니다.
```
문법) 1. 한 줄 주석 : // 주석문
2. 여러 줄 주석 : /* 주석문 */
```