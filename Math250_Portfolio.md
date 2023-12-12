<h1 align="center">Portfolio Draft</h1>
<p align="center">Charles Barth</p>
<p align="center">12/11/2023</p>

## 1. Direct Proof of an If-Then Statement or a Statement with For All and There Exists

**General Proof Type Guide:**
In this proof, we are dealing with a statement that involves both "for all" and "there exists" quantifiers. The strategy is to start with the given conditions (in this case, 'n is a multiple of 3' and 'm is even') and logically show that these conditions lead to the conclusion ('nm is a multiple of 6'). The proof will involve understanding the properties of multiples and even numbers and how they interact.

**Statement to Prove:**
If n is a multiple of 3 and m is even, then nm is a multiple of 6.

**Proof:**
Let's assume n is a multiple of 3, which means n = 3k for some integer k. Also, let m be an even number, so m = 2j for some integer j. The product nm then becomes (3k)(2j) = 6kj. Since kj is an integer (as the product of two integers), nm is a multiple of 6. Therefore, if n is a multiple of 3 and m is even, then nm is indeed a multiple of 6.

## 2. Direct Proof Where the Outcome Has Either an AND or an OR

**General Proof Type Guide:**
This proof involves a statement with an "or" outcome, which means we need to demonstrate that at least one of the conditions holds true. The approach is to start with an odd integer n and show that it can be expressed in one of the two given forms.

**Statement to Prove:**
If n is an odd integer, then there exists an integer x such that n = 4x + 1 or n = 4x + 3.

**Proof:**
Let n be an odd integer. By definition, an odd integer can be written as 2k + 1, where k is an integer. We can express 2k as either 4j (if k is even) or 4j + 2 (if k is odd), where j is an integer. Substituting these into n = 2k + 1 gives n = 4j + 1 or n = 4j + 3 + 1, which simplifies to n = 4j + 1 or n = 4(j + 1) + 1. Therefore, for any odd integer n, there exists an integer x (either j or j + 1) such that n = 4x + 1 or n = 4x + 3.

## 3. Proof by Contrapositive or Contradiction

**General Proof Type Guide:**
In this proof, we use the contrapositive approach. The contrapositive of a statement "if P, then Q" is "if not Q, then not P". This method often simplifies the proof, especially when dealing with negations or complex conditions.

**Statement to Prove:**
If n + m is even, then n is even or m is not a multiple of 4.

**Proof:**
The contrapositive of the given statement is: If n is not even (i.e., odd) and m is a multiple of 4, then n + m is not even (i.e., odd). Let's assume n is odd and m is a multiple of 4. An odd number can be expressed as 2k + 1, so let n = 2k + 1. Since m is a multiple of 4, let m = 4j for some integer j. Then, n + m = (2k + 1) + 4j = 2k + 4j + 1 = 2(k + 2j) + 1, which is an odd number. Therefore, if n + m is even, then it must be true that n is even or m is not a multiple of 4.

## 4. Proof that One Set is a Subset of Another or NOT a Subset of Another

**General Proof Type Guide:**
This proof involves demonstrating the equality of two sets based on their definitions. To prove that two sets A and B are equal, we need to show that every element of A is in B and every element of B is in A.

**Statement to Prove:**
Let A = {n in Z: n = 4t+1 for some t in Z} and B = {n in Z: n = 4t+9 for some t in Z}. Prove that A = B.

**Proof:**
First, we show that every element of A is in B. Let n be an element of A. Then n = 4t + 1 for some integer t. We can write n = 4(t+2) - 7. Since t+2 is an integer, n is of the form 4s + 9 for some integer s (where s = t+2), and thus n is in B.

Next, we show that every element of B is in A. Let n be an element of B. Then n = 4t + 9 for some integer t. We can write n = 4(t-2) + 17. Since t-2 is an integer, n is of the form 4s + 1 for some integer s (where s = t-2), and thus n is in A.

Since every element of A is in B and every element of B is in A, we conclude that A = B.

Certainly! Let's continue with the structure and style similar to the example portfolio for the remaining proofs:

## 5. Proof Involving Collections of Sets

**General Proof Type Guide:**
This proof involves showing a relationship between the union and intersection of sets. The approach is to use the definitions of set union and intersection and the properties of sets to demonstrate the equality.

**Statement to Prove:**
Let A and B be sets. Prove that A ∪ (A ∩ B) = A.

**Proof:**
To prove A ∪ (A ∩ B) = A, we need to show that each element of A ∪ (A ∩ B) is in A and each element of A is in A ∪ (A ∩ B).

First, let x be an element of A ∪ (A ∩ B). This means x is in A or x is in A ∩ B. If x is in A, we are done. If x is in A ∩ B, then x is in both A and B, and particularly, x is in A.

Next, let x be an element of A. Then clearly, x is in A ∪ (A ∩ B) because x is in A.

Since every element of A ∪ (A ∩ B) is in A and every element of A is in A ∪ (A ∩ B), we conclude that A ∪ (A ∩ B) = A.

Certainly! Let's continue with the structure and style similar to the example portfolio for the remaining proofs:

## 6. Proof Using Modular Arithmetic

**General Proof Type Guide:**
This proof involves demonstrating a relationship between divisibility and modular arithmetic. The approach is to use the properties of divisibility and modular arithmetic to show that if two numbers divide a third, their product divides the square of the third.

**Statement to Prove:**
Let a, b, and c be integers. Prove that if a|c and b|c, then ab | c².

**Proof:**
Assume a|c and b|c. This means there exist integers m and n such that c = am and c = bn. We need to show that ab divides c².

Since c = am, we can write c² = (am)² = a²m². Similarly, since c = bn, we can write c² = (bn)² = b²n². Therefore, c² = a²m² = b²n².

Now, since a divides a² and b divides b², it follows that ab divides a²m² and b²n². Since a²m² and b²n² are both equal to c², ab divides c².

Therefore, if a|c and b|c, then ab | c².

### 7. Proof of a Statement Involving an Infinite Union of Subsets

**General Proof Type Guide:**
This proof involves demonstrating the nature of the infinite union and intersection of a series of sets. The approach is to use the definitions of union and intersection in the context of an infinite series of sets.

**Statement to Prove:**
Let \( A_i = \{i, i+1\} \) where \( i \) is an element of \( \mathbb{Z}^+ \). Prove what the intersection and union from 1 to infinity are.

**Proof:**
Consider the sets \( A_i = \{i, i+1\} \) for \( i \in \mathbb{Z}^+ \).

For the union, \( \bigcup_{i=1}^{\infty} A_i \), observe that each set \( A_i \) contains the elements \( i \) and \( i+1 \). As \( i \) ranges over all positive integers, the union will include every integer from 1 onwards. Therefore, \( \bigcup_{i=1}^{\infty} A_i = \mathbb{Z}^+ \).

For the intersection, \( \bigcap_{i=1}^{\infty} A_i \), note that no single integer is present in all sets \( A_i \) simultaneously. Each set \( A_i \) contains only two consecutive integers, and as \( i \) increases, these integers change. Therefore, \( \bigcap_{i=1}^{\infty} A_i = \emptyset \) (the empty set).

Thus, the union of the sets \( A_i \) from 1 to infinity is \( \mathbb{Z}^+ \), and their intersection is the empty set.

## 8. Proof that the Image of a Function is a Given Set

**General Proof Type Guide:**
This proof involves computing and proving the image of a function over a given interval. The approach is to apply the function to every element in the interval and determine the resulting set.

**Statement to Prove:**
Let f: R → R be defined by f(x) = x². Compute f([0,1]) and prove your answer.

**Proof:**
The function f(x) = x² maps any real number x to its square. To find f([0,1]), we consider the image of the interval [0,1] under f. For any x in [0,1], x² is a non-negative number and is at most 1, since the square of any number between 0 and 1 (inclusive) is within this range. Therefore, f([0,1]) is the set of all numbers y such that 0 ≤ y ≤ 1.

To prove this, let y be an element of f([0,1]). Then there exists an x in [0,1] such that y = x². Since 0 ≤ x ≤ 1, it follows that 0 ≤ x² ≤ 1, and hence 0 ≤ y ≤ 1. Therefore, f([0,1]) = [0,1].

## 9. Proving a Function is 1-1 or Onto

**General Proof Type Guide:**
This proof involves showing that a function is both surjective (onto) and injective (1-1). Surjectivity is proven by showing that every element in the codomain has a preimage in the domain, while injectivity is shown by proving that distinct elements in the domain map to distinct elements in the codomain.

**Statement to Prove:**
Let f: R → R with f(x) = 4x - 2.
a. Prove that f is surjective (onto).
b. Prove that f is injective (1-1).

**Proof:**
a. To prove surjectivity, let y be any element in R. We need to find an x in R such that f(x) = y. Solving the equation 4x - 2 = y gives x = (y + 2)/4. Since y is any real number, (y + 2)/4 is also a real number. Therefore, for every y in R, there exists an x in R such that f(x) = y, proving that f is surjective.

b. To prove injectivity, assume x₁ and x₂ are elements in R such that f(x₁) = f(x₂). This means 4x₁ - 2 = 4x₂ - 2. Simplifying this equation gives x₁ = x₂. Therefore, if f(x₁) = f(x₂), then x₁ = x₂, proving that f is injective.

## 10. Proof by Induction

**General Proof Type Guide:**
This proof involves using the Principle of Mathematical Induction to prove a statement for all positive integers. The process includes proving the base case and then showing that if the statement holds for an arbitrary positive integer k, it also holds for k+1.

**Statement to Prove:**
Use the Principle of Mathematical Induction to prove that for all positive integers n, 1 + 3 + 5 + ... + (2n-1) = n².

**Proof:**
Base Case (n=1): When n=1, the left-hand side is 1, and the right-hand side is 1² = 1. So, the statement holds for n=1.

Inductive Step: Assume the statement is true for some positive integer k, i.e., 1 + 3 + 5 + ... + (2k-1) = k². We need to show it holds for k+1.

The sum for k+1 terms is 1 + 3 + 5 + ... + (2k-1) + (2(k+1)-1). By the inductive hypothesis, this is equal to k² + (2k+1). Simplifying, we get k² + 2k + 1, which is (k+1)².

Therefore, if the statement holds for k, it holds for k+1. By the Principle of Mathematical Induction, the statement is true for all positive integers n.
