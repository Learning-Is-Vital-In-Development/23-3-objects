# 6장 - 메시지와 인터페이스

- 스터디 중 삼색볼펜법으로 체크한 부분들을 팀원들과 공유한 내용입니다.
- 스터디원들이 2명 이상 겹치는 부분은 **강조표시(BOLD)** 되어 있습니다.
- 문장은 페이지의 오름차순으로 정렬되어 있습니다.

## 🔴 빨강 (아주 중요하다고 생각한 내용!)
- 애플리케이션은 클래스로 구성되지만 메세지를 통해 정의된다는 사실을 기억하라(175p)
- 최소한의 인터페이스는 꼭 필요한 오퍼레이션만을 인터페이스에 포함한다. 추상적인 인터페이스는 어떻게 수행하는 지가 아니라 무엇을 하는 지를 표현한다.(181p)
- 원칙이 현재 상황에 부적합하다고 판단된다면 과감하게 원칙을 무시하라. (198p)
- 훌륭한 메세지를 얻기 위한 출발점은 책임 주도 설계 원칙을 따르는 것이다.(214ps)

## 🔵 파랑 (중요하다고 생각한 내용!)
- 클래스라는 구현 도구에 지나치게 집착하면 경직되고 유연하지 못할 설계에 이를 확률이 높아진다.(175p)
- 좀 더 정확하게 말해서 협력 안에서 객체가 수행하는 책임에 초점을 맞춰야 한다.(175p)
- 협력은 어떤 객체가 다른 객체엑 무언가를 요청할 때 시작된다.(176p)
- 반면 객체는 메시지와 메서드라는 두 가지 서로 다른 개념을 실행 시점에 연결해야 하기 때문에 컴파일 시점과 실행 시점의 의미가 달라질 수 있다.(178p)
- **메서드의 이름을 짓는 두 번째 방법은 ‘어떻게’가 아니라 ‘무엇’을 하는지를 드러내는 것이다.(188p)**
- 잊지 말아야 할 사실은 설계가 트레이드 오프의 산물이라는 것이다.(198p)
- 참조 투명성이란 “어떤 표현식 e가 있을 때 모든 e를 e의 값으로 바꾸더라도 결과가 달라지지 않는 특성”이라는 점을 기억하라(212p)
- 사실 어떤 값이 불변한다는 말은 부수효과가 발생하지 않는 다는 말과 동일하다.(212p)

## 🟢 초록 (흥미롭다고 생각한 내용!)
- 디미터 법칙을 따르면 부끄럼타는 코드를 작성할 수 있다.(185p)
- 묻지 말고 시켜라(186p)
- **매우 다른 두 번쨰 구현을 상상하라. 그러고는 해당 메서드의 동일한 이름을 붙인다고 상상해보라.(190p)**
- 방정식을 푸는 방법을 제시하지 말고 이를 공식으로 표현하라. 문제를 내라. 하지만 문제를 푸는 방법을 표현해서는 안된다.(191p)
- 어떻게 x에 1을 더한 값이 x와 같을 수 있단 말인가?(211p)