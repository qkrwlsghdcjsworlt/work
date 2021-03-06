---
layout: post
title:  "relaxation dephasing"
date:   2016-12-31 11:00:00 +0900
categories: QD

---

relaxation 과 dephasing 개념은 항상 헷갈리는데, [여기에]({{ site.baseurl }}/public/QD/relaxation-dephasing.pdf) 자세한 구분이 나와있는 논문을 발견해서 스크랩해둔다.

2.3.1 Relaxation

>
Over time, the qubit will end up in thermal equilibrium with the
environment. It can exchange energy with the environment, changing
the polar angle \\( \theta \\) in the Bloch sphere representation. Any uncontrolled
change in energy will cause the loss of quantum information.
This can be measured by preparing the qubit in the excited state and
measuring the time it takes to go to thermal equilibrium. The decay
constant is generally called T1.

`relaxation 은 qubit information 의 polar angle` \\( \theta \\)  `과 관계있고, enviroment 와 energy 교환을 통한 dissipation 되는 시간을 뜻한다.`

2.3.2 Dephasing

Information in the azimuthal angle φ on the Bloch sphere can also
be lost to the environment, without energy dissipation. This is called
dephasing. There is no classical equivalent for this. The loss of phase
can be measured by so called Ramsey Interferometry. The qubit is
initialized in the \\( | 0 \rangle \\) state and brought to the equator of the Bloch
sphere by a \\( \pi /2 \\)  pulse. After a time delay, a second \\( \pi /2 \\) pulse along
the same axis is applied and the qubit is measured along the \\( z \\)-Axis.
During the delay time, the qubit undergoes Lamor precession in the
energy subspace. The oscillations decay because of noise. The decay
constant of these oscillations is called \\( T^{*2} \\)

If the noise causing this dephasing is slow compared to qubit evolution
time, more elaborate sequences of pulses can be used to extend
the lifetime of the phase information. This goes by the name
of spin-echo sequences and was developed in the context of nuclear
magnetic resonance physics. Hence, the dephasing time dependends
on the pulse sequence. The upper limit is called T2.

`dephasing 은 qubit information의 azimuthal angle` \\( \phi \\) `와 관련이 있고, energy dissipation 없이도 일어날 수 있다. dephasing은 Ramsey Interferometry를 통해서 측정할 수 있다.`
