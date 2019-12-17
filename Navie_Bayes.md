Bayes’ theorem(베이즈 정리)
=============
- P(A) : A가 일어날 확률
- P(B) : B가 일어날 확률


Conditional Probability(조건부 확률)
---------------

- P(A|B) : B가 일어나고나서 A가 일어날 확률, P(B)>0 로 가정 

<img src="/bayes1.jpg" width="250px" height="100px" ></img><br/>

- P(B|A) : A가 일어나고나서 B가 일어날 확률, P(A)>0 로 가정

<img src="/bayes2.jpg" width="250px" height="100px" ></img><br/>

위의 두 식을 이용하면,

<img src="/bayes3.jpg" width="400px" height="100px" ></img><br/>


Independence(독립)
----------------
- 두 사건이 서로 독립이라면 다음 식이 성립한다.

> P(A∩B)=P(A)P(B)
 
- 이를 사건이 n개가 있는 경우로 확장시키면,
어떠한 1≤i1<⋯<ik≤n에 대해서도 다음 식을 만족시킨다면 사건 A1,⋯,An를 독립인 사건이라고 한다.

<img src="/bayes4.jpg" width="500px" height="100px" ></img><br/>

- i1,⋯,ik라는 숫자는 1에서 n까지의 숫자중 임의의 k개(n개 이하)를 뽑은 인덱스, 즉 n개의 사건 중 아무거나 k개 뽑아서 교집합한 확률이 각각 확률의 곱과 같다면 독립이라고 할 수 있다.
 
 
