

quick project so I can learn compilers for elisp -> wasm
derivative of racket so I can learn how to make my own language
* Tooling
Development IDE 
 Based on Emacs
 Presumes the user doesn't have all variants of kanbun/wenyan memorized and is otherwise a native or ESL English / Japanese / Chinese speaker with no knowledge of the variants
 Dictionary of wenyan with proper dictionary loaders and subloaders (e.g., translation from kanbun to English)
 Flash-cards with anki and org-note
 
 
* Language dev steps
1. Racket derivative for quick devel and testing
2. Re-implement racket derivative not relying on racket (machine code compiler for normal and quantum compute)


* Why another wenyan? 
differs from existing wenyan in that 
1) not oriented around javascript or its ecosystem; design based on racket and preferably itself recursively -- should be developed to not depend upon racket, and be as minimal as possible (should be feasible as a language to write asm programs for kolibrios)
2) LISP syntax
3) Xuanxue principles - Focus on compiling for quantum machines; primarily is concerned with paraconsistent logic and dialethia (intends to incorporate all logical progress from Richard Sylvan's Meingnon's Jungle). Wenyan in its Daoist flavor (given that xuanxue is not itself a unified language) is the most useful when its multiplicity, indeterminacy, and meontological properties are fully leveraged for systems that can play in such spaces)
4) GPL not MIT license and GNU FRD, not CC attribution
5) Daoist; no code of conduct
6) Still can interop with existing wenyan (ideally can transpile between both wenyans)
7) Multiplexed - ideally, have an infinite variety of versions of itself that can be s(n)eeded (through ML / AI)
8) Intended to be a practical tool rather than an esoteric language

The project is intended to largely be solitary yet communal; the ecosystem is likely to be more similar to the Emacs ecosystem than npm. 

regardless existing wenyan is cool and lots of respect for what they've managed to accomplish - check it out at https://github.com/wenyan-lang 

- Laozi


* Foundational questions with wenyan and computing
Ambiguous grammars, quantum state, weights 
Context sensitive grammars and success of python -- compynator



[Koh18]: Michael Kohlhase. "Logic-Based Natural Language Processing. Winter Semester 2018/19. Lecture Notes." URL: https://kwarc.info/teaching/LBS/notes.pdf. URL of course description: https://kwarc.info/courses/lbs/ (in German)


https://cs.stackexchange.com/questions/110402/why-are-ambiguous-grammars-bad
https://www.grammaticalframework.org/


** Discrete math and operator (precedence/associativity) w/ paraconsistent mathematics

** Ability to switch grammars and degree of ambiguity for hardware DSL

** Parsers - check Du Handbook's


Intent and parameters of the domain specific language: Primarily a low level language that can deal with ambiguity and paraconsistency in hardware or NLP programming 

*** Targets / domains of DSL / use-cases
- WASM
- Machine Learning - NLP
- Quantum compilation
- Ideal OS environment: Kolibrios / various flavors of TempleOS / Mezzanno / LISP OS derivative (ideally running on quantum hardware)
