# dismathportfolio-isaiahbautista

##WEEK 1

➤ Orientation about the course DISMATH (Discrete Mathematics)

➤ Introduction of some applications of Dismath in certain word problems

Ex. Knights and Knaves

  
➤ Introduction to Logical Operations

Logical Symbol	Logical Operator	Shorthand	Logical Expression

¬	Negation	not	¬p

∧	Conjunction	and	p ∧ q

v	Disjunction	or	p v q

⊕	Exclusive Disjunction	xor	p ⊕ q

→	Conditional	if, then	p → q

↔	Biconditional	iff	p ↔ q


➤ Propositional Logic: (p → q)

∙ is the area of logic dealing with propositions.

   ✓ Inverse: ¬p → ¬q

   ✓ Converse: q → p

   ✓ Contraposition: ¬q → ¬p 
   
   
##WEEK 2

➤ Logical Equivalences helps in simplification of logical statments
I have yet to memorize ALL of these. 
Here are some of the logical euivalences:

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
   
  
##WEEK 3

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
    
    
##WEEK 4

➤ Mathematical Induction


  - It is a form of direct proof, and it is done in two steps. 
  
1st step: Basic Step
-prove the statement by substituting a value and see if the statement holds true. 

  
  
2nd step: Inductive step
-prove that the statement is true for all possible values by using any of the kinds of proof. 
  
  
  
➤ Summation

  - Symbol: ∑
  - addition of a sequence of numbers


➤ Recursive/Inductive

  - Repeated application of functions in order to solve a function. 

  Steps:

  1.Basic Step

      - Specify the value of a given as a function at F(0) 

  2. Recursive Step
      - create a statement that makee the function true for any value substituted to it. 

##WEEK 5

Program Correctness

Steps:

  1 Partial correctness

      - initial assertion(input)

      - final assertion (output)

  2. Show that the program terminates correctly
    Hoare Triple: p{S}q

     given:

        p = initial assertion

       {S} = program segment

        q = final assertion

      Steps:

        1. Assume tha p is TRUE

        2. Substitute to the program {S}, showing that q is TRUE
        
 Power Series

  -Example: Zeno's Paradox

   Can be solved using GEOMETRIC SERIES formula:

    a1/ 1-r
    
  Introduction to set theory

  Set-  an unordered collection of objects

  a. Set Difference
      (A-B) or (A/B)

  b. Set Intersection
        A△B

  Power Set- a set containing all subsets
  
  ##Week 6
  
  Cardinality- total number of distinct elements
  
  No- pronounced as "aleph zero"/"aleph-null"
  
  Had a review about nested quantifiers
  - a for loop within another for loop
  
  Functions

  1. One to one function
    - each domain is assigned to a certain co-domain
    - no common co-domain
    -
  2. Onto Function
    -each co-domain is assigned to a domain.
    - no co-domain is left without a partner. 
    
##Week 7
-no classes

##Week 8

➤ Algorithm

- is a finite set of precise instruction

   Precondition- describes the input

   Postcondition- describes what the output should satisfy

    ✓ Properties:

       • Input

       • Output

       • Definiteness

       • Correctness

       • Finiteness

       • Generality
       
       
  ##Week 9
  
  ➤ Seaching Algorithm-The problem of locating an element in an ordered list

  ➤ Linear Search
    - Precondition: ({A1,A2,...,Ai,...An})

      Postcondition: location of x (loc)

  Code:
  
  i=1

  while [(x≠A)^(i≤n)]

      i = i+1

    if(i≤n)

      loc = i

    else

       loc = -1
       
➤ Binary Search
-  Precondition: ({A1,A2,...,Ai,...An})

   Postcondition: location of x (loc)

      Code:
      
      while [(i≠j) ≠ (i>j)]

         mid = [(i+j)/2]

            if x>A(mid) 

               then i = 1+mid

            else j=mid

            if (x==Ai)

                loc=i

            else 
            loc = -1;
            
  ##Week 10
  
  ➤ Sorting Algorithm
- the problem of putting elements in increasing order

  ➤ Bubble sort
- Precondition: ({A1,A2,...,Ai,...An})

  Postcondition: (X1<X2<...<Xn)

      for j: 1 to n-1

         for i: 1 to n-j

            if(Ai > Aj+1)

               swap (Ai,Ai+1)
               
➤ Insertion sort
- Precondition: ({A1,A2,...,Ai,...An}) ∈ n≥2 for j= 2 to n

  Postcondition: (X1<X2<...<Xn)
      
      Code:
      for j = 2 to n

          i = 1

      while Aj>Ai

          i = i+1

       m = Aj

       for k = 0 to j-i-1

        Aj-k = Aj-i-1

      Ai = m
      
➤ Greedy Algorithm
•	Selects the best choice instead of considering all sequences
•	Can be applied in optimization problems

Precondition: ({C1,C2,...,Ci,...Cn})
Postcondition: (C1>C2>...>Cni n ∈ Z+)

  Code:
  for i = 1 to 4 

    while(n≥Ci)

        n = n-Ci

           n = n+1
  end
  
##Week 11

➤ Growth of Functions
- is often described using the big o notation
➤ Big O Notation
- Let f and g be functions from R to Ri f(x) is O(g(x)) if there are constants c and k such that 
  |f(x)|≤ C|g(x)| whenever x>k
➤ Big Omega
- lower bound of a function 
  
➤ Big Theta
- lower and upper bound of a function
➤ Complexity of Algorithms
- can be expressed in term of the number of operationsused by the algorithm when the input has a particular size

##Week 12
-no classes this week

##Week 13
➤ Graph Theory  G(V,E)
- consist of vertices/nodes and degrees/edges
Vertices- the points in the graph
Edges- composed of two vertices
Degree- number of connections to the vertice

➤ Handshaking Theorem
- formula: 2e = Σ(degrees)*v

➤ Euler Path
- covers all the edges/degrees only once
- is open 
- has a different starting and ending point

➤ Euler Circuit
- covers all the edges/degrees only once 
- is closed 
- has the same starting and ending point
➤ Hamilton Path
- covers all the nodes/vertices only once
- is open
- has a different starting and ending point
➤ Hamilton Circuit
- covers all the nodes/vertices only once
- is closed
- has the same starting and ending point
➤ Matrices
• Adjacency Matrix
   - relationship between the nodes/vertices 

• Incidence Matrix
   - relationship between the edges/degrees
➤ Isomorphism
- is the comparison of 2 graphs
➤ Planar
- is a plane that has no intersecting lines/edges/degrees
➤ Non-Planar
- is a plane that has intersecting lines/edges/degrees
➤ Euler's Formula
- formula: r = e(edges) - v(vertices) + 2


##Week 14

  Tree- undirected graph with no circuit. Cotains leaves and parents.
  Parents- no with children
  Leaf- node without children
  
  Forest- 2 or more trees
  
  Rooted Tree- with a "root" at top of the graph
  Internal Vertice- node without children
  
  M-ary tree- contains uniform children throughout the tree
  
  Ordered rooted tree- follows a certain order, cannot be interchanged
  
  Modeling Computation
  Grammars- used to generate words of a language and determine if the word is a language
  Formal languages- provide models for natural languages
  
  Alan Turing- Father of computation
  
  
  
  
        


  
  
  
      
