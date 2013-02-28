---
title: Proceedings
template: page.jade
---
The 2011 Imperial College Computing Student Workshop proceedings are
available [online](/2011/files/volume.pdf) as
well as individual submissions below.

### [Combining Markov Decision Processes with Linear Optimal Controllers](/2011/files/00010003.pdf) 
#### Ekaterina Abramova, Daniel Kuhn, and Aldo Faisal
##### Imperial College London

*Abstract.* Linear Quadratic Gaussian (LQG) control has a known
analytical solution but non-linear problems do not. The state of the art
method used to ﬁnd approximate solutions to non-linear control problems
(iterative LQG) carries a large computational cost associated with
iterative calculations. We propose a novel approach for solving
nonlinear Optimal Control (OC) problems which combines Reinforcement
Learning (RL) with OC. The new algorithm, RLOC, uses a small set of
localized optimal linear controllers and applies a Monte Carlo algorithm
that learns the mapping from the state space to controllers. We
illustrate our approach by solving a non-linear OC problem of the
2-joint arm operating in a plane with two point masses. We show that
controlling the arm with the RLOC is less costly than using the Linear
Quadratic Regulator (LQR). This ﬁnding shows that non-linear optimal
control problems can be solved using a novel approach of adaptive RL.

* * *

### [Neural-Symbolic Cognitive Agents: Architecture and Theory](/2011/files/00010010.pdf) 
#### H.L.H. de Penning, A.S. d'Avila Garcez, L.C. Lamb, J-J.C. Meyer
##### TNO Behaviour and Societal Sciences, City University London, Universidade Federal do Rio Grande do Sul, Utrecht University

*Abstract.* In real-world applications, the effective integration of
learning and reasoning in a cognitive agent model is a difficult task.
However, such integration may lead to a better understanding, use and
construction of more realistic models. Unfortunately, existing models
are either oversimplified or require much processing time, which is
unsuitable for online learning and reasoning. Currently, controlled
environments like training simulators do not effectively integrate
learning and reasoning. In particular, higher-order concepts and
cognitive abilities have many unknown temporal relations with the data,
making it impossible to represent such relationships by hand. We
introduce a novel cognitive agent model and architecture for online
learning and reasoning that seeks to effectively represent, learn and
reason in complex real-world applications. The agent architecture of the
model combines neural learning with symbolic knowledge representation.
It is capable of learning new hypotheses from observed data, and
inferring new beliefs based on these hypotheses. Furthermore, it deals
with uncertainty and errors in the data using a Bayesian inference
model. The model has successfully been applied in real-time simulation
and visual intelligence systems.

* * *

### [Time-Bounded Veriﬁcation of CTMCs against MTL speciﬁcations](/2011/files/00010017.pdf) 
### Taolue Chen, Marco Diciolla, Marta Kwiatkowska, and Alexandru Mereacre
##### Oxford University

*Abstract.* In this paper we study time-bounded veriﬁcation of a ﬁnite
continuoustime Markov chain (CTMC) C against a real-time speciﬁcation,
provided as a metric temporal logic (MTL) property ϕ. The key question
is: what is the probability of the set of timed paths of C that satisfy
ϕ over a time interval of ﬁxed, bounded length? We provide approximation
algorithms to solve these problems. We ﬁrst derive a bound N such that
timed paths of C with at most N discrete jumps are sufﬁcient to
approximate the desired probability up to ε. Then, for each discrete
(untimed) path σ of length at most N , we generate timed constraints
over variables determining the residence time of each state along σ,
depending on the real-time speciﬁcation under consideration. The
probability of the set of timed paths, determined by the discrete path
and the associated timed constraints, can thus be formulated as a
multidimensional integral. Summing up all such probabilities yields the
result.

* * *

### [MASSPA-Modeller: A Spatial Stochastic Process Algebra modelling tool](/2011/files/00010024.pdf) 
#### Marcel C. Guenther and Jeremy T. Bradley
##### Imperial College London

*Abstract.* We introduce MASSPA–Modeller, a visual modelling tool for
the recently developed spatial stochastic process algebra MASSPA which
describes Markovian Agent Models (MAM)s. The major advantage of using a
visual editor to generate MASSPA models is that the laborious task of
modelling the communication between agents is partially automated by the
tool. Furthermore the tool can separately check the correctness of local
and spatial aspects of the model and thereby help users to ﬁnd mistakes.
For the analysis of the resulting models MASSPA–Modeller uses the
powerful GPA–analyser engine. Additionally we brieﬂy summarise the
latest developments in spatial stochastic process algebras.

* * *

### [Argumentation and Temporal Persistence](/2011/files/00010031.pdf) 
#### E. Hadjisoteriou and A. Kakas
##### University of Cyprus

*Abstract.* We study how the problem of temporal projection can be
formalized in terms of argumentation. In particular, we extend earlier
work of translating the language E for Reasoning about Actions and
Change into a Logic Programming argumentation framework, by introducing
new types of arguments for (i) backward persistence and (ii) persistence
from observations. This forms a conservative extension of the language E
that gives semantic meaning to domains that cannot be interpreted in the
language E.

* * *

### [Facial Action Recognition using sparse appearance descriptors and their pyramid representations](/2011/files/00010039.pdf) 
#### Bihan Jiang, Michel F. Valstar, and Maja Pantic
##### Imperial College London, University of Twente

*Abstract.* Most existing work on automatic analysis of facial
expressions has focused on a small set of prototypic emotional facial
expressions such as fear, happiness, and surprise. The system proposed
here enables detection of a much larger range of facial behaviour by
detecting facial muscle actions (action units, AUs). It automatically
detect all 9 upper face AUs using local apperance descriptors.
Meanwhile, the merits of the family of local binary pattern descriptors
are investigated. We compare Local Binary Patterns, Local Phase
Quantisation, Pyramid Local Binary Pattern, as well as our proposed
descriptors Block-based Pyramid Local Binary Pattern and Block-based
Pyramid Local Phase Quantisation for AU detection. Results show that our
proposed descriptor Block-based pyramid Local Binary Pattern outperforms
all other tested methods for the problem of FACS Action Unit analysis
and the systems that utilise pyramid representation outperform those
that use basic appearance descriptors.

* * *

### [Note on a Dichotomy for the Classes W\[P\](C) Deﬁned via Symmetric Connectives](/2011/files/00010046.pdf) 
#### Bjorn Lellmann
##### Imperial College London

*Abstract.* Adopting a generalised notion of connectives as
ptime-computable symmetric boolean functions, for ﬁnite sets C of such
connectives the classes W\[P\](C) are deﬁned via the parameterised
weighted satisﬁability problem for circuits with C-gates. This note will
prove the following dichotomy result: for all ﬁnite sets C of
connectives W\[P\](C) = FPT or W\[P\](C) = W[P].

* * *

### [Agent Oriented Programming: from Revolution to Evolution (Position Paper)](/2011/files/00010052.pdf) 
#### Alex Muscar
##### University of Craiova

*Abstract.* Despite being around for quite some time, agents have failed
to gain wide acceptance. Their AI heritage has forced them into a niche
from which they cannot seem to escape: being the vehicle of AI
experimentation. Even though the premises of Agent Oriented Programming
(AOP) is a revolutionary departure from Object Oriented Programming
(OOP) the vision has not materialized. In this paper we propose taking a
step back and looking at AOP as an evolution from OOP. Rather than
viewing agents as specialized AI tools, we adopt a view on agents as a
generic metaphor for building complex software systems. The guiding
lines of our approach are: (i) overall conceptual simplicity; and (ii)
the use of programming languages as the main means of expression. We
will explore some paradigms and approaches that we think can greatly
beneﬁt the view of agents as an evolution from OOP.

* * *

### [Conditional Labelling for Abstract Argumentation](/2011/files/00010059.pdf) 
#### Guido Boella, Dov M. Gabbay, Alan Perotti, Leendert van der Torre, and Serena Villata
##### Universita di Torino, King’s College London, University of Luxembourg, INRIA

*Abstract.* Agents engage in dialogues having as goals to make some
arguments acceptable or unacceptable. To do so they may put forward
arguments, adding them to the argumentation framework. Argumentation
semantics can relate a change in the framework to the resulting
extensions but it is not clear, given an argumentation framework and a
desired acceptance state for a given set of arguments, which further
arguments should be added in order to achieve those justiﬁcation
statuses. Our methodology, called conditional labelling, is based on
argument labelling and assigns to each argument three propositional
formulae. These formulae describe which arguments should be attacked by
the agent in order to get a particular argument in, out, or undecided,
respectively. Given a conditional labelling, the agents have a full
knowledge about the consequences of their attacks on the acceptability
of each arguments, without having to recompute the overall labelling of
the framework for each possible set of attacks they may raise.

* * *

### [A Persuasive Dialogue Game for Coalition Formation](/2011/files/00010066.pdf) 
#### Luke Riley
##### University of Liverpool

*Abstract.* In this paper, I propose a formal dialogue framework that
enables autonomous agents to engage in a process of practical reasoning,
in which they can propose to form coalitions that perform joint actions,
using argumentation. An argumentation scheme is used to drive this
coalition formation process that results in qualitative payoffs. This
paper builds on existing work that uses value-based argumentation in the
context of a dialogue system, which has been empirically veriﬁed. This
framework is designed explicitly for closed cooperative systems where
agents hold different preferences.

* * *

### [Model-based Self-Adaptive Components: A Preliminary Approach](/2011/files/00010073.pdf) 
#### Pedro Rodrigues and Emil Lupu
##### Imperial College London

*Abstract.* Due to the increasing scale, complexity, dynamicity and
heterogeneity of modern software systems, it is not feasible to solely
rely upon human management to guarantee a good service level with such
availability demand. Self-managing systems are needed as an eﬀective
approach to deal with those issues by exploiting adaptive techniques to
adjust a system. On top of that, model-based adaptation improves
reliability, hence enhancing trust in self-managing systems. However, a
centralised approach can be too complex to manage thus compromising
system dependability. This paper presents a preliminary decentralised
approach on model-based self-adaptive components.

* * *

### [Safe, Flexible Recursive Types for Featherweight Java](/2011/files/00010080.pdf) 
#### Reuben N. S. Rowe
##### Imperial College London

*Abstract.* This paper presents a type assignment system with recursive
types for Featherweight Java, inspired by the work of Nakano. Nakano’s
innovation consists in adding a modal type constructor which acts to
control the folding of recursive types, resulting in a
head-normalisation guarantee. We build on this approach by introducing a
second modal type constructor which prevents the unfolding of types in
contexts where doing so results in non-termination. Moreover our system
inherits the ﬂexibility of Nakano’s approach, allowing object-oriented
features (such as binary methods) to be typed in a safe and intuitive
way. The work described in this paper is preliminary, and no formal
results are claimed. However, we conjecture that our type system enjoys
strong normalisation and we motivate this by working through some
apposite examples.

* * *

### [Measuring minimal change in argument premise revision](/2011/files/00010087.pdf) 
#### Mark Snaith and Chris Reed
##### University of Dundee

*Abstract.* The ﬁeld of belief revision studies how information can be
given up in the face of new, conﬂicting information, while argumentation
provides methods through which conﬂict can be modelled and the resultant
acceptability of arguments evaluated. Prominent theories of belief
revision depend on the notion of minimal change, measured in terms of
epistemic entrenchment, to determine what beliefs to give up. In this
paper, we take an initial look at the eﬀects of removing an argument
from a system of structured argumentation, in terms of both argument
construction and acceptability, and how these can be used in the
determination of minimal change.

### [Applying Algebraic Specifications on Digital Right Management Systems](/2011/files/00010094.pdf) 
#### Nikolaos Triantafyllou, Katerina Ksystra, Petros Stefaneas and Panayiotis Frangos
##### National Technical University of Athens

*Abstract.* Digital Right Management (DRM) Systems have been created to
meet the need for digital content protection and distribution. In this
survey paper we present some of the directions of our ongoing research
on the applications of the algebraic specification techniques on mobile
DRM systems.

* * *

### [Reduction of Variability in Split–Merge Systems](/2011/files/00010101.pdf) 
#### Iryna Tsimashenka and William Knottenbelt
##### Imperial College London

*Abstract.* We consider an optimisation problem applicable to systems
that can be represented as split–merge queueing networks with a limited
buﬀer space for processed subtasks. We assume Poisson arrivals and
generally distributed service times. The proposition is to reduce
variability in terms of the diﬀerence in the times of arrival of the
ﬁrst and last subtasks in systems where the release times of the
subtasks can be controlled. This stands in contrast to the overwhelming
majority of research which is focused on reduction of mean response time
or percentiles of response time. We formally deﬁne our notion of
variability in split–merge systems and construct an associated cost
function and optimisation problem. For two case studies we use
simulation to explore the optimisation landscape and to solve the
associated optimisation problem.

* * *

### [Real-Time Detection of Process Change using Process Mining](/2011/files/00010108.pdf) 
#### Phil Weber, Behzad Bordbar, and Peter Tino
##### University of Birmingham

*Abstract.* Process Mining is the discovery of business processes from
log ﬁles. One application is ensuring conformance to prescribed
processes or business rules. Since businesses operate in real time,
needing to quickly react to change, processes change; but how can such
changes be detected? We consider requirements for process mining to
support this: a notion of real time, and methods to compare processes
and detect signiﬁcant change. We present initial results conﬁrming the
validity of the approach.
