# Vectors

## Chapter Goals

The more overarching goal of this section is to complete the first goal in the 18.02 syllabus:

{% hint style="success" %}
Fluency with vector operations, including vector proofs and the ability to translate back and forth among the various ways to describe geometric properties, namely, in pictures, in words, in vector notation, and in coordinate notation.
{% endhint %}

In gaining fluency with vector operations, this section will introduce a few technical skills:

* Dot product
* Determinant
* Cross product

## Section 1

Section 1 corresponds to the [first lecture from OCW 18.02.](https://ia802700.us.archive.org/4/items/MIT18.02F07/ocw-18_02-f07-lec01_300k.mp4) Readings include:

* [Introduction to vectors](https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/1.-vectors-and-matrices/part-a-vectors-determinants-and-planes/session-1-vectors/MIT18_02SC_notes_0.pdf)
  * [Vector lengths](https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/1.-vectors-and-matrices/part-a-vectors-determinants-and-planes/session-1-vectors/MIT18_02SC_we_2_comb.pdf)
  * [Force is a vector](https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/1.-vectors-and-matrices/part-a-vectors-determinants-and-planes/session-1-vectors/MIT18_02SC_we_3_comb.pdf)
  * [Proofs using vectors](https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/1.-vectors-and-matrices/part-a-vectors-determinants-and-planes/session-1-vectors/MIT18_02SC_we_4_comb.pdf)
  * [Vector problems](https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/1.-vectors-and-matrices/part-a-vectors-determinants-and-planes/session-1-vectors/MIT18_02SC_pb_1_quest.pdf)
* [Dot product](https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/1.-vectors-and-matrices/part-a-vectors-determinants-and-planes/session-2-dot-products/MIT18_02SC_notes_1.pdf)
  * [Dot product problems](https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/1.-vectors-and-matrices/part-a-vectors-determinants-and-planes/session-2-dot-products/MIT18_02SC_pb_2_quest.pdf)
  * [Uses of the dot product](https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/1.-vectors-and-matrices/part-a-vectors-determinants-and-planes/session-3-uses-of-the-dot-product-lengths-and-angles/MIT18_02SC_we_5_comb.pdf)
  * [Uses of the dot product problems](https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/1.-vectors-and-matrices/part-a-vectors-determinants-and-planes/session-3-uses-of-the-dot-product-lengths-and-angles/MIT18_02SC_pb_3_quest.pdf)

### Introduction to vectors

Vectors can be described geometrically as a thing \(technical term\) that has both a magnitude and a direction. 

{% tabs %}
{% tab title="Question V1" %}
a\) A river flows at 3 mph and a rower rows at 6 mph. What heading should the rower take to go straight across a river? b\) Answer the same question if the river flows at 6 mph and the rower rows at 3 mph.
{% endtab %}

{% tab title="Answer" %}
![Geometric setup to V1](../.gitbook/assets/river.PNG)

  
We can represent vectors geometrically, as seen in the figure above.

\(a\) If the river has size 3 and the boat size 6, then the angle made by the right triangle between the two \(making a straight path across the river\) is $$ sin^{-1}(3/6) =  sin^{-1}(1/2) =  \frac{\pi}{2}$$ or $$30 \degree$$. 

\(b\) If the boat has size 3 and the river has size 6, then the angle made is $$sin^{-1}(6/3) = sin^{-1}(2)$$which is undefined. Thus, there is no possible straight path for a boat with a speed of 3 across a river with a speed of 6.
{% endtab %}
{% endtabs %}

Any vector can also be written in algebraic form. Any vector has components in the x, y, z, etc plane. A vector that has a length of 1 along the x axis can be written as $$<1, 0, 0, ...>$$. With a length of 1 along the y axis: $$<0, 1, 0, ...>$$, etc. I'll generally just use 2 or 3 numbers for 2 or 3 dimensions. 

The length of any vector with $$<x, y>$$ components is just $$\sqrt{x^2 + y^2}$$ \(just the Pythagorean theorem, remember?\). This can be generalized to n dimensions, so the length of any vector $$<x, y, z, ...>$$ is $$\sqrt{x^2 + y^2 + z^2 ...}$$ . 



### 





