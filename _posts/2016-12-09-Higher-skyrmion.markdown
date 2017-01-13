---
layout: post
title:  "Higher skyrmion"
date:   2016-12-09 17:00:00 +0900
categories: skyrmion

---

논문 리뷰의뢰가 왔는데, Higher skyrmion number 에 관한 연구이다. Kondo model로 부터 weak coupling limit 에서 two helice 상태가 바닥상태이라는 것이 알려져 있는데, heavy한 수치계산으로 부터 skyrmion lattice 가 가능하다는 것을 보여준다.

그동안의 다양한 격자구조에서 skyrmion 상태가 연구되었는데, 그동안의 연구를 정리해 본다.

[PRL 101, 156402 (2008)]({{ site.baseurl }}/public/skyrmion/08-Martin-Batista-QHE-triangular-lattice-PRL.pdf)  Itinerant Electron-Driven Chiral Magnetic Ordering and Spontaneous Quantum Hall Effect in Triangular Lattice Models `08-Martin-Batista`

[J. Phys. Soc. Jpn. 79, 083711 (2010)]({{ site.baseurl }}/public/skyrmion/10-Akagi-spin-chirality-ordering-triangular-lattice-jpsj.pdf) Spin Chirality Ordering and Anomalous Hall Effect in the Ferromagnetic Kondo Lattice Model on a Triangular Lattice `10-Akagi`


논문을 꼼꼼히 읽어보았다. 메모를 해둬야 나중에 리뷰를 쓸때 손쉬울거 같다.

먼저 삼각격자에서 nearest hopping 과 3rd nearest hopping 을 고려하여 bare magnetic susceptibility를 계산하여 세가지 helical state가 degenerate되어 있음을 확인한 후, Langevin-Landau numerical method를 통해서 magnetic ordering이 있음을 보인 논문이다. numerical 방법이 없으면 밝히지 못할 skyrmion phase라 논문의 의의가 깊다. 그런데 놀랍게도 saturate 되는 skyrmion phase는 보통의 n=1 skyrmion 이 아니라
n=2 skyrmion 이고, 자기장을 가함에 따라 2->1->0 으로 transition을 보인다.

생각한 문제점:

제목: high topological number이라고 제목을 쓰기에는 n=2 밖에 없어서 설득력이 없다.

그림 2 : spin texture와 charge texture을 그렸지만, 이것이 왜 이런 패턴인지 설명이 없이 최소한 symmetry argument 역시 없다. page 4, in our simulation으로 시작하는 paragraph는 그냥 캡션에 불과하다.


그림 1: 그림 2와 그림 1을 비교할 수 있나? gray unit을 그리는 것이 비교에 도움이 될 것이다.

SM S1(c) 는 그냥 ring으로 보이는데, three peaks 는 보이지 않는다.
Q_1, Q_2, Q_3 다시 한번 확인할 수 있나?
그림과 일치해야 된다.

(3)는 어떻게 얻었나?

Could you write down the optimal variational parameter elsewhere (e.g. SM) to give sufficient information.



SM to compare the skyrmion size it should be refer the system size 30 times 30, unit cell.


when turn on 2nd nearest neighbor turn off 3rd it has  skyrmion with antiferromagnetic order.
what is topological number for this skyrmion pattern?

그냥 결과만 보여주고, 토론은 없어서 PRL로 부족하다. 토론을 더 넣어서 PRB나 다른 논문이 적합해 보인다.



12/28

리뷰하다가 어떻게 skyrmion number = 2 얻었나 확인하기 위해서 계산을 해보았다.

[scan note]({{ site.baseurl }}/public/skyrmion/skyrmion_number-2-scan.pdf)

[mathematica file]({{ site.baseurl }}/public/skyrmion/skyrmion_number-2-cal.nb)
