# Allen-Swift-Master-School
Today I learned  
#### 2021.08.27  
### 열거형  
1. 열거형의 개념  
    -여러가지 케이스를 하나의 타입으로 정의하는 것  
    -enum 키워드 사용  
2. 열거형의 원시값과 연관값  
    -원시값은 열거형 속 케이스의 rawValue  
    -연관값은 특징이 다 다른 케이스들을 다양한 형태로 선언하는 것  
    -원시값과 열거형은 동시에 사용하지 못함  
3. 열거형과 옵셔널
    -옵셔널은 사실 열거형으로 선언된 Custom Type임
    -case some/none으로 구성된 열거형이며, none은 nil과 같음.
---
#### 2021.08.26  
### 배열  
3. 배열 기타  
    -배열의 반복문  
4. 딕셔너리/해셔블    
    -딕셔너리는 순서가 없이 키-값으로 짝지어진 컬렉션  
    -해셔블이라는 고유한 값을 통해 빠르게 검색이 가능  
5. 딕셔너리 다루기  
    -딕셔너리는 insert/replace/remove 대신 update사용  
6. 집합 Set  
    -중복이 안되고, 순서가 없는 데이터 컬렉션  
7. 스위프트컬렉션  
    -KeyValuePairs (Swift 5.2 이상)  
---
#### 2021.08.25  
### 배열  
1. 배열  
    -순서를 가진 요소의 배열  
2. 배열 다루기  
    -배열의 삽입(insert), 교체(replace), 제거(remove), 추가(append)  
### 옵셔널  
2. 옵셔널값의 추출방법  
    -주로 옵셔널 바인딩(if let바인딩 사용)  
3. 옵셔널 타입의 응용  
---
#### 2021.08.24  
### 옵셔널  
1. 옵셔널 타입의 기본 개념  
    -옵셔널은 초기값을 지정하지 않았을 때 나타내는 오류를 막아줌
    -타입? 의 형태로 사용
    -초기화하지 않으면 nil값으로 초기화됨
### 함수  
8. 함수 실행의 메모리구조  
9. 조건문과 반복문의 명령어 구조  
10. 입출력 파라미터(inout)
    -기본적으로 함수는 값타입이지만, inout파라미터 통해 참조 타입으로 사용 가능  
11. guard문  
    -if문의 떨어지는 가독성을 높여줌  
    -조건과 안 맞을 경우 else문을 실행하고, 조건과 맞으면 다음 문자 실행   
    -조건에 안 맞을 경우 early exit이 가능해짐  
12. @discardableResult  
    -리턴값이 있는 함수에서 리턴값을 사용하지 않게 되면 경고문 생김  
    -이 때 @discardableResult를 함수에 붙여주면 경고 사라짐  
13. print함수 제대로 알기 / API  
---
#### 2021.08.23  
### 함수  
3. 함수 사용 시 주의점  
4. 함수의 표기법(지칭) / 함수의 타입 표기  
5. 함수의 오버로딩  
6. 범위에 대한 이해  
7. 제어전송문 정리  
---
#### 2021.08.22  
### 함수  
2. 함수의 응용  
---
#### 2021.08.21  
### 함수
1. 함수의 기본 개념
### 반복문(for문)  
1. 반복문(for문)  
2. for문 사용시 주의점
3. while문 / repeat-while문
4. 반복문의 제어전송문
5. 연습문제
---
### 삼항연산자와 범위연산자  
1. 삼항연산자  
    -조건이 딱 2개인 경우(참/거짓)  
    -a > 29 ? print("10대입니다.") : print("20대 이상입니다.")  
2. 범위 연산자  
    -범위를 나타낼 때 사용하는 연산자 예) 1...10, ... 10  
    -한쪽이 열린 연산을 할 때는 띄어쓰기 해야 함.  
    -1..<10, ..>10 과 같은 연산도 가능  
3. 패턴매칭 연산자(~=)  
    -범위연산자와 함께 사용하는 연산자. 해당 범위에 해당되면 참, 아니면 거짓  
    -a...b ~= age  
---  
#### 2021.08.20  
### 튜플  
1. 튜플 기본  
    -튜플의 데이터의 조합.   
    -예) let iOS = ("Swift", "5") == let iOS = (language: "Swift", version="5")  
2. 튜플의 활용  
    -튜플은 switch문과 함께 자주 활용됨.  
    -where절 이용해 조건을 부여할 수도 있음.  
### 프로그래밍의 기본 원리와 조건문  
2. switch문  
    -조건을 범위로 구성할 때 주의할 것(부등식 사용 불가능)  
3. switch문의 활용  
    -각 케이스에 where조건절을 추가하여 사용할 수 있음  
4. 연습문제  
---
#### 2021.08.19  
### 프로그래밍의 기본 원리와 조건문  
1. 프로그래밍의 기본 원리와 if조건문  
### 기본연산자  
1. 기본연산자  
2. 복합할당/비교/논리 연산자/연산의 우선순위/접근연산자  
---
#### 2021.08.18  
### 변수와 상수/데이터 타입  
3. Swift 데이터 타입
4. 타입 주석(Annotation) / 타입추론(Inference) / 타입안정성(Safety) / 타입변환(Conversion)
5. Type Alias
6. 프로그래밍 관련 용어 정리
---
#### 2021.08.17  
### 변수와 상수/데이터 타입  
1. 변수와 상수  
2. 변수와 상수 정리  
---
#### 2021.08.17  
### 사전 준비  
1. 플레이그라운드 사용법  
2. 등호의 의미  
3. 키보드 특수문자  
---
#### 2021.08.16
### CS101
1. 컴퓨터의 동작원리   
    -메모리구조 : 메모리는 코드-데이터-힙-스택으로 나뉜다.  
2. CPU와 메모리(RAM)  
3. 메모리 저장방식  
4. 메모리 음수표현  
