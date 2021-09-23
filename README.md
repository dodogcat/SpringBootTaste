# SpringBootTaste

https://bedmil.tistory.com/31 글을 따라 만들어진 프로젝트다

하지만 그대로 따라하면 여러가지 문제가 발생한다.

아마도 Spring Initialier 사이트의 내용이 약간 달라져 호환에 문제가 생긴 것으로 보인다.

마주친 문제들

1. Thymeleaf 이 작동하지 않는다. https://bamdule.tistory.com/33 를 참고해서 Dependency를 몇개 추가하면 작동한다.

2. 뭔지 모를 로그인 창이 나온다. Spring Security 때문에 발생한 문제로 관련 Dependency를 주석처리하거나 username에 "user" password에 "Using generated security password:" 뒤에 나오는 값을 입력하면 로그인 가능하다.

3. 사이트가 못생기고 제대로 작동을 안한다. webjar 관련 Dependency를 추가하면 된다.
