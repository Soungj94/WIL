변수: 어떤 정보에 이름을 붙여서 사용하소 싶을때 사용합니다

Let 과 Const

1.변수는 문자와 숫자, $와 _ 만 사용 

2.첫글자는 숫자가 될 수 없습니다 

3. 예약어는 사용할 수 없습니다. (let let =99)

4. 가급적 상수는 올 대문자로 알려주세요

5. 변수명은 읽기 쉽고 이해할 수 있게 (isAdult )

 

자료형:

문자형 string "Mike", 'Mike', ``백틱은 문자열 내부의 변수를 정해줄때 편하다${}

숫자형 + - * / %

불형식 Boolean true/false

null 과 undefined

type of 연산자( 자료형)

*숫자형과 문자형을 더할 수 있다 그럴때는 문자형으로 바뀐다는 사실*

 

alert, prompt, confirm

알려줌, 입력받음, 확인받음

단점은 창이 떠있는 동안 스크립트 일시 정지

스타일링 x 그래서 사용하는게 모덜창 

 

형변환 (type conversion)

String() 문자형으로 변환

Number() 숫자형으로 변환 = (true는 1 false 는 0) ("문자는"=NaN), (Null = 0), (undefined=NaN);

Boolean() 불린형으로 변환 =(1, 123, "javascript")== true  (숫자 0, 빈 문자열, null, undefined, NaN) ==  false;

Boolean(0) // false

Boolean('0') // true

Boolean('') //false

Boolean(' ') //true

*자동형변환, 명시적 형변환

 

기본 연산자 (Operators)

*/  > +- 우선순위 

(num = num + 5 는

num +=5 와 같다)

++ 증가 연산자 --감소연산자  (++num 과 num++) 증가시킨 값을 넣어주는것, 증가시키기 전의 값을 넣는것 

 

비교 연산자 

<, >, <=, >=, ==, !=

a=3 을 넣어주는것 == 동등연산자 와는 다르다  === type 까지 똑같은 일치 연산자도 있다

 

조건문 if, else

if, else, else if

 

논리 연산자(And, Or, Not)

|| or , && And, ! Not 

 

반복문 (for, while, do while) loop

for(let i =0; i <4; i ++){}

do while: while 과 비슷한데, 조건문을 아래로 움직일 수 있다, do,,, something while doing something

break: 멈추고 빠져나옴, continue: 멈추고 다음 반복으로 진행

 

switch 문

