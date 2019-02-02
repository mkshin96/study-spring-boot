# REST, RESTful, HATEOAS

---
**1. REST(Representational State Transfer)**
- HTTP URI(Uniform Resource Identifier)를 통해 자원(Resource)을 명시하고, HTTP Method(POST, GET, PUT, DELETE)를 통해 해당 자원에 대한 CRUD Operation을 적용하는 것을 의미

- 장단점
  - 장점
    - HTTP 표준 프로토콜에 따르는 모든 플랫폼에서 사용이 가능
    - 서버와 클라이언트의 역할을 명확하게 분리
    - 여러가지 서비스 디자인에서 생길 수 있는 문제를 최소화
  - 단점
    - 표준이 존재하지 않음
    - 사용할 수 있는 메소드가 4가지 밖에 없음(HTTP Method 형태가 제한적)

**2. RESTful**
- 일반적으로 REST라는 아키텍처를 구현하는 웹 서비스를 나타내기 위해 사용되는 용어
  - 'REST API'를 제공하는 웹 서비스를 'RESTful'하다고 할 수 있음
    - API : 데이터와 기능의 집합을 제공하여 프로그램 간 상호작용을 촉진하며, **서로 정보를 교환 가능 하도록 하는 것**
    - REST API
      - REST 기반으로 서비스 API를 구현한 것
      - OpenAPI(누구나 사용 가능하도록 공개된 API, ex)구글 맵, 공공 데이터)

[출처](https://gmlwjd9405.github.io/2018/09/21/rest-and-restful.html)

**3. HATEOAS**
- [HATEOAS 정리](https://jinson.tistory.com/190)
