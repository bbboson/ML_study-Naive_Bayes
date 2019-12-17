Bayes’ Law(베이즈 정리)
=============

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
 

Bayes’ Law(베이즈 정리)
--------------

> 분할(Partition)
- K개의 집합 B1,⋯,BK가 어떤 집합 S의 분할이 되려면 두 조건을 만족해야 한다.
 1. B1,⋯,BK  는 각각 서로소, 집합이 서로소 라는 것은 무작위로 두개를 뽑았을 때 겹치는 부분이 없어야 한다는 뜻
 2. K 개의  B1,⋯,BK를 합집합 하였을때 그 집합은 정확히 S가 되어야 한다. 
 
- 이 두 조건을 만족해야 B1,⋯,BK를  S의 분할이라고 할 수 있다.
 
<img src="/bayes5.jpg" width="300px" height="250px" ></img><br/>

- K개의 집합 B1,⋯,BK 가 어떤 사건 S의 분할이라고 하면, 모든 S의 부분집합 A에 대해서 다음과 같은 식이 성립하게 된다. 

<img src="/bayes6.jpg" width="250px" height="100px" ></img><br/>
 
- 괄호안의 사건들이 각각 서로소이기 때문에 사건 A가 일어날 확률은 아래의 식과 같이 계산 가능

<img src="/bayes7.jpg" width="250px" height="100px" ></img><br/>
 
- 따라서 어떤 A라는 사건이 일어났을때, Bj라는 사건이 일어날 조건부 확률은 다음과 같이 계산 가능

<img src="/bayes8.jpg" width="450px" height="100px" ></img><br/>



