---
layout: page
title: Berry
---


I. INTRODUCTION A. Topical overview

In 1984, Michael Berry wrote a paper that has generated immense interest throughout the different fields of physics including quantum chemistry (Berry, 1984). This paper is about the adiabatic evolution of an eigenenergy state when the external parameters of a quantum system change slowly and make up a loop in the parameter space. In the absence of degeneracy, the eigenstate will surely come back to itself when finishing the loop, but there will be a phase difference equal to the time integral of the energy  divided by plus an extra, which is now commonly known as the Berry phase.

The Berry phase has three key properties that make the concept important (Shapere and Wilczek, 1989; Bohm et al., 2003). First, it is gauge invariant. The eigenwave function is defined by a homogeneous linear equation the eigenvalue equation, so one has the gauge freedom of multiplying it with an overall phase factor which can be parameter dependent. The Berry phase is unchanged  (up to integer multiple of 2 \\( \pi \\)) by such a phase factor, provided the eigenwave function is kept to be single valued over the loop. This property makes the Berry phase physical, and the early experimental studies were focused on measuring it directly through interference phenomena.

Second, the Berry phase is geometrical. It can be written as a line integral over the loop in the parameter space and does not depend on the exact rate of change along the loop. This property makes it possible to express the Berry phase in terms of local geometrical quantities in the parameter space. Indeed, Berry himself showed that one can write the Berry phase as an integral of a field, which we now call the Berry curvature, over a surface suspending the loop. A large class of applications of the Berry phase concept occur when the parameters themselves are actually dynamical variables of slow degrees of freedom. The Berry curvature plays an essential role in the effective dynamics of these slow variables. The vast majority of applications considered in this review are of this nature.

Third, the Berry phase has close analogies to gauge field theories and differential geometry (Simon, 1983). This makes the Berry phase a beautiful, intuitive, and powerful unifying concept, especially valuable in today’s ever specializing physical science. In primitive terms, the Berry phase is like the Aharonov-Bohm phase of a charged particle traversing a loop including a magnetic flux, while the Berry curvature is like the magnetic field. The integral of the Berry curvature over closed surfaces, such as a sphere or torus, is known to be topological and quantized as integers (Chern numbers). This is analogous to the Dirac monopoles of magnetic charges that must be quantized in order to have a consistent quantum-mechanical theory for charged particles in magnetic fields. Interestingly, while the magnetic monopoles are yet to be detected in the real world, the topological Chern numbers have already found correspondence with the quantized Hall conductance plateaus in the spectacular quantum Hall phenomenon (Thouless et al., 1982).

This review concerns applications of the Berry phase concept in solid-state physics. In this field, we are typically interested in macroscopic phenomena which is slow in time and smooth in space in comparison with the atomic scales. Not surprisingly, the vast majority of applications of the Berry phase concept are discussed here. This field of physics is also extremely diverse, and we have many layers of theoretical frameworks with different degrees of transparency and validity (Ashcroft and Mermin, 1976; Marder, 2000). Therefore, a unifying organizing principle such as the Berry phase concept is particularly valuable.

We focus our attention on electronic properties, which play a dominant role in various aspects of material properties. The electrons are the glue of materials and they are also the agents responding swiftly to external fields and giving rise to strong and useful signals. A basic paradigm of the theoretical framework is based on the assumption that electrons are in Bloch waves traveling more or less independently in periodic potentials of the lattice, except that the Pauli exclusion principle has to be satisfied and electron-electron interactions are taken care of in some self-consistent manner. Much of our in- tuition on electron transport is derived from the semi- classical picture that electrons behave almost as free particles in response to external fields provided one uses the band energy in place of the free-particle dispersion. Be- cause of this, first-principles studies of electronic properties tend to document only the energy band structures and various density profiles.

There has been overwhelming evidence that such a simple picture cannot give complete account of effects to first order in electromagnetic fields. A prime example is the anomalous velocity, a correction to the usual qua- siparticle group velocity from the band energy disper- sion. This correction can be understood from a linear response analysis: the velocity operator has off-diagonal elements and electric field mixes the bands so that the expectation value of the velocity acquires an additional term to first order in the field  Karplus and Luttinger, 1954; Kohn and Luttinger, 1957 . The anomalous veloc- ity can also be understood as due to the Berry curvature of the Bloch states, which exist in the absence of the external fields and manifest in the quasiparticle velocity when the crystal momentum is moved by external forces
Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
 Chang and Niu, 1995, 1996; Sundaram and Niu, 1999 . This understanding enabled us to make a direct connec- tion with the topological Chern number formulation of the quantum Hall effect  Thouless et al., 1982; Kohmoto, 1985 , providing motivation as well as confidence in our pursuit of the eventually successful intrinsic explanation of the anomalous Hall effect  Jungwirth et al., 2002; Na- gaosa et al., 2010 .
Interestingly enough, the traditional view cannot even explain some basic effects to zeroth order of the fields. The two basic electromagnetic properties of solids as a medium are the electric polarization and magnetization, which can exist in the absence of electric and magnetic fields in ferroelectric and ferromagnetic materials. Their classical definitions were based on the picture of bound charges and currents, but these are clearly inadequate for the electronic contribution and it was known that the polarization and orbital magnetization cannot be deter- mined from the charge and current densities in the bulk of a crystal at all. A breakthrough on electric polariza- tion was made in the early 1990s by linking it with the phenomenon of adiabatic charge transport and express- ing it in terms of the Berry phase1 across the entire Bril- louin zone  Resta, 1992; King-Smith and Vanderbilt, 1993 . Based on the Berry phase formula, one can now routinely calculate polarization related properties using first-principles methods, with a typical precision of the density functional theory. The breakthrough on orbital magnetization came only recently, showing that it not only consists of the orbital moments of quasiparticles but also contains a Berry curvature contribution of to- pological origin  Thonhauser et al., 2005; Xiao et al., 2005; Shi et al., 2007 .
In this article, we follow the traditional semiclassical formalism of quasiparticle dynamics, only to make it more rigorous by including the Berry curvatures in the various facets of the phase space including the adiabatic time parameter. All of the above-mentioned effects are transparently revealed with complete precision of the full quantum theory. A number of new and related ef- fects, such as anomalous thermoelectric, valley Hall, and magnetotransport, are easily predicted, and other effects due to crystal deformation and order parameter inho- mogeneity can also be explored without difficulty. More- over, by including Berry phase induced anomalous trans- port between collisions and “side jumps” during collisions  which is itself a kind of Berry phase effect , the semiclassical Boltzmann transport theory can give complete account of linear response phenomena in weakly disordered systems  Sinitsyn, 2008 . On a micro- scopic level, although the electron wave-packet dynam- ics is yet to be directly observed in solids, the formalism has been replicated for light transport in photonic crys- tals, where the associated Berry phase effects are vividly exhibited in experiments  Bliokh et al., 2008 . Finally, it
1Also called Zak’s phase, it is independent of the Berry cur- vature which only characterizes Berry phases over loops con- tinuously shrinkable to zero  Zak, 1989 .
is possible to generalize the semiclassical dynamics in a single band into one with degenerate or nearly degener- ate bands  Culcer et al., 2005; Shindou and Imura, 2005 , and one can study transport phenomena where inter- band coherence effects as in spin transport, only to real- ize that the Berry curvatures and quasiparticle magnetic moments become non-Abelian  i.e., matrices .
The semiclassical formalism is certainly amendable to include quantization effects. For integrable dynamics, such as Bloch oscillations and cyclotron orbits, one can use the Bohr-Sommerfeld or Einstein-Brillouin-Keller quantization rule. The Berry phase enters naturally as a shift to the classical action, affecting the energies of the quantized levels, e.g., the Wannier-Stark ladders and the Landau levels. A high point of this kind of application is the explanation of the intricate fractal-like Hofstadter spectrum  Chang and Niu, 1995, 1996 . A recent break- through has also enabled us to find the density of quan- tum states in the phase space for the general case  in- cluding nonintegrable systems   Xiao et al., 2005 , revealing Berry curvature corrections which should have broad impacts on calculations of equilibrium as well as transport properties. Finally, one can execute a general- ized Peierls substitution relating the physical variables to the canonical variables, turning the semiclassical dynam- ics into a full quantum theory valid to first order in the fields  Chang and Niu, 2008 . Spin-orbit coupling and anomalous corrections to the velocity and magnetic mo- ment are all found from a simple explanation of this generalized Peierls substitution.
Therefore, it is clear that Berry phase effects in solid- state physics are not something just nice to be found here and there; the concept is essential for a coherent understanding of all the basic phenomena. It is the pur- pose of this review to summarize a theoretical frame- work which continues the traditional semiclassical point of view but with a much broader range of validity. It is necessary and sufficient to include the Berry phases and gradient energy corrections in addition to the energy dispersions in order to account for all phenomena up to first order in the fields.
B. Organization of the review
This review can be divided into three main parts. In Sec. II we consider the simplest example of Berry phase in crystals: the adiabatic transport in a band insulator. In particular, we show that induced adiabatic current due to a time-dependent perturbation can be written as a Berry phase of the electronic wave functions. Based on this understanding, the modern theory of electric polar- ization is reviewed. In Sec. III the electron dynamics in the presence of an electric field is discussed as a specific example of the time-dependent problem, and the basic formula developed in Sec. II can be directly applied. In this case, the Berry phase is made manifest as transverse velocity of the electrons, which gives rise to a Hall cur- rent. We then apply this formula to study the quantum, anomalous, and valley Hall effect.
Xiao, Chang, and Niu: Berry phase effects on electronic properties 1961
 Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
1962 Xiao, Chang, and Niu: Berry phase effects on electronic properties
To study the electron dynamics under spatial- dependent perturbations, we turn to the semiclassical formalism of Bloch electron dynamics, which has proven to be a powerful tool to investigate the influence of slowly varying perturbations on the electron dynamics. In Sec. IV we discuss the construction of the electron wave packet and show that the wave packet carries an orbital magnetic moment. Two applications of the wave- packet approach, the orbital magnetization and anoma- lous thermoelectric transport in ferromagnet, are dis- cussed. In Sec. V the wave-packet dynamics in the presence of electromagnetic fields is studied. We show that the Berry phase not only affects the equations of motion but also modifies the electron density of states in the phase space, which can be changed by applying a magnetic field. The formula for orbital magnetization is rederived using the modified density of states. We also present a comprehensive study of the magnetotransport in the presence of the Berry phase. The electron dynam- ics under more general perturbations is discussed in Sec. VI. We also present two applications: electron dynamics in deformed crystals and polarization induced by inho- mogeneity.
In the remaining part of the review we focus on the requantization of the semiclassical formulation. In Sec. VII the Bohr-Sommerfeld quantization is reviewed in detail. With its help, one can incorporate the Berry phase effect into the Wannier-Stark ladders and the Lan- dau levels very easily. In Sec. VIII we show that the same semiclassical approach can be applied to systems subject to a very strong magnetic field. One only has to separate the field into a quantization part and a pertur- bation. The former should be treated quantum mechani- cally to obtain the magnetic Bloch band spectrum while the latter is treated perturbatively. Using this formalism, the cyclotron motion, the splitting into magnetic sub- bands, and the quantum Hall effect are discussed. In Sec. IX we review recent advances on the non-Abelian Berry phase in degenerate bands. The Berry connection now plays an explicit role in spin dynamics and is deeply related to the spin-orbit interaction. The relativistic Dirac electrons and the Kane model in semiconductors are cited as two applied examples. Finally, we discuss the requantization of the semiclassical theory and the hier- archy of effective quantum theories.
We do not attempt to cover all of the Berry phase effects in this review. Interested readers can consult the following: Shapere and Wilczek  1989 ; Nenciu  1991 ; Resta  1994, 2000 ; Thouless  1998 ; Bohm et al.  2003 ; Teufel  2003 ; Chang and Niu  2008 . In this review, we focus on a pedagogical and self-contained approach, with the main focus on the semiclassical formalism of Bloch electron dynamics  Chang and Niu, 1995, 1996; Sundaram and Niu, 1999 . We start with the simplest case, then gradually expand the formalism as more com- plicated physical situations are considered. Whenever a new ingredient is added, a few applications are provided to demonstrate the basic ideas. The vast number of ap- plications we discuss is a reflection of the universality of the Berry phase effect.
C. Basic concepts of the Berry phase
In this section we introduce the basic concepts of the Berry phase. Following Berry’s original paper  Berry, 1984 , we first discuss how the Berry phase arises during the adiabatic evolution of a quantum state. We then in- troduce the local description of the Berry phase in terms of the Berry curvature. A two-level model is used to demonstrate these concepts as well as some important properties, such as the quantization of the Berry phase. Our aim is to provide a minimal but self-contained in- troduction. For a detailed account of the Berry phase, including its mathematical foundation and applications in a wide range of fields in physics, see Shapere and Wilczek  1989  and Bohm et al.  2003 , and references therein.
1. Cyclic adiabatic evolution
Consider a physical system described by a Hamil- tonian that depends on time through a set of param- eters, denoted by R= R1,R2, ... , i.e.,
H = H R ,
R = R t .
 1.1
We are interested in the adiabatic evolution of the sys- tem as R t  moves slowly along a path C in the param- eter space. For this purpose, it is useful to introduce an instantaneous orthonormal basis from the eigenstates of H R  at each value of the parameter R, i.e.,
H R  n R   =  n R  n R  .
 1.2
However, Eq.  1.2  alone does not completely determine the basis function  n R  ; it still allows an arbitrary R-dependent phase factor of  n R  . One can make a phase choice, also known as a gauge, to remove this arbitrariness. Here we require that the phase of the basis function is smooth and single valued along the path C in the parameter space.2
According to the quantum adiabatic theorem  Kato, 1950; Messiah, 1962 , a system initially in one of its eigenstates  n„R 0 ...  will stay as an instantaneous eigen- state of the Hamiltonian H„R t ... throughout the pro- cess.  A derivation can be found in the Appendix.  Therefore the only degree of freedom we have is the phase of the quantum state. We write the state at time t as
2Strictly speaking, such a phase choice is guaranteed only in finite neighborhoods of the parameter space. In the general case, one can proceed by dividing the path into several such neighborhoods overlapping with each other, then use the fact that in the overlapping region the wave functions are related by a gauge transformation of form  1.7 .
 Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
  n t   = e
n
exp
−   dt   „R t  ...  n„R t ... , n
i  t  it
now known as the Berry phase or geometric phase in general; it is given by
where the second exponential is known as the dynamical phase factor. Inserting Eq.  1.3  into the time-dependent Schrödinger equation
C
i      n t   = H„R t ...  n t    t
 1.4
From the above definition, we can see that the Berry phase only depends on the geometric aspect of the closed path and is independent of how R t  varies in time. The explicit time dependence is thus not essential in the description of the Berry phase and will be dropped in the following discussion.
2. Berry curvature
It is useful to define, in analogy to electrodynamics, a gauge-field tensor derived from the Berry vector poten- tial:
Xiao, Chang, and Niu: Berry phase effects on electronic properties 1963
     0
  1.3
 n =
dR · A  R . n
 1.10
 and multiplying it from the left by  n„R t ... , one finds that  n can be expressed as a path integral in the param- eter space
 n =  dR · An R , C
 1.5
 1.6
This vector An R  is called the Berry connection or the Berry vector potential. Equation  1.5  shows that, in ad- dition to the dynamical phase, the quantum state will acquire an additional phase  n during the adiabatic evo- lution.
Obviously, An R  is gauge dependent. If we make a gauge transformation
where An R  is a vector-valued function  

  n R   n R      
=i  R   R
 n  R =   
An R − An R   R     R   
  An R  = i n R    R  n R   .
−  ↔  

.  1.11
    n R   → ei  R  n R  ,
with   R  an arbitrary smooth function and An R  trans-
forms according to
A  R →A  R −     R .
Consequently, the phase  n given by Eq.  1.5  will be changed by  „R 0 ... −  „R T ... after the transformation, where R 0  and R T  are the initial and final points of the path C. This observation has led Fock  1928  to con- clude that one can always choose a suitable   R  such that  n accumulated along the path C is canceled out, leaving Eq.  1.3  with only the dynamical phase. Because of this, the phase  n has long been deemed unimportant and it was usually neglected in the theoretical treatment of time-dependent problems.
This conclusion remained unchallenged until Berry
 1984  reconsidered the cyclic evolution of the system
along a closed path C with R T  = R 0 . The phase choice
we made earlier on the basis function  n R   requires
i  R
valued, which implies
 „R 0 ... −  „R T ... = 2    integer.
 1.7
where S is an arbitrary surface enclosed by the path C. It can be verified from Eq.  1.11  that, unlike the Berry vector potential, the Berry curvature is gauge invariant and thus observable.
If the parameter space is three dimensional, Eqs.  1.11  and  1.12  can be recast into a vector form
This field is called the Berry curvature. Then according to Stokes’s theorem the Berry phase can be written as a surface integral
 1.12

 n= dR ∧dR 1 n  R ,
 S
2   
 n n  R
 1.8
 e
      −   2
in the gauge transformation  Eq.  1.7   to be single
 n  H/ R  n   n   H/ R  n  −    ↔     n R =i  .
This shows that  n can be only changed by an integer multiple of 2  under the gauge transformation  Eq.  1.7   and it cannot be removed. Therefore for a closed path,  n becomes a gauge-invariant physical quantity,
Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
 1.9
 n R  =  R   An R ,
S
lated by     =       n   with      the Levi-Cività anti- symmetry tensor. The vector form gives us an intuitive picture of the Berry curvature: it can be viewed as the magnetic field in the parameter space.
Besides the differential formula given in Eq.  1.11 , the Berry curvature can be also written as a summation over the eigenstates:
 1.13
The curvature can be obtained from Eq.  1.11  using  n  H/ R n  =  n/ R n    n− n   for n  n. The sum- mation formula has the advantage that no differentia- tion on the wave function is involved, therefore it can be evaluated under any gauge choice. This property is par-

 1.11    1.12  
and vector   are re- n    n
 n =
The Berry curvature tensor  n
dS ·    R . n
n  n
n n
1964 Xiao, Chang, and Niu: Berry phase effects on electronic properties
ticularly useful for numerical calculations, in which the condition of a smooth phase choice of the eigenstates is not guaranteed in standard diagonalization algorithms. It has been used to evaluate the Berry curvature in crys- tals with the eigenfunctions supplied from first- principles calculations  Fang et al., 2003; Yao et al., 2004 .
Equation  1.13  offers further insight on the origin of the Berry curvature. The adiabatic approximation adopted earlier is essentially a projection operation, i.e., the dynamics of the system is restricted to the nth en- ergy level. In view of Eq.  1.13 , the Berry curvature can be regarded as the result of the “residual” interaction of those projected-out energy levels. In fact, if all energy levels are included, it follows from Eq.  1.13  that the total Berry curvature vanishes for each value of R,
3. Example: The two-level system
Consider a concrete example: a two-level system. The purpose to study this system is twofold. First, as a simple model, it demonstrates the basic concepts as well as sev- eral important properties of the Berry phase. Second, it will be repeatedly used later in this article, although in different physical context. It is therefore useful to go through the basis of this model.
The generic Hamiltonian of a two-level system takes the following form:
H = h R  ·  ,  1.15
where   are the Pauli matrices. Despite its simple form, the above Hamiltonian describes a number of physical systems in condensed-matter physics for which the Berry phase effect has been discussed. Examples include spin- orbit coupled systems  Culcer et al., 2003; Liu et al., 2008 , linearly conjugated diatomic polymers  Su et al., 1979; Rice and Mele, 1982 , one-dimensional ferroelec- trics  Vanderbilt and King-Smith, 1993; Onoda et al., 2004b , graphene  Semenoff, 1984; Haldane, 1988 , and Bogoliubov quasiparticles  Zhang et al., 2006 .
Parametrize h by its polar angle   and azimuthal angle
  n  R =0.   
n
 1.14
This is the local conservation law for the Berry curvature.3 Equation  1.13  also shows that  n  R  be-

comes singular if two energy levels  n R  and  n  R  are
brought together at certain value of R. This degeneracy point corresponds to a monopole in the parameter space; an explicit example is given below.
So far we have discussed the situation where a single energy level can be separated out in the adiabatic evo- lution. However, if the energy levels are degenerate, then the dynamics must be projected to a subspace spanned by those degenerate eigenstates. Wilczek and Zee  1984  showed that in this situation non-Abelian Berry curvature naturally arises. Culcer et al.  2005  and Shindou and Imura  2005  discussed the non-Abelian Berry curvature in the context of degenerate Bloch bands. In the following we focus on the Abelian formu- lation and defer the discussion of the non-Abelian Berry curvature to Sec. IX.
Compared to the Berry phase which is always associ- ated with a closed path, the Berry curvature is truly a local quantity. It provides a local description of the geo- metric properties of the parameter space. Moreover, so far we have treated the adiabatic parameters as passive quantities in the adiabatic process, i.e., their time evolu- tion is given from the outset. Later we will show that the parameters can be regarded as dynamical variables and the Berry curvature will directly participate in the dy- namics of the adiabatic parameters  Kuratsuji and Iida, 1985 . In this sense, the Berry curvature is a more fun- damental quantity than the Berry phase.
3The conservation law is obtained under the condition that the full Hamiltonian is known. However, in practice one usu- ally deals with effective Hamiltonians which are obtained through some projection process of the full Hamiltonian. Therefore there will always be some “residual” Berry curva- ture accompanying the effective Hamiltonian  see Chang and Niu  2008  and discussions in Sec. IX .
 , h=h sin   cos  ,sin   sin  ,cos   , the states, with energies ±h, are
two
eigen-
 1.16
 u− =
2 ,  u+ = 2
.
 sin   e−i     cos   e−i   
  − cos   sin   22
  We are, of course, free to add an arbitrary phase to these wave functions. Consider the lower energy level. The Berry connection is given by
A  =  u i  u  = 0,
A  =  u i  u  = sin2   ,
2 and the Berry curvature is
pole   =  . We can choose another gauge by multiply- ing  u−  by ei  so that the wave function is smooth and single valued everywhere except at the north pole. Un- der this gauge we find A =0 and A =−cos2  /2, and the same expression for the Berry curvature as in Eq.  1.18 . This is not surprising because the Berry curvature is a gauge-independent quantity and the Berry connection is not.4
4One can verify that  u =„sin  /2 e−i  ,−cos  /2 ei  −1  ...T is
also an eigenstate. The phase accumulated by such a state
along the loop defined by  = /2 is  =2   −1 , which seems 2
to imply that the Berry phase is gauge dependent. This is be- cause for an arbitrary   the basis function  u  is not single valued; one must also trace the phase change in the basis func- tion. For integer value of   the function  u  is single valued along the loop and the Berry phase is well defined up to an integer multiple of 2 .
 1.17a   1.17b
 1.18  However, the phase of  u−  is not defined at the south
   = A− A=1sin .            2
    Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
If h R  depends on a set of parameters R, then
the following unitary transformation to obtain a q-dependent Hamiltonian:
  pˆ +   q   2
H q  = e−iq·rHeiq·r = 2m + V r .  1.24
The transformed eigenstate unq r =e−iq·r nq r  is just the cell-periodic part of the Bloch function. It satisfies the strict periodic boundary condition
unq r + a  = unq r .  1.25
This boundary condition ensures that all the eigenstates live in the same Hilbert space. We can thus identify the Brillouin zone as the parameter space of the trans- formed Hamiltonian H q  and  un q   as the basis func- tion.
Since the q dependence of the basis function is inher- ent to the Bloch problem, various Berry phase effects are expected in crystals. For example, if q is forced to vary in the momentum space, then the Bloch state will pick up a Berry phase:
 R1R2 =
1    ,cos    2   R1,R2
.
 1.19
Xiao, Chang, and Niu: Berry phase effects on electronic properties 1965
   Several important properties of the Berry curvature can be revealed by considering the specific case of h = x,y,z . Using Eq.  1.19 , we find the Berry curvature in its vector form
 =1h.  1.20  2h3
One recognizes that Eq.  1.20  is the field generated by a monopole at the origin h = 0  Dirac, 1931; Wu and Yang, 1975; Sakurai, 1993 , where the two energy levels be- come degenerate. Therefore the degeneracy points act as sources and drains of the Berry curvature flux. Inte- grate the Berry curvature over a sphere containing the monopole, which is the Berry phase on the sphere; we find
  1  d d   2  S2
In general, the Berry curvature integrated over a closed manifold is quantized in the units of 2  and equals to the net number of monopoles inside. This number is called the Chern number and is responsible for a num- ber of quantization effects discussed below.
D. Berry phase in Bloch bands
Above we introduced the basic concepts of the Berry phase for a generic system described by a parameter- dependent Hamiltonian. We now consider its realization in crystalline solids. As we shall see, the band structure of crystals provides a natural platform to investigate the occurrence of the Berry phase effect.
Within the independent electron approximation, the band structure of a crystal is determined by the follow- ing Hamiltonian for a single electron:
pˆ 2
H = 2m + V r ,  1.22
where V r + a  = V r  is the periodic potential with a the Bravais lattice vector. According to Bloch’s theorem, the eigenstates of a periodic Hamiltonian satisfy the follow- ing boundary condition:5
 nq r + a  = eiq·a nq r ,  1.23
where n is the band index and  q is the crystal momen- tum, which resides in the Brillouin zone. Thus the sys- tem is described by a q-independent Hamiltonian with a q-dependent boundary condition  Eq.  1.23  . To comply with the general formalism of the Berry phase, we make
5Through out this article, q refers to the canonical momen- tum and k is reserved for mechanical momentum.

C

=1.  1.21
 n =
dq ·  u  q  i   u  q  . nqn
 1.26
We emphasize that the path C must be closed to make  n a gauge-invariant quantity with physical significance.
Generally speaking, there are two ways to generate a closed path in the momentum space. One can apply a magnetic field, which induces a cyclotron motion along a closed orbit in the q space. This way the Berry phase can manifest in various magneto-oscillatory effects  Mikitik and Sharlai, 1999, 2004, 2007 , which have been ob- served in metallic compound LaRhIn5  Goodrich et al., 2002 , and most recently graphene systems  Novoselov et al., 2005, 2006; Zhang et al., 2005 . Such a closed orbit is possible only in two- or three-dimensional  3D  sys- tems  see Sec. VII.A . Following our discussion in Sec. I.C, we define the Berry curvature of the energy bands by
 n q  =  q    un q  i q un q  .  1.27  The Berry curvature  n q  is an intrinsic property of the
band structure because it only depends on the wave function. It is nonzero in a wide range of materials, in particular, crystals with broken time-reversal or inver- sion symmetry. In fact, once we have introduced the con- cept of the Berry curvature, a closed loop is not neces- sary because the Berry curvature itself is a local gauge- invariant quantity. It is now well recognized that information on the Berry curvature is essential in a proper description of the dynamics of Bloch electrons, which has various effects on transport and thermody- namic properties of crystals.
One can also apply an electric field to cause a linear variation in q. In this case, a closed path is realized when q sweeps the entire Brillouin zone. To see this, we note that the Brillouin zone has the topology of a torus: the two points q and q+G can be identified as the same point, where G is the reciprocal lattice vector. This can
  Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
1966 Xiao, Chang, and Niu: Berry phase effects on electronic properties
be seen by noting that   n q   and   n q + G   satisfy the same boundary condition in Eq.  1.23 ; therefore, they can at most differ by a phase factor. The torus topology is realized by making the phase choice   n q   =   n q +G  . Consequently,  un q   and  un q+G   satisfy the following phase relation:
the perturbation is periodic in time, i.e., the Hamiltonian satisfies
H t + T  = H t .  2.1
Since the time-dependent Hamiltonian still has the translational symmetry of the crystal, its instantaneous eigenstates have the Bloch form eiqx un q , t  . It is con- venient to work with the q-space representation of the Hamiltonian H q , t   see Eq.  1.24   with eigenstates  un q , t  . We note that under this parametrization the wave vector q and time t are put on an equal footing as both are independent coordinates of the parameter space.
We are interested in the adiabatic current induced by the variation in external potentials. Apart from an un- important overall phase factor and up to first order in the rate of the change in the Hamiltonian, the wave function is given by  see the Appendix
u  r  = eiG·ru  r  . nq nq+G
 1.28
This gauge choice is called the periodic gauge  Resta, 2000 .
In this case, the Berry phase across the Brillouin zone is called Zak’s phase  Zak, 1989
 n =   BZ
dq ·  u  q  i   u  q   . nqn
 1.29
This phase plays an important role in the formation of Wannier-Stark ladders  Wannier, 1962 ; see Sec. VII.B. We note that this phase is entirely due to the torus to- pology of the Brillouin zone, and it is the only way to realize a closed path in a one-dimensional parameter space. By analyzing the symmetry properties of Wannier functions  Kohn, 1959  of a one-dimensional crystal, Zak  1989  showed that  n is either 0 or   in the presence of inversion symmetry; a simple argument is given in Sec. II.C. If the crystal lacks inversion symmetry,  n can as- sume any value. Zak’s phase is also related to macro- scopic polarization of an insulator  King-Smith and Vanderbilt, 1993; Resta, 1994; Sipe and Zak, 1999 ; see Sec. II.C.
II. ADIABATIC TRANSPORT AND ELECTRIC POLARIZATION
One of the earlier examples of the Berry phase effect in crystals is the adiabatic transport in a one- dimensional band insulator, first considered by Thouless  1983 . He found that if the potential varies slowly in time and returns to itself after some time, the particle transport during the time cycle can be expressed as a Berry phase and it is an integer. This idea was later gen- eralized to many-body systems with interactions and dis- order provided that the Fermi energy always lies in a bulk energy gap during the cycle  Niu and Thouless, 1984 . Avron and Seiler  1985  studied the adiabatic transport in multiply connected systems. The scheme of adiabatic transport under one or several controlling pa- rameters has proven very powerful and opened the door to the field of parametric charge pumping  Niu, 1990; Talyanskii et al., 1997; Brouwer, 1998; Switkes et al., 1999; Zhou et al., 1999 . It also provides a firm founda- tion to the modern theory of polarization developed in the early 1990s  King-Smith and Vanderbilt, 1993; Ortiz and Martin, 1994; Resta, 1994 .
A. Adiabatic current
Consider a one-dimensional band insulator under a slowly varying time-dependent perturbation. We assume
 un  − i     un   un   un/ t  . n  n  n −  n
 2.2
 The velocity operator in the q representation has the form v q , t  =  H q , t  /    q .6 Hence, the average veloc- ity in a state of given q is found to first order as
vn q  =   n q    q
− i     un  H/ q un   un   un/ t  − c.c. , n  n  n −  n
 2.3
where c.c. denotes the complex conjugate. Using the fact
that  un  H /  q un   =   n −  n    un /  q   un   and the iden-
tity    u   u  =1, we find n  n  n
      q     u   u     u   u    vn q = n −i n n − n n .
       q  q  t  t  q
The second term is exactly the Berry curvature  n de-
fined in the parameter space  q , t   see Eq.  1.11  . Therefore Eq.  2.4  can be recast into a compact form
v  q  =   n q  −  n . n   q qt
 2.5
 2.4  qt
 Upon integration over the Brillouin zone, the zeroth- order term given by the derivative of the band energy vanishes, and only the first-order term survives. The in- duced adiabatic current is given by
6The velocity operator is defined by v r ̇= i/   H,r . In the q representation, it becomes v q  = e−iq·r i /    r , H eiq·r = H q,t /   q .
 Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
 y D=(0,1)
A=(0,0)
dy A  0,y  − A  1,y   ,  2.8   1  
0
where the band index n is dropped for simplicity. Now consider the integration over x. By definition Ax x,y  = u x,y  i x u x,y  . Recall that  u x,0   and  u x,1   describe physically equivalent states, therefore they can only differ by a phase factor, i.e., ei x x  u x , 1   = u x,0  . We thus have
Xiao, Chang, and Niu: Berry phase effects on electronic properties 1967
  C=(1,1)
B=(1,0) x (b)
−
yy
 R(t) q
     (a)
FIG. 1. Brillouin zone as a torus.  a  A torus with its surface parametrized by  q,t . The control parameter R t  is periodic in t.  b  The equivalence of a torus: a rectangle with periodic boundary conditions: AB=DC and AD=BC. To make use of Stokes’s theorem, we relax the boundary condition and allow the wave functions on parallel sides to have different phases.
 1
0 Similarly,
j=− dq n ,  2.6  where ei y y  u y,1  = u y,0  . The total integral is   0
1   x 1  −  x 0  +  y 0  −  y 1  . 2
dx A  x,0  − A  x,1   =    1  −    0 . xxxx
 2.9
 2.10
     1
dy A  0,y  − A  1,y   =    1  −    0 , yyyy
 n BZ2
qt
 where the sum is over filled bands. We have thus derived the result that the adiabatic current induced by a time- dependent perturbation in a band is equal to the q inte- gral of the Berry curvature  n  Thouless, 1983 .
B. Quantized adiabatic particle transport
Next we consider the particle transport for the nth band over a time cycle given by
c =
the four corners A, B, C, and D,
cn = −
 T  dqn dt 2  qt. 0 BZ
 2.7
Since the Hamiltonian H q,t  is periodic in both t and q, the parameter space of H q,t  is a torus, schematically shown in Fig. 1 a . By definition  1.12 , 2 cn is nothing but the Berry phase over the torus.
In Sec. I.C.3 we showed that the Berry phase over a closed manifold, the surface of a sphere S2 in that case, is quantized in the unit of 2 . Here we prove that it is also true in the case of a torus. Our strategy is to evalu- ate the surface integral  2.7  using Stokes’s theorem, which requires the surface to be simply connected. To do that, we cut the torus open and transform it into a rect- angle, as shown in Fig. 1 b . The basis function along the contour of the rectangle is assumed to be single valued. We introduce x=t/T and y=q/2 . According to Eq.  1.10 , the Berry phase in Eq.  2.7  can be written into a contour integral of the Berry vector potential, i.e.,
c = dxAx x,0  + dyAy 1,y  1   B  C
The single valuedness of  u  requires that the exponent must be an integer multiple of 2 . Therefore the trans- ported particle number c, given in Eq.  2.11 , must be quantized. This integer is called the first Chern number, which characterizes the topological structure of the map- ping from the parameter space  q,t  to the Bloch states  u q,t  . Note that in our proof we made no reference to the original physical system; the quantization of the Chern number is always true as long as the Hamiltonian is periodic in both parameters.
For a particular case in which the entire periodic po- tential is sliding, an intuitive picture of the quantized particle transport is the following. If the periodic poten- tial slides its position without changing its shape, we ex- pect that the electrons simply follow the potential. If the potential shifts one spatial period in the time cycle, the particle transport should be equal to the number of filled Bloch bands  double if the spin degeneracy is counted . This follows from the fact that there is on average one state per unit cell in each filled band.
1. Conditions for nonzero particle transport in cyclic motion
We have shown that the adiabatic particle transport over a time period takes the form of the Chern number
qt
ei x 0  u 0,1   =  u 0,0  , ei x 1  u 1,1   =  u 1,0  , ei y 0  u 1,0   =  u 0,0  ,
ei y 1  u 1,1   =  u 0,1  , we obtain
 u 0,0   = ei  x 1 − x 0 + y 0 − y 1   u 0,0  .
 2.11  On the other hand, using the phase matching relations at
  2.12
 2 A B
dxA  x,1  + dyA  0,y   D  A  
+
= 2  dx A  x,0  − A  x,1  
x CD
y
1   1 0
xx
 Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
1968 Xiao, Chang, and Niu: Berry phase effects on electronic properties
and it is quantized. However, the exact quantization does not guarantee that the electrons will be transported at the end of the cycle because zero is also an integer. According to the discussion in Sec. I.C.3, the Chern number counts the net number of monopoles enclosed by the surface. Therefore the number of transported electrons can be related to the number of monopoles, which are degeneracy points in the parameter space.
To formulate this problem, we let the Hamiltonian depend on time through a set of control parameters R t , i.e.,
H  , t  = exp i    xi H t exp − i    xi  with the strict periodic boundary condition
 2.17
H q,t  = H„q,R t ...,
The particle transport is now given by, in terms of R,
  ̃  ;x ,...,x +L,...,x  =  ̃   ;x ,...,x,...,x  . 1i N 1iN
 2.18
The Hamiltonian H  ,t  together with the boundary condition  2.18  describes a one-dimensional system placed on a ring of length L and threaded by a magnetic flux of   /e  L  Kohn, 1964 . We note that the above transformation  2.17  with the boundary condition  2.18  is similar to that of the one-particle case, given by Eqs.  1.24  and  1.25 .
One can verify that the current operator is given by  H  ,t /     . For each  , we can repeat the same steps in Sec. II.A by identifying  un  in Eq.  2.2  as the many-
body ground-state    ̃ 0  and  un   as the excited state. We have
j    =       − i     ̃ 0    ̃ 0 −     ̃ 0    ̃ 0  
cn = 1  dR   dq  n . 2  qR
BZ
 2.14
R t + T  = R t .
 2.13
 If R t  is a smooth function of t, as it is usually the case for physical quantities, then R must have at least two components, say R1 and R2. Otherwise, the trajectory of R t  cannot trace out a circle on the torus  see Fig. 1 a  . To find the monopoles inside the torus, we now relax the constraint that R1 and R2 can only move on the surface and extend their domains inside the torus such that the parameter space of  q , R1 , R2  becomes a toroid. Thus, the criterion for cn to be nonzero is that a degeneracy point must occur somewhere inside the torus as one var- ies q, R1, and R2. In the context of quasi-one- dimensional ferroelectrics, Onoda et al.  2004b  dis- cussed the situation where R has three components and showed how the topological structure in the R space affects the particle transport.
2. Many-body interactions and disorder
Above we considered only band insulators of nonin- teracting electrons. However, in real materials both many-body interactions and disorder are ubiquitous. Niu and Thouless  1984  studied this problem and showed that in the general case the quantization of particle transport is still valid as long as the system remains an insulator during the whole process.
Consider a time-dependent Hamiltonian of an N-particle system
        t =       −   ̃  t .

 t   
 2.19
      So far the derivation is formal and we still cannot see why the particle transport should be quantized. The key step is achieved by realizing that if the Fermi energy lies in a gap, then the current j    should be insensitive to the boundary condition specified by    Thouless, 1981; Niu and Thouless, 1984 . Consequently, we can take the thermodynamic limit and average j    over different boundary conditions. Note that   and   + 2  / L describe the same boundary condition in Eq.  2.16 . Therefore the parameter space for   and t is a torus T2: 0    2 /L,0 t T . The particle transport is given by
1  T  2 /L c = − 2   d t
00
d     ̃   t ,   2 . 2 0  
 N   pˆ 2   N
H t =  i +U xi,t  + V xi−xj ,
i2m i j
 2.15
which, according to the previous discussion, is quan- tized.
We emphasize that the quantization of the particle transport only depends on two conditions:
 1  The ground state is separated from the excited states in the bulk by a finite energy gap.
 2  The ground state is nondegenerate.
The exact quantization of the Chern number in the presence of many-body interactions and disorder is re- markable. Usually, small perturbations to the Hamil- tonian result in small changes of physical quantities. However, the fact that the Chern number must be an integer means that it can only be changed in a discon- tinuous way and does not change at all if the perturba- tion is small. This is a general outcome of the topological invariance.
 where the one-particle potential U xi,t  varies slowly in time and repeats itself in period T. Note that we have not assumed any specific periodicity of the potential U xi,t . The trick is to use the so-called twisted bound- ary condition by requiring that the many-body wave function satisfies
  x1, ... ,xi + L, ... ,xN  = ei L  x1, ... ,xi, ... ,xN ,  2.16
where L is the size of the system. This is equivalent to solving a  -dependent Hamiltonian
Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
Later we show that the same quantity also appears in the quantum Hall effect. Equation  2.19 , the induced current, also provides a many-body formulation for adiabatic transport.
3. Adiabatic pumping
The phenomenon of adiabatic transport is sometimes called adiabatic pumping because it can generate a dc current I via periodic variations of some parameters of the system, i.e.,
I = ec ,  2.21
where c is the Chern number and   is the frequency of the variation. Niu  1990  suggested that the exact quan- tization of the adiabatic transport can be used as a stan- dard for charge current and proposed an experimental realization in nanodevices, which could serve as a charge pump. Later a similar device was realized in the experi- mental study of acoustoelectric current induced by a sur- face acoustic wave in a one-dimensional channel in a GaAs-AlxGa1−x heterostructure  Talyanskii et al., 1997 . The same idea has led to the proposal of a quantum spin pump in an antiferromagnetic chain  Shindou, 2005 .
Recently much effort has focused on adiabatic pump- ing in mesoscopic systems  Brouwer, 1998; Zhou et al., 1999; Avron et al., 2001, 2004; Sharma and Chamon, 2001; Mucciolo et al., 2002; Zheng et al., 2003 . Experi- mentally both charge and spin pumping have been ob- served in a quantum dot system  Switkes et al., 1999; Watson et al., 2003 . Instead of the wave function, the central quantity in a mesoscopic system is the scattering matrix. Brouwer  1998  showed that the pumped charge over a time period is given by
that in crystals the charge distribution is periodic in space, for which the electric dipole operator is not well defined. This difficulty is most exemplified in covalent solids, where the electron charges are continuously dis- tributed between atoms. In this case, simple integration over charge density would give arbitrary values depend- ing on the choice of the unit cell  Martin, 1972, 1974 . It has prompted the question whether the electric polariza- tion can be defined as a bulk property. These problems are eventually solved by the modern theory of polariza- tion  King-Smith and Vanderbilt, 1993; Resta, 1994 , where it is shown that only the change in polarization has physical meaning and it can be quantified using the Berry phase of the electronic wave function. The result- ing Berry phase formula has been very successful in first-principles studies of dielectric and ferroelectric ma- terials. Resta and Vanderbilt  2007  reviewed recent progress in this field.
Here we discuss the theory of polarization based on the concept of adiabatic transport. Their relation is re- vealed by elementary arguments from macroscopic elec- trostatics  Ortiz and Martin, 1994 . We begin with
  · P r  = −   r ,  2.23
where P r  is the polarization density and   r  is the charge density. Coupled with the continuity equation
Xiao, Chang, and Niu: Berry phase effects on electronic properties 1969
   r  + ·j=0,  t
Eq.  2.23  leads to   ·   P − j = 0.
 t
 2.22     
 2.24
  Q m  =
dX dX
I
the polarization density is given by
e
 S   S
      ,
 2.25  Therefore up to a divergence-free part,7 the change in

 X  X
T
0
12
A    m12
where m labels the contact, X1 and X2 are two external  P  = parameters whose trace encloses the area A in the pa-
dt j .  
 2.26
rameter space,   and   label the conducting channels, and S   is the scattering matrix. Although the physical descriptions of these open systems are dramatically dif- ferent from the closed ones, the concepts of gauge field and geometric phase can still be applied. The integrand in Eq.  2.22  can be thought as the Berry curvature  X1X2 = −2I  X1u    X2u  if we identify the inner product of the state vector with the matrix product. Zhou et al.  2003  showed the pumped charge  spin  is essentially the Abelian  non-Abelian  geometric phase associated with scattering matrix S  .
C. Electric polarization of crystalline solids
Electric polarization is one of the fundamental quan- tities in condensed-matter physics, essential to any proper description of dielectric phenomena of matter. Despite its importance, the theory of polarization in crystals had been plagued by the lack of a proper micro- scopic understanding. The main difficulty lies in the fact
Equation  2.26  can be interpreted in the following way: The polarization difference between two states is given by the integrated bulk current as the system adiabati- cally evolves from the initial state at t = 0 to the final state at t = T. This description implies a time-dependent Hamiltonian H t , and the electric polarization can be regarded as “unquantized” adiabatic particle transport. The above interpretation is also consistent with experi- ments, as it is always the change in the polarization that has been measured  Resta and Vanderbilt, 2007 .
Obviously, the time t in the Hamiltonian can be re- placed by any scalar that describes the adiabatic process. For example, if the process corresponds to a deforma- tion of the crystal, then it makes sense to use the param-
7The divergence-free part of the current is usually given by the magnetization current. In a uniform system, such current vanishes identically in the bulk. Hirst  1997  gave an in-depth discussion on the separation between polarization and magne- tization current.
 Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
1970 Xiao, Chang, and Niu: Berry phase effects on electronic properties
eter that characterizes the atomic displacement within a unit cell. For general purpose, we assume the adiabatic transformation is parametrized by a scalar   t  with   0  = 0 and   T  = 1. It follows from Eqs.  2.6  and  2.26  that
King-Smith and Vanderbilt  1993  further showed that, based on Eq.  2.28 , the polarization per unit cell can be defined as the dipole moment of the Wannier charge density,
 P =e
q

 2.30  where Wn r  is the Wannier function of the nth band,
1dqn n d   2  d   ,  2.27
n
P = − e   dr r W  r  2,
 n 0 BZ
where d is the dimensionality of the system. This is the Berry phase formula obtained by King-Smith and Vanderbilt  1993 .
In numerical calculations, a two-point version of Eq.  2.27  that involves only the initial and final states of the system is commonly used to reduce the computational load. This version is obtained under the periodic gauge  see Eq.  1.28  .8 The Berry curvature  q   is written as  q A  −   Aq . Under the periodic gauge, A  is periodic in q , and integration of  q A  over q  vanishes. Hence
W  r − R  =  NV   dq eiq· r−R u  r .  2.31  n 0 2  3nk
BZ
In this definition, one effectively maps a band insulator into a periodic array of localized distributions with truly quantized charges. This resembles an ideal ionic crystal where the polarization can be understood in the classical picture of localized charges. The quantum uncertainty found in Eq.  2.29  is reflected by the fact that the Wan- nier center position is defined only up to a lattice vector.
Before concluding, we point out that the polarization defined above is clearly a bulk quantity as it is given by the Berry phase of the ground-state wave function. A many-body formulation was developed by Ortiz and Martin  1994  based on the work of Niu and Thouless  1984 .
Recent development in this field falls into two catego- ries. On the computational side, calculating polarization in finite electric fields has been addressed, which has a strong influence on density functional theory in ex- tended systems  Nunes and Vanderbilt, 1994; Nunes and Gonze, 2001; Souza et al., 2002 . On the theory side, Resta  1998  proposed a quantum-mechanical position operator for extended systems. It was shown that the expectation value of such an operator can be used to characterize the phase transition between the metallic and insulating states  Resta and Sorella, 1999; Souza et al., 2000  and is closely related to the phenomenon of electron localization  Kohn, 1964 .
1. The Rice-Mele model
So far our discussion of the adiabatic transport and electric polarization has been rather abstract. We now consider a concrete example: a one-dimensional dimer- ized lattice model described by the following Hamil- tonian:
+H.c. +  −1 c c , j †j j
 2.32
where t is the uniform hopping amplitude,   is the dimerization order, and   is a staggered sublattice po- tential. It is the prototype Hamiltonian for a class of one-dimensional ferroelectrics. At half filling, the system is a metal for  = =0, and an insulator otherwise. Rice and Mele  1982  considered this model in the study of solitons in polyenes. It was later used to study ferroelec- tricity  Vanderbilt and King-Smith, 1993; Onoda et al.,
   P =e dq An      1
.
 2.28
 BZ  2  d q
 =0
In view of Eq.  2.28 , both the adiabatic transport and the electric polarization can be regarded as the manifes- tation of Zak’s phase, given in Eq.  1.29 .
A price must be paid, however, to use the two-point formula, namely, the polarization in Eq.  2.28  is deter- mined up to an uncertainty quantum. Since the integral  2.28  does not track the history of  , there is no infor- mation on how many cycles   has gone through. Accord- ing to our discussion on quantized particle transport in Sec. II.B, for each cycle an integer number of electrons are transported across the sample, hence the polariza- tion is changed by multiple of the quantum
ea V ,
0
 2.29
 where a is the Bravais lattice vector and V0 is the volume of the unit cell.
Because of this uncertainty quantum, the polarization may be regarded as a multivalued quantity with each value differed by the quantum. With this in mind, con- sider Zak’s phase in a one-dimensional system with in- version symmetry. Now we know that Zak’s phase is just 2  / e times the polarization density P. Under spatial in- version, P transforms to −P. On the other hand, inver- sion symmetry requires that P and −P describes the same state, which is only possible if P and −P differ by multiple of the polarization quantum ea. Therefore P is either 0 or ea/2  modulo ea . Any other value of P will break the inversion symmetry. Consequently, Zak’s phase can only take the value 0 or    modulo 2  .
8A more general phase choice is given by the path- independent gauge  un q ,     = ei   q +G·r  un q + G ,    , where   q  is an arbitrary phase  Ortiz and Martin, 1994 .
H =     t j22
 c c  
+  − 1
j   †j j + 1
   Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
0.5
0
-0.5
FIG. 2.  Color online  Polarization as a function of   and   in the Rice-Mele model. The unit is ea with a the lattice constant. The line of discontinuity can be chosen anywhere depending on the particular phase choice of the eigenstate.
2004b . If   = 0, it reduces to the celebrated Su-Shrieffer- Heeger model  Su et al., 1979 .
Assuming periodic boundary conditions, the Bloch representation of the above Hamiltonian is given by H q =h q · , where
III. ELECTRON DYNAMICS IN AN ELECTRIC FIELD
The dynamics of Bloch electrons under the perturba- tion of an electric field is one of the oldest problems in solid-state physics. It is usually understood that while the electric field can drive electron motion in momen- tum space, it does not appear in the electron velocity; the latter is simply given by  see, for example, Chap. 12 of Ashcroft and Mermin  1976  
vn q  =   n q  .  3.1    q
Through recent progress on the semiclassical dynamics of Bloch electrons it has been made increasingly clear that this description is incomplete. In the presence of an electric field, an electron can acquire an anomalous ve- locity proportional to the Berry curvature of the band  Chang and Niu, 1995, 1996; Sundaram and Niu, 1999 . This anomalous velocity is responsible for a number of transport phenomena, in particular various Hall effects, which we study in this section.
A. Anomalous velocity
Consider a crystal under the perturbation of a weak electric field E, which enters into the Hamiltonian through the coupling to the electrostatic potential   r . A uniform E means that   r  varies linearly in space and breaks the translational symmetry of the crystal so that Bloch’s theorem cannot be applied. To avoid this diffi- culty, one can let the electric field enter through a uni- form vector potential A t  that changes in time. Using the Peierls substitution, the Hamiltonian is written as
 pˆ + eA t  2
H t  = 2m + V r .  3.2
This is the time-dependent problem studied in last sec- tion. Transforming to the q-space representation, we have
Xiao, Chang, and Niu: Berry phase effects on electronic properties 1971
    h =  t cos qa,−   sin qa,  . 22
 2.33
  This is the two-level model discussed in Sec. I.C.3. Its energy spectrum consists of two bands with eigenener- gies  ±=±  2+ 2 sin2 qa/2+t2 cos2 qa/2 1/2. The degen- eracy point occurs at
 =0,  =0, q= /a.  2.34  The polarization is calculated using the two-point for-
mula  2.28  with the Berry connection given by
Aq =  q A  +  q A  = sin2    q  ,  2.35
2
where   and   are the spherical angles of h.
Consider the case of   = 0. In the parameter space of h, it lies in the x-y plane with  = /2. As q varies from 0 to 2 /a,   changes from 0 to   if   0 and 0 to −  if     0. Therefore the polarization difference between P    and P −   is ea / 2. This is consistent with the obser- vation that the state with P −   can be obtained by shift-
ing the state with P    by half of the unit cell length a. Figure 2 shows the calculated polarization for arbi- trary   and  . If the system adiabatically evolves along a loop enclosing the degeneracy point  0,0  in the    ,    space, then the polarization will be changed by ea, which means that if we allow   ,   to change in time along this loop, for example,   t  =  0 sin t  and   t  =  0 cos t , a quantized charge of e is pumped out of the system after one cycle. On the other hand, if the loop does not con- tain the degeneracy point, then the pumped charge is
zero.
H q,t =H q+ A t  .  e
Introduce the gauge-invariant crystal momentum k=q+ eA t .

 3.3
 3.4
    The parameter-dependent Hamiltonian can be simply written as H„k q , t .... Hence the eigenstates of the time- dependent Hamiltonian can be labeled by a single pa- rameter k. Moreover, because A t  preserves the trans- lational symmetry, q is still a good quantum number and is a constant of motion q ̇ =0. It then follows from Eq.  3.4  that k satisfies the following equation of motion:
k ̇ = − e E .   3 . 5    
 Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
1972 Xiao, Chang, and Niu: Berry phase effects on electronic properties
Using  / q = / k  and  / t=− e/  E  / k , the gen- eral formula  2.5  for the velocity in a given state k be- comes
vn k  =   n k  − e E    n k  ,  3.6    k  
where  n k  is the Berry curvature of the nth band:
 n k  = i  kun k       kun k  .  3.7
We can see that, in addition to the usual band dispersion contribution, an extra term previously known as an anomalous velocity also contributes to vn k . This veloc- ity is always transverse to the electric field, which will give rise to a Hall current. Historically the anomalous velocity was obtained by Karplus and Luttinger  1954 , Kohn and Luttinger  1957 , and Adams and Blount  1959 ; its relation to the Berry phase was realized much later. In Sec. V we rederive this term using a wave- packet approach.
B. Berry curvature: Symmetry considerations
The velocity formula  3.6  reveals that, in addition to the band energy, the Berry curvature of the Bloch bands is also required for a complete description of the elec- tron dynamics. However, the conventional formula  Eq.  3.1   has much success in describing various electronic properties in the past. It is thus important to know under what conditions the Berry curvature term cannot be ne- glected.
The general form of the Berry curvature  n k  can be obtained via symmetry analysis. The velocity formula  3.6  should be invariant under time-reversal and spatial inversion operations if the unperturbed system has these symmetries. Under time reversal, vn and k change sign while E is fixed. Under spatial inversion, vn, k, and E change sign. If the system has time-reversal symmetry, the symmetry condition on Eq.  3.6  requires that
 n − k  = −  n k .  3.8  If the system has spatial inversion symmetry, then
 n − k  =  n k .  3.9
Therefore, for crystals with simultaneous time-reversal and spatial inversion symmetry the Berry curvature van- ishes identically throughout the Brillouin zone. In this case Eq.  3.6  reduces to the simple expression  3.1 . However, in systems with broken either time-reversal or inversion symmetries, their proper description requires the use of the full velocity formula  3.6 .
There are many important physical systems where both symmetries are not simultaneously present. For ex- ample, in the presence of ferromagnetic or antiferro- magnetic ordering the crystal breaks the time-reversal symmetry. Figure 3 shows the Berry curvature on the Fermi surface of fcc Fe. As shown the Berry curvature is negligible in most areas in the momentum space and displays sharp and pronounced peaks in regions where the Fermi lines  intersection of the Fermi surface with
H(001) (101)
                                                                                     5 105 4 104 3 103 2 102 1 101 0 0 -1 -101 -2 -102 -3 -103
                                                                                                                                                                                              (000) H(100)
FIG. 3.  Color online  Fermi surface in  010  plane  solid lines  and the integrated Berry curvature − z k  in atomic units  color map  of fcc Fe. From Yao et al., 2004.
 010  plane  have avoided crossings due to spin-orbit coupling. Such a structure has been identified in other materials as well  Fang et al., 2003 . Another example is provided by single-layered graphene sheet with stag- gered sublattice potential, which breaks inversion sym- metry  Zhou et al., 2007 . Figure 4 shows the energy band and Berry curvature of this system. The Berry cur- vature at valley K1 and K2 have opposite signs due to time-reversal symmetry. We note that as the gap ap- proaches zero, the Berry phase acquired by an electron during one circle around the valley becomes exactly ± . This Berry phase of   has been observed in intrinsic
(a)
80
40 00
    1 0.5
−0.5
−40
                        Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
(b)
−1 −80 19 16 13 13 16 19
12 12 12 12 12 12
kx ( /a)
FIG. 4.  Color online  Energy bands  top panel  and Berry curvature of the conduction band  bottom panel  of a graphene sheet with broken inversion symmetry. The first Bril- louin zone is outlined by the dashed lines, and two inequiva- lent valleys are labeled as K1 and K2. Details are presented in Xiao, Yao, and Niu  2007 .
(eV)
(a2)
~ ~
graphene sheet  Novoselov et al., 2005; Zhang et al., 2005 .
C. The quantum Hall effect
The quantum Hall effect was discovered by Klitzing et al.  1980 . They found that in a strong magnetic field the Hall conductivity of a two-dimensional  2D  electron gas is exactly quantized in the units of e2/h. The exact quan- tization was subsequently explained by Laughlin  1981  based on gauge invariance and was later related to a topological invariance of the energy bands  Thouless et al., 1982; Avron et al., 1983; Niu et al., 1985 . Since then it has blossomed into an important research field in condensed-matter physics. In this section we focus only on the quantization aspect of the quantum Hall effect using the formulation developed so far.
Consider a two-dimensional band insulator. It follows from Eq.  3.6  that the Hall conductivity of the system is given by
 3.10
where the integration is over the entire Brillouin. Once again we encounter the situation where the Berry curva- ture is integrated over a closed manifold. Here  xy is the Chern number in the units of e2/h, i.e.,
2
 xy=ne.  3.11
h
φ1
φ2
FIG. 5. Magnetic flux going through the holes of the torus.
riodic boundary conditions in both directions. One can then thread the torus with magnetic flux through its holes  Fig. 5  and make the Hamiltonian H  1, 2  de- pend on the flux  1 and  2. The Hall conductivity is calculated using the Kubo formula
 xy=e2  d2k   , kk
n 0 0n
Xiao, Chang, and Niu: Berry phase effects on electronic properties
1973

H
= ie2      0 v1  n   n v2  0  −  1 ↔ 2  ,    −    2
 3.12
     BZ  2  2 x y
where  n is the many-body wave function with   0  the ground state. In the presence of flux, the velocity opera- tor is given by vi= H  1, 2 /    i  with  i= e/   i/Li and Li the dimensions of the system. We recognize that Eq.  3.12  is the summation formula  1.13  for the Berry curvature   1 2 of the state   0 . The existence of a bulk energy gap guarantees that the Hall conductivity re- mains unchanged after thermodynamic averaging, which is given by
 Therefore the Hall conductivity is quantized for a two-
dimensional band insulator of noninteracting electrons.   
Historically the quantization of the Hall conductivity e2 in a crystal was first shown by Thouless et al.  1982  for  H=  magnetic Bloch bands  see also Sec. VIII . It was shown
that, due to the magnetic translational symmetry, the
phase of the wave function in the magnetic Brillouin
zone carries a vortex and leads to a nonzero quantized
Hall conductivity  Kohmoto, 1985 . However, it is clear
from the above derivation that for the quantum Hall
effect to occur the only condition is that the Chern num-
ber of the bands must be nonzero. It is possible that in
some materials the Chern number can be nonzero even
in the absence of an external magnetic field. Haldane
 1988  constructed a tight-binding model on a honey-
comb lattice which displays the quantum Hall effect with
zero net flux per unit cell. Another model is proposed
for semiconductor quantum well where the spin-orbit
interaction plays the role of the magnetic field  Qi et al.,
2006; Liu et al., 2008  and leads to a quantized Hall con-
ductance. The possibility of realizing the quantum Hall
effect without a magnetic field is attractive in device de-
sign.
Niu et al.  1985  further showed that the quantized Hall conductivity in two-dimensions is robust against many-body interactions and disorder  see also Avron and Seiler  1985  . Their derivation involves the same technique discussed in Sec. II.B.2. A two-dimensional many-body system is placed on a torus by assuming pe-
2 /L2
Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
2 /L1 00
d
that the Hamiltonian
d  1 2. 2  
 3.13  in  i
to its
 period 2  / Li because
periodic returns
1
Note
with
original state after the flux is changed by a flux quantum h / e  and  i changed by 2  / Li . Therefore the Hall con- ductivity is quantized even in the presence of many- body interaction and disorder. Due to the high precision of the measurement and the robustness of the quantiza- tion, the quantum Hall resistance is now used as the primary standard of resistance.
The geometric and topological ideas developed in the study of the quantum Hall effect has a far-reaching im- pact on modern condensed-matter physics. The robust- ness of the Hall conductivity suggests that it can be used as a topological invariance to classify many-body phases of electronic states with a bulk energy gap  Avron et al., 1983 : states with different topological orders  Hall con- ductivities in the quantum Hall effect  cannot be adia- batically transformed into each other; if that happens, a phase transition must occur. The Hall conductivity has important applications in strongly correlated electron systems, such as the fractional quantum Hall effect  Wen and Niu, 1990 , and most recently the topological quan- tum computing  for a review, see Nayak et al.  2008  .
H  1 ,  2  is the system
1974 Xiao, Chang, and Niu: Berry phase effects on electronic properties
  0.4 0.3 0.2 0.1
-
(a)
 k
   (b)
-
                      Fermi energy
 D. The anomalous Hall effect
Next we discuss the anomalous Hall effect, which re- fers to the appearance of a large spontaneous Hall cur- rent in a ferromagnet in response to an electric field alone  for early works in this field see Chien and West- gate  1980  . Despite its century-long history and impor- tance in sample characterization, the microscopic mechanism of the anomalous Hall effect has been a con- troversial subject and it comes to light only recently  for a recent review see Nagaosa et al.  2010  . In the past, three mechanisms have been identified: the intrinsic contribution  Karplus and Luttinger, 1954; Luttinger, 1958 , the extrinsic contributions from the skew  Smit, 1958 , and side-jump scattering  Berger, 1970 . The latter two describe the asymmetric scattering amplitudes for spin-up and spin-down electrons. It was later realized that the scattering-independent intrinsic contribution comes from the Berry phase supported anomalous ve- locity. This will be our primary interest here.
The intrinsic contribution to the anomalous Hall ef- fect can be regarded as an “unquantized” version of the quantum Hall effect. The Hall conductivity is given by
 xy = e2   dk f  k  k k ,  3.14     2  d xy
where f     is the Fermi-Dirac distribution function. k
However, unlike the quantum Hall effect, the anoma- lous Hall effect does not require a nonzero Chern num- ber of the band; for a band with zero Chern number, the local Berry curvature can be nonzero and give rise to a nonzero anomalous Hall conductivity.
Consider a generic Hamiltonian with spin-orbit  SO  split bands  Onoda, Sugimoto, and Nagaosa, 2006 ,
 2k2
H= 2m +  k   ·ez −  z,  3.15
where 2  is the SO split gap in the energy spectrum  ± =  2k2 / 2m ±   2k2 +  2 and   gives a linear dispersion in
the absence of  . This model also describes spin- polarized two-dimensional electron gas with Rashba SO coupling, with   the SO coupling strength and   the exchange field  Culcer et al., 2003 . Obviously the   term breaks time-reversal symmetry and the system is ferro- magnetic. However, the   term alone will not lead to a Hall current as it only breaks the time-reversal symme- try in the spin space. The SO interaction is needed to couple the spin and orbital part together. The Berry cur- vature is given by, using Eq.  1.19 ,
FIG. 6. Anomalous Hall effect in a simple two-band model.  a  Energy dispersion of spin-split bands.  b  The Hall conductiv- ity − xy in the units of e2/h as a function of Fermi energy.

curvature of a full band, 2  0 qdq ±, is ±  for the upper
and lower bands, respectively.9
Figure 6 shows the band dispersion, and the intrinsic
Hall conductivity  Eq.  3.14   as the Fermi energy sweeps across the SO split gap. As shown when the Fermi energy  F is in the gap region, the Hall conduc- tivity reaches its maximum value  about −e2 / 2h . If  F  − , the states with energies just below − , which con- tribute most to the Hall conductivity, are empty. If  F   , contributions from upper and lower bands cancel each other, and the Hall conductivity decreases quickly as  F moves away from the band gap. It is only when −     F    , the Hall conductivity is resonantly en- hanced  Onoda, Sugimoto, and Nagaosa, 2006 .
1. Intrinsic versus extrinsic contributions
The above discussion does not take into account the fact that, unlike insulators, in metallic systems electron scattering can be important in transport phenomena. Two contributions to the anomalous Hall effect arises due to scattering:  i  the skew scattering that refers to the asymmetric scattering amplitude with respect to the scattering angle between the incoming and outgoing electron waves  Smit, 1958  and  ii  the side jump which is a sudden shift of the electron coordinates during scat- tering  Berger, 1970 . In a more careful analysis, a sys-
9Since the integration is performed in an infinite momentum space, the result is not quantized in the unit of 2 .
      ± =  
 2  . 2  2k2 +  2 3/2
 3.16
 The Berry curvatures of the two energy bands have op- posite sign and are highly concentrated around the gap.  In fact, the Berry curvature has the same form of the Berry curvature in one valley of the graphene, shown in Fig. 4.  One can verify that the integration of the Berry
 Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
Hall conductivity
Energy
   tematic study of the anomalous Hall effect based on the semiclassical Boltzmann transport theory has been car- ried out  Sinitsyn, 2008 . The basic idea is to solve the following Boltzmann equation:
 gk −eE·     f =  kk  gk −gk −  feE· rkk  ,  t   k   k    
 3.17
where g is the nonequilibrium distribution function,   represents the asymmetric skew scattering, and  rkk  de- scribes the side-jump of the scattered electrons. The Hall conductivity is the sum of different contributions
 H =  Hin +  Hsk +  Hsj ,  3.18
where  Hin is the intrinsic contribution given by Eq.  3.14 ,  Hsk is the skew scattering contribution, which is proportional to the relaxation time  , and  Hsj is the side jump contribution, which is independent of  . Note that, in addition to Berger’s original proposal,  Hsj also in- cludes two other contributions: the intrinsic skew- scattering and anomalous distribution function  Sinitsyn, 2008 .
An important question is how to identify the domi- nant contribution to the anomalous Hall effect  AHE  among these mechanisms. If the sample is clean and the temperature is low, the relaxation time   can be ex- tremely large, and the skew scattering is expected to dominate. On the other hand, in dirty samples and at high temperatures  Hsk becomes small compared to both  Hin and  Hsj . Because the Berry phase contribution  Hin is independent of scattering, it can be readily evaluated using first-principles methods or effective Hamiltonians. Excellent agreement with experiments has been demon- strated in ferromagnetic transition metals and semicon- ductors  Jungwirth et al., 2002; Fang et al., 2003; Yao et al., 2004, 2007; Xiao, Yao, et al., 2006 , which leaves little room for the side-jump contribution.
In addition, a number of experimental results also gave favorable evidence for the dominance of the intrin- sic contribution  Lee et al., 2004b; Mathieu et al., 2004; Sales et al., 2006; Zeng et al., 2006; Chun et al., 2007 . In particular, Tian et al.  2009  recently measured the anomalous Hall conductivity in Fe thin films. By varying the film thickness and the temperature, they are able to control various scattering process such as the impurity scattering and the phonon scattering. Figure 7 shows their measured  ah as a function of  xx T 2. One can see that although  ah in different thin films and at different temperatures shows a large variation at finite  xx, they converge to a single point as  xx approaches zero, where the impurity-scattering-induced contribution should be washed out by the phonon scattering and only the intrin- sic contribution survives. It turns out that this converged value is very close to the bulk  ah of Fe, which confirms the dominance of the intrinsic contribution in Fe.
In addition to the semiclassical approach  Sinitsyn et al., 2005; Sinitsyn, 2008 , there are a number of works based on a full quantum-mechanical approach  Nozières
1.6
1.2
0.8
93 nm
37 nm
23 nm
20 nm
15 nm
10 nm
6 .5 n m
5 nm
4 nm
B u lk F e
Theory
Xiao, Chang, and Niu: Berry phase effects on electronic properties
1975
                      kk
2 (T)(1010 -2cm -2) xx
2
FIG. 7.  Color online   ah vs  xx T  in Fe thin films with
different film thickness over the temperature range of 5–300 K. From Tian et al., 2009.
and Lewiner, 1973; Onoda and Nagaosa, 2002; Dugaev et al., 2005; Inoue et al., 2006; Onoda, Sugimoto, and Na- gaosa, 2006; Kato et al., 2007; Sinitsyn et al., 2007; Onoda et al., 2008 . In both approaches, the Berry phase sup- ported intrinsic contribution to the anomalous Hall ef- fect has been firmly established.
2. Anomalous Hall conductivity as a Fermi surface property
An interesting aspect of the intrinsic contribution to the anomalous Hall effect is that the Hall conductivity  Eq.  3.14   is given as an integration over all occupied states below the Fermi energy. It seems to be against the spirit of the Landau Fermi-liquid theory, which states that the transport property of an electron system is de- termined by quasiparticles at the Fermi energy. This is- sue was first raised by Haldane  2004 , and he showed that the Hall conductivity can be written, in the units of e2 / 2 h, as the Berry phase of quasiparticles on the Fermi surface, up to a multiple of 2 . Therefore the intrinsic Hall conductivity is also a Fermi surface prop- erty. This observation suggests that the Berry phase on the Fermi surface should be added as a topological in- gredient to the Landau Fermi-liquid theory.
For simplicity, consider a two-dimensional system. We assume there is only one partially filled band. If we write the Berry curvature in terms of the Berry vector poten- tial and integrate Eq.  3.14  by part, one finds
.  3.19
Note that the Fermi distribution function f is a step func- tion at the Fermi energy. If we assume the Fermi surface is a closed loop in the Brillouin zone, then
0246
A−A    
 2D = e2 d2k  f  f
    kk xy   2  ky x  kx y
2D e2
 xy =2 h dk·Ak.
 3.20
 Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
The integral is nothing but the Berry phase along the Fermi circle in the Brillouin zone. The three- dimensional case is more complicated; Haldane  2004  showed that the same conclusion can be reached.
Wang et al.  2007  implemented Haldane’s idea in first-principles calculations of the anomalous Hall con- ductivity. From a computational point of view, the ad-
AH (103 -1cm-1)
1976 Xiao, Chang, and Niu: Berry phase effects on electronic properties
vantage lies in that the integral over the Fermi sea is converted to a more efficient integral on the Fermi sur- face. On the theory side, Shindou and Balents  2006, 2008  derived an effective Boltzmann equation for qua- siparticles on the Fermi surface using the Keldysh for- malism, where the Berry phase of the Fermi surface is defined in terms of the quasiparticle Green’s functions, which nicely fits into the Landau Fermi-liquid theory.
E. The valley Hall effect
A necessary condition for the charge Hall effect to manifest is the broken time-reversal symmetry of the system. In this section we discuss another type of Hall effect which relies on inversion symmetry breaking and survives in time-reversal invariant systems.
We use graphene as our prototype system. The band structure of intrinsic graphene has two degenerate and inequivalent Dirac points at the corners of the Brillouin zone, where the conduction and valance bands touch each other, forming a valley structure. Because of their large separation in momentum space, the intervalley scattering is strongly suppressed  Morozov et al., 2006; Morpurgo and Guinea, 2006; Gorbachev et al., 2007 , which makes the valley index a good quantum number. Interesting valley-dependent phenomena, which con- cerns about the detection and generation of valley po- larization, are currently being explored  Akhmerov and Beenakker, 2007; Rycerz et al., 2007; Xiao, Yao, and Niu, 2007; Yao et al., 2008 .
The system we are interested in is graphene with bro- ken inversion symmetry. Zhou et al.  2007  recently re- ported the observation of a band-gap opening in epitax- ial graphene, attributed to the inversion symmetry breaking by the substrate potential. In addition, in bi- ased graphene bilayer inversion symmetry can be explic- itly broken by the applied interlayer voltage  McCann and Fal’ko, 2006; Ohta et al., 2006; Min et al., 2007 . It is this broken inversion symmetry that allows a valley Hall effect. Introducing the valley index  z = ± 1 which labels the two valleys, we can write the valley Hall effect as
Dirac points. The Hamiltonian is given by  Semenoff, 1984
j v =   Hv zˆ   E ,   3 . 2 1   where  v is the valley Hall conductivity, and the valley
Note that the Berry curvatures in two valleys have op- posite sign as required by time-reversal symmetry. The energy spectrum and the Berry curvature are shown in Fig. 4. Once the structure of the Berry curvature is re- vealed, the valley Hall effect becomes transparent: upon the application of an electric field, electrons in different valleys will flow to opposite directions transverse to the electric field, giving rise to a net valley Hall current in the bulk.
We remark that as   goes to zero, the Berry curvature vanishes everywhere except at the Dirac points where it diverges. Meanwhile, the Berry phase around the Dirac points becomes exactly ±   see also Sec. VII.C .
As shown the valley transport in systems with broken inversion symmetry is a very general phenomenon. It provides a new and standard pathway to potential appli- cations of valleytronics or valley-based electronic appli- cations in a broad class of semiconductors  Gunawan et al., 2006; Xiao, Yao, and Niu, 2007; Yao et al., 2008 .
IV. WAVE PACKET: CONSTRUCTION AND PROPERTIES
Our discussion so far has focused on crystals under time-dependent perturbations, and we have shown that the Berry phase will manifest itself as an anomalous term in the electron velocity. However, in general situa- tions the electron dynamics can be also driven by pertur- bations that vary in space. In this case, the most useful description is provided by the semiclassical theory of Bloch electron dynamics, which describes the motion of a narrow wave packet obtained by superposing the Bloch states of a band  see, for example, Chap. 12 of Ashcroft and Mermin  1976  . The current and next sec- tions are devoted to the study of the wave-packet dy- namics, where the Berry curvature naturally appears in the equations of motion.
In this section we discuss the construction and the general properties of the wave packet. Two quantities emerge in the wave-packet approach, i.e., the orbital magnetic moment of the wave packet and the dipole moment of a physical observable. For their applications, we consider the problems of orbital magnetization and anomalous thermoelectric transport in ferromagnets.
H
current jv =   zv  is defined as the average of the valley
index  z times the velocity operator v. Under time rever- sal, both the valley current and electric field are invari- ant   z changes sign because the two valleys switch when the crystal momentum changes sign . Under spatial in- version, the valley current is still invariant but the elec- tric field changes sign. Therefore, the valley Hall con- ductivity can be nonzero when the inversion symmetry is broken even if time-reversal symmetry remains.
In the tight-binding approximation, the Hamiltonian of a single graphene sheet can be modeled with a nearest-neighbor hopping energy t and a site energy dif- ference   between sublattices. For relatively low doping, we can resort to the low-energy description near the
Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
 3  
H = 2 at qx z x + qy y  + 2  z,
 3.22
   where   is the Pauli matrix accounting for the sublattice index and q is measured from the valley center K1,2 = ±4 /3a xˆ with a the lattice constant. The Berry cur- vature of the conduction band is given by
  q  =   3a2t2  . z 2  2 + 3q2a2t2 3/2
 3.23

A. Construction of the wave packet and its orbital moment
We assume the perturbations are sufficiently weak that transitions between different bands can be ne- glected; i.e., the electron dynamics is confined within a single band. Under this assumption, we construct a wave packet using the Bloch functions   n q   from the nth band,
bound  Marzari and Vanderbilt, 1997 . Therefore, a wave packet may possess a self-rotation around its cen- ter of mass, which will in turn give rise to an orbital magnetic moment. By calculating the angular momen- tum of a wave packet directly, one finds  Chang and Niu, 1996
qc =   dqq w q, t  2 . To first order,  w q , t  2
can be
approximated
 4.2  by   q
 4.3
−qc  and one has
  dqf q  w q, t  2   f q
c
  ,
where f q  is an arbitrary function of q. Equation  4.3  is useful in evaluating various quantities related to the wave packet. Second, the wave packet has to be nar- rowly localized around its center of mass, denoted by rc, in the real space, i.e.,
Xiao, Chang, and Niu: Berry phase effects on electronic properties 1977
m q  = − e W0  r − rc    j W0  2
  W0  =  dqw q,t     q  .  4.1  ne
= − i 2    qu     H q  −   q    qu  ,
 4.6
 There are two requirements on the envelope function w q,t . First, w q,t  must have a sharp distribution in the Brillouin zone such that it makes sense to speak of the wave vector qc of the wave packet given by
where H q =e−iq·rHeiq·r is the q-dependent Hamiltonian. Equation  4.3  is used to obtain this result. This shows that the wave packet of a Bloch electron generally ro- tates around its mass center and carries an orbital mag- netic moment in addition to its spin moment.
We emphasize that the orbital moment is an intrinsic property of the band. Its final expression  Eq.  4.6   does not depend on the actual shape and size of the wave packet and only depends on the Bloch functions. Under symmetry operations, the orbital moment transforms ex- actly like the Berry curvature. Therefore unless the sys- tem has both time-reversal and inversion symmetry, m q  is in general nonzero. Information of the orbital moment can be obtained by measuring magnetic circular dichroism  MCD  spectrum of a crystal  Souza and Vanderbilt, 2008; Yao et al., 2008 . In the single-band case, MCD directly measures the magnetic moment.
This orbital moment behaves exactly like the electron spin. For example, upon the application of a magnetic field, the orbital moment will couple to the field through a Zeeman-like term −m q ·B. If one can construct a wave packet using only the positive energy states  the electron branch  of the Dirac Hamiltonian, its orbital moment in the nonrelativistic limit is exactly the Bohr magneton  Sec. IX . For Bloch electrons, the orbital mo- ment can be related to the electron g factor  Yafet, 1963 . Consider a specific example. For the graphene model with broken-inversion symmetry, discussed in Sec. III.E, the orbital moment of the conduction band is given by  Xiao, Yao, and Niu, 2007
rc =  W0 r W0  .
Using Eq.  4.3  we obtain
r =−   arg w q ,t +An q  , c q c qc
c
where Aqn = i un q   q un q   is the
 4.4
 4.5
rigorous consideration of the wave-packet construction is given by Hagedorn  1980 .
In principle, more dynamical variables, such as the width of the wave packet in both the real space and momentum space, can be added to allow a more elabo- rate description of the time evolution of the wave packet. However, in short period the dynamics is domi- nated by the motion of the wave-packet center, and Eqs.  4.2  and  4.5  are sufficient requirements.
When more than one band come close to each other or even become degenerate, the single-band approxima- tion breaks down and the wave packet must be con- structed using Bloch functions from multiple bands. Cul- cer et al.  2005  and Shindou and Imura  2005  developed the multiband formalism for electron dynam- ics, which will be presented in Sec. IX. For now, we fo- cus on the single-band formulation and drop the band index n for simplicity.
The wave packet, unlike a classical point particle, has a finite spread in real space. In fact, since it is con- structed using an incomplete basis of the Bloch func- tions, the size of the wave packet has a nonzero lower
 Berry
the nth band defined using  un q   = e−ik·r  n q  . A more
connection of
3ea2 t2
2 2 2 2 .  4.7
So orbital moments in different valleys have opposite signs, as required by time-reversal symmetry. Interest- ingly, the orbital moment at exactly the band bottom takes the following form:
m  z,q = z
4    + 3q a t  
 m   =   ,   =e , z zB B2m
 4.8
 Rev. Mod. Phys., Vol. 82, No. 3, July–September 2010
where m  is the effective mass at the band bottom. The close analogy with the Bohr magneton for the electron spin is transparent. In realistic situations, the moment can be 30 times larger than the spin moment and can be used as an effective way to detect and generate the val- ley polarization  Xiao, Yao, and Niu, 2007; Yao et al., 2008 .
