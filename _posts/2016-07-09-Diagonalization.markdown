---
layout: post
title:  "Diagonalization"
date:   2016-07-09 13:00:00 +0900
categories: numerics

---

Diagonalization 도 내가 생각하는 당면과제인다.

검색후 찾은 키워드들은 Lapack++, TNT, Eigen 이 있다.
반드시 implementation 하자.

행렬대각화의 꿈은 아마도 Eigen을 통해서 이룰수 있을 거 같다.
Eigen을 compile 시키기위해서 
c++ -I /sw/include/eigen3/ test.cpp
와 같이 include 시켜주면 된다.

---
2016/7/11

드디어 Eigen을 통해서 대각화 프로그램을 만들었다.
이제 complex matrix에 대한 대각화 프로그램역시 만들어 보자.

---

2016/7/12
complex matrix 에 대한 대각화 프로그램도 완성이 되었다.
앞으로는 적적한 모델을 찾아서 계산해봐야겠다.
