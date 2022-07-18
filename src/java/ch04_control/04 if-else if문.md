# if-else if문
- if-else 문은 두 가지 경우 중 하나가 수행된다
- 처리해야 할 경우의 수가 셋 이상인 경우 사용하기 유용하다
- 중복 사용 가능

## if-else if문 기본 문법
```
if(조건식 A){
조건식 A가 참(true)일 때 수행될 문장
}else if (조건식 B){
조건식 B가 참일 때 수행될 문장
}else if (조건식 C){
조건식 C가 참일 때 수행될 문장
}else{
맞는 조건식이 없을 때 수행될 문장
}

= 예시 =
int grade = 20;
        if(grade >= 90){
            System.out.println("성적 : A");
        }else if(grade >= 80){
            System.out.println("성적 : B");
        }else if(grade >= 70){
            System.out.println("성적 : C");
        }else if(grade >= 60){
            System.out.println("성적 : D");
        }else{
            System.out.println("성적 : F");
        }
.
.
.
성적 : F
```
- 첫번째 조건문을 먼저 확인한 다음 조건문이 거짓이면 다음 조건문을 살핀다
- 조건식의 결과가 참인 조건문이 없기 때문에 else 문장이 실행되었다
