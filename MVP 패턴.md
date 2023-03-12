# MVP 패턴 (2023/03/12)

## 정의

- MVC 패턴에서 컨트롤러를 프레젠터(Presenter)로 바꾼 패턴

- Presenter는 View와 Model의 인스턴스를 가지며 둘을 연결하는 역할을 함

- Presenter 와 View는 1 : 1관계를 가짐

## 장점

- View와 Model의 의존성이 사라짐

## 단점

- 하지만 애플리케이션이 복잡해질수록 View와 Presenter 사이의 의존성이 강해짐


