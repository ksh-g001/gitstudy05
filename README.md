## 10 & 11 단원 예외처리 & 기본API 클래스 - 김수현
* **연습 문제**
   
    1. String 클래스의 메소드를 이용하여 아래와 같이 정의된 words String 배열 속에서 입력된 단어로 시작되는 단어를 모두 찾아 차례대로 출력하시오. 자바 기본 라이브러리에 대한 내용은 [여기](https://docs.oracle.com/en/java/javase/17/docs/api/index.html)에서 참조 가능.
    ```java
        String[] words = {"apple", "sigma", "java", "node", "beta", "apple pie", "java.lang.Math"};

    ```
    2. 문자열 "10248"를 Integer형으로 변환하여 자료형명과 값을 출력하시오.<br/>
    출력 결과<br/>
        자료형: Integer<br/>
        값: 10248

    3. String 클래스의 charAt() 메소드를 활용하여 대소문자 상관없이 알파벳을 나열한 문장을 입력하면 알파벳 순서에 따라서 0부터 25까지의 숫자가 출력되는 프로그램을 만드시오. 아래는 프로그램의 예시이다. <br/>
    출력 예시<br/>
        입력: "BaCdefc"<br/>
        출력: 1023452


* **도전 문제**
   
    1. 당신은 꽤나 규모가 큰 동아리 행사의 동아리 명단 관리 프로그램 제작을 부탁받았다. 방문자는 행사 주체측이 정리하여 관리하기에 문제가 없었지만, 부스 참가를 희망하는 동아리 측에서 그들이 내놓은 공지를 잘 읽지 않아 무작위의 신청서를 보내왔고 그로 인해 행사 주체는 동아리 명단을 작성하는데에 큰 어려움을 겪고 있다. 따라서, 그들은 큰 예산없이 빠르게 동아리 명단 관리 프로그램을 얻을 필요가 있었다. IDLE 환경에서 작동하고 끝나는 작은 동아리 명단 관리 프로그램이라도 좋으니 아래의 조건을 충족하는 프로그램을 만들어 달라고 한다.
        * 행사 주체 측은 행사 준비의 번잡함을 줄이기 위해 부스에 참여하는 동아리 수를 20개로 제한하고 각 동아리 부스당 동아리 사람들이 5명까지 올 수 있도록 제한했다.
        * 신청서의 내용을 키보드로 입력받아 처리한다.
        * 모든 신청서가 통과되는 것이 아니다. 신청 요청이 조건을 어긴다면 신청은 등록되지 않는다.
        * id는 등록된 순서대로 부여된다. ex) 4번째로 등록이 된다면 id는 4가 된다.
        * 동아리를 먼저 등록하지 않는다면 부스 참가는 이루어지지 않는다.
        * 메인메뉴로 신규 동아리 등록, 동아리 이름으로 조회, 동아리 전체 조회, 신규 부스 참가자 등록, 동아리로 부스 참가자 조회, 부스 참가자 전체 조회 기능을 선택하여 사용할 수 있어야 한다.
        * 메인메뉴는 숫자키로 선택이 가능하고 위의 기능을 차례대로 1부터 시작하여 6까지에 대응한다. 프로그램 종료는 0번으로 한다. ex) 메인메뉴에서 1을 입력하면 신규 동아리 등록이 이루어진다.
        * 모든 예외는 예외처리가 되어야 한다.
        * 주체측이 보내온 소스코드를 활용하여 완성해야 한다.
        * 주체측이 보내온 소스코드는 Q4 파일에 존재한다.