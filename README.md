# Contents
- [Java](https://github.com/Hyung1Jung/LearnKit#-java-study-)
- [Kotlin](https://github.com/Hyung1Jung/LearnKit#-kotlin-)
- [Spring Framework](https://github.com/Hyung1Jung/LearnKit#-spring-framework-)
- [Jpa](https://github.com/Hyung1Jung/LearnKit#-jpa-)
- [Database](https://github.com/Hyung1Jung/LearnKit#-database-)
- [Network](https://github.com/Hyung1Jung/LearnKit#-network-)
- [Operating System](https://github.com/Hyung1Jung/LearnKit#-os-)
- [infra](https://github.com/Hyung1Jung/LearnKit#-infra-)  
- [IntelliJ](https://github.com/Hyung1Jung/LearnKit#-intellj-tip-)

---

## 📄 JAVA STUDY 🔍
**[repository 보기](https://github.com/Hyung1Jung/JAVA)**

### JVM 메모리 동작 관련 및 GC
* [JVM 메모리 구조](https://junghyungil.tistory.com/94?category=892275)
* [상수 풀(String Pool)은 GC가 될까?](https://junghyungil.tistory.com/210)
* [Garbage collection(1)](https://junghyungil.tistory.com/8?category=892275)
* [Garbage collection(2)](https://junghyungil.tistory.com/9?category=892275)
* [시간 복잡도와 BiG-O 표기법](https://junghyungil.tistory.com/10?category=892275)
* [Call by value의 메모리 관리 과정](https://junghyungil.tistory.com/89?category=892275)
* [JVM과 하드웨어 아키텍쳐 간의 관계](https://junghyungil.tistory.com/127)
* [메모리 누수(Memory Leak)과 GC 성능 튜닝](https://junghyungil.tistory.com/133?category=892275)

### 스트링
* [String, String +, StringBuffer, StringBuilder, Wrapper Class, boxing & unboxing](https://junghyungil.tistory.com/70?category=892275)

### 제네릭
* [제네릭](https://junghyungil.tistory.com/71?category=892275)

### 상속, 인터페이스, Enum
* [열거형 Enum](https://junghyungil.tistory.com/88?category=892275)

### I/O, Serializable과 NIO
* [표준 입출력스트림](https://junghyungil.tistory.com/72?category=892275)
* [바이트 단위 입출력 스트림](https://junghyungil.tistory.com/73?category=892275)
* [문자 단위 입출력 스트림, 그 외 입출력 스트림](https://junghyungil.tistory.com/74?category=892275)
* [보조 스트림](https://junghyungil.tistory.com/75?category=892275)
* [Serializable과 NIO](https://junghyungil.tistory.com/77?category=892275)
* [Serializable, 마커 인터페이스](https://junghyungil.tistory.com/120?category=892275)

### 콜렉션
* [Collection](https://junghyungil.tistory.com/90?category=892275)
  * [List, array vs arrayList, arrayList vs LinkedList](https://junghyungil.tistory.com/91?category=892275)
  * [Set, Queue](https://junghyungil.tistory.com/92?category=892275)
  * [Map 및 HashTable vs HashMap, LoadFactor, bucket에 관해 자세히](https://junghyungil.tistory.com/93?category=892275)
* [ArrayList 깊은 복사, 얕은 복사](https://junghyungil.tistory.com/category/Java)
* [ArrayList는 어떻게 동적으로 사이즈가 늘어나는가? add() flow(동작 방식)](https://junghyungil.tistory.com/96?category=892275)
* [PriorityQueue(우선순위 큐)와 용량 및 동작방식](https://junghyungil.tistory.com/102?category=892275)
* [ConcurrentHashMap](https://junghyungil.tistory.com/104?category=892275)
* [일급 컬렉션](https://junghyungil.tistory.com/112?category=892275)
* [ArrayDeque](https://junghyungil.tistory.com/116?category=892275)
* [블로킹 큐(Blocking Queues)](https://junghyungil.tistory.com/128?category=892275)

### 싱글톤
[싱글톤 패턴은 객체가 단 1개만 생성되는 것을 보장할까? 및 자바에서 싱글톤을 구현하는 패턴들](https://junghyungil.tistory.com/150?category=892275)

### 쓰레드
* [자바 병렬 프로그래밍 - 병렬 처리의 중요성 (1)](https://junghyungil.tistory.com/198)
* [자바 병렬 프로그래밍 - 스레드 안전성(Thread Safe) (2)](https://junghyungil.tistory.com/200)
* [쓰레드](https://junghyungil.tistory.com/68?category=892275)
* [멀티 쓰레드](https://junghyungil.tistory.com/69?category=892275)
* [쓰레드들에 대한 변수의 변경의 가시성을 보장하는 volatile 키워드](https://junghyungil.tistory.com/99?category=892275)
* [쓰레드 영역에 변수를 설정하여 특정 쓰레드가 실행하는 코드에서 그 쓰레드의 설정된 변수 값을 사용할 수 있는 ThreadLocal](https://junghyungil.tistory.com/100?category=892275)
* [Fork Join Pool](https://junghyungil.tistory.com/103?category=892275)
* [64비트는 왜 원자적이지 않을까? 및 연산의 원자성에 관한 고찰](https://junghyungil.tistory.com/126?category=892275)
* [Blocking I/O, Non-Blocking I/O(NIO)와 대용량 트레픽](https://junghyungil.tistory.com/131?category=892275)

### 람다, 옵셔널, 스트림
* [람다식](https://junghyungil.tistory.com/39?category=892275)
* [스트림, 람다를 활용할 수 있는 기술중 하나인 스트림](https://junghyungil.tistory.com/40?category=892275)
  * [스트림 API 3가지 매칭메소드](https://junghyungil.tistory.com/48?category=892275)
  * [스트림 메서드 정리](https://junghyungil.tistory.com/49?category=892275)
* [옵셔널](https://junghyungil.tistory.com/44?category=892275)

### 디자인 패턴
* [템플릿 메서드 패턴](https://junghyungil.tistory.com/64?category=892275)
* [템플릿 메서드 활용 ~ ing]()
* [싱글톤 패턴(1)](https://junghyungil.tistory.com/66?category=892275)
* [데코레이터 패턴](https://junghyungil.tistory.com/67?category=892275)
* [전략 패턴](https://junghyungil.tistory.com/106?category=892275)
* [어댑터 패턴](https://junghyungil.tistory.com/107?category=892275)
* [프록시 패턴](https://junghyungil.tistory.com/109?category=892275)
* [팩토리 메서드 패턴](https://junghyungil.tistory.com/115?category=892275)

### 성능 튜닝
* [반복문? 알고 쓰자!](https://junghyungil.tistory.com/65?category=892275)
* [서버를 어떻게 세팅해야 할까?](https://junghyungil.tistory.com/172)

### 자바 객체 지향의 원리와 이해
* [스프링을 위한 자바 객체 지향의 원리와 이해를 읽으며 중요한 것들 위주로 정리](https://junghyungil.tistory.com/97?category=892275)
* [객체 지향 설계 5원칙 - SOLID](https://junghyungil.tistory.com/98?category=892275)

### 이펙티브 자바
* 2장, 객체 생성과 파괴
  * [아이템 1 : 생성자 대신 정적 팩터리 메서드를 고려하라](https://github.com/Hyung1Jung/JAVA/tree/master/src/effectiveJava/chapter02/item01)
  * [아이템 2 : 생성자에 매개변수가 많으면 빌더를 고려하라](https://github.com/Hyung1Jung/JAVA/tree/master/src/effectiveJava/chapter02/item02)

### 그 외
* [재귀호출](https://junghyungil.tistory.com/16?category=892275)

---

## 📄 Kotlin 🔍
**[repository 보기](https://github.com/Hyung1Jung/kotlin)**

- 기본 개념
  - [기본 문법, 변수와 자료형, 함수, 연산자 개념 정리](https://github.com/Hyung1Jung/kotlin/blob/master/basic/src/me/hyungil/%EA%B0%9C%EC%9A%94%20%EB%B0%8F%20%EA%B8%B0%EB%B3%B8%20%EB%AC%B8%EB%B2%95.md)
  - [제어문 -> IF문, When, 반복문, break countinue return](https://github.com/Hyung1Jung/kotlin/blob/master/basic/src/me/hyungil/%EC%A0%9C%EC%96%B4%EB%AC%B8.md)
  - [객체지향 -> 생성자, 상속, 모듈, 접근제한자, Property, 지연초기화, Overriding, Any, this와 super, 추상클래스, 인터페이스](https://github.com/Hyung1Jung/kotlin/blob/master/basic/src/me/hyungil/%EA%B0%9D%EC%B2%B4%EC%A7%80%ED%96%A5%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D.md)
  - [kotlin의 다양한 클래스 -> Companion, DataClass, Generic, 중첩클래스, 형변환, null처리 및 안전성을 위한 형변환, 열거형, Sealed Class, 리플렉션, 연산자 오버로딩](https://github.com/Hyung1Jung/kotlin/blob/master/basic/src/me/hyungil/kotlin%EC%9D%98%20%EB%8B%A4%EC%96%91%ED%95%9C%20%ED%81%B4%EB%9E%98%EC%8A%A4.md)
  - [함수형 프로그래밍 -> 익명, 인라인, 확장, Infix, 고차 함수](https://github.com/Hyung1Jung/kotlin/blob/master/basic/src/me/hyungil/%ED%95%A8%EC%88%98%ED%98%95%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D.md)
  - [kotlin의 컬렉션](https://github.com/Hyung1Jung/kotlin/blob/master/basic/src/me/hyungil/kotlin%EC%9D%98%20%EC%BB%AC%EB%A0%89%EC%85%98.md)
  
- [코틀린 공식 레퍼런스 공부](https://github.com/Hyung1Jung/kotlin#%EC%BD%94%ED%8B%80%EB%A6%B0-%EA%B3%B5%EC%8B%9D-%EB%A0%88%ED%8D%BC%EB%9F%B0%EC%8A%A4-%EA%B3%B5%EB%B6%80-%EA%B8%B0%EB%A1%9D)
- [코틀린 인 액션](https://github.com/Hyung1Jung/kotlin#%EC%BD%94%ED%8B%80%EB%A6%B0-%EC%9D%B8-%EC%95%A1%EC%85%98)

- Kotlin + SptringBoot 
  - [kotlin에서 Lombok가 필요할까?](https://junghyungil.tistory.com/157?category=953012)
  - [코틀린에서 빌더를 사용할 필요가 있을까?](https://junghyungil.tistory.com/184)
  - [유지보수하기 좋은 코드란? 및 확장성을 고려한 설계](https://junghyungil.tistory.com/158?category=953012)
  - [entity class에서 Id를 선언할 때, 생성자의 파라미터 순서 상 가장 밑으로 두는 것이 좋은 이유](https://junghyungil.tistory.com/205?category=953012)
  - [가변성을 제한하라](https://junghyungil.tistory.com/214)
---

## 📄 Spring Framework 🔍

**[repository 보기](https://github.com/Hyung1Jung/spring-study-record)**

* [스프링이란 무엇?](https://junghyungil.tistory.com/11)
* [Spring이 왜 Spring인지? 와  SpringBoot VS Spring](https://junghyungil.tistory.com/62?category=892281)
* [레이어 구조](https://junghyungil.tistory.com/86?category=892281)
* [IntellJ로 Maven(Spring Boot) 프로젝트 생성하기](https://junghyungil.tistory.com/29?category=892281)
* [Spring Boot Devtools을 이용한 자동화](https://junghyungil.tistory.com/36?category=892281)
* [의존성 주입(DI)과 스프링 및 테스트코드](https://junghyungil.tistory.com/13?category=892281)
* [필드주입보다 생성자 주입을 권하는 이유, Autowired의 3가지 방법](https://junghyungil.tistory.com/50?category=892281)
* [프론트와 백이 서로 다른 주소를 가지고 있을 때 @CrossOrigin을 이용한 통신](https://junghyungil.tistory.com/80?category=892281)
* [HTTP 방식 중 URLConnection, HttpClient보다  RestTemplate가 효율적인 이유](https://junghyungil.tistory.com/84?category=892281)
* [RestTemplate(2), xml -> json 변환 후, jackson을 이용하여 DTO와 mapping](https://junghyungil.tistory.com/87?category=892281)
* [Filter와 Interceptor](https://junghyungil.tistory.com/123?category=892281)
* [Profile](https://junghyungil.tistory.com/159?category=892281)
* [log4j vs Lockback vs log4j2, 프로젝트에 무엇을 적용하는게 좋을까?](https://junghyungil.tistory.com/160?category=892281)
* [Log4j2의 Log Level과 성능 향상에 관하여](https://junghyungil.tistory.com/161?category=892281)
* [opaque token을 사용하여 JWT 자체 만료시간 강제 무효화 하기](https://junghyungil.tistory.com/191)
* [SMTP 메일 인증 시, 로컬에서는 잘 작동하는데 EC2에서는 왜 FAIL이 발생할까?](https://junghyungil.tistory.com/211)
* [상품 주문 시, Pessimistic Lock으로 동시성 제어](https://junghyungil.tistory.com/212)

- 인프런, 스프링 핵심원리 기본편 정리
  - [DI, IOC, Bean, Context 등등](https://www.notion.so/2815624d66fa46f98aed3a9184523499)
  
### Junit5
* [단위테스트 & 통합테스트](https://junghyungil.tistory.com/85?category=892281)
* [단위테스트시 좀 더 정확한 테스트를 위하여 고급 기술 ArgumenMatcher](https://junghyungil.tistory.com/51?category=892281)
* [checked exception을 unchecked exception으로 변경해서 던져야 하는 경우](https://junghyungil.tistory.com/52?category=892281)
* [예외처리를 위한 ExceptionHandler 및 아주 간단한 responseentity](https://junghyungil.tistory.com/53?category=892281)
* [responseentity / 작성중](https://junghyungil.tistory.com/)
* [예외처리 할 때, controller 전역에 적용되는 ControllerAdvice annotation -> 1. @RestControllerAdvice](https://junghyungil.tistory.com/57?category=892281)
* [예외처리 할 때, controller 전역에 적용되는 ControllerAdvice annotation -> 2. @ControllerAdvice](https://junghyungil.tistory.com/57?category=892281)
* [Junit4 -> Junit5 (목적(쓰임새)은 같지만 4 -> 5 로직 비교)](https://junghyungil.tistory.com/78?category=892281)

- 인프런, 더 자바
    - [Junit5, Mockito, 도커와테스트 및 성능테스트 정리](https://www.notion.so/e905531d8b4248feabeb8958cb976481)
    - [코드 모음](https://github.com/Hyung1Jung/spring-study-record/tree/master/inflearn-the-java-test/src)
    - [출처](https://www.inflearn.com/course/the-java-application-test#curriculum)

### AOP
* [Spring AOP와 AspectJ](https://junghyungil.tistory.com/111?category=892281)
* [Spring AOP(Aspect)를 이용한 메서드 시간측정 및 @LogExecutionTime, JoinPoint 활용 ](https://junghyungil.tistory.com/56?category=8922)

### Gradle 관련
* [implementation와 api(compile)](https://junghyungil.tistory.com/148?category=892281)

### 스프링을 위한 객체지향
* [스프링을 위한 자바 객체 지향의 원리와 이해를 읽으며 중요한 것들 위주로 정리](https://junghyungil.tistory.com/97?category=892275)
* [객체 지향 설계 5원칙 - SOLID](https://junghyungil.tistory.com/98?category=892275)

### 토비의 스프링 (면접에서 물어볼만한 키워드들로 정리...공부하며 밑 줄친 문장들 위주...)
* [들어가며](https://github.com/Hyung1Jung/spring-study-record/blob/master/toby-of-spring/0.%20%EB%93%A4%EC%96%B4%EA%B0%80%EB%A9%B0.md)
* [1장, 오브젝트와 의존관계](https://github.com/Hyung1Jung/spring-study-record/blob/master/toby-of-spring/1.%20%EC%98%A4%EB%B8%8C%EC%A0%9D%ED%8A%B8%EC%99%80%20%EC%9D%98%EC%A1%B4%EA%B4%80%EA%B3%84.md)
* [2장, 테스트](https://github.com/Hyung1Jung/spring-study-record/blob/master/toby-of-spring/2.%20%ED%85%8C%EC%8A%A4%ED%8A%B8.md)
* [3장, 템플릿](https://github.com/Hyung1Jung/spring-study-record/blob/master/toby-of-spring/3.%20%ED%85%9C%ED%94%8C%EB%A6%BF.md)
* [4장, 예외처리](https://github.com/Hyung1Jung/spring-study-record/blob/master/toby-of-spring/4.%20%EC%98%88%EC%99%B8%EC%B2%98%EB%A6%AC.md)
* [5장, 서비스와 추상회](https://github.com/Hyung1Jung/spring-study-record/blob/master/toby-of-spring/5.%20%EC%84%9C%EB%B9%84%EC%8A%A4%EC%99%80%20%EC%B6%94%EC%83%81%ED%99%94.md)
* [6장, AOP](https://github.com/Hyung1Jung/spring-study-record/blob/master/toby-of-spring/6.%20AOP.md)

---

## 📄 JPA 🔍
**[repository 보기](https://github.com/Hyung1Jung/jpa)**

* [자바 ORM 표준 JPA 프로그래밍](https://github.com/Hyung1Jung/jpa)
* [2차 캐시](https://junghyungil.tistory.com/203)

---

## 📄 DATABASE 🔍
**[repository 보기](https://github.com/Hyung1Jung/database-network-os-infra)**

- [트레픽 분산을 위한 Master/Slave DataSource 동적 라우팅 설정](https://junghyungil.tistory.com/177)
- [외래키(Foreign Key)와 데드락(DeadLock)](https://junghyungil.tistory.com/178)
- [MySQL 실행 계획 분석을 통해 페이징 쿼리 성능 개선](https://junghyungil.tistory.com/180?category=900222)

* Real MySQL
  * [Chapter03](https://github.com/Hyung1Jung/database-network-os-infra/blob/master/src/database/real-mysql/chapter03/README.md)
  * [Chapter04](https://github.com/Hyung1Jung/database-network-os-infra/blob/master/src/database/real-mysql/chapter04/README.md)
  * [Chapter05](https://github.com/Hyung1Jung/database-network-os-infra/blob/master/src/database/real-mysql/chapter05/README.md)
  * [Chapter06](https://github.com/Hyung1Jung/database-network-os-infra/blob/master/src/database/real-mysql/chapter06/README.md)

* Redis
  * [Redis(Remote dictionary server)란?](https://junghyungil.tistory.com/162?category=900222)
  * [Redis와 memcached 비교](https://junghyungil.tistory.com/165?category=892328)
  * [Redis(Remote dictionary server)란?](https://junghyungil.tistory.com/162)
  * [Redis 연동하기 및 Spring Boot Redis Docs 살펴보기](https://junghyungil.tistory.com/166)    
  
---

## 📄 Network 🔍
**[repository 보기](https://github.com/Hyung1Jung/database-network-os-infra)**

* [Web Server, WAS 차이와 이 두 개를 따로 두는 경우](https://junghyungil.tistory.com/108?category=892281)
* [Apache MPM vs Nginx](https://junghyungil.tistory.com/118?category=892281)
* [HttpServlet와 Spring, Dispatcher-Servlet](https://junghyungil.tistory.com/119?category=892281)
* [Proxy](https://junghyungil.tistory.com/114?category=892281)
* [커넥션 풀을 사용하지 않았을때 발생하는 "비용"은 구체적으로 어떤 비용일까? 네트워크와 관련하여 비용에 관한 고찰](https://junghyungil.tistory.com/129?category=892328)
* [HTTP Method](https://github.com/Hyung1Jung/LearnKit/blob/master/Network/HTTP/HTTP%20Method.md)
* [HTTP Status Code](https://github.com/Hyung1Jung/LearnKit/blob/master/Network/HTTP/HTTP%20Status%20Code.md)
* [HTTP vs HTTPS](https://github.com/Hyung1Jung/LearnKit/blob/master/Network/HTTP/HTTP%20vs%20HTTPS.md)
* [톰캣이 스레드를 부여하는 과정](https://github.com/Hyung1Jung/LearnKit/blob/master/Network/Tomcat/%ED%86%B0%EC%BA%A3%EC%9D%B4%20%EC%8A%A4%EB%A0%88%EB%93%9C%EB%A5%BC%20%EB%B6%80%EC%97%AC%ED%95%98%EB%8A%94%20%EA%B3%BC%EC%A0%95.md)
* [아파치 톰캣](https://github.com/Hyung1Jung/LearnKit/blob/master/Network/Tomcat/%EC%95%84%ED%8C%8C%EC%B9%98%20%ED%86%B0%EC%BA%A3..md)
* [서비스의 보안을 위해 어떻게 CIA를 지킬 수 있을까?](https://junghyungil.tistory.com/208)
* [서비스의 보안을 위해 어떻게 CIA를 지킬 수 있을까?(2) - RSA로 해결](https://junghyungil.tistory.com/209)
---

## 📄 OS 🔍
**[repository 보기](https://github.com/Hyung1Jung/database-network-os-infra)**

* [인터럽트(interrupt)](https://junghyungil.tistory.com/130?category=892324)
* [문맥교환(context switching)](https://junghyungil.tistory.com/105?category=892275)
* [커널 수준의 쓰레드 vs 사용자 수준의 쓰레드](https://junghyungil.tistory.com/132?category=892324)
* [프로세스 간 통신(Inter-Process Communication,IPC)](https://junghyungil.tistory.com/146?category=892324)
--- 

## 📄 infra 🔍
**[repository 보기](https://github.com/Hyung1Jung/LearnKit/tree/master/Infra)**

- [스케일 업 vs 스케일 아웃](https://junghyungil.tistory.com/151?category=952148)
* [세션 불일치 문제가 발생하는 이유와 세션 불일치를 해결하는 법](https://junghyungil.tistory.com/163?category=900222)

지속적 통합 - CI를 이용한 애자일 - 젠킨스 CI 구축
- [지속적 통합의 개념 - 애자일 방법론과 폭포수 모델](https://junghyungil.tistory.com/170)
- [CI란?, 어떤 CI 도구를 사용할까?](https://junghyungil.tistory.com/167)
- [젠킨스란? 젠킨스를 이용해 CI 자동화하기, 슬랙 연동](https://junghyungil.tistory.com/168)
- [젠킨스와 슬랙 연동하여 알람받기](https://junghyungil.tistory.com/169)

성능 테스트
- [리눅스 서버에 ngrinder 설치하기](https://junghyungil.tistory.com/175)
- [nGrinder를 이용해 Login API 성능 테스트 후 Scale-Out을 적용하여 성능 개선 - (1)](https://junghyungil.tistory.com/175)
- [nGrinder를 이용해 Login API 성능 테스트 후 Scale-Up을 적용하여 성능 개선 - (2)](https://junghyungil.tistory.com/181)


MSA(MicroService Architecture)
- [MSA(MicroService Architecture)란 무엇인가?](https://junghyungil.tistory.com/188)
- [Spring cloud 적용에 사용되는 컴포넌트 중 하나인 Eureka](https://junghyungil.tistory.com/193)
- [MSA의 BFF 패턴, 외부 구성 저장소 패턴, 인증 인가 패턴이란?](https://junghyungil.tistory.com/194)
- [장애 및 실패 처리를 위한 서킷 브레이커 패턴 및 모니터링과 추적 패턴 출처](https://junghyungil.tistory.com/195)

Kafka
- [Apache Kafka는 어떤 방식으로 동작할까?](https://junghyungil.tistory.com/190)

k8s
- [kubernetis(쿠버네티스), 왜 사용할까요?](https://junghyungil.tistory.com/215)
- [쿠버네티스(k8s) 서비스 메시 패턴의 구현체인 Istio란?](https://junghyungil.tistory.com/197)
- [Docker에서 k8s Service mesh parttern 의 구현체인 Istio 설치](https://junghyungil.tistory.com/207)

docker
- [M1 Mac에서 docker로 mysql 설치하기](https://junghyungil.tistory.com/201)

---

## 📄 IntellJ TIP 🔍
* [Translator Plugins (IntellJ에서 한 -> 영 번역)](https://junghyungil.tistory.com/63?category=905725)
* [IntelliJ JSON Fragment Edit 기능](https://junghyungil.tistory.com/79?category=905725)