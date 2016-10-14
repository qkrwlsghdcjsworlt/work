---
layout: page
title: iridates notes
---


2016/09/18 (일)

symmetry 관계를 이용해서 \\( J_{\textrm{eff} = 1/2} \\) 상태에 대해 line node 의 degeneracy 를 따져봄.


[Dirac line node with symmetry analysis]({{ site.baseurl }}/public/iridatesnotes/Dirac-line-symmetry-analysis-J-half-states.pdf)

근데 여기서 문제점은 inversion symmetry에 대해서 \\( d_{yz},  d_{zx} \\) orbital 이 odd parity를 갖는다고 했다.
하지만, d-orbital들은 inversion symmetry에 대해 even parity를 갖는다.

2016/09/19 (월)

어제 실수한 inversion symmetry 를 다시 고려해서 계산함. 하지만, 최종결과는 동일한데 왜냐하면, odd parity 이든 even parity 이든 eigenvalue 구할때는 두번 operator를 취해야 하기 때문이다.

[inversion symmetry corrected]({{ site.baseurl }}/public/iridatesnotes/inversion-symmetry-corrected.pdf)


2016/09/20 (화)

\\( \sqrt{2} \times \sqrt{2} \\) unit cell에 대해서 Hamiltonian 을 다시 써 보았다.

[\\( \sqrt{2} \times \sqrt{2} \\) Hamiltonian]({{ site.baseurl }}/public/iridatesnotes/sqrt2unitecell-Hamiltonian.pdf)


2016/09/22 (목)

이제 교수님 제안대로 rotation 각도에 따른 hopping parameter를 유도하고, 그 Hamiltonian 에 대해서 susceptibiltiy를 유도해 보자.

각도에 따른 Slater-Koster parameter를 계산하기 위해서 다음 [논문10-Konschuh-TB-SOC-graphene-PRB.pdf]({{ site.baseurl }}/public/iridatesnotes/10-Konschuh-TB-SOC-graphene-PRB.pdf) 으로 부터 영감을 받아서 [mathematica file d-orbital-rotation-translation_160922.nb]({{ site.baseurl }}/public/iridatesnotes/)을 만들어 보았다.

여기서 다음 [노트]({{ site.baseurl }}/public/iridatesnotes/slater-Koster-parameter-d-orbital-rotation.pdf)와 같이 Slater-Koster parameter를 만들면 될거 같다.

그리고 논문 검색중 Kane 그룹에서 spin-orbit semimetal에 대한 논문을 찾았다. [16-Wieder]({{ site.baseurl }}/public/iridatesnotes/16-Wieder-spin-orbit-semimetals-arXiv.pdf)


2016/09/23 (금)

rotation에 따른 slater Koster parameter가 어떻게 바뀌는지 살펴보았다.
먼저 간단하게 p-orbital에 대해서 살펴본후 d-orbital로 가보자.

[rotation Slater-Koster parameter]({{ site.baseurl }}/public/iridatesnotes/Rotation-slater-Koster.pdf) (p-orbital 로 연습)


2016/09/26 (월)

이제 d-orbital에 대해서 rotation에 대해 slater-Koster parameter가 어떻게 바뀔지 살펴보고 있다.

[rotation Slater-Koster parameter2]({{ site.baseurl }}/public/iridatesnotes/Rotation-slater-Koster2.pdf) ( \\( E_{zx,zx}, E_{yz, yz} \\) 계산, 그리고 마지막에 \\( E_{xy, xy} \\) 값을 예상해보았으나 밑에서 잘못됐음을 알고 아래에 수정했음. )

내일 할일은 \\( d_{xy} \\) orbital 끼리의 hopping 이 과연 위에 적은 대로 될것인가를 검증하는 일이다.

이계산할때 사용한 [mathematica file_SK-parameter-d_xy-2016SEP26.nb]({{ site.baseurl }}/public/iridatesnotes/SK-parameter-d_xy-2016SEP26.nb)

논문 검색을 하다가 Colorado에서 Sr_2IrO_4 에 대한 실험 논문을 찾았다. [paper]({{ site.baseurl }}/public/iridatesnotes/15-Yang-High-energy-electronic-excitation-PRB.pdf)


2016/09/27 (화)

이제 local rotation 과 공간 이동이 있을 때 \\( E_{yz, yz}, E_{zx,zx}, E_{xy,xy} \\) Slater-Koster parameter를 구하는 것이 끝났다. [관련 note를 첨부한다.]({{ site.baseurl }}/public/iridatesnotes/Rotation-slater-Koster3.pdf) ( \\( E_{zx,zx}, E_{yz, yz}, E_{xy, xy} \\) 를 정리해놓았음. )

이제 \\( E_{yz, zx}, E_{zx, yz} \\) 를 살펴볼 차례이다.
--> done!

[ \\( E_{yz, zx}, E_{zx, yz}  \\) note를 첨부한다.]({{ site.baseurl }}/public/iridatesnotes/Rotation-slater-Koster4.pdf)

노트 link 를 일일이 클릭할 필요없이 rotation 에 대한 Slater-Koster parameter는 다음과 같다.

\\[
\langle d_{yz, 0, \tau}| H |d_{yz, i, \overline{\tau}} \rangle = V_{dd\pi} \cos (\theta - \phi) \cos (\theta + \phi) - V_{dd\delta} \sin(\theta- \phi) \sin (\theta + \phi) = \langle d_{yz, 0, \overline{\tau}}| H |d_{yz, i, \tau} \rangle,
\\]
\\[ \langle d_{zx, 0, \tau}| H |d_{zx, i, \overline{\tau}} \rangle = V_{dd\delta} \cos (\theta - \phi) \cos (\theta + \phi) - V_{dd\pi} \sin(\theta- \phi) \sin (\theta + \phi) = \langle d_{zx, 0, \overline{\tau}}| H |d_{zx, i, \tau} \rangle
\\]
\\[ \langle d_{xy, 0, \tau}| H |d_{xy, i, \overline{\tau}} \rangle = V_{dd\pi} \cos [2(\theta - \phi)] \cos [2(\theta + \phi)] - V_{dd\sigma} \sin [2(\theta- \phi)] \sin [2(\theta + \phi)] = \langle d_{xy, 0, \overline{\tau}}| H |d_{xy, i, \tau} \rangle
\\]
\\[ \langle d_{yz, 0, \tau}| H |d_{zx, i, \overline{\tau}} \rangle = -V_{dd\pi} \cos (\theta - \phi) \sin (\theta + \phi) - V_{dd\delta} \cos (\theta+ \phi) \sin (\theta - \phi) = - \langle d_{yz, 0, \overline{\tau}}| H |d_{zx, i, \tau} \rangle
\\]
\\[ \langle d_{zx, 0, \tau}| H |d_{yz, i, \overline{\tau}} \rangle = V_{dd\pi} \sin (\theta - \phi) \cos (\theta + \phi) + V_{dd\delta} \cos (\theta - \phi) \sin (\theta + \phi) = - \langle d_{zx, 0, \overline{\tau}}| H |d_{yz, i, \tau} \rangle
\\]

이것은 다른 sublattice 끼리의 Slater-Koster parameter이고, 같은 sublattice 사이에서는 Slater-Koster parameter가 다음과 같이 달라진다.
\\[ \langle d_{yz, 0, \tau}  |H|  d_{yz, i, \tau} \rangle = V_{dd\pi} \cos^2 (\theta - \phi) + V_{dd\delta} \sin^2 (\theta - \phi) \\]
\\[ \langle d_{zx, 0, \tau} | H | d_{zx, i, \tau} \rangle = V_{dd\delta} \cos^2 (\theta - \phi) + V_{dd\pi} \sin^2 (\theta - \phi), \\]
\\[ \langle d_{xy, 0, \tau} | H | d_{xy, i, \tau} \rangle = V_{dd\pi} \cos^2 (2(\theta - \phi)) + V_{dd\sigma} \sin^2 (2(\theta - \phi)) \\]
이계산할때 사용한 [mathematica file_SK-parameter-d_xy-2016SEP27.nb]({{ site.baseurl }}/public/iridatesnotes/SK-parameter-d_xy-2016SEP27.nb)

이제 tight-binding model를 만들 차례이다.

[d_{yz} x축에 대해서 하나 계산해봄]({{ site.baseurl }}/public/iridatesnotes/tight-binding1.pdf)

10/03 (월)

Tremblay 두개의 논문

[PhysRevLett.117.137001]( https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.117.137001) Correlation-Enhanced Odd-Parity Interorbital Singlet Pairing in the Iron-Pnictide Superconductor LiFeAs `16-Nourafkan-PRL`


[1601.05813](https://arxiv.org/abs/1601.05813) Intrinsic anisotropy of spin and charge fluctuations and the nonsymmorphic space group of iron-based superconductors `16-Nourafkan-arXiv`
Tremblay 논문을 읽고nonsymmorphic symmetry 는 half-integer translation 과 point group symmetry 가 결합된 symmetry로 fraction 한 translation 으로 인해 orbital basis에 이 nonsymmorphic operator 가 적용됐을때 extra phase 가 발생하게 된다.
이 extra phase는 에너지 밴드에는 영향을 주지 않지만, response function 에는 영향을 주게 된다. anisotropic 한 fluctuation 을 야기하고, anisotropy 는 orbital 또는 spin nematic instability를 유발하여 결국에는 broken symmetry phase를 갖게 한다.

10/05 (수)

Wannier function 에 glide mirror operator를 act하는 것이 있어서 연습해보았다.
먼저 그전에 [glide mirror operator applies to J=1/2 state A]({{ site.baseurl }}/public/iridatesnotes/glide-symmetry-WannierFT.pdf)
10/06 (목)
glide mirror operator \\( G_y \\) 를 J=1/2 state 에 적용하고, \\( G_x \\) [를 d_{yz} A,B 에 적용해보았다.]({{ site.baseurl }}/public/iridatesnotes/glide-symmetry-WannierFT2.pdf)그럼 unit cell 를 어떻게 잡느냐에 따라서 extra phase가 다를 것인데, unitary transform 하고 나면 서로다른 두가의 경우만 남게 된다. [extra phase unit cell dependence]({{ site.baseurl }}/public/iridatesnotes/glide-symmetry-WannierFT3.pdf)
먼저 나머지 오비탈 \\( d_{zx}, d_{xy} \\)에 대해서 G_x를 적용해 보고, 그 다음 \\( G_y \\) 를 [J=1/2 상태에 적용해보았다.]({{ site.baseurl }}/public/iridatesnotes/glide-symmetry-WannierFT4.pdf)
주요결과는 unitary 변환된 Hamiltonian의 에너지값과 degeneracy는 nonsymmorphic operator 에 의해 변하지 않는다는 것이다. [0000_iridate_band-2D-Sr214-Gx.nb]({{ site.baseurl }}/public/iridatesnotes/0000_iridate_band-2D-Sr214-Gx.nb)
10/07 (금)
그럼 이제 nonsymmorphic operator가 susceptibility에 어떠한 영향을 주는지 살펴볼 차례이다.

그전에 mean-field 계산으로 각도에 따른 스핀 방향을 계산해보았다. rotation angle 이 0 도 일때는 c-axis ordering이 자연스럽게 얻어졌다.

rotation angle 이 0이 아니게 되면, 스핀은 ab-plane으로 눕게 되고, 하나의 값으로 수렴하는게 아니라, flustrated 한 경향을 보인다.


10/12 (수)

기혜영교수님 논문에 나온대로 U를 넣고 mean-field 방법으로 계산했을 때 결과가 똑같이 나올까 계산하려한다. [그러기 위해선 Hamiltonian 을 정확하게 알 필요가 있다.]({{ site.baseurl }}/public/iridatesnotes/Kee-Ir214-Hamiltonian.pdf)

10/14 (금)

mean-field 계산을 하고 있는데 드디어 half filling의 의미를 알거 같다. 가장 낮은 두개의 에너지 레벨의 A site 의 spin moments와 B site 의 spin moments 를 계산한 후 합치고 이것을 k-sum 해주어야 제대로된 계산을 할 수 있다.
