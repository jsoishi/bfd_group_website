+++
date = "2021-06-30T15:41:00Z"
title = "Theses, Papers, and other things."
[[authors]]
    name = "Jeffrey S. Oishi"
    is_member = true
    link = "/jeff_oishi"

+++

First off, a hearty congratulations to [Xiaole "Alex" Jiang (Bates '21)](/member/xjiang) and [Kirstin Koepnick (Bates '21)](/member/kkoepnic) for successfully defending their Honors Theses! Alex's work concerned [non-linear wave generation in rapidly rotating convection](https://scarab.bates.edu/honorstheses/369) while Kirstin began an investigation of the [smallest topologically protected system in *classical* mechanics](https://scarab.bates.edu/honorstheses/365). 

While we're congratulating, a very belated congrats to [Morgan Baxter (Bates '20)](/member/mbaxter), who defended the very [first Honors Thesis](https://scarab.bates.edu/honorstheses/319/) to come out of the Bates Fluids Group. Morgan's work studied *drosophila* of turbulence research, Taylor-Couette flow, using the Generalized Quasi-linear approximation. 

Second, the Dedalus collaboration has written a new paper on [eigentools](https://joss.theoj.org/papers/10.21105/joss.03079), published this month in the Journal of Open Source Software. eigentools sits on top of Dedalus and helps solve eigenvalue problems, including stability and most excitingly, the ability to compute pseudospectra of differential-algebraic equations (like incompressible Naiver-Stokes) in primitive form. As a cute example, we solved the venerable Orr-Sommerfeld problem directly in terms of *u* and *v*, rather than casting it into a streamfunction-vorticity form:

![Orr-Sommerfeld pseudospectra with eigentools](/img/pseudospectra.png)

The center panel shows the spectrum (in gray and orange) and pseudospectrum (labeled contours), while the four panels on the sides show the eigenfunctions corresponding to the orange eigenvalues in the spectrum. 

Finally, it's always nice to open up an old paper of yours to find in the very first paragraph you lay your eyes on a fine sentence like this:

![oops](/img/paper_mistake.png)

I suppose one and one is two, even in lower case Roman numerals.

<!--  LocalWords:  Oishi jeff oishi Xiaole Jiang Kirstin Koepnick
 -->
<!--  LocalWords:  Dedalus eigentools pseudospectra drosophila
 -->
<!--  LocalWords:  Couette Sommerfeld streamfunction vorticity
 -->
<!--  LocalWords:  pseudospectrum eigenfunctions
 -->
