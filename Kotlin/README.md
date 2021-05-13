## 📄 Kotlin 🔍

**server-side kotlin, I Leraned**

Java에 비해 코드를 간결하게 작성할 수 있으며, 좀 더 안전하게 null을 다룰 수 있는 문법을 제공하는 것이 주요 특징이다. 또한 Java와 100% 호환되어 기존 라이브러리를 활용할 수 있다. 그래서 기존에
Java로 작성된 프로젝트에 점진적으로 Kotlin을 도입한다.

- Gradle 멀티 모듈을 활용해서 연습하는 분야에 필요한 의존성만을 모듈에 추가한다.
- 공부한 것들 README.md에 기록

## 기본 개념 정리
- [기본 문법, 변수와 자료형, 함수, 연산자 개념 정리](https://github.com/Hyung1Jung/kotlin/blob/master/basic/src/me/hyungil/%EA%B0%9C%EC%9A%94%20%EB%B0%8F%20%EA%B8%B0%EB%B3%B8%20%EB%AC%B8%EB%B2%95.md)
- [제어문 -> IF문, When, 반복문, break countinue return](https://github.com/Hyung1Jung/kotlin/blob/master/basic/src/me/hyungil/%EC%A0%9C%EC%96%B4%EB%AC%B8.md)
- [객체지향 -> 생성자, 상속, 모듈, 접근제한자, Property, 지연초기화, Overriding, Any, this와 super, 추상클래스, 인터페이스](https://github.com/Hyung1Jung/kotlin/blob/master/basic/src/me/hyungil/%EA%B0%9D%EC%B2%B4%EC%A7%80%ED%96%A5%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D.md)
- [kotlin의 다양한 클래스 -> Companion, DataClass, Generic, 중첩클래스, 형변환, null처리 및 안전성을 위한 형변환, 열거형, Sealed Class, 리플렉션, 연산자 오버로딩](https://github.com/Hyung1Jung/kotlin/blob/master/basic/src/me/hyungil/kotlin%EC%9D%98%20%EB%8B%A4%EC%96%91%ED%95%9C%20%ED%81%B4%EB%9E%98%EC%8A%A4.md)
- [함수형 프로그래밍 -> 익명, 인라인, 확장, Infix, 고차 함수](https://github.com/Hyung1Jung/kotlin/blob/master/basic/src/me/hyungil/%ED%95%A8%EC%88%98%ED%98%95%20%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D.md)
- [kotlin의 컬렉션](https://github.com/Hyung1Jung/kotlin/blob/master/basic/src/me/hyungil/kotlin%EC%9D%98%20%EC%BB%AC%EB%A0%89%EC%85%98.md)

## 코틀린 공식 레퍼런스 공부 기록

<details>
  <summary>1.서버 사이드를 위한 코틀린</summary>
  <div markdown="1">

### 서버 사이드를 위한 코틀린

코틀린을 사용하면 간결하고 표현력있는 코드를 작성할 수 있다. 또한 기존의 자바 기반 기술 스택과 호환성을 완벽하게 유지하며 학습이 어렵지 않기에 서버 어플리케이션 개발에 매우 적합하다.

- 표현력 : 코틀린은 타입에 안전한 빌더 나 위임 프로퍼티 와 같은 혁신적인 언어 특징을 제공하며, 이를 통해 강력하고 사용하기 쉬운 추상화를 만들 수 있다.
- 확장성 : 코틀린이 지원하는 코루틴 은 적정 수준의 하드웨어 수준에서 대량의 클라이언트를 처리할 수 있는 확장성있는 서버 어플리케이션을 구축할 수 있게 해준다.
- 상호운용성 : 코틀린은 모든 자바 기반 프레임워크와 완전히 호환되므로 익숙한 기술 스택을 유지하면서 최신 언어의 장점을 누릴 수 있다.
- 마이그레이션 : 코틀린은 코드베이스를 자바에서 코틀린으로 단계적이면서 점진적으로 이전할 수 있도록 지원한다. 자바로 작성한 시스템을 유지하면서 신규 코드를 코틀린으로 작성할 수 있다.
- 도구 : IDE를 위한 코틀린 지원이 대체로 훌륭하며, 인텔리J IDEA Ultimate는 플러그인으로 프레임워크에 특화된 도구(예, 스프링을 위한 도구)를 제공한다.
- 학습 곡선 : 자바 개발자는 쉽게 코틀린을 시작할 수 있다. 코틀린 플러그인에 포함된 자바-코틀린 자동 변환기로 시작할 때 도움을 받을 수 있다. 코틀린 콘 은 대화식으 로 구성된 연습을 통해 언어의 핵심 특징을
  익힐 수 있는 가이드를 제공한다.

### 코틀린을 지원하는 서버 개발 프레임워크

- 스프링 은 5.0 버전부터 더 간결한 API 를 제공하기 위해 코틀린 언어 특징을 사용한다. 온라인 프로젝트 생성기 를 사용하면 신규 코틀린 프로젝트를 빠르게 생성할 수 있다.
- Vert.x 는 JVM에서 동작하는 리액티브 웹 어플리케이션을 만들기 위한 프레임워크로 완전한 문서 를 포함한 코틀린 전용 모듈을 제공한다.
- Ktor 은 JetBrains가 만든 코틀린-네이티브 웹 프레임워크이다. 이 프레임워크는 높은 확장성과 사용하기 쉽고 관용적인 API를 제공하기 위해 코루틴을 사용한다.
- kotlinx.html 은 웹 어플리케이션에서 HTML을 만들 때 사용할 수 있는 DSL이다. JSP나 FreeMarker와 같은 전통적인 템플릿 시스템에 대한 대안으로 사용한다.
- JDBC를 통한 직접 접근 외에 JPA, 자바 드라이버를 통한 NoSQL 데이터베이스 사용 등의 영속성 기술을 사용할 수 있다. JPA의 경우 kotlin-jpa 컴파일러 플러그인 을 사용하면 코틀린으로 컴파일한
  클래스를 프레임워크의 요구에 맞출 수 있다

### 코틀린 서버 사이드 어플리케이션 배포

- 아마존 웹 서비스, 구글 클라우드 플랫폼 등 자바 웹 어플리케이션을 지원하는 모든 호스트에 코틀린 어플리케이션을 배포할 수 있다.
- Heroku 에 코틀린 애플리케이션을 배포하려면 공식 Heroku 튜토리얼 을 따라하면 된다.
- AWS Labs는 코틀린을 사용해서 AWS Lambda 함수를 작성하는 예제 프로젝트 를 제공한다.

### 서버 사이드 코틀린 사용자

- Corda 는 주요 은행이 지원하는 오픈소스 분산 원장(ledger) 플랫픔으로, 전체를 코틀린으로 만들었다.
- JetBrains Account 는 JetBrains의 전체 라이스선 판매와 검증을 담당하는 시스템으로 100% 코틀린으로 작성했고 2015년부터 큰 문제 없이 운영에서 돌고 있다.

  </div>

</details>

<details>
  <summary>2.코틀린 1.1와 1.2 의 새로운 점</summary>
  <div markdown="1">

### 1.1 - JVM 백엔드

**자바 8 바이트코드 지원**

이제 자바 8 바이트코드 생성 옵션을 제공한다( -jvm-target 1.8 명령행 옵션이나 대응하는 앤트/메이븐/그레이들 옵션). 현재는 이 옵션이 바이트 코드의 세만틱을 변경하지 않지만(특히 인터페이스의 디폴트
메서드와 람다를 코틀린 1.0처럼 생성한다), 향후에 이를 더 사용할 계획이다

**자바 8 표준 라이브러리 지원**

이제 자바 7과 8에 추가된 새로운 JDK API를 지원하는 표준 라이브러리 버전을 따로 제공한다. 새 API에 접근하려면 표준 kotlin-stdlib 대신에 kotlin-stdlib-jre7 과
kotlin-stdlib-jre8 메이븐 아티팩트를 사용하면 된다. 이 아티팩트는 kotlin-stdlib 를 일부 확장한 것으로 의존성 전이로 kotlin-stdlib 를 포함한다.

**바이트코드의 파라미터 이름**

이제 바이트코드의 파라미터 이름 저장을 지원한다. -java-parameters 명령행 옵션을 사용해서 활성화할 수 있다.

**상수 인라인**

컴파일러는 이제 const val 프로퍼티의 값을 상수 사용 위치에 인라인한다.

**수정가능 클로저 변수**

람다에서 수정가능한 클로저 변수를 캡처하기 위해 사용한 박싱 클래스는 더 이상 volatile 필드를 갖지 않는다. 이 변화는 성능을 향상시키지만, 매우 드 물게 새로운 경쟁 조건(race condition)을
유발할 수 있다. 경쟁 조건에 영향을 받는다면 변수에 접근할 때 자신만의 동기화를 제공해야 한다.

**javax.script 지원**

코틀린은 이제 javax.script API (JSR-223)와의 통합을 지원한다. 이 API를 사용하면 런타임에 코드를 평가할 수 있다:

```kotlin
val engine = ScriptEngineManager().getEngineByExtension("kts")!!
engine.eval("val x = 3")
println(engine.eval("x + 2")) // 5를 출력
```

**kotlin.reflect.full**

자바 9 지원을 준비하기 위해 kotlin-reflect.jar 라이브러리에 있는 확장 함수와 프로퍼티를 kotlin.reflect.full 로 옮겼다. 이전 패키 지( kotlin.reflect )의 이름을
디프리케이트했고 코틀린 1.2에서는 삭제할 것이다. ( KClass 와 같은) 핵심 리플렉션 인터페이스는 kotlinreflect 가 아닌 코틀린 표준 라이브러리에 속하므로 이동에 영향을 받지 않는다.

### 1.2 - JVM 백엔드

**생성자 호출 정규화(normalization)**

1.0 버전부터 코틀린은 try-catch 식이나 인라인 함수 호출과 같은 복잡합 제어 흐름을 갖는 식을 지원했다. 그런 코드는 자바 가상 머신 스펙에 따르면 유효하다. 안타깝게도, 일부 바이트코드 처리 도구는
생성자 호출 인자에 그런 식이 위치할 때, 그런 코드를 잘 처리하지 못한다.

그런 바이트코드 처리 도구 사용자가 겪는 이런 문제를 완화하기 위해, 명령행 옵션( -Xnormalize-constructor-calls=MODE )을 추가했다. 이 옵션을 사용하면 컴파일러는 생성자에 대해 자바와
비슷한 바이트코드를 생성한다. MODE 는 다음 중 하나이다:

- disable (기본) - 코틀린 1.0 및 1.1과 같은 방법으로 바이트코드를 생성한다.
- enable - 생성자 호출에 대해 자바와 같은 바이트코드를 생성한다. 이는 클래스를 로딩하고 초기화하는 순서를 바꿀 수 있다.
- preserve-class-initialization - 생성자 호출에 대해 자바와 같은 바이트코드를 생성한다. 클래스 초기화 순서가 유지됨을 보장한다. 이 는 어플리케이션의 전체 성능에 영향을 줄 수 있다.
  여러 클래스가 복잡한 상태를 공유하고 클래스 초기화 시점에 수정하는 경우에 한해서만 사용해라.

“수동” 차선책은 호출 인자에서 직접 하위 식을 평가하는 대신, 변수에 흐름 제어를 갖는 하위 식 값을 저장하는 것이다. 이는 -Xnormalizeconstructor-calls=enable 와 유사하다.

**자바 디폴트 메서드 호출**

코틀린 1.2 이전에, JVM 1.6을 대상으로 할 때 인터페이스가 자바의 디폴트 메서드를 오버라이딩할 경우 상위 호출에 대해 Super calls to Java default methods are
deprecated in JVM target 1.6. Recompile with '-jvm-target 1.8' 경고를 발생했다. 코틀린 1.2부터는 경고 대신 에러 가 발생하며, JVM 1.8 대상으로 코드를
컴파일해야 한다.

**기존을 깨는 변경: 플랫폼 타입을 위해 x.equals(null)의 일관된 동작**

자바 기본 타입( Int! , Boolean! , Short !, Long! , Float! , Double! , Char! )에 매핑되는 플랫폼 타입에 대해 x.equals(null) 를 호출하면 x 가 null일
때 잘못된 값을 리턴한다. 코틀린 1.2부터 플랫폼 타입의 null 값에 대해 x.equals(...) 를 호출하면 NPE를 발생한다 (하지만 x == ... 는 아니다).

1.2 이전과 동일하게 동작하게 하려면, 컴파일러에 -Xno-exception-on-explicit-equals-for-boxed-null 플래그를 전달한다.

**기존을 깨는 변경: fix for platform null escaping through an inlined extension receiver**

플랫폼 타입인 null 값에 대해 호출되는 인라인 확장 함수는 리시버가 null인지 검사하지 않았고, 그래서 null이 다른 코드로 퍼지는 것을 허용했다. 코틀린 1.2는 호출 위치에서 이런 검사를 강제하며,
리시버가 null이면 익셉션을 발생한다.

이전 동작으로 바꾸려면, 컴파일러에 대체 플래그인 -Xno-receiver-assertions 를 전달한다.

  </div>
</details>

<details>
  <summary>3. 기초 구문</summary>
  <div markdown="1">

### 함수 정의

두 개의 Int 파라미터와 리턴 타입이 Int 인 함수:

```kotlin
fun sum(a: Int, b: Int): Int {
    return a + b
}
```

식 몸체(expression body)를 사용하고 리턴 타입을 추론:

```kotlin
fun sum(a: Int, b: Int) = a + b
```

의미없는 값을 리턴하는 함수:

```kotlin
fun printSum(a: Int, b: Int): Unit {
    println("sum of $a and $b is ${a + b}")
}
```

Unit 리턴 타입은 생략 가능:

```kotlin
fun printSum(a: Int, b: Int) {
    println("sum of $a and $b is ${a + b}")
}
```

### 로컬 변수 정의

한 번만 할당 가능한(읽기 전용) 로컬 변수:

```kotlin
val a: Int = 1 // 특시 할당
val b = 2 // `Int` 타입으로 추론
val c: Int // 초기화를 하지 않으면 타입 필요
c = 3 // 나중에 할당
```

### 변경가능 변수:

```kotlin
var x = 5 // `Int` 타입 추론
x += 1
```

### 문자열 템플릿 사용

```kotlin
var a = 1
// 템플릿에서 단순 이름 사용:
val s1 = "a is $a"
a = 2
// 템플릿에서 임의의 식 사용:
val s2 = "${s1.replace("is", "was")}, but now is $a"
```

### 조건 식 사용

```kotlin
fun maxOf(a: Int, b: Int): Int {
    if (a > b) {
        return a
    } else {
        return b
    }
}
```

### if 를 식으로 사용하기:

```kotlin
fun maxOf(a: Int, b: Int) = if (a > b) a else b
```

### null 가능 값 사용과 null 검사

null 값이 가능할 때 반드시 레퍼런스를 명시적으로 null 가능(nullable)으로 표시해야 한다.

아래 코드가 str 이 정수를 갖지 않으면 null 을 리턴한다고 할 때:

```kotlin
fun parseInt(str: String): Int? {
// ...
```

null 가능 값을 리턴하는 함수는 다음과 같이 사용한다:

```kotlin
fun printProduct(arg1: String, arg2: String) {
    val x = parseInt(arg1)
    val y = parseInt(arg2)
    // `x * y` 코드는 에러를 발생하는데, 이유는 null을 가질 수 있기 때문이다.
    if (x != null && y != null) {
        // null 검사 이후에 x와 y를 자동으로 null 불가로 변환
        println(x * y)
    } else {
        println("either '$arg1' or '$arg2' is not a number")
    }
}
```

또는

```kotlin
// ...
if (x == null) {
    println("Wrong number format in arg1: '$arg1'")
    return
}
if (y == null) {
    println("Wrong number format in arg2: '$arg2'")
    return
}
// null 검사 이후에 x와 y를 자동으로 null 불가로 변환
println(x * y)
```

### 타입 검사와 자동 변환 사용

is 연산자는 식이 타입의 인스턴스인지 검사한다. 불변 로컬 변수나 프로퍼티가 특정 타입인지 검사할 경우 명시적으로 타입을 변환할 필요가 없다:

```kotlin
fun getStringLength(obj: Any): Int? {
    if (obj is String) {
        // 이 블록에서는 `obj`를 자동으로 `String`으로 변환
        return obj.length
    }
    // 타입 검사 블록 밖에서 `obj`는 여전히 `Any` 타입
    return null
}
```

또는

```kotlin
fun getStringLength(obj: Any): Int? {
    if (obj !is String) return null
    // `obj`를 자동으로 `String`으로 변환
    return obj.length
}
```

또는 심지어 다음도 가능

```kotlin
fun getStringLength(obj: Any): Int? {
    // 우변의 `&&`에서 `obj`를 자동으로 `String`으로 변환
    if (obj is String && obj.length > 0) {
        return obj.length
    }
    return null
}
```

### for 루프 사용

```kotlin
val items = listOf("apple", "banana", "kiwi")
for (item in items) {
    println(item)
}
```

또는

```kotlin
val items = listOf("apple", "banana", "kiwi")
for (index in items.indices) {
    println("item at $index is ${items[index]}")
}
```

### while 루프 사용

```kotlin
val items = listOf("apple", "banana", "kiwi")
var index = 0
while (index < items.size) {
    println("item at $index is ${items[index]}")
    index++
}
```

### when 식 사용

```kotlin
fun describe(obj: Any): String =
        when (obj) {
            1 -> "One"
            "Hello" -> "Greeting"
            is Long -> "Long"
            !is String -> "Not a string"
            else -> "Unknown"
        }
```

### 범위 사용

```kotlin
val x = 10
val y = 9
if (x in 1..y + 1) {
    println("fits in range")
}
```

!in 연산자를 사용해서 숫자가 범위를 벗어나는지 검사한다:

```kotlin
val list = listOf("a", "b", "c")
if (-1 !in 0..list.lastIndex) {
    println("-1 is out of range")
}
if (list.size !in list.indices) {
    println("list size is out of valid list indices range too")
}
```

범위를 반복:

```kotlin
for (x in 1..5) {
    print(x)
}
```

또는 단순한 범위 이상:

```kotlin
for (x in 1..10 step 2) {
    print(x)
}
for (x in 9 downTo 0 step 3) {
    print(x)
}
```

### 콜렉션 사용

콜렉션에 대한 반복

```kotlin
for (item in items) {
    println(item)
}
```

in 연산자로 콜렉션이 객체를 포함하는지 검사:`

```kotlin
when {
    "orange" in items -> println("juicy")
    "apple" in items -> println("apple is fine too")
}
```

콜렉션을 걸러내고 변환하기 위해 람다 식 사용:

```kotlin
fruits
        .filter { it.startsWith("a") }
        .sortedBy { it }
        .map { it.toUpperCase() }
        .forEach { println(it) }
```

### 기본 클래스와 인스턴스 만들기:

```kotlin
val rectangle = Rectangle(5.0, 2.0) // 'new' 키워드 필요하지 않음
val triangle = Triangle(3.0, 4.0, 5.0)
```

### 이디엄

코틀린에서 종종 사용되는 이디엄을 정리했다. 선호하는 이디엄이 있다면 풀리퀘스트를 날려 기여해보자.

DTO 생성 (POJO/POCO)

```kotlin
data class Customer(val name: String, val email: String)
```

다음 기능을 가진 `Customer` 클래스를 제공한다:

- 모든 프로퍼티에 대한 getter (그리고 var 의 경우 setter)
- equals()
- hashCode()
- toString()
- copy()
- 모든 프로퍼티에 대한 component1() , component2() , …,

함수 파라미터의 기본 값

```kotlin
fun foo(a: Int = 0, b: String = "") {
    ...
}
```

리스트 필터링

```kotlin
val positives = list.filter { x -> x > 0 }
```

더 짧게 표현:

```kotlin
val positives = list.filter { it > 0 
```

스트링 삽입

```kotlin
println("Name $name")
```

인스턴스 검사

```kotlin
when (x) {
    is Foo -> ...
    is Bar -> ...
    else ->   ...
}
```

쌍으로 맵이나 목록 탐색

```kotlin
for ((k, v) in map) {
  println("$k -> $v")
}
```

k , v 대신 임의 이름을 사용할 수 있다.

범위 사용

```kotlin
for (i in 1..100) {
  ...
} // 닫힌 범위: 100 포함
for (i in 1 until 100) {
  ...
} // 반만 열린 범위: 100 미포함
for (x in 2..10 step 2) {
  ...
}
for (x in 10 downTo 1) {
  ...
}
if (x in 1..10) {
  ...
}
```

읽기 전용 리스트
```kotlin
val list = listOf("a", "b", "c")
```

읽기 전용 맵
```kotlin
val map = mapOf("a" to 1, "b" to 2, "c" to 3)
```

맵 접근
```kotlin
println(map["key"])
map["key"] = value
```

지연(lazy) 프로퍼티
```kotlin
val p: String by lazy {
// 문자열 계산
}
```

확장 함수
```kotlin
fun String.spaceToCamelCase() {
  ...
}
"Convert this to camelcase".spaceToCamelCase()
```

싱글톤 생성
```kotlin
object Resource {
  val name = "Name"
}
```

If not null 축약
```kotlin
val files = File("Test").listFiles()
println(files?.size)
```

If not null and else 축약
```kotlin
val files = File("Test").listFiles()
println(files?.size ?: "empty")
```      

  </div>
</details>


## 코틀린 인 액션

<details>
  <summary>2. 코틀린 기초</summary>
  <div markdown="1">

### 함수
```kotlin
fun max(a: Int, b: Int): Int {
return if (a > b) a else b // 블록이 본문
}
fun max2(a: Int, b: Int): Int = if (a > b) a else b // 식이 본문
fun max3(a: Int, b: Int) = if (a > b) a else b // 식이 본문이면 리턴 타입 생략 가능(타입추론)
```
- 함수 선언은 fun 키워드로 시작
- fun 다음이 함수 이름이 위치
- 함수 이름 뒤에 괄호 안에 파라미터 목록
    - 파라미터 이름과 타입은 콜론으로 구분
    - 각 파라미터는 콤마로 구분
- 본문
    - 블록이 본문인 함수 : 중괄호로 본문을 둘러쌈
    - 식이 본문이 함수 : 줄괄호 대신 등호와 식

### 변수
```kotlin
val question = "나는 누구인가?" // 타입 생략, 컴파일러가 초기화 식을 이용 유추
val answer1 = 30
val answer2: Int = 42 // 타입 지정
val answer3: Int // 초기화 식이 없으면 반드시 타입을 명시
answer3 = 42
```

### 변경 가능 변수와 변경 불가 변수
- val : 변경 불가능한 참조를 저장하는 변수. 일단 초기화하면 제대입이 불가능
    - 정확히 한 버만 초기화 실행 가능
- var : 변경 가능한 참조. 변수 타입은 고정
```kotlin
// 아래 코드 가능: message를 한 번만 초기화한다는 것을 컴파일러가 알 수 있음
val message: String
if (canPerformOperation()) {
message = "Success"
} else {
message = "Failed"
}
```

### 문자열 템플릿
```kotlin
val name = "bk"
println("Hello, $name!") // $ 뒤에 변수 사용
println("Hello, ${name}입니다.") // $ 뒤에 중괄호 사용
println("\$name의 값 = $name") // $ 자체는 \$ 탈출문자 사용
println("max(1, 2) = ${max(1, 2)}") // 중괄호 안에서 식 사용
println("args: ${if (args.isEmpty()) "empty" else args[0] }") // 식에서 큰 따옴표 사용
```
### 클래스
```kotlin
// Kotlin
class Person(val name: String) // 코틀린 클래스 기본 가시성: public
```

```java
// Java
public class Person {
    private final String name;
    
    public Person(String name) {
        this.name = name;
    }
    public String getName() {
        return name;
    }
}
```

### 프로퍼티
프로퍼티를 기본 언어 기능으로 제공하며 자바의 필드와 접근자 메서드를 완전히 대신함
```kotlin
class Person(
    val name: String, // 읽기 전용(val) 프로퍼티
    var isMarried: Boolean // 변경 가능(var) 프로퍼티
)
```
```kotlin
Person p = Person("Bob", false)
println(p.name)
println(p.isMarried)
p.isMarried = true
```

### 프로퍼티의 자바 표현
기본적으로 코틀린은 프로퍼티에 대해 다음을 생성
- 읽기 전용 프로퍼티: 비공개 필드와 필드를 읽는 공개 게터 생성
- 쓸 수 있는 프로퍼티: 비공개 필드와 공개 게터, 공개 세터 생성
- 프로퍼티 이름이 is로 시작할 경우
    - 프로퍼티 이름과 동일한 게터 생성: 예, isMarried())
    - is 대신에 set을 사용하는 세터 생성: 예, setMarried())

지원(backing) 필드: 프로퍼티의 값을 저장하기 위한 비공개 필드

### 커스텀 접근자
```kotlin
    class Rectanble(val height: Int, val width: Int) {
        val isSquare: Boolean
            get() { // 프로퍼티 게터 선언, 블록 사용
                return height == width;
            }
        val size: Int
            get() = height * width // 식 사용
    }
```

### 소스코드 구조
- 파일의 맨 앞에 package 문 사용해서 패키지 지정
- 파일의 모든 선언(클래스, 함수, 프로퍼티 등)이 해당 패키지에 속함
- 디렉토리 구조와 패키지 구조가 일치할 필요 없음 (하지만, 패키지별로 디렉토리 구성이 나음)
- 같은 패키지에 속해 있다면 다른 파일에서 임포트 없이 정의한 선언 사용 가능
- 다른 패키지에서 사용하려면 import 키워드로 사용할 선언을 임포트

### enum
enum 키워드를 사용해서 열거타입 지정
```kotlin
enum class Color {
    RED, ORANGE, YELLO, BLUE, VIOLET
}
```
프로퍼티와 메서드 선언 가능 (메서드 선언시 마지막 열거 값 뒤에 세미콜론 필요)
```kotlin
enum class Color(val r: Int, val g: Int, val b: Int) {
    RED(255, 0, 0), ORANGE(255, 165, 0), YELLOW(255, 255, 0),
    BLUE(0, 0, 255), VIOLET(238, 130, 238);
  
    fun rgb() = (r * 256 + g) * 256 + b
}
println(Color.BLUE.rgb())
```

### when
자바의 switch와 유사, when은 식
- 각 분기에 break 필요 없음
```kotlin
    fun getWarmth(color: Color) =
            when (color) {
                Color.RED ‐> "warm"
                Color.ORANGE ‐> "warm"
                Color.YELLOW ‐> "warm"
                Color.BLUE ‐> "cold"
                Color.VIOLET ‐> "cold"
            }
```

여러 매치 패턴을 지정할 수 있음
```kotlin
    fun getWarmth(color: Color) =
            when (color) {
                Color.RED, Color.ORANGE, Color.YELLOW ‐> "warm"
                Color.BLUE, Color.VIOLET ‐> "cold"
            }
```

모든 분기 식에 만족하지 않으면 else 분기
```kotlin
    fun getWarmth(color: Color) =
            when (color) {
                Color.RED ‐> "very warm"
                Color.ORANGE, Color.YELLOW ‐> "warm"
                else ‐> "cold"
            }
```

### when 식은 객체의 동등성 사용
```kotlin
    fun mix(c1: Color, c2: Color) =
            when (setOf(c1, c2)) {
                setOf(RED, YELLOW) ‐> ORANGE
                setOf(YELLOW, BLUE) ‐> GREEN
                else ‐> throw Exception("Dirty color")
            }
```

### 인자 없는 when 식
```kotlin
    fun mixOpt(c1: Color, c2: Color) =
        when {
          c1 == RED && c2 == YELLOW ‐> ORANGE
          c1 == YELLOW && c2 == RED ‐> ORANGE
          c1 == YELLOW && c2 == BLUE ‐> GREEN
          else ‐> throw Exception("Dirty color")
        }
```
when에 인자가 없으려면, 각 분기의 조건이 불리언 결과를 계산하는 식이어야 함

### 스마트 캐스트
```kotlin
    fun eval(e: Expr): Int {
        if (e is Num) {
            val n = e as Num // 실제로는 필요 없음
            return n.value
        }
        if (e is Sum) { // 컴파일러가 캐스트 처리
            return eval(e.left) + eval(e.right)
        }
        throw IllegalArgumentException("Unknown exp")
    }
```

```kotlin
fun eval(e: Expr): Int {
    when (e) {
        is Num ‐> e.value // 컴파일러가 캐스트 처리
        is Sum ‐> eval(e.left) + eval(e.right)
        else ‐>
          throw IllegalArgumentException("Unknown exp")
  }
```
- is 연산자로 변수 타입 검사
- 스마트 캐스트: is 검사 뒤 컴파일러가 캐스팅 수행
    - is 검사 뒤에 변수가 바뀌지 않는 경우에 적용

### if와 when의 블록
블록의 마지막 식이 if와 when의 결과가 됨
```kotlin
fun evalWithLogging(e: Expr) : Int =
    
```


  </div>
</details>

<details>
  <summary>3. 함수 정의와 호출</summary>
  <div markdown="1">

### 콜렉션 생성
주요 메서드

- val set = hashSetOf(1, 2, 3) // HashSet
- val list = arrayListOf(1, 2, 3) // ArrayList
- val map = hashMapOf(1 to "one", 2 to "two") // HashMap

자체 콜렉션이 아닌 자바 콜렉션 사용: 자바 코드와 상호작용 용이

추가 확장 확수 제공: 예, list.last(), set.max() 등





  </div>
</details>


출처 :

[코틀린 공식 레퍼런스](https://kotlinlang.org/docs/home.html)

[코틀린 스타일 가이드](https://developer.android.com/kotlin/style-guide?hl=ko)

[코틀린 인 액션](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=120267010)