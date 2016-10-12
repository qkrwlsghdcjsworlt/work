---
layout: page
title: tremblay
---

May 30 to June 10, 2016
Sherbrooke, Québec, Canada

* Poster advertisement [PDF]({{ site.baseurl }}/public/tremblay/Combines_1_pagers.pdf) 

Monday May 30, 2016

* Claude Spino, Welcome [PDF](/public/tremblay/WelcomeClaudeSpino.pdf)
* André-Marie Tremblay, Introduction [PDF](/public/tremblay/1605_Introduction_to_the_school.pdf)
* André-Marie Tremblay, Lecture Notes [PDF](/public/tremblay/N-corps-2014.pdf)
* André-Marie Tremblay, Hand-wrtitten Lecture Notes [PDF](/public/tremblay/Handwritten_lecture_notes_on_Refresher_Many-Body_theory_Tremblay.pdf)
    [PDF (updated June 9, 2016)](/public/tremblay/Handwritten-lecture-notes-on-Refresher-Many-Body-theory-Tremblay-updated.pdf)
* Michel Côté, Introduction to DFT [PDF (2.8 MB)](/public/tremblay/intro_dft.pdf)
* Xavier Gonze, Abinit [PDF (8.2 MB)](/public/tremblay/Sherbrooke_ABINIT_v5.pdf)


Tuesday May 31, 2016

* Ion Garate, Topological Materials [PDF (20.6 MB)](/public/tremblay/garate_jouvence.pdf)

Wednesday June 1, 2016

* David Sénéchal, DMFT and Quantum Cluster Methods [PDF (6.2 MB)](/public/tremblay/2016-Ecole.pdf)

Thursday June 2, 2016

* Olivier Parcollet, TRIQS [PDF (8.3 MB)](/public/tremblay/TRIQSCanada.pdf)
* Jan Gukelberger, Introduction to Monte Carlo [PDF](/public/tremblay/2016-06-MCIntro-Sherbrooke.pdf)
* Jan Gukelberger, Introduction to ALPS [PDF](/public/tremblay/2016-06-ALPS-Sherbrooke.pdf) [ALPS code zip file](/public/tremblay/2016-06-ALPS_bilayer_example.zip)

Friday June 3, 2016

* Roger Melko, Quantum Monte Carlo [PDF (2.9 MB)](/public/tremblay/QMC_Melko.pdf) [PDF (228 KB)](/public/tremblay/Melko_SSEQMC.pdf)
* Adrian Del Maestro, Path integral Monte Carlo and worm algorithms [GitHub repo](https://github.com/agdelma/pimc-notes)


Monday June 6, 2016

* Fabien Bruneval, GW Method [PDF (3.2 MB)](/public/tremblay/bruneval_sherbrooke_mbpt.pdf)
* Philipp Werner, Continuous-time Quantum Monte Carlo [PDF (1.9 MB)](/public/tremblay/Werner-Hand-written.pdf)

Tuesday June 7, 2016

* Gabriel Kotliar, Introduction to ab initio methods for correlated materials [Slides](/public/tremblay/kotliar_chuck.pdf) [Notes](/public/tremblay/kotliar-jouvence.pdf)
* Chuck-Hou Yee, WIEN2k Tutorial [PDF (1.4 MB)](/public/tremblay/W2KJouvence2016.pdf)


Wednesday June 8, 2016

* Kristjan Haule, Introduction to DMFT-LAPW [PDF (34.2MB)](/public/tremblay/Haule_Scherbrooke.pdf)
* Dominic Bergeron, Omega Max Ent [PDF (0.7MB)](/public/tremblay/OmegaMaxEnt_intro.pdf) \\( ~~ \\)  [Website](http://www.physique.usherbrooke.ca/MaxEnt/index.php/Main_Page)

Thursday June 9, 2016

* Ulrich Schollwock, Density-Matrix Renormalization Group [(2005)](/public/tremblay/0409292v1.pdf) [(2011)](/public/tremblay/1008.3477.pdf)
* Miles Stoudenmire, DMRG software and hands-on iTensor [PDF (3.0MB)](/public/tremblay/MPS_ITensor_Sherbrooke_2016.pdf)
-> To install the iTensor one should change the file [options.mk](/public/iTensor/options.mk)

-> iTensor 잘 작동한다. 다만, 연구실에 있는 iMac이랑 macbook 이랑 호환은 안 되는 거 같지만 iTensor main 폴더에서 make 를 실행하면 compile 잘 되는 것을 확인할 수 있다.


Sep., 2016

### My study on KWANT

kwant compile이 안 되었는데,
~/.bash_profile 에 있는
/Library/python/3.5~~~~ 이하 이걸 지우고

> `export LANG=en_US.UTF-8`
>
`export LC_ALL=en_US.UTF-8`


를 넣었더니 잘 작동한다.

[matplotlib issue](https://github.com/matplotlib/matplotlib/issues/5919/) 에서 찾음.


그리고

[KWANT github](https://github.com/kwant-project/billiard/blob/master/billiard.ipynb)에 있는 tutorial를 따라가 보면 아주 유익하다.

그리고 python을 mathematica 처럼 쓰고 싶으면

> `ipython notebook`

을 terminal 에 입력하면 된다.


[KWANT](https://kwant-project.org/doc/1.0/tutorial/tutorial1) 인터넷 문서인데, 따라서 공부하면 아주 유익할 듯 하다.

기본적인 [kwant](https://kwant-project.org/) 홈페이지
