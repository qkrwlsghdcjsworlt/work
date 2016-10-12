---
layout: post
title:  "Single particle Green's function"
date:   2016-08-14 14:00:00 +0900
categories: update

---

Single particle Schrodinger equation 에서 Green function으로 문제를 어떻게 풀지 살펴본다. 

interaction이 있는 문제에서 Green's function 은 아주 중요한 역할을 한다. interaction 이 없는 single particle Schrodinger 방정식, 즉 편미분방정식을 풀때 쓰는 "simple" Green's function 과 유사하지만, 상호작용을 고려할 시 좀 더 복잡해지는 것은 당연하다. 

그래서 Schrodinger 방정식으로부터 출발하여 섭동이론을 통한 Green's function 이론을 살펴보는 것이 가치있다. 이렇게 함으로써 우리는 상호작용하는 시스템에 대한 Green 함수 이론을 좀더 이해하기 쉬울 것이다.

\\[ (H(r) - E ) \psi (r) = 0 \\]

여기서 \\( H(r) \\)는 일반적인 [Hermitian](http://mathworld.wolfram.com/HermitianOperator.html) 연산자이다.

Schrodinger 방정식에서 Green 함수를 말할 때는 다음 방정식의 해로 정의할 수 있다. 

\\[ ( H(r) - E ) G(r, r', E) = - \delta (r - r') \\]

이렇게 정의된 Green 함수 역시 원래 해와 같은 경계조건을 만족한다. \\( \psi (r) \\) 과 \\( G(r, r', E) \\) 는 같은 경계조건을 만족하고, 같은 식이지만, 한가지 다른점은 \\( r' \\) 에 추가적인 `source` 가 있다는 것이다. 이 추가적인 자유도가 불편한 것이 아니라 Green 함수를 매우 유용하게 해 준다. 


예를 들어 [Helmholtz 방정식](https://en.wikipedia.org/wiki/Helmholtz_equation)을 고려해보자.

\\[ (\nabla^2 + k^2) \psi (r) = 0. \\]

Green 함수에 대한 방정식은 다음과 같다. 

\\[ (\nabla^2 + k^2) G(r,r',k) = - \delta(r-r').\\] 

일반적으로 unique 해는 없다. 그래서 문제 상황을 만족하는 경계조건을 주어야한다. 원형 대칭성(spherical symmetry) \\( {\bf r} - {\bf r'} = {\bf R}\\) 를 가정하면 다음과 같이 식을 다시 쓸 수 있다. 

그러면 방정식은 
\\[ \Bigl( {1 \over R^2}~ {d \over dR}~ R^2 ~{d \over dR}~ + k^2\Bigr) G(R, k) = -{1 \over 4 \pi R^2} \delta (R)\\]

이 된다.
참고로 구형 좌표계에서 라플라시안은

\\[  \nabla^2 = \Bigl( {1 \over r^2}~ {\partial \over \partial r}~  \Bigl( r^2 {\partial \over \partial r} \Bigr)+ {1 \over r^2 \sin \theta } ~ {\partial \over \partial \theta}~ \Bigl( \sin \theta {\partial \over \partial \theta}\Bigr) +  {1 \over r^2 \sin^2 \theta}~ {\partial^2\over \partial \phi^2}  \Bigr)  \\]

이 방정식의 일반해는 

\\[ G(R, k) = \pm {e^{\pm i k R}\over 4 \pi R},~ {1 \over 4\pi}~ {\sin kR \over R},~ {1 \over 4 \pi}~  {\cos kR\over R}.\\]

이들 해는 문제가 다루고자하는 것에 의존하여 사용된다. incoming wave solution이냐, outgoing wave solution 이냐 아니면 standing wave solution 이냐가 필요하다. 

Helmholtz 방정식은 끝났고, 다시 Schrodinger 방정식으로 돌아와 Green 함수의 잘 알려진 표현은 연산자의 고유값과 고유함수꼴로 표현한 것이다. 

\\[ (H(r) -E_n) \psi_n (r) = 0 \\]

여기서 \\( \psi_n (r) \\)은 시스템의 경계조건을 만족한다. \\( \psi_n (r) \\)는 orthogonal 함수의 complete set  을 이룬다. 

Green 함수는 

\\[ (H(r) - E_n) G(r,r',E_n) = - \delta (r-r') \\]
\\[ G(r,r',E_n) = - {\delta (r-r') \over H(r) - E_n }\\]
\\[ G(r,r',E_n) =  {\delta (r-r') \over E_n - H(r)}\\]
\\[ G(r,r',E_n) =  \sum_m{ \psi_m^* (r') \psi_m (r')\delta (r-r') \over E_n - E_m}\\]

\\[ G(r,r',E_n) =  \sum_m{  \psi_m (r) \psi_m^* (r')\over E_n - E_m}\\]

\\[ G(r,r',E) =  \sum_m{  \psi_m (r) \psi_m^* (r')\over E - E_m}\\]

\\[ G(r,r',E) =  \sum_n{  \psi_n (r) \psi_n^* (r')\over E - E_n}\\]

이런식으로 Green 함수를 얻었다면 그 사용법은 무엇일까? 가장 잘 알려진것은 미분방정식 이론의 inhomogeneous 문제에서 Green 함수가 해를 알려준다는 것이다. 만약 우리가 다음과 같은 형태의 식을 갖는다면,

\\[ (H(r) - E) \psi (r) = f(r) \\]

여기서 \\( f(r) \\) 은 잘 알려진 함수이고 다음과 같이 주어진다.

\\[ \psi (r) = - \int f(r') G(r,r',E) dr'\\]

이 식은 쉽게 증명이 되는데 양변에 \\( (H(r) - E) \\) 를 곱하면 된다.

\\[ (H(r) - E) \psi (r) = - \int (H(r) - E) G(r,r',E) f(r')  dr' \\]
\\[~~ = \int \delta (r-r') f(r')  dr' \\]
\\[ = f(r) \\]


그러므로 homogeneous 식에 대해서 Green 함수를 아는 것으로 조금의 수고만 더하면 다른 환경에서의 해를 알 수 있다. 



---
[optical-susceptibility](https://mega.nz/#!NMsDVbLB!RDp1Bsg-feXh8HGh4x6g_Rajm9r3q7MAb8zfDSPXJz0)