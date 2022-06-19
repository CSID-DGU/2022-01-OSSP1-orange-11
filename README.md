개요
============
자연어처리 분야는 기존 통계기반 모델에서 발전해왔으며, 요즈음에는 딥러닝을 통하여 좋은 성능을 달성하고 있다. 하지만, 딥러닝 모델의 높은 성능을 위해서는 대용량의 학습 데이터셋이 필요로 하기 마련이다. 이때, 무분별한 데이터 수집 속 욕설 및 폭언과 같은 데이터들은 모델의 성능을 저하할 수 있으며, 더 나아가 윤리적인 문제가 발생할 수 있다. 또한 윤리적 문제 뿐만 아니라 외국인 입장에서 욕설을 판단해줄 수 있는 서비스가 필요함을 느꼈다. 이 프로젝트는 수집된 한국어 데이터에서 욕설 및 폭언이 담긴 데이터를 제외하는 모델을 구축하고자 한다.

본 프로젝트에서는 한국어에 맞는 여러 토큰화 방법을 비교하며 적합한 토큰화 방법을 찾아내고 추가적으로, Computer Vision에 주로 쓰이는 CNN 모델의 자연어처리 접목 가능성을 실험하고자 한다. 이에 비교 모델로, SKT의 KoBERT 모델과 RNN계열중 하나인 GRU 모델을 함께 실험하며 결과를 비교해보고자 한다.

기존의 욕설 필터링 프로젝트와 다른 점은 GRU 모델과 kobert 모델을 함께 사용한다는 점과, 웹 크롤링 코드를 추가하여 해당 모델이 학습에 필요한 데이터를 자동적으로 추가해주는 기능이 있다는 것이다. 신조어가 자주 나타나는 요즘, 구글사의 bert 라이브러리와 직접적인 성격이 강한 크롤링을 함께 사용한다면 다양한 단어에 대한 분석이 더욱 원활해질 것이라고 판단하였다.

_동국대학교 공개소프트웨어 소속 팀 '다국적 기업'에서 프로젝트를 진행하였으며_ </br>
_yeonsikch님의 nlp-filter-out/SKTBrain님의 kobert 프로젝트를 기반으로 하였습니다_

프로젝트 진행 절차
===============
![Alt text](/img/슬라이드6.jpg)
