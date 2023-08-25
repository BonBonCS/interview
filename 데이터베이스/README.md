# 데이터베이스

### 강다은
<details>
   <summary> <b>1. </b> 사용자의 관점에 따라 스키마를 3가지로 나누어 간단히 설명해주세요. </summary> <br />
<div>
      
- 스키마는 외부 스키마, 개념 스키마, 내부 스키마로 구분합니다. 
- 외부 스키마는 실제 세계에 존재하는 데이터를 사용자에게 어떻게 보여줄 것인지 정의합니다.
- 개념 스키마는 데이터베이스의 전체적인 논리 구조를 정의합니다.
- 내부 스키마는 데이터베이스의 물리적 저장 구조입니다.

</div>
</details>
<br />
<details>
   <summary> <b>2. </b> SQL Injection을 방어하기 위한 방법 중 하나를 설명해주세요. </summary> <br />
<div>
      
- prepared statement를 사용할 수 있습니다. 쿼리문에서 전달 인자를 ?로 받아 서버측에서 필터링 과정을 거치는 방식으로 공격을 방어합니다.

</div>
</details>
<br />
<details>
   <summary> <b>3. </b> NoSQL을 사용한 적 있나요? 사용한 적이 있다면 사용한 이유를, 사용하지 않았다면 사용하지 않은 이유를 설명해주세요.  </summary> <br />
<div>
      
- NoSQL을 사용한 적이 없습니다. 저는 데이터 무결성을 보장하기 위해 주로RDBMS를 사용했던 것 같습니다.
  
</div>
</details>
<br />


### 정효인
<details>
   <summary> <b>1. </b> Primary key와 Unique key의 공통점과 차이점을 알려주세요. </summary> <br />
<div>
      
- Primary key와 Unique key 모두 중복값을 허용하지 않는다는 공통점이 있습니다.
- 차이점으로는 Primary key는 null값을 허용하지 않고 테이블에서 1개만 생성가능하지만 Unique key는 null값을 허용하고 테이블에서 여러개 생성 가능합니다.

</div>
</details>
<br />
<details>
   <summary> <b>2. </b> 데이터베이스의 특징에 대해 설명해주세요. </summary> <br />
<div>
   
   - **실시간 접근성(Real-Time Accessibility)** : 비정형적인 질의(조회)에 대하여 실시간 처리에 의한 응답이 가능해야 한다.
   - **지속적인 변화(Continuous Evloution)** : 데이터베이스의 상태는 동적입니다. 즉 새로운 데이터의 삽입(Insert), 삭제(Delete), 갱신(Update)으로 항상 최신의 데이터를 유지해야 한다.
   - **동시 공용(Concurrent Sharing)** : 데이터베이스는 서로 다른 목적을 가진 여러 응용자들을 위한 것이므로 다수의 사용자가 동시에 같은 내용의 데이터를 이용할 수 있어야 한다.
   - **내용에 의한 참조(Content Reference)** : 데이터베이스에 있는 데이터를 참조할 때 데이터 레코드의 주소나 위치에 의해서가 아니라 사용자가 요구하는 데이터 내용으로 찾는다.

</div>
</details>
<br />
<details>
   <summary> <b>3. </b> SELECT 쿼리의 수행 순서를 알려주세요.  </summary> <br />
<div>
      
- FROM, ON, JOIN > WHERE, GROUP BY, HAVING > SELECT > DISTINCT > ORDER BY > LIMIT 순으로 실행됩니다.
- (간단) FROM, WHERE, GROUP BY, HAVING, SELECT, ORDER BY
  
</div>
</details>
<br />

### 황주원
<details>
   <summary> <b>1. </b> RDBMS와 NoSQL(Not Only SQL)의 차이를 설명해주세요. </summary> <br />
<div>
      
- RDBMS는 모든 데이터를 2차원 테이블 형태로 표현합니다.
- NoSQL은 RDBMS와 반대로 데이터간의 관계를 정의하지 않고, 스키마가 없어 좀 더 자유롭게 데이터를 관리할 수 있으며, 컬렉션이라는 형태로 데이터를 관리합니다.

</div>
</details>
<br />
<details>
   <summary> <b>2. </b> SQL Injection이 무엇인지 설명해주세요. </summary> <br />
<div>
   
   - SQL Injection이란 공격자가 악의적인 의도를 갖는 SQL 구문을 삽입하여 데이터베이스를 비정상적으로 조작하는 코드 인젝션 공격 기법입니다.
</div>
</details>
<br />
<details>
   <summary> <b>3. </b> RDBMS와 NoSQL은 어느 경우에 적합한가요?  </summary> <br />
<div>
      
- RDBMS는 중복된 데이터가 없어(데이터 무결성) 변경이 용이하기 때문에 관계를 맺고 있는 데이터가 자주 변경이 이루어지지 않는 시스템에 적합합니다.
    
   - 데이터 구조가 명확하고, 변경 될 여지가 없으며 스키마가 중요한 경우 사용하는 것이 좋습니다.
    
- NoSQL은  또한 단점에서도 명확하듯 데이터 중복이 발생할 수 있으며 중복된 데이터가 변경될 시 모든 컬렉션에서 수정해야 하기 때문에 Update가 많이 이루어지지 않는 시스템에 좋으며, Scale-out이 가능하다는 장점을 활용해 막대한 데이터를 저장해야 해서 DB를 Scale-out 해야 되는 시스템에 적합합니다.
    
   - 정확한 데이터 구조를 알 수 없고 데이터가 변경/확장 될 수 있는 경우 사용하는 것이 좋습니다.
  
</div>
</details>
<br />
