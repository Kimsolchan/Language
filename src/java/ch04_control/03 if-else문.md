# if-else문
- if문의 변형
- 조건식의 결과가 참이 아닐 때(false) else문의 문장을 수행한다

## if-else문 기본 문법
```
if(조건식){
조건식의 결과가 참(true)이면 이 문장들이 실행된다
}else{
조건식이 거짓(false)이면 이 문장이 실행된다
}

= 예시 =
int time = 6;

if(time > 8){
System.out.println("일어날 시간이야!");
}else{
System.out.println("아직 자도 괜찮아");
}
.
.
.
아직 자도 괜찮아
```
- if조건식(time > 9)의 결과가 거짓이기 때문에 else문 안에 문장이 실행된다
