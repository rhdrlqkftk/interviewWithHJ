11번가 1차 실무진 면접 - 2020.03.24
---

처음에 **기술적인 질문** 먼저 하고, **내 경력에 대한 기술 질문**을 다음으로 했다.

마지막으로는 11번가 개발 문화에 대해 설명해주고, 궁금한 질문을 받았다.

기술적인 질문 주로 11번가에서 사용하는 기술을 물어봤다.
- Spring Aop
- @Transactional
- MSA아키텍처
- java8 => stream(map 설명, filter 설명 - 조건 true가 return되는가?)
- rxJava

### 대답 잘한 부분
- Kafka를 써본거에 대해서 좋게 보았다. (토픽, 파티션)
- DBMS 많이 사용해본거에 좋게 보았다.
- JWT 설명 잘한거 칭찬함
- Spring Security, eventbus, AWS S3 사용해서 이미지 업로드 해본거 좋게 봄
- stream에 대해 장점 설명해봐라(optional 추가해서 설명함. method chain) 가독성 좋고, 코드를 간결하게 해준다.

### 대답 잘 못한 부분
- RxJava가 뭔지 물어보았는데 대답을 제대로 못함.
- flatMap, map 차이
- Spring 2.5 버전인거에 대해 놀람. Spring boot 버전은 몇 버전 썼는지 물어보셨는데 1인지 2인지 잘 몰랐다.)
- Transactional 에 대해서 물었고, propagation 전략에 대해서 물음 (propagation 전략이나 isolation에 대해서는 모르지만 ReadOnly 기능에 대해서 알아서 아는 부분까지 설명함)
- Spring AoP에 대해서 설명해보아라.


### 11번가 개발 문화 (Q&A시간)
- 출퇴근시간은 (8~11시사이) - 워킹 타임은 8시간(주 52시간 철저히)
- 화요일에 스터디 Modern Java in Action 책으로 stream 을 많이 쓰니까 공부한다.
- 수요일인가 일주일에 한번 모여서 같은 로직을 짜고, 코드 스타일을 맞춘다.
- Oracle을 헤비하게 많이 사용하신다고 하셨다.
- 코드리뷰하는 방식이 뭐 굉장히 열려있고 좋다라고 말하긴 어려우나, 따라가기 위해 노력하고 있다고 하셨다.
- 코드를 Pull Request를 하면 모든 개발자가 보고 reply를 남겨준다고 한다. (클린코드 와 관련된 유명한 분(?) 이 있다고 했다. 그분이 다 본다고 했다.)
- bitbucket 사용, mac Intellij 사용