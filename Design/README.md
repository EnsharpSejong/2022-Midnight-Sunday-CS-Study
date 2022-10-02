## Design Pattern, Test, 프로그래밍 전반

1. Singleton pattern 이란 무엇이고, 어떤 장점과 단점이 있을까요?
2. 싱글턴 코드는 테스트를 어렵게 만드는 문제가 있습니다. 왜 그럴까요? 싱글턴이 좋지 않다는데 왜 스프링 프레임워크 같은 녀석들은 별다른 규칙이 없을 때 기본으로 Singleton bean 을 만들까요?
3. 좋은 Test 라고 평가할 수 있는 가장 중요한 요소를 말씀해주세요. 후보자님은 어떤 Test 를 좋은 Test 라고 정의하십니까?
4. Callback function(또는 Closure) 이 뭔가요? 주의할 점이 있을까요?
5. Mutable, Immutable 이란 뭔가요? 각각은 어떤 특징이 있을까요?
6. Acceptance, Smoke, End-to-End, Integration, Unit test 같은 용어들을 본인만의 방법으로 구분짓는 기준이 있습니까?
7. [메소드의 파라미터로 전달한 객체를 메소드 내에서 마음대로 바꾸지 못 하게 하려면 어떻게 코딩하는게 좋을까요? 왜 메소드가 파라미터를 조작하는 것이 문제가 될까요? 문제가 아닐 수도 있지 않을까요?](7.md)
8. 음료수 자판기에 탑재한 소프트웨어를 제작했다고 가정해 보겠습니다. 작성하신 소프트웨어의 통합 테스트 시나리오를 어떻게 작성하시겠습니까? 생각나는대로 말씀해 주세요.
9.  현재 다루시는 플랫폼에서의 테스트 자동화를 어떻게 구축 하시겠습니까?
10. [test code 를 작성하는 본인만의 기준이 있습니까? test 실행 속도를 높이려면 어떤 방법이 좋을까요?](10.md)
11. blackbox testing, whitebox testing 의 차이에 대해 설명해주세요. 어떤 상황에서 어떤 테스트 방법을 사용하시겠습니까?
12. 상속의 이점 중 "코드의 중복을 줄여준다" 는 말이 있습니다. 그런데 코드 중복을 줄이기 위해서 상속을 쓰는 것은 매우 좋지 않은 코딩 방식이라고 저희는 생각합니다. 이에 대한 후보자님의 의견을 듣고 싶습니다.
13. Java 의 Marker interface (아무 메소드도 없이 타입만 있는) 에 대해 어떻게 생각하시나요?
14. 코드 응집성(cohesion)이란 말을 어떻게 설명하실 수 있습니까? 응집도가 낮은 코드와 높은 코드를 예를 들어 설명해 주세요.
15. NodeJS 로 실행하는 서버와 통신하는 Spring 또는 Python 서버를 구현할 때, 어떻게 하시겠습니까? HTTP 외의 방법을 쓰고 싶다면 어떻게 해야 할까요?
16. 네이버 같은 서비스에서 IP 주소가 바뀔 경우 접속 경고 등의 오류를 발생시킨다. 어떻게 구현하시겠습니까?
17. 서비스의 memory leak 을 어떻게 판단하고, 해결하시겠습니까?
18. 우리 서비스가 대 성공해서 이용자가 4000만이 되었다고 가정합니다. 이용자 4천만 돌파 기념으로 선착순으로 접속한 사용자에게 보너스 포인트를 주는 이벤트를 운영하려 합니다. 모든 이용자들에게 공평하게, 플랫폼이 제공하는 Push 를 보내려 하는데요. 이 경우, 어떤 점들을 고려해야 할까요?
19. MSA vs Monolithic 을 선택하는 기준이 있습니까?
20. M 인프라 시스템이 A 시스템 대비 가격이 많이 싸졌다고 가정해 보겠습니다. 우리의 인프라 시스템을 A 에서 M 으로 최대한 빨리 바꾸려면 어떤 점을 고려해야 할까요?
21. 우리 앱의 어떤 페이지(또는 특정 view) 의 로딩이 매우 늦다면 어떻게 개선할 수 있을까요?
22. 우리가 사용하는 앱들의 API 는 예고없이 바뀌기도 합니다. 외부 API 가 마구 변경되는 상황에서도 우리 앱이 크래시 나지 않게 하려면 어떻게 해야 할까요?
23. 제작한 애플리케이션이 얼마나 사용자 친화적인지를 측정할 수 있는 방법이 있을까요?