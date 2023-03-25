공부 과정 기록
https://velog.io/@pdy0207/%EB%B0%B1%EC%97%94%EB%93%9C-%EC%8A%A4%ED%84%B0%EB%94%94-1%EC%A3%BC%EC%B0%A8

필수 정리 내용
1. MVC 패턴이란?
   MVC패턴은 일종의 디자인 패턴으로 Model, View, Controller의 약자이다. 하나의 프로젝트를 할 때 각자의 역할을 3가지로 분담한 것이다. 
   우선 Model은 애플리케이션의 정보, 데이타를 나타낸다.
   다음으로 View는 데이타를 기반으로 사용자들이 볼 수 있는 화면이다.
   마지막으로 Controller는 데이터와 사용자인터페이스 요소들을 잇는 다리역할을 한다. 
   (스프링 강의에서 대충 작업하기 쉽게 역할을 구분하는 것이란 것을 알았지만 명확히 이해가 안되어 인터넷에 검색을 해본 내용이다.)

2. API와 서버? 
   이것도 강의에서 다룬 내용이지만 사실 명확하게 뭔지 와닿지 않아서 구글링을 해보았다.
   API는 프로그램과 프로그램을 연결시켜주는 매개체라고 한다.API 서버는 이러한 역할이 규격화되어 있는 서버라고 보면 된다. 

3. RESTful 이란?
   우선 REST란, “Representational State Transfer” 의 약자이다. 이는 API 작동 방식에 대한 조건을 부과하는 소프트웨어 아키텍처라고 한다.
   >REST의 구성 :
    자원(RESOURCE) - URI
    행위(Verb) - HTTP METHOD
    표현(Representations)

   >REST의 특징:
     1.유니폼 인터페이스
     2.무상태성
     3.캐시 가능
     4.자체표현구조
     5.Client-Server구조
     6.계층형 구조

   RESTful API는 그럼 무언인가? 두 컴퓨터 시스템이 인터넷을 통해 정보를 안전하게 교환하기 위해 사용하는 인터페이스이다. REST의 특징을 기반으로 서비스 API를 구현한 것. 
   가장 큰 특징은 각 요청이 어떤 동작이나 정보를 위한 것인지를 그 요청의 모습 자체로 추론가능하다는 점이다. 

    >REST API 디자인 가이드
     1.URI는 정보의 자원을 표현해야 한다.
     2.자원에 대한 행위는 HTTP Method(GET,POST,PUT,PATCH,DELETE)로 표현한다.

   사실 내가 인터넷을 보고 요약을 한 것이지만 무슨 소리인지 모르겠다. 일단 적어본다. 앞으로 강의를 계속해서 듣다보면, 읽을 때마다 점점 이해가 가는 부분이 생길 것이라고 생각한다. 
