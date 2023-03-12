# MVVM 패턴 (2023/03/12)

## 정의

- MVC 패턴의 Controller가 View Model로 바뀐 패턴

- View Model은 View를 표현하기 위해 만든 View를 위한 Model이며, View를 나타내주고 View를 나타내기 위한 데이터 처리를 함

## 장점

- View와 Model 사이의 의존성을 없애고 또한 Command 패턴과 Data Binding을 통해 View와 View Model 사이의 의존성도 없앰

- 각각의 부분은 독립적이므로 모듈화 하여 개발 가능

## 단점

- View Model의 설계가 쉽지 않음
