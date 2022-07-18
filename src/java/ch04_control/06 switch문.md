# switch문
- if문은 조건식의 결과가 참 / 거짓 두가지 밖에 없기 때문에 경우의 수가 많아질 수록

  else - if를 계속 추가해야 하므로 복잡해지고 처리시간도 많이 걸린다


- switch문은 단 하나의 조건으로 많은 경우의 수를 처리할 수 있고 표현도 간결하면서 알아보기 쉽다


- 그래서 처리할 경우의 수가 많은 경우에는 if문보다 유용하다 다만 제약조건이 있기 때문에 
  
  경우의 수가 많아도 if문을 사용해야 하는 경우가 있다 

## switch문의 제약조건
- switch : 정수, 문자, 문자열이어야 한다(변수사용 불가)
- case문의 값은 정수 상수(문자 포함), 문자열만 가능하며 중복은 불가하다

## switch문 기본 문법
- 하나의 case가 끝나는 마지막에는 'break'문을 사용해서 종료한다
- default : 매칭되는 case 값이 없을때 실행 할 코드가 있으면 사용합니다(사용은 선택사항)
- break : switch 종료
```
switch(조건식){
  case 상수값:
    실행코드
    break;
  case 상수값:
    실행코드
    breakl;
    default;
    실행코드
}

= 예시 =
        int num = 10;

        switch(num){
            case 2:
            case 4:
            case 6:
            case 8:
            case 10:
                System.out.println("num : 1 ~ 10중 짝수");
                break;
            case 1:
            case 3:
            case 5:
            case 7:
            case 9:
                System.out.println("num : 1 ~ 10중 홀수");
                break;
            default:
                System.out.println("num : ?");
        }
.
.
.
num : 1 ~ 10중 짝수
```
1. num 의 값을 10으로 저장했다

2. switch 의 조건 즉 num의 값에 따라 문장을 출력하게끔 코드를 짠다
3. case(2,4,6,8,10) : num의 값이 2,4,6,8,10 중 하나일 경우 "num : 1 ~ 10중 짝수" 문장이 출력되고

   break문에 의해 코드가 종료된다
4. 같은 개념으로 num의 값이 홀수였다면 "num : 1 ~ 10중 홀수"라는 문장이 출력된다
5. 매칭되는 case값이 없을 경우 default 문 아래 문장이 실행된다
