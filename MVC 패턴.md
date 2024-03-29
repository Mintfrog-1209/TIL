# MVC 패턴 (2023/03/11)

## 정의

- 모델(Model), 뷰(View), 컨트롤러(Controller)로 이루어진 디자인 패턴

- 애플리케이션의 구성 요소를 세 가지 역할로 구분하여 개발 프로세스에서 각각의 구성 요소에만 집중해서 개발할 수 있음

## 장점

- 재사용성과 확장성이 용이함

## 단점

- 애플리케이션이 복잡해질수록 모델과 뷰의 관계가 복잡해짐

## 모델(Model)

- 애플리케이션의 데이터인 데이터베이스, 상수, 변수 등을 뜻함

- 뷰에서 데이터를 생성하거나 수정하면 컨트롤러를 통해 모델을 생성하거나 갱신함

## 뷰(View)

- inputbox, checkbox, textarea 등 사용자 인터페이스 요소를 나타냄

- 모델을 기반으로 사용자가 볼 수 있는 화면

- 모델이 가지고 잇는 정보를 따로 저장하지 않아야 하며 단순히 화면에 표시하는 정보만 가지고 있어야 함

## 컨트롤러(Controller)

- 하나 이상의 모델과 하나 이상의 뷰를 잇는 다리 역할을 하며 이벤트 등 메인 로직을 담당함

- 모델과 뷰의 생명주기도 관리하고, 모델이나 뷰의 변경 통지를 받으며 이를 해석하여 각각의 구성 요소에 해당 내용에 대해 알려줌


