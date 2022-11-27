# JavaScript의 ES란?, ES5/ES6 문법 차이

우선 자바스크립트의 ES란 ??

ES는 ECMA Script의 약자

자바스크립트는 1990년대 Netscape 회사의 Brendan Eich 라는 사람에 의해 최초 개발되었다. 자바스크립트가 잘 되자, MS에서 Jscript라는 언어를 개발해 IE에 탑재하였는데, 이 두 스크립트가 너무 제각각이라, 표준이 필요하게 되었다..

표준을 위해 자바스크립트를 ECMA(European Computer Manufactures Association)라는 정보와 통신시스템의 비영리 표준 기구에 제출하였고 표준에 대한 작업을 ECMA-262란 이름으로 1996년 11월에 시작해 1997년 6월에 채택되었다.

ES5는 ECMA Script5의 규격을 따른다고 생각하면 된다.

현재는 👉 ES6 ECMA Script6의 규격을 따르고 있다.

즉 ECMA 스크립트는 규격, 표준 즉, 스펙을 말한다.

1️⃣ ES5문법

1. 배열과 관련해서 새로운 메소드들이 생겼는데 대표적으로 forEach, map, filter, reduce, some, every와 같은 메소드가 생김.

이 메소드들은 개발자가 반복 횟수나 조건을 잘못 입력하는 등의 실수를 줄여주는 효과 있음. 2. object에 대한 getter/setter 지원 3. 자바스크립트 strict 모드 지원(더욱 세심하게 문법 검사) 4. JSON 지원(과거에는 XML을 사용하다가, json이 뜨면서 지원) 5. bind() 메소드가 생겼습니다. (this를 강제로 bind 시켜주는 메소드)

2️⃣ ES6문법

1. let, const 키워드 추가
2. arrow 문법 지원

3. iterator / generator 추가

4. module import / export 추가

5. Promise 도입 ( Callback Hell을 해결해 줄 기법이 추가 되었습니다.)

6. Default, Rest 파라미터

7. 해체 할당, Spread 연산자

8. 템플릿 리터럴

9. 호이스팅이 사라진 것 같은 효과

10. 함수 단위 스코프에서 블록 단위 스코프로 변경

11. 화살표 함수를 사용
