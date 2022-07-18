# Switch : Membership

<br />

## 회원 등급에 따라 할인을 해주는 코드 만들어 보기
- vip  : 20%
- gold : 15%
- silver : 10%
- general : 0%

<br />

### 작성한 코드
```
        Scanner scanner = new Scanner(System.in);

        System.out.println("고객명 : ");
        String name = scanner.next();

        System.out.println("등급 : ");
        String member = scanner.next();

        int dc = 0;

        switch(member){
            case "vip":
                dc = 20;
                break;
            case "gold":
                dc = 15;
                break;
            case "silver":
                dc = 10;
                break;
            case "general":
                dc = 0;
            default:
                System.out.println("입력 오류,다시 입력하시오");
        }

        System.out.println("==등급별 할인율==");
        System.out.println("고객명 : " + name);
        System.out.println("등급 : " + member);
        System.out.println("할인율 : " + dc + "%");
        .
        .
        .
        =코드 실행 결과=
        고객명 : 
        java
        등급 : 
        gold
       ==등급별 할인율==
       고객명 : java
       등급 : gold
       할인율 : 15%
```
1. Scanner를 이용하여 고객명, 고객등급을 키보드로 직접 입력받는다
2. 할인율의 초기값은 0으로 설정해놓는다
3. switch문의 조건식으로 입력한 고객등급으로 설정한다
4. 입력한 고객등급이 해당하는 case의 값이 있는지 확인하고 있다면 할인율(dc)을 바꿔준다
5. 입력한 고객명, 등급, 등급에 따른 할인율을 모두 출력해준다
