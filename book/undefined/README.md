---
description: 켄트벡이 쓴 TDD 를 읽고 한번 책에 나온대로 읽고 책에 내용을 곱씹어 보기 위해 작성하였습니다.
---

# 🚦 테스트 주도 개발

## 들어가기 앞서...

### 왜 이 책을 보게 되었는가

이전에 개발을 진행했을때는 테스트 코드를 작성을 안했습니다.

이유는 간단하다. 귀찮고, 하기 힘든것 뿐만 아니라 납기를 맞추기에 바쁜 와중에, 어떻게 테스트 코드까지 작성을 하겠는가? 하지만, 시간이 지나고 점차 개발을 하는 과정속에서 테스트 코드 유무에 대해 코드 퀄리티가 다르다는걸 차차 느끼게 됐다.&#x20;

그래서 TDD 의 성경책과 같다는 켄트 벡 책을 리뷰하는 시간을 통해 보다 코드의 품질을 상승시키는 계기가 됐으면 좋겠다.

단순히 각 장마다 테스트를 직접 작성하면서 진행 해 볼수 있지만, 크게 작성할 코드 부분이 없을 경우엔 소회하는 글을 작성할 예정이다.



### 책에서  알려주는 TDD 수련법

* 간단하고 쉬운 문제들을 TDD로 시도한다.
* [초록 막대 주기](#user-content-fn-1)[^1]는 가능하면 짧게 한다.
* 초록 막대 주기의 최대 시간을 정해놓고 진행하다, \
  시간을 초과하면 직전 초록막대 상태로 되돌린 다음, 새로 시작하라
* 진짜를 만들기 전에 가짜로 구현하기를 적극적으로 사용해라
* 같은 문제를 여러번 풀어봐라





[^1]: 초록 막대가 나오는 시점에서&#x20;

    다음 초록막대가 나오는 시점
