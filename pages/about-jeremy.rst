.. title: About Jeremy
.. slug: about-jeremy
.. date: 2025-02-19
.. tags: 
.. category: 
.. link: 
.. description: About Jeremy Dawson - many links fixed. Provision for files in subfolder
.. type: text
.. hidetitle: True

.. _top:

.. comment: Many links fixed. Need checking. 2025-02-14

Jeremy Dawson
=============

* formerly `Computer Sciences Laboratory <http://csl.rsise.anu.edu.au/>`__, `Research School of Information Sciences and Engineering <http://rsise.anu.edu.au/>`__.

* now `Research School of Computer Science <http://cs.anu.edu.au/>`__, `College of Engineering and Computer Science <http://cecs.anu.edu.au/>`__, `Australian National University <http://www.anu.edu.au/textonly/external.html>`__, Canberra `ACT <http://www.act.gov.au/>`__  0200, `AUSTRALIA <http://www.fed.gov.au/>`__.

--------------------------------------------------------------------------------------

**Note:** Some of the links on this page may not work. Try the similar page at
ANU `here <http://users.cecs.anu.edu.au/~jeremy/index.html>`__

--------------------------------------------------------------------------------------

| **Email:**   firstname-surname at gmx.com
|

Retirement
----------

In retirement I've been doing more of a variety of things, including

-  some category theory proofs in Coq

-  reverting to my earlier interest in the law, including being rather
   outspoken about legal issues and cases that attract my interest, see
   further `here <legal-docs/legal-docs/>`__

Employment (1998-2021)
----------------------

For this period of 24 years I was at the Logic and Computation Group in
the `Research School of Information Sciences and
Engineering <http://rsise.anu.edu.au/>`__ at the `Australian National
University <http://www.anu.edu.au/textonly/external.html>`__,
subsequently in the `Research School of Computer
Science <http://cs.anu.edu.au/>`__, part of the `College of Engineering
and Computer Science <http://cecs.anu.edu.au/>`__, see further details
below.

I have held positions under various funding sources including ARC
Discovery Projects held by `Rajeev
Goré <http://users.cecs.anu.edu.au/~rpg/>`__ concerned with verifying
cut-admissibility theorems, interpolation theorems and similar
meta-logical results.

My earlier research work in computer science was largely about embedding
a display calculus in Isabelle/HOL, and proving, in Isabelle, Belnap's
cut-elimination theorem. In the course of work on a stronger result, the
strong normalization property of the set of proof reductions used in
cut-elimination, we discovered that the published proof of this omits a
case, requiring a largely new proof, which we have now completed. The
Isabelle files are `here <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/fdeep/>`__.

We then realized that this proof can be translated into the context of
general term-rewriting theory, and have accordingly derived theorems on
termination of term-rewriting. The Isabelle files are
`here <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/snabs/>`__.

Topics I have worked on more recently have included

-  proving in Isabelle a version of Craig's interpolation theorem for
   Display Calculi, based on work of James Brotherston and Rajeev Goré.
   The Isabelle files are `here <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/interp/>`__

-  formalising in Isabelle some aspects of a claimed (and later
   contradicted) proof of decidability of ticket entailment. The
   Isabelle files are `here <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/bimbo-dunn/>`__

-  formalising in Isabelle results of Nachum Dershowitz about
   well-founded unions of well-founded relations. The Isabelle files are
   `here <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/gen/>`__ (see ``tripartite.{thy,ML}``)

-  formalising in Isabelle results on proof systems for Full
   Intuitionistic Linear Logic, based on work with Alwen Tiu, Ranald
   Clouston and Rajeev Goré. The Isabelle files are
   `here <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/seqms/>`__

-  formalising in HOL4 a dual tableaux calculus of Melvin Fitting for
   intuitionistic logic. The HOL4 files are `here <hol/idt/hol>`__

-  proving in Coq cut admissibility for Dyckhoff's LJT system for
   intuitionistic propositional logic (designed to easily show
   decidability), and an attempted simpler variation

-  formalising in Coq the syntactic (ie, by transforming a derivation
   tree) proof of cut admissibility for linear logic

Studies/Thesis (1997)
---------------------

In 1997 I did the Graduate Diploma in Computer Science. My honours
thesis, Mechanised Proof Systems for Relation Algebras, was on
automating display logic in
`Isabelle <https://www.cl.cam.ac.uk/research/hvg/Isabelle/>`__; my
supervisor was `Rajeev Goré <http://cecs.anu.edu.au/~rpg>`__ of the
Automated Reasoning Group. In 1998 and late 1999 I did some further work
along these lines, see the papers below.

Here are copies of my thesis, in `ps.gz <https://users.cecs.anu.edu.au/~jeremy/thesis/thesis.ps.gz>`__,
`dvi.gz <https://users.cecs.anu.edu.au/~jeremy/thesis/thesis.dvi.gz>`__, and `here <https://users.cecs.anu.edu.au/~jeremy/thesis/thesis-files>`__
are the source code files referred to in it.

Earlier employment (up to 1996)
-------------------------------

I have previously worked (among others) in CSIRO Division of Mathematics
and Statistics (doing statistical analyses and research in combinatorial
mathematics, particularly matroid theory), and in the Department of
Defence, doing Computer Security, where I became interested in the
formal verification of software. At one point I studied law and worked
in the office administering the Commonwealth Superannuation Scheme, in
the Review and Reconsideration area, handling appeals against the
office's decisions.

Projects
--------

L4.verified
~~~~~~~~~~~

For about three years I was actively involved in NICTA's L4.verified
project, which used Isabelle to formally verify an operating system
microkernel. In that project I was primarily responsible for the library
concerning machine words of definite finite lengths and the hardware
operations on them, obtaining relevant lemmas and automated proof
precedures. See the AVOCS'07 paper listed below.

EVACS
~~~~~

In 2001, I wrote a prototype vote-counting program for the complex
proportional representation system used in electing the ACT Assembly.
Recently the requirements of the system have been encoded in the
language of the HOL theorem proving system and I am engaged in similarly
encoding the actions of my program, with a view to formally proving that
it correctly meets its requirements. Further information on this is at
http://users.cecs.anu.edu.au/~rpg/EVoting

Research Interests
------------------

-  Formal verification
-  Automated theorem proving, especially in relation to

   -  metalogic and cut-elimination
   -  termination of term-rewriting

-  Functional programming

Software
--------

I've written some publicly available and, I hope, useful, software, see
`here <https://users.cecs.anu.edu.au/~jeremy/sw/>`__; currently this includes `code <https://users.cecs.anu.edu.au/~jeremy/sw/xfig>`__ to create
``.fig`` graphics files, as can be produced interactively and displayed
by the ``xfig`` program.

Publications
------------

A list of publications is `here <https://users.cecs.anu.edu.au/~jeremy/cv/papers.html>`__; some online ones
follow - note that copyrights to some are held by publishers, including
`Springer-Verlag <http://www.springer.de/comp/lncs/>`__. A more detailed
CV is also `here <https://users.cecs.anu.edu.au/~jeremy/cv/cvc.html>`__.

Journals and Refereed Conferences
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  Jeremy Dawson, Nachum Dershowitz, Rajeev Goré, `Well-Founded
   Unions <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/gen/tripartite-paper/from_nd>`__, In: Automated
   Reasoning (IJCAR 2018), Oxford, LNCS/LNAI 10900, 117-133. `Isabelle
   source files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/gen/>`__ (see ``tripartite.{thy,ML}``)

-  Jeremy E. Dawson & Rajeev Goré, `Machine-checked Meta-theory of
   Dual-Tableaux for Intuitionistic Logic <hol/idt/orlowska-idt>`__, in
   Ewa Orłowska on Relational Methods in Logic and Computer Science, pp
   253-282, Springer series Outstanding Contributions to Logic, 17, 2018
   `HOL4 source files <hol/idt/hol>`__

-  Jeremy E. Dawson & Rajeev Goré, `Issues in Machine-Checking the
   Decidability of Implicational Ticket
   Entailment. <pubs/ticket/final>`__ In: Automated Reasoning with
   Analytic Tableaux and Related Methods 2017 (Tableaux 2017), LNAI
   10501, 347-363. `Isabelle source files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/bimbo-dunn/>`__

-  Jeremy E. Dawson, James Brotherston & Rajeev Goré, `Machine-checked
   Interpolation Theorems for Substructural Logics using Display
   Calculi <https://users.cecs.anu.edu.au/~jeremy/pubs/interp/ijcar>`__ In: International Joint Conference on
   Automated Reasoning, Coimbra, Portugal, 2016 (IJCAR 2016), LNCS 9706,
   452-468. `Isabelle source files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/interp/>`__

-  Jeremy E. Dawson, Rajeev Goré & Jesse Wu, `Machine-Checked
   Proof-Theory for Propositional Modal
   Logics <pubs/cutelim/jaegerfest>`__ In: Progress Computer
   Science(Birkhäuser), Vol. 28, Reinhard Kahle et al. (Eds): Advances
   in Proof Theory, Chapter 5 `Isabelle source
   files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/seqms/>`__ `link to publisher's
   site <http://www.springer.com/gp/book/9783319291963>`__

-  Jeremy E. Dawson, Rajeev Goré, Thomas Meumann: `Machine-Checked
   Reasoning About Complex Voting Schemes Using Higher-Order
   Logic. <https://users.cecs.anu.edu.au/~jeremy/pubs/evoting>`__ In Proc. E-Voting and Identity - 5th
   International Conference, VoteID 2015, Bern, Switzerland, September
   2-4, 2015.

-  Jeremy E. Dawson, Ranald Clouston, Rajeev Goré & Alwen Tiu, `From
   Display Calculi to Deep Nested Sequent Calculi: Formalised for Full
   Intuitionistic Linear Logic. <pubs/fill/git/tcs2014>`__ In Proc. TCS
   2014: Theoretical Computer Science, LNCS 8705, 250-264. `Isabelle
   source files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/seqms/>`__

-  Ranald Clouston, Jeremy E. Dawson, Rajeev Goré & Alwen Tiu,
   `Annotation-Free Sequent Calculi for Full Intuitionistic Linear
   Logic. <pubs/fill/git/csl2013>`__ In Proc. CSL 2013: European
   Conferences on Computer Science Logics, Schloss Dagstuhl -
   Leibniz-Zentrum für Informatik, LIPIcs, 23:197-214. `Isabelle source
   files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/fill/>`__

-  Jeremy E. Dawson & Rajeev Goré, `Generic Methods for Formalising
   Sequent Calculi Applied to Provability
   Logic. <pubs/cutelim/gls/lpar-final>`__ In Logic for Programming,
   Artificial Intelligence and Reasoning (LPAR 2010), LNCS 6397,
   263-277. `Isabelle source files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/seqms/>`__

-  Alwen Tiu, Rajeev Goré & Jeremy Dawson, A Proof Theoretic Analysis of
   Intruder Theories. Logical Methods in Computer Science 6 (3:12),
   2010, 1-37. ``http://arxiv.org/pdf/1005.4508`` `details of Isabelle
   proofs <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/spi/Intruder.pdf>`__ \| `Isabelle source
   files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/spi/>`__

-  Alwen Tiu & Jeremy E. Dawson, Automating Open Bisimulation Checking
   for the Spi Calculus. In Computer Security Foundations Symposium (CSF
   2010), 307-321. `Isabelle source files <isabelle/2005/spi/>`__

-  Jeremy E. Dawson & Alwen Tiu `Formalising Observer Theory for
   Environment-Sensitive Bisimulation <pubs/spi/fotesb>`__ In 22nd
   International Conference on Theorem Proving in Higher Order Logics,
   Munich, August 2009 (TPHOLs 2009), LNCS 5674, 244-259. `Isabelle
   source files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/spi/>`__

-  Jeremy E. Dawson & Rajeev Goré, `Termination of Abstract Reduction
   Systems <pubs/rewr_term/ijfcs>`__ International Journal of
   Foundations of Computer Science 20 (2009), 57-82. (contains material
   from CATS 2007 and CSL 2004 papers).

-  Jeremy E. Dawson, `Isabelle Theories for Machine
   Words <https://users.cecs.anu.edu.au/~jeremy/pubs/l4/avocs/>`__ In Seventh International Workshop on
   Automated Verification of Critical Systems (AVOCS'07), Oxford,
   September 2007, Electronic Notes in Theoretical Computer Science, 250
   (2009), pp. 55-70, Elsevier.

-  Jeremy E. Dawson, `Compound Monads in Specification
   Languages <https://users.cecs.anu.edu.au/~jeremy/pubs/fgc/cmmc/plpv/>`__ In Proceedings of Programming
   Languages meets Program Verification (PLPV) 2007, Freiburg, October
   2007, ACM, 2007, 3-10. `Isabelle source files
   (monads) <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/monad/>`__ `(modelling
   computations) <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/fgc/>`__

-  Jeremy E. Dawson, `Formalising Generalised
   Substitutions <https://users.cecs.anu.edu.au/~jeremy/pubs/fgc/fgs/>`__ In 20th International Conference on
   Theorem Proving in Higher Order Logics, Kaiserslautern, September
   2007 (TPHOLs 2007), LNCS 4732, 54-69. `Isabelle source
   files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/fgc/>`__

-  Jeremy E. Dawson & Rajeev Goré, `Termination of Abstract Reduction
   Systems <pubs/rewr_term/cats>`__ Computing: The Australasian Theory
   Symposium, 2007 (CATS 2007), Conferences in Research and Practice in
   Information Technology (CRPIT), Vol. 65, 35-43 `Isabelle source
   files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/snabs/>`__

-  Jeremy E. Dawson & Rajeev Goré, `A General Theorem on Termination of
   Rewriting <https://users.cecs.anu.edu.au/~jeremy/pubs/rewr_term/csl04>`__ Computer Science Logic (CSL'04),
   LNCS 3210, 100-114. `Isabelle source files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/snabs/>`__
   `more Isabelle source files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/snlc/>`__

-  Jeremy E. Dawson, `Formalising General
   Correctness <https://users.cecs.anu.edu.au/~jeremy/pubs/fgc/cats/>`__ Computing: The Australasian Theory
   Symposium, 2004, Electronic Notes in Theoretical Computer Science 91,
   46-65, Elsevier. `Isabelle source files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/fgc/>`__

-  Jeremy E. Dawson & Rajeev Goré, `A New Machine-checked Proof of
   Strong Normalisation for Display Logic <https://users.cecs.anu.edu.au/~jeremy/pubs/cutelim/cats/>`__,
   Computing: The Australasian Theory Symposium, 2003, Electronic Notes
   in Theoretical Computer Science 78, 16-35, Elsevier. `Isabelle source
   files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/fdeep/>`__

-  Jeremy E. Dawson & Rajeev Goré, `Machine-checking the Timed Interval
   Calculus <pubs/tic/>`__, 15th Australian Joint Conference on
   Artificial Intelligence (AI'02), LNCS 2557, 95-106, `Isabelle source
   files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/tic/>`__

-  Jeremy E. Dawson & Rajeev Goré, `Formalised Cut Admissibility for
   Display Logic <https://users.cecs.anu.edu.au/~jeremy/pubs/cutelim/tphols/final/>`__ 15th International
   Conference on Theorem Proving in Higher Order Logics (TPHOLs 2002),
   LNCS 2410, 131-147. `Isabelle source files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/fdeep/>`__

-  Jeremy E. Dawson & Rajeev Goré, `Embedding Display Calculi into
   Logical Frameworks : Comparing Twelf and
   Isabelle <https://users.cecs.anu.edu.au/~jeremy/pubs/embed/cats-final>`__, Computing: The Australasian
   Theory Symposium, 2001, Electronic Notes in Theoretical Computer
   Science, Elsevier, volume 42.

-  Jeremy E. Dawson & Rajeev Goré, `A Mechanisation of Classical Modal
   Tense Logics Using Isabelle <https://users.cecs.anu.edu.au/~jeremy/pubs/dkt/final>`__, Proceedings of the
   11th Australian Joint Conference on Artificial Intelligence, LNCS
   1502 (1998), 107-118. `Isabelle source files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/ss/>`__

-  Jeremy E. Dawson & Rajeev Goré, `A Mechanised Proof System for
   Relation Algebra using Display Logic <https://users.cecs.anu.edu.au/~jeremy/pubs/dra/final>`__, Proceedings
   of the 6th European Workshop on Logics in Artificial Intelligence,
   LNCS 1489 (1998), 264-278. `Isabelle source
   files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/ss/>`__

Workshops
~~~~~~~~~

-  Jeremy E. Dawson, `Formalising General
   Correctness <pubs/fgc/tphols-b/>`__, In Theorem Proving in Higher
   Order Logics, NASA/CP-2002-211736, 36-47. `Isabelle source
   files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/fgc/>`__

-  Jeremy E. Dawson & Matt Fairtlough, Automatic Constraint Calculation
   using Lax Logic, In Theorem Proving in Higher Order Logics,
   NASA/CP-2002-211736, 48-59.

-  Jeremy E. Dawson, `Simulating Term-Rewriting in LPF and in Display
   Logic <https://users.cecs.anu.edu.au/~jeremy/pubs/rewr/wip-submitted>`__, Theorem Proving in Higher Order
   Logics: Emerging Trends (supplementary proceedings of TPHOLs'98),
   TR-CS-98-08, Australian National University, 47-62. `(later
   version) <https://users.cecs.anu.edu.au/~jeremy/pubs/rewr/fac-submitted>`__, Isabelle source files for
   `LPF <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/lpf/>`__ \| `Display Logic <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/dl/>`__

Technical reports, etc
~~~~~~~~~~~~~~~~~~~~~~

-  Jeremy E. Dawson, `Compound Monads and the Kleisli
   Category <https://users.cecs.anu.edu.au/~jeremy/pubs/cmkc/>`__, submitted `Isabelle source
   files <https://users.cecs.anu.edu.au/~jeremy/isabelle/2005/monad/>`__

Other
-----

Ranked =17th in 1998 International Functional Programming Contest, see
`table of results <http://www.ai.mit.edu/extra/icfp-contest/phase1.html>`__

Finalist in 1999 International Functional Programming Contest, see
`report <http://www.eecs.harvard.edu/~nr/pubs/icfp99-abstract.html>`__

--------------

Jeremy Dawson, jeredaw at gmx dot com


`[Goto Top] <#top>`_
