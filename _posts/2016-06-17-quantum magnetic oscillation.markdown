---
layout: post
title:  "Quantum magnetic oscillation"
date:   2016-06-17 15:00:00 +0900
categories: superconductivity

---

PRL로 부터 논문 리뷰를 의뢰 받았는데 러시아 과학자로 부터 온 논문이다. 주제는 초전도체로 내가 한번도 연구한 적이 없는 분야이긴하지만, 공부한다고 생각하고 리뷰해봐야겠다.

Quantum magnetic oscillation 은 전자구조 특히 Fermi surface를 구할 수 있는 tool 로서 오랫동안 이용되어져 왔다. 잘 알려진 실험 방법이라 cuprate 물질에서도 그 측정이 이루어졌는데, cuprate 물질에서 Magnetic oscillation의 fourier component 형태에서 peak 가 생기는 것이 알려져 있다.

이 peak 의 원인이 이전에는 CDW 에 의해서 fermi surface 가 reconstruct 되어서 그렇다는 논문들이 주를 이루었지만, 이논문은 Fermi surface reconstruction이 원인이 아니라 bilayer interaction 과 interbilayer interaction에 의한 것이라는 주장을 함.

물론 구체적인 내용은 읽어보니 아주 복잡해서 평가할 수 없지만, 기본적인 주장은 알거 같다.

이것을 언제까지 리뷰할 수 있을지는 모르지만, 다음에 다시한번 차근차근 보면서 리뷰해보자.

---
2016/7/5
SI 를 읽어봤는데 여전히 이해할수 없다.


---
2016/7/6

Abrikosov 책을 보면서 quantum oscillation 에 대해 공부했다.

de Haas-van effect 는 자기장을 금속에 걸면 Landau level 이 생성되고, thermodynamic potential (or magnetic moment)가 빠르게 oscillation 한다는 것이 de-Hass-van effect 이다.
이것으로 fermi surface를 측정할 수 있다고 하는데 그 연결관계는 잘 모르겠다.

다른 자기장에 대한 다른 효과는 Shubnikov-de Haas effect가 있다.
이것은 자기장에 대해서 conductivity가 oscillation 한다는 것이다.

---

논문 내용중 YBCO에 있다는 ortho-2 structure에 대한 논문을 읽어봤지만, 무슨내용인지 모르겠다. (98-Straube-ortho-2-structure-YBCO-physicaC.pdf)
-> ortho-2는 oxygen ordering 구조를 뜻한다. (Blackburn-ECRYS-12-August-2014.pdf 에서 확인함) 

---
 
 Quantum Oscillation 실험을 정리하면 다음과 같다. hole doped YBCO 가 관심대상이고, underdoped YBCO 에 대한 고자기장을 이용하여 quantum oscillation 를 측정하였는데 parent compound가 mott insulator라서 Fermi liquid가 아니라고 생각했던 영역에서 Quantum oscillation 신호를 발견했다. 이것은 underdoped YBCO가 Fermi liquid 영역이라는 것이다. 그것은 Landau quantization과 Fermi-Dirac statistics로 부터 알수 있다.
 
Quantum oscillation으로 부터 Fermi surface 면적을 알 수 있는데, 전체 brillioun zone의 2% 밖에 안된다는 것을 실험 사실로 알 수 있고, 낮은 온도에서 마이너스 부호를 가지는 홀 저항 실험결과로 부터 이것은 electron pocket으로 부터 Quantum oscillation 이 기인한다고 결론 내릴수 있다. 그러면 무엇이 hole-성격을 띄는 fermi surface를 작은 electron pocket으로 만들수 있냐는 질문이 있을 수 있는데, 그것은 charge ordering에 의해서 그렇다는 것이다.

15-Sebastian-quantum-oscillation-cuprate-annurev.pdf 를 한번 읽고 요약함.

---

# What is driving force for CDW and its wave vector?
# -> It can be calculated using susceptibility calculation.
 
---


YBCO tight-binding model
-> 96-Xiang-YBCO-tight-binding-PRL.pdf

---

pseudo gap 과 charge order 는 별개의 현상이고,
(증거는 charge order critical doping point 와 Pseudo gap critical doping point 가 다름.)

pseudo gap 과 antiferromagnetic mott insulator 는 서로 연결되어있다. 이것이 16-Badoux 의 결과이다.


---

[pnictide 에서 Quantum magnetic oscillation](http://iopscience.iop.org/article/10.1088/0034-4885/74/12/124507)
