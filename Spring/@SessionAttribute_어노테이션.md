# SessionAttribute
### @SessionAttribute란?
모델(model) 정보를 HTTP 세션에 저장해주는 어노테이션이다.

HTTPSession을 직접 사용할 수도 있지만, SessionAttribute의 경우 이 어노테이션에 설정한 이름에 해당하는 모델 정보를 세션에 넣어준다.

SessionAttribute는 여러 화면에서 사용해야 하는 객체를 공유할 때 사용한다.
ex) 장바구니, 여러화면에 걸쳐 나누어진 회원가입

### 장점
직접 세션 객체에 (setAttribute(), getAttribute() 메서드를 사용하여 작업을 할 수 있지만, @ModelAttribute가 세션에 객체를 저장하고, 찾도록 한정할 수 있다는 장점이 있다.

 또한 @ModelAttribute와 같이 사용해서 세션 객체에 넣고 빼는 작업을 숨겨주고 스프링 form 태그와 연동되어 폼에 값을 넣는 작업도 단순화 되는 장점이 있다.

### @SessionAttribute 사용 시 주의점
SessionStatus의 setComplete 메소드를 활용하여 세션을 할당 해지 시켜줘야한다.
그렇게 하지 않으면 세션에 계속 남아있게 된다.

> 출처 : https://2ham-s.tistory.com/309