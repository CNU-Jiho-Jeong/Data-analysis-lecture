### 2022년 수학과 데이터 분석 교육

- 수학과 데이터 분석 교육을 수강하며 실습했던 자료들을 올리는 레포지토리입니다.


- 교육 내용
  - 데이터분석개론 : Colab, Python 기초, 기초통계, 선형함수 
  - 분류분석 이론 및 시각화
  - 선형함수를 이용한 데이터 분석 이론 및 실습
  - 신경망을 이용한 데이터 분석 이론 및 실습

- 프로그램 일정

![image](https://user-images.githubusercontent.com/108641325/201295447-b0f98170-6100-4d12-aab9-64a93d572642.png)

---

### 활성화 함수

- 입력 신호의 총합을 출력 신호로 변환하는 함수를 일반적으로 활성화 함수라고 한다.

- 입력 신호의 총합이 활성화를 일으키는지를 정하는 역할

- 신경망의 활성화 함수는 비선형 함수를 사용해야 한다. 신경망에서 선형 함수를 이용하면 신경망의 층을 깊게하는 의미가 없어진다.(활성화 함수를 사용하지 않아도 신경망의 층을 깊게 하는 의미가 없어진다.)

- **그러니까 층을 쌓기 위해서는 비선형 함수인 활성화 함수를 사용해야 하고, 활성화 함수로는 비선형 함수를 사용해야 한다.**

### 활성화 함수로 쓸 수 있는 함수로 **시그모이드 함수**가 있다(**카.공 프로젝트 때 사용**). 
### 시그모이드 함수는 **기울기 소멸 문제가 발생한다는 단점**이 있다. **이때 lstm의 핵심요소들은 이 문제를 방지할 수 있다(카공 프로젝트 참고).**
