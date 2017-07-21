---
layout: page
title: iridates notes
---

__2017/03/04 (토)__

Stoner instability에 대해 한발짝 이해를 하게 되었다. 우선 이해는 [이 ppt]({{site.baseurl}}/public/susceptibility/stoner_instability.pdf)의 도움덕분이다.
구체적인 argument를 정리하면 다음과 같다.

>
어떤 물질은 narrow band를 가지고 Fermi level에 large density of state를 갖는다. 이 Large density of state는 large Pauli susceptibility를 야기한다. 이 Pauli susceptibility가 커지면 자연스럽게 spin up, spin down band가 갈라지고 ferromagnetism이 나타난다. 이런 ferromagnetic exchange in metal 이 언제나 ferromagnetic order로 이어지진 않는다. 어떤 threshold를 넘어야한다. 그 threshold를 제시한 것이 Stoner criterion이다. total field는 (H + n_s M)꼴을 취하고 Pauli susceptibility 는 (H + n_s M) \chi_p = M 의 꼴을 갖는다. applied field에 대한 magnetization 의 반응은 \chi = M/H = \chi_p (H + n_s M)/H = \chi_p (1 + n_s \chi)이다. \chi (1 - n_s \chi_p) = \chi_p. 즉 \chi = \chi_p / (1 - n_s \chi_p). 즉 n_s \chi_p >1 인 조건에서 susceptibility가 diverge 한다


2017/02/28 (화)

인터넷 검색을 하다가 Tetrahedral crystal field splitting에 대한 ppt를 발견하여 첨부한다.
요약은 Tetrahedral crystal field splitting은 octahedron과는 반대로 e_g 상태의 에너지가 아래로 가고, t_2g 상태가 높은 에너지를 같는다.

[crystal field splitting in Tetrahedron]({{site.baseurl}}/public/iridatesnotes/Lec_note/Lecture_9.pdf)




2017/02/23 (목)

expectation value를 구할때 필요한 행렬공식. total energy 계산할 때 이것이 필요했었다.

[expectation-value-total-energy-170223.pdf]({{site.baseurl}}/public/iridatesnotes/notes/expectation-value-total-energy-170223.pdf)


2017/02/20(월)

mean-field self-consistent solution 구할때, 이것과 비슷한 결과를 주는 것이 에너지를 최소화하는 variational parameter m 를 찾는 것이다.
이에 대한 [Fazekas 책에 나와있는 것을 scan 노트]({{site.baseurl}}/public/iridatesnotes/notes/mean-field-solution-alternative-method-170220.pdf)로 요약해두었다.



2017/02/08(수)

[Vanderbilit 와 King-Smith PRB 논문 "Electric polarization as a bulk quantity and its relation to surface charge"](http://journals.aps.org/prb/abstract/10.1103/PhysRevB.48.4442)에서 hopping amplitude 가 bonding type 에 따라 결정됨을 보인 Harrison 의  논문을 찾았다. `93-Vanderbilt`

http://journals.aps.org/prb/pdf/10.1103/PhysRevB.27.3592 Theory of the two-center bond `83-Harrison`

http://journals.aps.org/prb/pdf/10.1103/PhysRevB.24.5835  New tight-binding parameters for covalent solids obtained using Louie peripheral states `81-Harrison`


2017/01/21 (토)

교수님이 effective Hamiltonian을 쓸수있다고 했는데, 아마도 예전에 본 논문의 appendix가 도움이 될거 같아서, [Das sarma 논문 nphys(2011)]({{ site.baseurl }}/public/iridatesnotes/11-Sun-dasSarma-topological-semimetal-in-optical-lattice-naturephy.pdf)를 걸어둔다.
**그리고 Auerbach 책을 참고할 필요가 있다.**




2017/01/20 (금)

논문을 보고 왜 monolayer를 쓸 수 있고, 어떤항을 넣어야 in-plane 으로 되는가 살펴보자.
각항은 어떤 의미를 가지는지 살펴보자.
일반적으로 어떻게 표현할 수 있는지 살펴보자.
하나의 Hamiltonian으로 어떻게 표현할 수 있을까?


[PhysRevB.88.035111](http://journals.aps.org/prb/abstract/10.1103/PhysRevB.88.035111) Theory of metal-insulator transition in the family of perovskite iridium oxides

>
Jean-Michel Carter, Vijay Shankar V., and Hae-Young Kee
Phys. Rev. B 88, 035111 – Published 9 July 2013

[Magnetic structural change of Sr2IrO4 upon Mn doping](http://journals.aps.org/prb/pdf/10.1103/PhysRevB.86.220403) `Mn Doping`

[Noncollinear versus collinear description of the Ir-based one-t2g-hole perovskite-related
compounds: SrIrO3 and Sr2IrO4](http://journals.aps.org/prb/pdf/10.1103/PhysRevB.92.155151) `collinear vs noncollinear`

[Collapse of the Mott Gap and Emergence of a Nodal Liquid in Lightly Doped Sr2IrO](http://journals.aps.org/prl/pdf/10.1103/PhysRevLett.115.176402) `Collapse of Mott gap`

[Electron and hole doping in the relativistic Mott insulator Sr2IrO4:
A first-principles study using band unfolding technique](http://journals.aps.org/prb/pdf/10.1103/PhysRevB.94.195145)

[Substrate-tuning of correlated spin-orbit oxides revealed by optical conductivity calculations](http://www.nature.com/articles/srep27095)

[Tuning Magnetic Coupling in Sr2IrO4 Thin Films with Epitaxial Strain](http://journals.aps.org/prl/pdf/10.1103/PhysRevLett.112.147201)

[Low-energy model and electron-hole doping asymmetry of single-layer Ruddlesden-Popper iridates](http://journals.aps.org/prb/pdf/10.1103/PhysRevB.92.085141) `Ba2IrO4`

[Manipulation of electronic structure via alteration of local orbital environment
in (SrIrO3)m,(SrTiO3)(m = 1, 2, and∞) superlattices](http://journals.aps.org/prb/pdf/10.1103/PhysRevB.94.245113)

[Surface states of perovskite iridates AIrO3: Signatures of a topological crystalline metal
with nontrivial Z2 index](http://journals.aps.org/prb/pdf/10.1103/PhysRevB.91.235103)

[Odd-Parity Triplet Superconducting Phase in Multiorbital Materials
with a Strong Spin-Orbit Coupling: Application to Doped Sr2IrO4](http://journals.aps.org/prl/pdf/10.1103/PhysRevLett.113.177003)

[Theoretical study of insulating mechanism in multiorbital Hubbard models with a
large spin-orbit coupling: Slater versus Mott scenario in Sr2IrO4](http://journals.aps.org/prb/pdf/10.1103/PhysRevB.89.165115) `VMC`

[Weyl fermions and the anomalous Hall effect in metallic ferromagnets](http://journals.aps.org/prb/pdf/10.1103/PhysRevB.88.125110) `Burkov`


[Interplay between Hund’s Coupling and Spin–Orbit Interaction on Elementary Excitations in Sr2IrO4](http://journals.jps.jp/doi/10.7566/JPSJ.83.053709)

[Magnetic properties of bilayer Sr3Ir2O7: Role of epitaxial strain and oxygen vacancies](http://journals.aps.org/prb/pdf/10.1103/PhysRevB.95.024406)

[A charge density wave-like instability in a doped
spin–orbit-assisted weak Mott insulator](http://www.nature.com/nmat/journal/vaop/ncurrent/pdf/nmat4836.pdf) `A charge density wave-like instability`


2017/01/19 (목)

[1701.04979.pdf](https://arxiv.org/pdf/1701.04979.pdf)

[PhysRevLett.109.157402](http://journals.aps.org/prl/abstract/10.1103/PhysRevLett.109.157402)

[magnetism.pdf](http://susi.theochem.tuwien.ac.at/reg_user/textbooks/WIEN2k_lecture-notes_2013/magnetism.pdf)

[PhysRevB.59.419](http://journals.aps.org/prb/abstract/10.1103/PhysRevB.59.419)

[nmat3409](http://www.nature.com/nmat/journal/v11/n10/full/nmat3409.html)

2017/01/18 (수)

mean-field Hamiltonian 에서 solution 을 구할때의 \\( S_x ,  S_y,  S_z \\) 공식

\\( \langle S_x \rangle  = {1 \over 2}  \langle \Psi  \|  \sigma_x \| \Psi \rangle = \psi_\uparrow^r \psi_\downarrow^r + \psi_\uparrow^i \psi_\downarrow^i. \\)

\\( \langle S_y \rangle  = {1 \over 2}  \langle \Psi  \|  \sigma_y \| \Psi \rangle = \psi_\uparrow^r \psi_\downarrow^i - \psi_\uparrow^i \psi_\downarrow^r. \\)

\\( \langle S_z \rangle  = {1 \over 2}  \langle \Psi  \|  \sigma_z \| \Psi \rangle = {1 \over 2} \Big( (\psi_\uparrow^r)^2 + ( \psi_\uparrow^i )^2 - (\psi_\downarrow^r )^2 - ( \psi_\downarrow^i )^2 \Bigr). \\)


[mathematica file 은 여기]({{ site.baseurl }}/public/iridatesnotes/expectation_value.nb)

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

> 10/31 (토) 새로운 Slater Koster parameter를 추가한다. \\( E_{xy,xy} \\) Slater Koster parameter 이다. \\( \delta \\)-bonding xy, xy orbital 사이 hopping 에는 없을 거라고 생각했는데, 있어야 할 듯하여 추가하였다.
[Exy,xy Slater Koster parameters]({{ site.baseurl }}/public/iridatesnotes/Rotation-slater-Koster-Exyxy.pdf)



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

10/15 (토)

half-filling 전략을 쓰면, BZ을 정하고, 그렇게 얻은 에너지 밴드를 내림차순으로 정리한다음 절반되는 상대의 에너지를 받아들인다. 이런식으로 하면 어떤 k points 는 모든 에너지 레벨이 포함되기도 하고, 어떤 k points는 하나도 포함되지 않기도 한다.

10/19 (수)

c++ 으로 돌아가는 eigensystem program을 짜고 있는데, 거기서 쓰이는 eigensystem check 에 들어가는 real part와 imaginary part
[공식]({{ site.baseurl }}/public/iridatesnotes/eigensystem_check_19OCT2016.pdf)

c++ 로 header file을 구분하고, function 을 따로 쓰는 프로그램을 구현하고 있다. 현재는 Hamiltonian 만들고 있는데, interaction 넣기 전까지 끝냈다.


10/25(화)

mean-field계산은 어느정도 잘 돌아가는 거 같고,  rotation angle에 따른 phase transition point를 찾는 것이 임무이다.
그러기 위해서는 tight-binding parameter를 잘 비교해봐야할 거 같다.
간단한 [mathematica file]({{ site.baseurl }}/public/iridatesnotes/comparing_11Hamiltonian-rotationHamiltonian.nb)


11/10(목)

mean-field 계산을 c++ 프로그램으로 돌릴려고 한다. 그전에 [mean-field decoupling of Hubbard interaction]({{ site.baseurl }}/public/iridatesnotes/mean-field-decoupling-2016Nov10.pdf)을 정리해 둘 필요가 있을 거 같다.
논문은 여기서 [`16-Lambert`]({{ site.baseurl }}/public/iridatesnotes/16-Lambert-QPI-pyrochlore-iridates-PRB.pdf) 참고했음. `13-Carter` 이것 역시.


11/16(수)

[mean-field-Hubbard model arXiv]({{ site.baseurl }}/public/iridatesnotes/14-Claveau-mean-field-Hubbard-model-arXiv.pdf) 이논문도 따라가 볼 필요가 있다.

>
[k space sampling]({{ site.baseurl }}/public/iridatesnotes/89-Methfessel-high-precision-sampling-PRB.pdf) High-precision sampling for brillouin-zone integration in metals `89-Methfessel`
>
[Slater MIT]({{ site.baseurl }}/public/iridatesnotes/51-Slater-magnetic-effects-HF-eq-PR.pdf) Magnetic effects and the hartree-fock equation `51-Slater`
>
[mean-field, Hirsch]({{ site.baseurl }}/public/iridatesnotes/85-Hirsch-2D-Hubbard-mean-field-PRB.pdf) Two-dimensional hubbard model: Numerical simulation study. `85-Hirsch`
>
[Stoner model]({{ site.baseurl }}/public/iridatesnotes/35-Stoner-PRSLSA.pdf) Collective electron specific heat and spin para
magnetism in metals. `35-Stoner`
>
[AFM mean-field]({{ site.baseurl }}/public/iridatesnotes/84-Lee-AFM-mean-field-theory-PRB.pdf)  Anti
ferromagnetic classical XY model: A mean-field analysis `84-Lee`
>
[mean-field, Lin Hirsch]({{ site.baseurl }}/public/iridatesnotes/87-Lin-Hirsch-mean-field-PRB.pdf) `87-Lin`
>
[spin-1 three degenerate orbitals]({{ site.baseurl }}/public/iridatesnotes/02-Matteo-spin-1-effective-Hamiltonian-PRB.pdf) Spin-1 effective hamiltonian with three degenerate orbitals: An application to the case of \\( \mathrm{V}_2\mathrm{O}_3 \\)
>
[Anderson]({{ site.baseurl }}/public/iridatesnotes/61-anderson-Localized-magnetic-states-in-metals-PR.pdf) Localized magnetic states in metals `61-anderson`
>
[HTCS Emery]({{ site.baseurl }}/public/iridatesnotes/87-Emery-HTCS-oxides-PRL.pdf) Theory of high-Tc superconductivity in oxides `87-Emery`
>
[Varma pairing instability]({{ site.baseurl }}/public/iridatesnotes/97-Varma-non-Fermi-Liquid-states-pairing-instability-PRB.pdf) Non-fermi-liquid states and pairing instabili
ty of a general model of copper oxide metals `97-Varma`
>
[LaMnO3 magnetic, orbital ordering]({{ site.baseurl }}/public/iridatesnotes/99-Feiner-magnetic-orbital-ordering-LMO-PRB.pdf) Electronic origin of magnetic and orbital ordering in insulating \\( \mathrm{LaMnO}_3\\) `99-Feiner`
>
[Metal insulator transition]Metal-insulator transitions `98-Imada`


11/24

삼각격자에서 Mott transition 에 대해 연구한 이 논문도 괜찮은 참고 자료인거 같다.
[Mott metal-insulator transition in the half-filled Hubbard model on the triangular lattice]({{ site.baseurl }}/public/iridatesnotes/01-Capone-Mott-transition-triangular-lattice-PRB.pdf)

M Capone, Sergio Caprara 이 두사람 논문을 따라가 볼 필요도 있을 거 같다.

perfect nesting 을 찾다가 다음 논문을 찾았음.
[chubukov graphene chiral superconductor]({{ site.baseurl }}/public/iridatesnotes/12-Nandkishore-graphene-chiral-superconductor-nphys.pdf)

다음 lecture series 역시 공부하는데 도움이 될 거 같다.
[1]({{ site.baseurl }}/public/iridatesnotes/chapter12.pdf)
[2]({{ site.baseurl }}/public/iridatesnotes/chapter14.pdf)


11/27


[Hatree-Fock approximation 검색하다가 발견한 website](https://www.eng.fsu.edu/~dommelen/quantum/style_a/contents.html)


12/01

Iridate 에서 magnetic ordering을 어떻게 다루었는지 살펴보자.

회의중 Glazer 가 제안한 간단한 [rotation tilting distortion 에 대해서 살펴보자.]({{ site.baseurl }}/public/iridatesnotes/75-Glazer-perovskite-structure-ActaCryst.pdf)


stoner instability 와 flat-band ferromagnetism 에 대해서 생각해봐야겠다.

[Khomskii 의 콜로퀴엄]({{ site.baseurl }}/public/iridatesnotes/Khomskii-talk.pdf)

[Khomskii 의 crystal splitting 에 관한 논문 arXiv]({{ site.baseurl }}/public/iridatesnotes/05-Khomskii-arXiv.pdf)

[Khomskii 의 crystal splitting 에 관한 논문 출판 버전]({{ site.baseurl }}/public/iridatesnotes/05-Khomskii-PhysScr.pdf)

Mostovoy의 M-O-M 각도가 90, [edge-sharing octahedral에 대해 연구한 논문]({{ site.baseurl }}/public/iridatesnotes/02-Mostovoy-orbital-ordering-90-Exchange-PRL.pdf)

참고로 riken에서 종종 보았던 Kugel의 [face-sharing octahedral 역시 있어서 참고해둔다.]({{ site.baseurl }}/public/iridatesnotes/14-Kugel-face-sharing-octahedral-arXiv.pdf)



12/22

조환범씨랑 회의를 하던중 [ICSD](http://icsd.kisti.re.kr/icsd/icsd_chemistry.jsp) 라는 것을 알았는데, 물질만 입력하면, 그물질이 가지는 crystal structure가 주르륵 나왔다.

이걸로 material search를 할 수 있을거같다.


12/23

교수님께서 옥타헤드론에서 실험적으로 회전을 어떻게 실현시킬 것인가를 발표하셨다. [관련 웹페이지]({{ site.baseurl }}/magnetism/2016/12/23/octahedron-rotation.html)


12/27

spin susceptibility와 magnetism 의 관계를 다음과 같은 논문에서도 다루었다.

1. [1612.07633](https://arxiv.org/abs/1612.07633) Unravelling incommensurate magnetism and the path to intrinsic topological
superconductivity in iron-pnictides `16-Christensen`

2. 일본그룹 high-topological number 스커미온 논문


2017/01/02

tight-binding 계산할 때 사각격자의 대각성분끼리의 hopping을 다룰 때 cos kx cos ky에 비례하는 항이 나오는 이유.
[scan note]({{ site.baseurl }}/public/iridatesnotes/scannote_tight-binding-cross-points.pdf)



01/04

벡터 각도 구하는 공식

[capture]({{ site.baseurl }}/public/iridatesnotes/ArcCos.png)

[mathematica]({{ site.baseurl }}/public/iridatesnotes/ArcCos.nb)



01/06

[Matsuno and Takagi 2015 PRL 논문]({{ site.baseurl }}/public/iridatesnotes/15-Matsuno-Takagi-PRL.pdf)


17.01.15

예전에 찾은 [다른 사람의 졸업논문]({{ site.baseurl }}/public/thesis/thesis2.pdf)에서 susceptibility의 다른 channel를 어떻게 계산할 수 있을 지 힌트를 얻을 수 있었다. 이논문의 introduction에 graphene에 in-plane magnetic field 가 걸리면 Fermi surface 의 density of state 가 vanishing 되지 않고, 유한한 값을 가지고 이러한 상태는 canted AFM 으로  instability 를 갖는다는 연구가 있다는 것이다.

출발점으로 좋은 논문은 아마도 [Magnetic field induced semimetal-to-canted-antiferromagnet transition
on the honeycomb lattice]({{ site.baseurl }}/public/susceptibility/0902.2922v2.pdf) `09-Bercx` 이다. introduction 을 읽어보면 이미 이런 논의가 mean-field level 에서 이루어졌다고 한다. 이논문은 quantum monte carlo 계산을 통해서 이것을 밝혔다는 것이다.

[continuum limit에서 이러한 in-plane magnetic field가 spontaneous symmetry breaking을 가능하게 한다는 것이 이미 지적되었다고 하는 논문]({{ site.baseurl }}/public/susceptibility/0611251v1.pdf) `06-Kharzeev` 역시 공부해야 될 것이다.

mean-field level에서 가능하다고 하는 것이 다음 논문이다.
[9] I. Milat, F. F. Assaad and M. Sigrist, Eur. Phys. J. B38, 571 (2004).[10] K. S. D. Beach, P. A. Lee and P. Monthoux, Phys. Rev.Lett. 92, 026401 (2004).
[11] N. M. R. Peres, M. A. N. Arau ́jo and D. Bozi, Phys. Rev. B 70, 195122 (2004).

[Ghost excitonic insulator transition in layered graphite](https://arxiv.org/abs/cond-mat/0101306v4) `01-Khveshchenko` 이 중요한지는 모르겠는데, 인터넷 브라우저에 창이 열려있었다. -> 이 논문에서 [Haldane 논문](http://journals.aps.org/prl/abstract/10.1103/PhysRevLett.61.2015)과 [semenoff 논문](http://journals.aps.org/prl/abstract/10.1103/PhysRevLett.53.2449)이 인용되었음을 알 수 있었다.

[다른 사람의 졸업논문]({{ site.baseurl }}/public/thesis/thesis2.pdf)으로부터 다른 channel susceptibility를 어떻게 계산할 수 있을지 공부해보자.
---



17.01.17

교수님과 회의 끝에 에너지 차이가 맞다는 것을 알았다. 칠판의 계산은 FM 계산이고, 실제로 우리의 계산은 AFM 하에 계산이므로 에너지 차이가 작을 수 있다.
그러면, 모델에 anisotropy를 줄수 있는 방법은 무엇이 있을까?
itinerant model 에서 자성을 어떻게 기술했는지 살펴보자.
기혜영교수님 논문과 그것을 인용한 논문을 찾아보자. random 숫자를 주어서 계산을 했는지도 살펴보자.
그리고 일반적으로 mean-field로 anisotropy를 어떻게 induce했는가 다른 논문역시 찾아보자.
