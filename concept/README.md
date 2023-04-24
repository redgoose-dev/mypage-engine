# docs

구상하던것들을 기록하는 공간입니다.

이 프로젝트의 역할은 json 형태의 데이터를 시각적으로 요소들을 표현해주는 일이 목적이다.  
그에 필요한 도구들을 담아두고 외부에서 사용할 수 있도록 도움을 주는것이라고 볼 수 있다.


## 데이터에서 UI로 변환

`DATA -> UI`

이런 모습으로 만드는 역할을 해야하는데 데이터를 받아서 함수로 UI를 표현하거나 UI 컴포넌트로 바로 출력하는 여러가지 방법들이 존재하니 좋은 방법을 찾아서 만들어야 할것이다.  
개발 범위의 가능성이 너무 열려있어서 개발 방법의 선택이 어려울 지경이다.

가장 처음에는 데이터를 받아서 각자 환경에 맞춰 일일히 출력하는 쪽으로 생각하고 있었지만 UI로 출력하는 부분의 파편화가 너무크게 일어나서 새로운 공간에다 분리하는게 좋겠다는 결론이 나왔다.

주로 웹에서 만드는걸로 생각하고 있는데 여기에서 만들기 좋은 방법은 웹컴포넌트라고 생각한다.


## 어떤 도구가 있는것이 좋을까?

### 데이터를 UI로 변환

`json` 형태의 데이터를 UI 요소로 변환시켜주는 도구는 필수적으로 들어갈 것이다.  
UI의 형태가 너무나도 다양하기 때문에 머릿속이 복잡해진다고 느껴진다.

그렇다면 일단 어떤 UI로 변환할지 정하면 되는데 여러가지 UI로 만들어질지에 대한 대비를 하려고 생각하니 좀더 복잡해지는 기분이다.  
아직 명확하게 정해지지 않으니 문서단계에서 더이상 진행되지 않고있다.

### 데이터 -> 스타일시트 변환도구

일반적인 객체 데이터를 스타일시트 값으로 변환시켜주는 도구가 필요할 것이다.  
각 컴포넌트에서 요구하는 스타일시트 스펙도 고정될 것이니 함수 형태로 만들어둘 필요가 있어 보인다.


## 도구는 어떻게 구성할까?

TODO: 고민중..
