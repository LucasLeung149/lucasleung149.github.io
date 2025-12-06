---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

Broadly speaking, my main research interests lie in the intersection between theoretical physics (string theory and quantum gravity), pure mathematics and machine learning. 

One of the problems that have confused many generations of theoretical physicists is whether there exists a theory that describes all the phenomenon we know -- this is typically known as the 'theory of everything'. Over the past century, the leading theory that describes three of the four fundamental forces, namely electromagnetic, strong and weak force, and the fundamental building blocks of matter, is the Standard Model. This is a Quantum Field Theory that describes particles as excitations in a quantum-mechanical field theory.

On the other hand, Einstein's theory of gravity, in which matter is described as sources that curve spacetime, is well developed. It is however extremely difficult to combine the gravitational force with the Standard Model. Theories that consistently combine both theories and can describe all four fundamental forces are known as Quantum Gravity theories (QG).

This is where string theory comes in - it is the only consistent Quantum Gravity (QG) model that mathematicians and physicists can study and manipulate. Whilst many debate about its difficulty to be tested experimentally, the subfield of String Phenomenology has been developed over the past three decades to address the potential observational issues and difficulties of string theory, and to satisfy all particle and cosmological observations to make quantifiable predictions. Doing this is useful -- not only can we find out ways to test string theory in quantifiable observations, but working in a consistent string theory framework where the mathematics is under better control also allows us to figure out how different changing different 'nuts and bolts' in a high energy, UV-complete theory, will affect low-energy theory, observations and phenomenology.

The most exciting development in the past decade was the inception of using data science techniques to address theoretical issues in string theory. Heuristic search methods such as genetic algorithms (GA) as well as machine learning (ML) methods like reinforcement learning (RL) have been applied to a variety of mathematical and theoretical physics problems, leading to new predictions and results such as the computation of Yukawa couplings (i.e. masses of fundamental particles such as quarks and electrons) from heterotic string theory.

I am interested in a wide range of topics in the intersection between string theory with ML and geometry. Here are some of my current research topics that I am currently investigating.

## String Model Building and ML

One could ask the question -- is it possible to extract the Standard Model as a low-energy theory of string theory? To answer that is highly-nontrivial -- string theory (as well as M-theory, F-theory) works in ten or more dimensions and since we only observe four dimensions at low-energies (3 spatial dimensions and 1 time dimension), we must 'hide' the six dimensions that we don't see by saying they are very small, wrapped up manifolds. This is called 'compactification' and typically this requires picking manifolds with particular topological and geometrical properties (Calabi-Yau manifolds) to obtain the correct low-energy spectrum and couplings.

There is a very high number of topological and geometrical choices that will lead to the Standard Model. This is known as the string landscape - and we can use machine learning techniques to help us look for correct choices in this vast parameter space. For example, we can use genetic algorithms to look for string theories with matter taking correct charges in some symmetry that will give correct mass data at low-energies.

I currently mainly work with the heterotic $$E_8 \times E_8$$ theory, but these techniques can be similarly generalised to analyse under string theory models, such as Type IIB orientifold compactifications, F-theory models, as so on.

## Physics4ML

We have been talking a lot about AI these days. The fundamental unit, which most people more or less have heard of, are known as neural networks - these are simple ML architectures that one can use to approximate any function. This property (called the Universal Approximation) is why neural networks can be applied to many problems - it can basically numerically estimate the outcome.

Despite the current advancements in artificial intelligence, machine learning techniques, deep neural network theory and, most widely-known, large language models (LLMs) however, the theory behind how these structures exactly work remains obscure. In particular, although we have some ideas in how to interpret neural network architectures and we can intuitively understand the process of training and initialisation of neural networks, a rigorous theory on exactly how neural networks behave under training is still unknown.

There are some exciting new research in this direction however. One can for example try and understand the initialisation of neural networks by using a field theory approach. These mathematical approaches have been studied by theoretical physicists for over half a century and their theories have been well-developed. By reinterpreting neural networks as a particular configuration in the field-parameter space, we can perhaps gain some insight as to why certain choices of parameter initialisations are better suited in approximating functions.

We can even use this to understand the behaviour of neural networks under training too! In particular, training neural networks requires playing around the so-called loss or target function in each particular problem - by interpreting the neural network as a field, one could perhaps find optimal ways of training neural networks. This is currently something being explored by our research group.

## Maths & Strings

There are many mathematical structures hidden in string theory. For example, one of the major problems in string theory is to understand why geometrical parameters in our string compactifications, known as moduli fields, are not observed at low-energies. This is known as 'moduli stabilisation' in string theory. Understanding this problem requires a deep knowledge of the geometrical and topological properties of the internal manifold, as well as the low-energy supersymmetry breaking mechanisms and phenomenological calculations. Finding these possible scenarios where everything 'works out' is extremely difficult, and there is no single scenario which is mathematically-rigorous and avoids all phenomenological problems.

In particular, the complex-structure moduli dependence of terms in the Lagrangian has a huge impact in moduli stabilisation. This concerns how the internal cycles within the Calabi-Yau manifold intersect and interact. It turns out that understanding this so-called 'period structure' is related to counting zeros of certain Riemann functions and is related to number theory, the field of counting prime numbers in pure mathematics! These structures are prevalent in theoretical physics and pure mathematics, and relates the Langlands programme with many physical problems such as scattering amplitudes in Quantum Field Theory. I am particularly interested in the relationship between number theory, enumerative geometry, mirror symmetry and string theory, and in particular, how we can use these mathematical properties to find new and mathematically-rigorous moduli stabilisation scenarios and to compute amplitudes in different QG theories.

## Non-perturbative effects in string theory and QG

The current formulation of superstring theory is perturbative - where the amplitudes are calculated order-by-order. We however know that topological effects, which arise non-perturbatively, also contribute to the theory (and therefore into amplitudes and couplings). For example, there are extended objects in string theory known as D-branes that could wrap themselves around internal cycles, which provides a correction to low-energy physics.

Computing these corrections are extremely difficult, and my collaborators and I have been trying to understand these computations systematically using algebraic geometry. In particular, calculating the exact corrections in a specific model requires the determination of the Gopakumar-Vafa invariants of the manifold as well as the locations of the cycles, both of which are still poorly understood and difficult to construct in generic cases.

## Non-stringy QGs

I am also interested in other QG theories other than string theories. A particular type of QGs requires the use of matrices! These typically have a non-commutative structure and the formulation of matrix theories require the use non-commutative theory techniques. Some of these matrix theories are also conjectured to be non-perturbative formulations of string theory and M-theory, the particular relationship is still poorly understood.

The revival of matrix theories in recent years has been driven by its holographic relationship with gravity theories. In particular, these holographic relationships between QFTs in $$d$$-dimensions and gravity theories in $$(d-1)$$-dimensions allow the calculation of black hole thermodynamic quantities. This is a potential avenue to understand the black hole information paradox.

## Other interests and reading groups
I have a broad interest in theoretical physics, pure mathematics and data science. Over my time in Oxford I have organised several reading groups, some of which you can find in [this page](https://lucasleung149.github.io/reading_groups/).