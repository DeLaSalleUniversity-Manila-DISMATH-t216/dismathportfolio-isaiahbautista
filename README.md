# dismathportfolio-isaiahbautista

WEEK 1
➤ Orientation about the course DISMATH (Discrete Mathematics)

➤ Introduction of some applications of Dismath in certain word problems

  E.g. Knights and Knaves
➤ Introduction to Logical Operations

Logical Symbol	Logical Operator	Shorthand	Logical Expression
¬	Negation	not	¬p
∧	Conjunction	and	p ∧ q
v	Disjunction	or	p v q
⊕	Exclusive Disjunction	xor	p ⊕ q
→	Conditional	if, then	p → q
↔	Biconditional	iff	p ↔ q
➤ The truth table for Conjunction, Disjunction, Exclusive Disjunction, Conditional, Biconditional (T & F) or (1 & 0)

p	q	p ∧ q	p v q	p ⊕ q	p → q	p ↔ q
F	F	F	F	F	T	T
F	T	F	T	T	T	F
T	F	F	T	T	F	F
T	T	T	T	F	T	T
➤ Propositional Logic: (p → q)

∙ is the area of logic dealing with propositions.

   ✓ Inverse: ¬p → ¬q

   ✓ Converse: q → p

   ✓ Contraposition: ¬q → ¬p 
WEEK 2
➤ Logical Equivalences are the rules that can help in simplifying a given proposition

∙ Identity Law
    ✓ p ∧ T ≡ p

    ✓ p ∧ F ≡ p

∙ Domination Law

    ✓ p v T ≡ T  

    ✓ p ∧ F ≡ F 

∙ Idempotent Law

    ✓ p v p ≡ p 

    ✓ p ∧ p ≡ p 

∙ Double Negation Law

    ✓ ¬(¬p)≡ p 


∙ Commutative Law

    ✓ p v q ≡ q v p

    ✓ p ∧ q ≡ q ∧ p 

∙ Associative Law

    ✓ (p v q) v r ≡ p v (q v r) 

    ✓ (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)

∙ Distributive Law

    ✓ p v (q v r) ≡ (p v q) v (p v r)

    ✓ p ∧ (q ∧ r) ≡ (p ∧ q) ∧ (p ∧ r) 

∙ De Morgan's Law

    ✓ ¬(p ∧ q) ≡ ¬p ∧ ¬q

    ✓ ¬(p v q) ≡ ¬p v ¬q 

∙ Absorption Law

    ✓ p v (p ∧ q) ≡ p 

    ✓ p ∧ (p v q)≡ p 

∙ Negation Law

    ✓ p v ¬p ≡ T

    ✓ p ∧ ¬p ≡ F 
➤ Rules of Interference are used to test the validity of arguments.

Name	Equivalent
Modus ponens	p, p→q ∴q
Modus tollens	¬q, p→q ∴ ¬p
Hypothetical syllogism	p → q, q → r ∴p → r
Disjunctive syllogism	p ∨ q, ¬p ∴q
Addition	p ∴p ∨ q
Simplication	p ∧ q ∴p
Conjunction	p, q ∴p ∧ q
Resolution	p ∨ q, ¬p ∨ r ∴q ∨ r
➤ Quantifiers

• Universal Quantifier

  - "for all"

  - Symbol: ∀(x)

• Existential Quantifier

  - "there exist"

  - Symbol: ∃(x)
WEEK 3
➤ Introduction to Methods of Proof

∙ Direct Proof:

   First Step: Assume that "p" is TRUE

   Second Step: Show that "q" is also TRUE

∙ Indirect Proof:

    First Step: Assume that "¬q" is TRUE

    Second Step: Show that "¬p" is also TRUE

∙ Proof by Contradiction:

    First Step: Assume that the "antecedent" is FALSE

    Second Step: Using an assumption and other facts show that it is a contradiction

∙ Proof by Contraposition:

    First Step: Assume that the "premise" is FALSE

    Second Step: Using an assumption and other facts show that it is a contraposition
WEEK 4
➤ Mathematical Induction

  - A means of proving a theorem by showing that if it is true of any particular case, it is true of the 

  next case in series, and then showing that it is indeed true in one particular case.


  - It is a form of direct proof, and it is done in two steps. The first step, known as the Basic Step, is 

  to prove the given statement for the first natural number. The second step, known as the 

  Inductive step,it is to prove that the given statement for any one natural number implies the given 

  statement for the next natural number.  
➤ Summation

  - Symbol: ∑

  - Is the addition of a sequence of numbers; the result is called the sum or the total. 
➤ Recursive/Inductive

  - An algorithm that solves a problem by reducing it to a simpler input.

  Steps:

  1.) Basic Step

      - Specify the value of a given as a function a "0" 

  2.) Recursive Step

      - Create a rule in finding its value at a certain integer from its values at smaller integers.
