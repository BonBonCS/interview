# 언어

### 이하린
<details>
   <summary> <b>1. </b> Java와 C++ C언어의 차이를 알려주세요. </summary> <br />
<div>

- C언어와 C++ 언어는 메모리 할당과 해제를 수동으로 처리해야 합니다. 
- 하지만 Java는 가비지 컬렉션을 통해 자동으로 더 이상 사용되지 않는 객체를 정리하여 메모리 누수를 방지할 수 있습니다.
      
</div>
</details>
<br />

<details>
   <summary> <b>2. </b> Java의 객체 지향 특성 4가지를 말씀해주시고 자세히 설명해주세요. </summary> <br />
<div>
      
- Java의 객체 지향 특징은 추상화, 다형성, 상속, 캡슐화 가 있습니다. 
- 추상화란 객체들의 공통적인 데이터와 기능을 도출하는 것입니다. 예를 들어 Class 기능이 있습니다.
- 다형성이란 하나의 메소드나 클래스가 다양한 방법으로 동작하는 것을 말합니다. 오버라이딩이나 오버로딩을 통하여 한 요소에 여러 개념을 넣어 놓은 것입니다.
- 상속은 새로운 클래스가 기존의 클래스의 자료와 연산을 이용하게 해주는 것입니다. 공통적으로 필요한 성격을 가장 기본적인 클래스로 정의해두고, 상속받아 사용하여 중복을 최소화합니다.
- 캡슐화는 객체가 맡은 역할을 수행하기 위한 하나의 목적을 위해 데이터와 기능을 묶는 것을 말합니다. public, protected, private라는 접근 제한자를 통해 클래스에 담는 내용 중 중요한 데이터나 기능을 외부에서 접근하지 못하도록 합니다.

</div>
</details>
<br />

<details>
   <summary> <b>3. </b> 컴파일 에러, 런타임 에러, 링크 에러를 설명해주세요. </summary> <br />
<div>
      
- 컴파일 에러는 프로그램의 실행을 막는 오류입니다. 컴파일러가 이해하지 못하는 코드를 발견하면 컴파일 오류가 발생합니다. 대부분의 컴파일러 오류는 문법적인 오류 때문에 발생합니다.
- 런타임 에러는 프로그램 실행 중에 발생하는 오류입니다. 이러한 오류는 0으로 나누는 경우, Null Point 에러 등 일반적으로 프로그램에서 수행할 수 없는 작업을 시도할 때 발생합니다.
- 링크 에러는 흩어진 소스 코드 파일들을 컴파일한 뒤 각자 연결할 때 발생하는 에러입니다. 어딘가에 선언되어 있는 헤더 파일이나 다른 코드 파일이 실제로 존재하지 않을 때 이러한 오류가 발생합니다.
  
</div>
</details>
<br />
<br />

### 강다은
<details>
   <summary> <b>1. </b> Java는 객체 지향 프로그래밍 언어이다. 객체 지향 프로그래밍이 무엇인지, 그리고 그 장단점은 무엇인지 설명하세요. </summary> <br />
<div>
      
- 객체 지향 프로그래밍은 데이터를 추상화시켜 객체로 만들고 객체들 간 상호작용을 로직으로 구현하는 방식이다.
- 장점으로는 코드의 재사용성이 높고, 유지보수가 쉽다.
- 단점으로는 설계 단계에 많은 시간을 소모해야 하며, 실행 속도가 느리다.

</div>
</details>
<br />

<details>
   <summary> <b>2. </b> Java에서 final 키워드가 클래스, 메소드, 변수 앞에 붙었을 때 어떤 의미로 사용되나요? </summary> <br />
<div>
      
- final class는 다른 클래스가 상속받지 못한다.
- final method는 상위 클래스의 메소드로 사용되었을 경우 자식 클래스가 오버라이드하지 못한다.
- final variable은 변하지 않는 상수 값이다.

</div>
</details>
<br />

<details>
   <summary> <b>3. </b> Java와 Python을 비교해주세요. </summary> <br />
<div>
      
- Java는 정적인 데이터 타입 명시가 필요하지만, Python은 데이터 타입이 동적으로 입력되는 즉 런타임에 의해 타입이 결정된다.
- Java는 컴파일링 언어로 한 번에 컴파일 되지만, Python은 인터프리터 언어로 한 줄씩 컴파일링된다.오후 8:58 2023-09-13

</div>
</details>
<br />

<details>
   <summary> <b>4. </b> Spring의 Annotation이 무엇인지 설명해주세요. </summary> <br />
<div>
      
- annotation은 Java5부터 추가된 문법 요소로 코드에 @를 이용해 주석처럼 달아 특별한 의미를 부여합니다.
- 프로그램 관련 데이터를 제공하고 코드에 정보를 추가하는 정형화된 방법입니다.

Component, Controller, Service, RequestHeader, RequestMapping, ResponseBody, Autowired 등이 있습니다.
   
</div>
</details>
<br />

<details>
   <summary> <b>5. </b> 다양한 의존성 주입 방법 중 생성자 주입을 사용해야 하는 이유를 알고있나요? 하나에 대해서 자세히 설명해주세요. </summary> <br />
<div>
      
- 변경의 가능성을 배제하고 불변성을 보장 (의존 관계의 변경이 거의 없기 때문에 수정의 가능성을 열어두면 유지보수성이 떨어짐)
- 테스트 코드 작성이 쉬워짐 (컴파일 시점에 객체를 주입받아 코드를 작성하며, 주입하는 객체가 누락된 경우 컴파일 시점에 오류를 발견할 수 있음)
- final 키워드 사용 가능 (다른 주입 방법은 객체 생성 이후에 호출되기 때문에 final을 사용할 수 없다. 근데 생성자 주입 방식은 필드 객체에 final 키워드를 사용할 수 있어 컴파일 시점에 누락된 의존성 확인 가능)
- 객체 생성 시 순환 참조 에러를 파악할 수 있음 (객체의 생성과 의존관계 주입이 동시에 실행되기 때문, 다른 방식의 경우 빈의 생성과 @Autowired 시점이 분리되어 있어 호출이 되어야 에러를 확인할 수 있음)

</div>
</details>
<br />

<details>
   <summary> <b>6. </b> AutoWiring 과정에 대해 설명해주세요. </summary> <br />
<div>
      
- 컨테이너에서 타입(인터페이스 또는 오브젝트)을 이용해 의존 대상 객체를 검색하고 할당할 수 있는 빈 객체를 찾아 주입한다

</div>
</details>
<br />

### 황주원
<details>
   <summary> <b>1. </b> 오버라이딩과 오버로딩이 무엇이며 어떤 차이가 있을까요? </summary> <br />
<div>
      
- 오버라이딩은 상위 클래스의 메소드를 재정의 하는 것을 의미합니다. 또한, 런타임 다형성이기도 합니다.
- 오버로딩은 같은 클래스 내에서 동일한 메소드 이름을 가지지만, 매개변수의 타입, 개수가 다르게 구현할 수 있는 것을 의미합니다. 또한, 컴파일 타임 다형성이기도 합니다. 따라서 오버라이딩 될 수 있습니다.

</div>
</details>
<br />

<details>
   <summary> <b>2. </b> String, StringBuilder, StringBuffer 각각의 차이에 대해 설명해주세요. </summary> <br />
<div>
      
- String은 불변입니다. StringBuilder와 StringBuffer는 가변타입입니다.
- StringBuilder와 StringBuffer는 Thread-safe 여부의 차이가 있습니다. StringBuilder는 Thread-safe하지 않습니다. 따라서 Multi-Thread 환경에서 사용할 때는 StringBuffer를 사용합니다.

</div>
</details>
<br />

<details>
   <summary> <b>3. </b> Optional에 대해 설명해주세요. </summary> <br />
<div>
      
- Optional은 null이 될 수도 있는 객체를 감싸고 있는 일종의 래퍼 클래스입니다. 따라서, Optional 객체를 이용하면 복잡한 조건문 없이도 null값으로 인해 발생하는 예외를 처리할 수 있습니다.

</div>
</details>
<br />

<details>
   <summary> <b>4. </b> MVC Pattern의 동작 과정에 대해 설명해주세요. </summary> <br />
<div>
      
1. 클라이언트로부터 요청이 들어오면 dispatcherServlet이 가장 먼저 받습니다.
2. HandlerMapping이 요청 URL과 매핑되는 Controller 검색 후 리턴합니다.
3. HandlerAdapter에서 알맞은 controller 처리 요청합니다.
4. ViewResolver에서 controller가 리턴한 view 검색후 view를 클라이언트로 보냅니다.
   
</div>
</details>
<br />

<details>
   <summary> <b>5. </b> DTO를 사용하는 이유에 대해 설명해주세요. </summary> <br />
<div>
      
- 순환참조를 예방할 수 있습니다.
    - JPA로 개발할 때, 양방향 참조를 사용했다면 순환참조를 조심해야 합니다.
- 엔티티 내부 구현을 캡슐화할 수 있습니다.
- DB Layer와 View Layer 사이의 역할을 분리하기 위해서입니다.

</div>
</details>
<br />

<details>
   <summary> <b>6. </b> 생성자 주입 사용시 장점에 대해 설명해주세요. </summary> <br />
<div>
      
- 순환 참조를 방지할 수 있습니다.
    - 순환 참조는 A -> B를 참조하면서, B -> A를 참조하는 경우 발생하는 문제입니다.
    - 생성자 주입은 먼저 빈을 생성하지 않고 주입하려는 빈을 찾습니다. 그래서 실행시 바로 순환참조 에러가 뜨면서 찾을 수 있습니다.
- final 선언이 가능합니다.
    - 생성자 주입 시, 의존성 주입이 클래스 인스턴스화 중에 시작되므로 final을 선언할 수 있습니다. 따라서 객체를 변경이 불가능하게 할 수 있습니다.
- 테스트 코드를 작성하는데 용이합니다.
    - 스프링 컨테이너 도움 없이 테스트 코드를 더 편리하게 작성 가능합니다.

</div>
</details>
<br />

### 정효인
<details>
   <summary> <b>1. </b> GC(garbage collection)란 무엇인가요? </summary> <br />
<div>

- 힙 영역에서 사용하지 않는 객체들을 제거하는 작업입니다. 자바는 gc로 인해 개발자가 별도의 메모리 관리가 필요 없습니다.
      
</div>
</details>
<br />

<details>
   <summary> <b>2. </b> 인터페이스와 추상클래스의 차이점에 대해 설명해주세요. </summary> <br />
<div>
      
- 추상클래스는 공통된 개념을 표현할 때 사용합니다. 단일 상속만 가능하고 추상클래스를 상속하는 집합간에는 연관관계가 있습니다.
- 인터페이스는 구현 객체가 같은 동작을 한다는 것을 보장하기 위해 사용합니다. 다중 상속이 가능하고 인터페이스를 구현하는 집합간에는 관계가 없을 수 있습니다.

</div>
</details>
<br />

<details>
   <summary> <b>3. </b> 자바는 Call by Reference인가요 아니면 Call by Value인가요? </summary> <br />
<div>
      
- 자바는 Call by Reference로 함수에 인자를 전달할 때 인자값을 복사하여 전달합니다.
- 원본 데이터와 전달된 복사본이 서로 다른 메모리 주소를 가지기 때문에, 함수 내에서 인자의 값을 변경해도 원본 데이터에는 영향을 미치지 않습니다.
- ex) C, C++, Java, Python
  
</div>
</details>
<br />
<br />
