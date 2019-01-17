# Study-Spring-Boot

![교재](/1.jpg)

#### 2018 겨울방학 스터디
 - 교재 : 처음 배우는 스프링 부트2(한빛미디어)
 - 인원 : [민경환](https://www.github.com/ber01), [박동현](https://www.github.com/pdh6547), [신무곤](https://www.github.com/mkshin96), [신재홍](https://www.github.com/woghd9072), [양기석](https://www.github.com/yks095), [엄태균](https://www.github.com/etg6550), [임동훈](https://www.github.com/dongh9508), [최광민](https://www.github.com/rhkd4560), [하상엽](https://www.github.com/hagome0)

1. 의존성
  - 코드에서 두 모듈 간의 연결.
  - 일반적으로 둘 중 하나가 다른 하나를 어떤 용도를 위해 사용함.

2. 의존성 주입
  - DI는 스프링 컨테이너가 지원하는 핵심 개념 중 하나.
  - DI는 객체 사이의 의존 관계를 객체 자신이 아닌 외부의 조립기(스프링 컨테이너)가 수행한다는 개념.
  - 스프링은 설정 파일이나 어노테이션을 이용하여 객체 간의 의존 관계를 설정 가능.

3. Bean container
  - Spring에서 의존 관계들을 관리하는 컨테이너, DI를 위해 사용.

4. @Rest Controller
  - 기존의 Controller처럼 뷰만 처리하는 것이 아닌 데이터를 처리하는 컨트롤러

5. @Value
  - 프로퍼티의 키를 사용하여 특정한 값을 호출 할 수 있다. 값이 없을 경우 예외처리를 해줘야함.

6. @RunWith
  - JUnit 프레임워크의 테스트 실행 방법을 확장할 때 사용하는 어노테이션

7. @Get Mapping
  - 컨트롤러 내부에서 uri경로를 설정하는 어노테이션

8. @SpringBootConfiguration
  - 스프링 부트의 설정을 나타내는 어노테이션. 스프링의 @Configuration을 대체하며 스프링 부트 전용으로 사용. 예를 들어 스프링 부트의 테스트 어노테이션을 사용할 때 찾기 알고리즘을 사용하여 계속 @SpringBootConfiguration 어노테이션을 찾기 때문에 스프링 부트에서는 필수 어노테이션.

9. @EnableAutoConfiguration
  - 자동 설정의 핵심 어노테이션. 클래스 경로에 지정된 내용을 기반으로 영리하게 설정 자동화를 수행. 특별한 설정값을 추가하지 않으면 기본값으로 작동.

10. JSON(JavaScript Object Notation)
  - DATA-교환형식

11. @(Annotation)
  - 인터페이스를 기반으로 한 어떠한 기능을 주입하는데 사용하는 것

12. JDBC(JAVA DATABASE CONNECTIVITY)
  - 자바에서 데이터베이스에 접속할 수 있도록 하는 자바 인터페이스(인터페이스가 중요!)

13. h2
  - 자바로 작성된 인메모리 관계형 데이터베이스
