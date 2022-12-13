# mvc-framwork-pratice


<details>
<summary><h3>OOP</h3></summary>

<details> 
    <summary><h4>객체지향 프로그래밍 특징 4가지</h4></summary>
    1. 추상화 (Abstraction) </br>
    2. 다형성 (Polymorphism) </br>
    3. 캡슐화 (Encapsulation) </br>
    4. 상속 (Inheritance)
</details> 
<details> 
    <summary><h4>객체지향 설계 원칙 5가지 (SOLID)</h4></summary>
    1. SRP : Single Responsibility Principle (단일 책임의 원칙) </br>
    2. OCP : Open/Closed Principle (개방 폐쇄의 원칙) </br>
    3. LSP : Liskov’s Substitution Principle (리스코프 치환의 원칙) </br>
    4. ISP : Interface Segregation Principle (인터페이스 분리의 원칙) </br>
    5. DIP : Dependency Inversion Principle (의존성 역전의 원칙) </br>
</details> 

</details>

<details>
<summary><h3>HTTP</h3></summary>

<details> 
    <summary><h4>HTTP 프로토콜 이해</h4></summary>
    HTTP  </br>
        - 서버와 클라이언트가 웹에서 데이터를 주고 받기위한 프로토콜
</details> 
<details> 
    <summary><h4>HTTP 특징</h4></summary>
    클라이언트-서버 모델  </br>
    무상태 프로토콜(Stateless) </br>
        - 서버가 클라이언트 상태를 유지하지 않음 </br>
    비 연결성(Connectionless) </br>
        - 서버가 클라이언트 요청에 대해 응답을 마치면 맺었던 연결을 끊어 버림
</details> 

</details>

<details>
<summary><h3>서블릿 프로그래밍</h3></summary>

<details> 
    <summary><h4>CGI(Common Gateway Interface)</h4></summary>
    - 웹 서버와 애플리케이션 사이에 데이터를 주고받는 규약 </br>
    - CGI 규칙에 따라서 만들어진 프로그램을 CGI 프로그램이라고 함
</details> 
<details> 
    <summary><h4>Servlet</h4></summary>
    - 자바에서 웹 애플리케이션을 만드는 기술 </br>
    - 자바에서 동적인 웹 페이지를 구현하기 위한 표준
</details> 
<details> 
    <summary><h4>ServletContainer</h4></summary>
    - 서블릿의 생성부터 소멸까지의 라이프사이클을 관리하는 역할 </br>
    - 서블릿 컨테이너는 웹 서버와 소켓을 만들고 통신하는 과정을 대신 처리해준다. 개발자는 비즈니스 로직에만 집중하면 된다. </br>
    - 서블릿 객체를 싱글톤으로 관리 (인스턴스 하나만 생성하여 공유하는 방식)
</details> 

<details> 
    <summary><h4>WAS vs 서블릿 컨테이너</h4></summary>
    - WAS는 서블릿 컨테이너를 포함하는 개념 </br>
    - WAS는 매 요청마다 스레드 풀에서 기존 스레드를 사용함
</details> 

</details>