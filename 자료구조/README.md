# 자료구조

### 이하린
<details>
   <summary> <b>1. </b> Priority Queue(우선순위 큐)에 대해 설명해주세요. </summary> <br />
<div>
      
- 우선순위 큐는 들어간 순서에 상관없이 우선순위가 높은 데이터를 먼저 꺼내기 위해 고안된 자료구조입니다.
- 우선순위 큐 구현 방식에는 배열, 연결 리스트, 힙이 있고, 그중 힙 방식이 worst case라도 시간 복잡도 O(logN)을 보장하기 때문에 일반적으로 완전 이진트리 형태의 힙을 이용해 구현합니다.

</div>
</details>
<br />

<details>
   <summary> <b>2. </b> Tree 구조에 대해 설명해주세요. </summary> <br />
<div>
      
- 트리는 노드로 이루어진 자료구조입니다.
- 스택과 큐와 같은 선형 구조가 아닌 **비선형** 자료구조이며, 계층적 관계를 표현하기에 적합합니다.

</div>
</details>
<br />

<details>
   <summary> <b>3. </b> Hash Table에 대해서 설명해주세요. </summary> <br />
<div>
      
- 해시 테이블은 (Key, Value)로 데이터를 저장하는 자료구조 중 하나로 빠르게 데이터를 검색할 수 있는 자료구조입니다.
- 각 Key값은 해시함수에 의해 고유한 index를 가지게 되어 바로 접근할 수 있으므로 평균 O(1)의 시간 복잡도로 데이터를 조회합니다. 
- 하지만 index값이 충돌이 발생한 경우 Chanining에 연결된 리스트들까지 검색해야 하므로 O(N)까지 증가할 수 있습니다.
  
</div>
</details>
<br />

### 강다은
<details>
   <summary> <b>1. </b> Heap 자료구조에 대해 설명하고, 어디에 주로 사용되는지 말해주세요. </summary> <br />
<div>
      
- Heap은 배열 기반의 완전 이진 트리입니다. 빠르게 최댓값 또는 최솟값을 찾기 위해 주로 사용됩니다.
- 대표적인 예시로는 우선순위 큐를 구현하기 위해 사용됩니다.

</div>
</details>
<br />

<details>
   <summary> <b>2. </b> Array와 LinkedList를 비교해서 설명해주세요. </summary> <br />
<div>
      
- Array는 배열로 정적 메모리 할당을 하는 자료구조로 크기 변경이 불가능합니다. 인덱스를 활용하여 원소에 접근할 수 있기 때문에 검색 시간 복잡도가 O(1) 입니다.
- LinkedList는 동적 메모리 할당을 하는 자료구조입니다. 각 노드들이 메모리 상에서 연속적이지 않으며 각 노드가 자신의 다음 노드 위치를 알고 있습니다. 사용자는 첫 노드의 위치만 알고 있어 검색 시간 복잡도가 O(N)입니다.

</div>
</details>
<br />

<details>
   <summary> <b>3. </b> 완전 이진 트리가 무엇인지 설명해주세요. </summary> <br />
<div>
      
- 완전 이진 트리는 이진 트리 중 왼쪽부터 순서대로 전부 채워진 트리를 의미합니다. 
  
</div>
</details>
<br />

### 황주원
<details>
   <summary> <b>1. </b> Hash Map과 Hash Table의 차이점에 대해 설명해주세요. </summary> <br />
<div>
      
- 동기화 지원 여부와 null 값 허용 여부의 차이가 있습니다.
- 해시 테이블은 동기화를 지원하여 Thread-safe 합니다. 또한, Null 값을 허용하지 않습니다.
- 해시 맵은 동기화를 지원하지 않아 Thread-safe하지 않습니다. 또한, Null 값을 허용합니다.

</div>
</details>
<br />

<details>
   <summary> <b>2. </b> Array와 ArrayList의 차이점에 대해 설명해주세요. </summary> <br />
<div>
      
- Array는 크기가 고정적이고, ArrayList는 크기가 가변적입니다.
- Array는 초기화 시 메모리에 할당되어 ArrayList보다 속도가 빠르고, ArrayList는 데이터 추가 및 삭제 시 메모리를 재할당하기 때문에 속도가 Array보다 느립니다.

</div>
</details>
<br />

<details>
   <summary> <b>3. </b> Stack과 Queue의 실사용 예를 들어 간단히 설명해주세요. </summary> <br />
<div>
      
- **Stack**은 **자바의 Stack 메모리 영역**에 사용됩니다.
   - 지역변수와 매개변수 데이터 값이 저장되는 공간입니다. 메소드 호출시 메모리에 할당되고 종료되면 메모리가 해제되며, LIFO(Last In First Out)구조를 가집니다.

- **Queue**는 **OS의 스케쥴러**에 사용됩니다.
   - 자원의 할당과 회수를 하는 스케쥴러 역할을 큐가 할 수 있습니다. 메모리에 적재된 다수의 프로세스 중 어떤 프로세스에게 자원을 할당할 것인가 그 순서를 결정하는 것이 자원의 효율적인 사용에 있습니다. 
   - 가장 단순한 형태의 스케쥴링 정책이 FCFS(First Com First Served) 즉, 큐라고 볼 수 있습니다.
  
</div>
</details>
<br />

### 정효인
<details>
   <summary> <b>1. </b> Binary Tree와 Binary Search Tree에 대해서 설명해주세요. </summary> <br />
<div>
      
- 이진트리(Binary Tree)는 자식 노드가 최대 두 개인 노드들로 구성된 트리이고, 이진 탐색 트리(BST)는 이진 탐색과 연결 리스트를 결합한 자료구조입니다.
- 이진 탐색 트리(BST)는 왼쪽 트리의 모든 값은 반드시 부모 노드보다 작아야 하고, 오른쪽 트리의 값은 부모 노드보다 커야 하는 특징이 있습니다.
- 시간 복잡도는 O(h)이며, 트리의 균형이 한쪽으로 치우쳐진 경우 worst case가 되고 O(n)의 시간 복잡도를 가집니다. → 이런 worst case를 막기 위해 나온 기법이 RBT(Red-Black Tree)

</div>
</details>
<br />

<details>
   <summary> <b>2. </b> HashMap과 HashTable의 차이점에 대해 설명해주세요. </summary> <br />
<div>
      
- 동기화 지원 여부와 null 값 허용 여부의 차이가 있습니다.
- 해시 테이블(Hash Table)은 병렬 처리를 할 때 (동기화를 고려해야 하는 상황) Thread-safe 하고 Null 값을 허용하지 않습니다.
- 해시 맵(Hash Map)은 Thread-safe하지 않고 Null 값을 허용합니다.

</div>
</details>
<br />

<details>
   <summary> <b>3. </b> 그래프와 트리의 차이점에 대해 설명해주세요. </summary> <br />
<div>
      
- 그래프>트리(그래프가 트리를 포함하는 형태)
- 그래프는 방향, 무방향 모두 존재하지만 트리는 방향만 존재합니다.
  
</div>
</details>
<br />


