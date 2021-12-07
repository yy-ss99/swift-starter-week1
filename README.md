# step 1 정확히 Rull Request 보내기 

## 1번
3번질문 컴퓨터가 고안된지 수십년이 지난 지금 왜 컴퓨터는 아직까지 이진법을
사용하용하고 있을까요? 컴퓨터도 우리와 같이 십진법을 사용하면 안될까요?

답변 : 10진수 보다 2진수를 컴퓨터가 사용하는 첫번째 이유는 10진수를 활용하면 컴퓨터가 10가지 전기적 신호로 받아 연산하여야 하고 2진수를 활용하면 2가지 전기적 신호로
받아들여 처리를 하여야 합니다. 컴퓨터가 10진수를 사용한다면 트렌지스터하나 하나가
10가지 전기적 신호로 구분되어야 할것이며 2진수를 활용할때 보다는 더 적고 많은 기능을 가진 트렌지스터가 필요할 것입니다. 이러한 트렌지스터를 활용하면 트렌지스터 연산속도가 빨라질 수도 있겠지만 오류가 발생할 가능성이 올라가기때문에(10가지 전기적 신호를 구별해야 하기때문) 2진법을 사용하여 하나의 트렌지스터가 온오프 방식으로 처리하는게 아직까지는 가장 효율적인 방법이기 떄문에 2진법을 아직까지 사용한다 생각합니다.    
 10진수 보다 2진수를 컴퓨터가 사용하는 두번째 이유는 소프트웨어상에서는 10가지의 상황보다 2가지 상황이 더많이 발생하기 때문이라 생각합니다. 문을 예를 들면 일상 생활에서는 문이 열려있다 문이 닫혀있다 이 두가지 방식으로 문의 열림 상태를 전부 표현할 수 없지만 프로그램안에서는 문이 열려있다. 문이 닫혀있다. 이 두가지만 존재하면 큰 문제없이 프로그램이 돌아갈 것입니다.  프로그램내에서 함수를 처리하는 방식과 트렌지스터를 온오프 하는 방식이 유사한 점이 많아 10진법 보다는 2진법이 하드웨어적으로나 소프트웨어적으로나 알맞다 생각합니다.

## 2번 
2번질문 주기억장치는 왜 주기억장치라 불릴까요?


답변 :컴퓨터가 정보를 불러오는 과정은 cpu에서 명령을 내려 보조기억장치에 있는 정보를 주기억 장치로 정보를 올려 주기억장치에 올라온 정보를 cpu가 처리 하는 방식입니다. 왜 이런 복잡한 방식으로 컴퓨터가 정보를 처리하냐면 메모리 읽기쓰기 속도는 가격에 따라 천차만별이기 때문입니다. 예를 들어 cpu캐시메모리 경우 3600과 3600x의 성능과 가격비교를 보면 나머지 성능은 전부 같고 L3캐시 메모리만 16mb차이가 나는데 가격은 3만원 차이가 납니다. 240gb짜리 ssd의 가격 또한 3만원입니다(성능에 따라 다르지만 평균적으로). 만약 사용자가 L3캐시메모리와 같이 성능좋고 빠른 메모리로만 컴퓨터를 구성한다면 엄청빠른 컴퓨터를 구성할 수 있을테지만 128gb의 자료만 저장할 수 있는 컴퓨터를 사려면 천문학적인 돈이 필요 할 것 입니다. 반대로 보조기억장치의 성능의 메모리로만 컴퓨터를 구성한다면 컴퓨터를 거의 사용할 수 없을 것입니다. 보통 cpu와 보조기억장치 사이의 속도차이는 수만배에서 수십만배 차이가 납니다. 또한 두 장치로만 컴퓨터를 구성한다면 심각한 속도차이로 인해 병목현상이 발생할 수 있습니다. 빠른속도와 많은 데이터 저장공간과 병목없는 컴퓨터를 구성하기 위해 cpu(캐시) 주기억장치 보조기억장치로 컴퓨터의 저장공간을 분배합니다. 때문에 cpu가 정보를 처리할때 직접적으로 또는 처음 정보를 처리하는 공간은 주기억장치가 되기 때문에 ram(기본적으로)이 주기억장치(primary memory)가 됩니다. /
