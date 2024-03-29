## ❗ ArrayList vs LinkedList
### 🔹 ArrayList
- ArrayList는 기본적으로 배열을 사용한다. 하지만 일반 배열과 차이점이 존재한다.일반 배열은 처음에 메모리를 할당할 때 크기를 지정해주어야 하지만,ArrayList는 크기를 지정하지 않고 동적으로 값을 삽입하고 삭제할 수 있다.
- ArrayList는 각 데이터의 index를 가지고 있고 무작위 접근이 가능하기 때문에, 해당 index의 데이터를 한번에 가져올 수 있다.
- 데이터의 삽입과 삭제시 ArrayList는 그만큼 위치를 맞춰주어야 한다. 삽입과 삭제가 많다면 ArrayList는 비효율적이다.
### 🔹 LinkedList
- LinkedList는 내부적으로 양방향의 연결 리스트로 구성되어 있어 참조하려는 원소에 따라 처음부터 정방향 또는 역순으로 순회 가능(배열의 단점을 보완하기 위해 LinkedList가 고안되었다.)
- LinkedList는 순차적 접근이기 때문에 검색의 속도가 느리다.
- LinkedList는 데이터를 추가·삭제시 가리키고 있는 주소값만 변경해주면 되기 때문에 ArrayList에 비해 상당히 효율적이다.
  
##
조회시에는 ArrayList가 우위에 있지만,삽입/삭제 시에는 LinkedList가 뛰어난 성능을 보여준다.소량의 데이터를 가지고 사용할 때는 사실 큰 차이가 없지만,정적인 데이터를 활용하면서 조회가 빈번하다면 ArrayList를 사용하는 것이 좋고,동적으로 추가/삭제 요구사항이 빈번하다면 LinkedList를 사용하는 것이 좋다.
