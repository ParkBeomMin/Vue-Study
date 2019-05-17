Vue.js의 특징
====

## 1. UI 화면단 라이브러리
> Vue.js는 MVVM 패턴(Model - View - ViewModel)의 VM(ViewModel)에 해당하는 화면단 라이브러리  

![Vue Framework](/assets/mvvm.png)
출처 : https://012.vuejs.org/guide/

| 용어       | 설명       | 
| :-------------: | ------------- |
| View | 사용자에게 보이는 화면                      |
| DOM | HTML 문서에 들어가는 요소(태그, 클래스, 속성 등)의 정보를 담고 있는 데이터 트리                      |
| DOM Listener | 돔의 변경 내역에 대해 즉각적으로 반응하여 특정 로직을 수행하는 장치                         |
| Model | 데이터를 담는 용기. 보통은 서버에서 가져온 데이터를 자바스크립트 객체 형태로 저장                         |
| Data Binding | View에 표시되는 내용과 모델의 데이터를 동기화 |
| ViewModel | View와 Model의 중간 영역. DOM Listener와 Data Binding을 제공하는 영역 |
## 2. 컴포넌트 기반 프레임워크
> 컴포넌트를 조합하여 화면을 구성

![Vue Framework](/assets/component-structure.png)
출처 : https://zuminternet.github.io/ZUM-Pilot-cms/

- 컴포넌트 기반 방식의 장점
    - 코드의 재사용
    - 직관적 파악 가능

## 3. 리액트와 앵귤러의 장점을 가진 프레임워크
> 뷰는 앵귤러의 양방향 데이터 바인딩과 리액트의 단방향 데이터 흐름의 장점을 모두 결합한 프레임워크  

> 빠른 화면 렌더링을 위해 리액트의 가상 돔 렌더링 방식을 적용.  
> 사용자 인터랙션이 많은 웹 화면에 적합한 동작 구조.  
> 가상 돔을 활용하면 특정 돔 요소를 추가하거나 삭제하는 변경이 일어날 때 화면 전체를 다시 그리지 않고 프레임워크에서 정의한 방식에 따라 화면을 갱신.