# JavaScript01

## 자바스크립트의  개요

### 프로그래밍 언어의 정의

---

프로그래밍 언어란 컴퓨터 프로그램을 작성하기 위한 언어이다. 다시 말해 소프트웨어의 동작(알고리즘)을 설명하기 위한 언어이다. 프로그래밍 언어로 프로그램을 개발하는 행위를 프로그래밍, 프로그래밍 언어로 작성한 프로그램을 소스 코드 또는 줄여서 코드라고 부른다.

### 컴파일 언어와 인터프리터 언어

---

소스 코드를 실행하기 전 기계어로 번역하는 행위를 컴파일이라고 하며, 컴파일을 수행하는 소픝웨어를 컴파일러라고 한다. 소스 코드 여러 개를 하나로 묶어서 컴파일한 후에 실행하는 프로그래밍 언어를 컴파일 언어라고 합니다. C, C+, Java, Objective C등의 언어가 대표적인 컴파일 언어이다.

컴파일 언어로 작성한 프로그램은 컴파일하는 데는 시간이 걸리지만 실행되는 속도가 빠르다.

프로그램을 한 줄마다 기계어로 번역해서 실행하는 프로그래밍 언어를 인터프리터 언어라고 하며, 프로그램을 번역해서 실행시키는 소프트웨어를 인터프리터라고 한다.

자바 스크립트는 인터프리터 언어이다. 자바스크립트 외에도 LISP, Perl, Ruby, Python 등이 인터프리터 언어이다.

인터프리터 언어는 프로그램을 바로 실행할 수 있고 동작을 확인해 가면서 프로그램을 개발할 수 있다는 장점이 있다. 하지만 프로그램 코드를 한 줄 한 줄 기계어로 번역하면서 실행하기 때문에 컴파일 언어보다 처리 속도가 느리다는 단점이 있다.

### 프로그래밍 언어의 유형

---

절차를 순서대로 작성해 나가는 절차적 언어, 처리와 관련된 데이터와 절차를 하나로 묶어 객체 단위로 관리하는 객체 지향 언어, 프로그램을 함수를 조합하여 구현해 나가는 함수형 언어, 데이터 사이의 관계과 논리를 설명해 나가는 논리형 언어 등이 있습니다. 

자바 스크립트는 객체 지향 언어이지만 함수형 언어의 특징도 가지고 있다.

### 자바스크립트의 특징

> 자바스크립트는 한마디로 강력하고 유연한 알고리즘 표현 능력을 갖춘 프로그래밍 언어입니다. 자바스크립트의 특징은 다음과 같습니다.
> 

---

1. 인터프리터 언어다.

   자바 스크립트는 인터프리터 언어이다. 최근 웹 브라우저 대부분에는 실행 시간에 자바스크립트 코드를 컴파일하는 JIT 컴파일러가 내장되어 있어 실행 속도가 매우 빨라졌다. 이는 자바스크립트를 활용한 고기능 웹 애플리케이션을 구현할 수 있게 된 중요한 요인 중 하나이다.
2. 동적 프로토타입 기반 객체 지향 언어다.

   C++와 Java 등은 클래스를 이용하여 객체를 생성하는 클래스 기반 객체 지향 언어이다. 반면에 자바스크립트는 클래스가 아닌 프로토타입을 상속하는 프로토타입 기반 객체 지향 언어이다. 자바스크립트에서는 객체를 생성한 후에도 프로퍼티와 메서드를 동적으로 추가하거나 삭제할 수 있다. 이 또한 C++와 Java 같은 클래스 기반 객체 지향 언어의 객체와 다른 점이다.
3. 동적 타입 언어다.

   C++와 Java는 실행되기 전엔 변수 타입이 결정되는 정적 타입 언어이다. 반면에 자바스크립트는 변수 타입이 없다. 따라서 프로그램을 실행하는 도중에 변수에 저장되는 데이터 타입이 동적으로 바뀔 수 있다. 이러한 언어를 동적 타입 언어라고 한다.
4. 함수가 일급 객체다.

   자바스크립트의 함수는 객체이며, 함수에 함수를 인수를 넘길 수 있다. 이것이 자바스크립트의 함수가 일급 객체인 이유이다. 이 특성을 활용하면 고차 함수를 구현할 수 있어 함수형 프로그래밍이 가능하다.
5. 함수가 클로저를 정의한다.

   자바스크립트의 함수는 클로저를 정의한다. 클로저로 변수를 은닉하거나 영속성을 보장하는 등 다양한 기능을 구현할 수 있다.

###  자바스크립트의 기술적 요소

> 자바스크립트는 기술적 요소로 구성된 언어이다. 

---

1. ECMAScript(코어 언어)

   자바스크립트의 핵심 기술은 ECMAScript로 규정되어 있다. ECMAScript는 ECMA라는 조직의  TC-39위원회가 표준화 작업을 하고 있고, ECMA-262라는 문서로 공개되고 있다. 최신 버전은 ECMAScript 8 (일명 ECMAScript 2017)입니다. 자바스크립트를 배울 때는 먼저 코어 언어의 내용부터 제대로 이해해야한다.

2. 클라이언트 측의 고유한 기술 요소

   웹 브라우저에서 동작하는 자바스크립트를 클라이언트 측 자바스크립트라고 합니다. 클라이언트 측 자바스크립트는 ECMAScript가 규정한 코어 언어와 웹 브라우저의 API(Application Porgram Interface)로 구성되어 있다. 웹 브라우저의 주요 API(Application Porgram Interface)는 다음과 같다.

   | API              | 설명                                                         |
   | ---------------- | ------------------------------------------------------------ |
   | Drag and Drop    | HTML 요소 혹은 파일을 드래그해서 다른 HTML 요소에 드롭할 때 데이터를 전달하는 기능을 제공한다. |
   | Blob             | 이진 데이터를 다루는 기능을 제공한다.                        |
   | File             | 로컬 파일 시스템을 읽고 쓸 수 있는 기능을 제공한다.          |
   | Web Workers      | 프로그램 여러 개를 멀티스레드로 병렬 처리하는 기능을 제공한다. |
   | Web Storage      | 대용량이며 저장 기간에 제한이 없는 데이터를 로컬에 저장하는 기능을 제공한다. |
   | Indexed Database | 로컬에 키값 타입의 관계형 데이터베이스 기능을 제공한다.      |
   | WebSockets       | 서버와의 양방향 통신 기능을 제공한다.                        |
   | Geolocation      | GPS 등의 위치 정보를 다루는 기능을 제공한다.                 |
   | Canvas           | 2차원, 3차원 그래픽스 기능을 제공한다.                       |

3. 서버 측 자바스크립트의 고유한 기술 요소

   웹 서버에서 동작하는 자바스크립트를 서버 측 자바스크립트라고 한다. 웹 서버를 구현하는 데는  Perl, PHP, Python, Ruby 등의 프로그래밍 언어가 널리 사용되고 있다. 최근에는 서버 측 언어로 자바스크립트 또한 많이 사용되고 있다. 서버 측 자바스크립트 실행 환경에는 다음과 같은 구현체가 있다.

   **Node.js** : 구글이 개발한 자바스크립트 실행 환경 (웹 애플리케이션을 만드는 데 자주 사용된다.)

   **Rhino** : 오픈 소스로 개발되어 현재는 모질라(Mozilla)가 관리하고 있는 자바스크립트 실행 환경

   **Aptana Jaxer** : 압타나(Aptana)사가 개발하고 현재를 오픈 소스로 개발되고 있는 자바스크립트 실행 환경