---
layout: post
# Your title goes here
title: "Deltas for Functional Programs with Algebraic Data Types"
# List authors here as they appear in the paper
authors: Ferruccio Damiani, Eduard Kamburjan, Michael Lienhardt, Luca Paolini
# List keywords to get more visibility
tags: [Delta-oriented programming,Family-based analysis,Functional programming,Language design,Type checking]
# Add the journal / proceedings
journal: Proceedings of the 27th ACM International Systems and Software Product Line Conference
# Add the DOI
doi: 10.1145/3579027.3608977
# Everithing written before <!--more--> will appear directly in the publications page
excerpt_separator: <!--more-->
---

The development of feature-oriented programming (FOP) and of (its generalization) delta-oriented programming (DOP) has focused primarily on SPLs of class-based object oriented programs. In this paper, we introduce delta-oriented SPLs of functional programs with algebraic data types (ADTs). To pave the way towards SPLs of multi-paradigm programs, we tailor our presentation to the functional sublanguage of the multi-paradigm modeling language ABS, which already features DOP support for its class-based object-oriented sublanguage. Our main contributions are: (i) we motivate and illustrate our proposal by an example from an industrial modeling scenario; (ii) we formalize delta-oriented SPLs for functional programs with ADTs in terms of a foundational calculus; (iii) we define family-based analyses to check whether an SPL satisfies certain well-formedness conditions and whether all variants can be generated and are well-typed; and (iv) we briefly outline how, in the context of the toolchain of ABS, the proposed delta-oriented constructs and analyses for functional programs can be integrated with their counterparts for object-oriented programs.
