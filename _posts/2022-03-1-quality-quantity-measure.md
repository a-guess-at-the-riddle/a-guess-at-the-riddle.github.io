---
layout: post
title: Quality, Quantity, Measure
---

\*[^1]

**INCOMPLETE ROUGH DRAFT**

**associated topic tags:** quality, semantic dimensions, semantic spaces, conceptual spaces, Peter Gärdenfors, *The Ascent of Man*, Jacob Bronowski, development of complexity, phenomenology, perception, developmental psychology, measurement theory, *Foundations of Measurement*, level of measurement, nominal, ordinal, order, interval, ratio, Stanley Smith Stevens, Benjamin Drake Wright, Georg Wilhelm Friedrich Hegel, Charles Sanders Peirce, semiotics, icon, index, symbol, Terrence Deacon, *The Symbolic Species*, necessity, history of mathematics, number, quantity, discrete, continuous, measure, 

**currently researching:** Jean Piaget, Herbert Spencer, data structures, data structure design space, combinatorial design, incidence structures, formal concept analysis, extension, intension, comprehension, formal concept analysis, order theory, lattice, mathematical property, degeneracy

I recently watched a lecture on conceptual spaces where the cognitive scientist Peter Gärdenfors was talking about meaning with concepts like "qualitative dimension" and "semantic space". I was left with the feeling that I didn't really understand in any rigorous way what was meant by terms like "quality", "qualitative" and "qualitiative dimension". The first question that comes to mind is how can we relate this concept to the more familar notion of a quantitative dimension that we encounter in mathematics and the natural sciences?

One fact of the world that any thinker will eventually come to realize is that complexity develops in a stratified manner (what mathematician and author of *The Ascent of Man*, Jacob Bronowksi, called **statified stability**). That is to say obviously our present day environment (including ourselves) is full of things that that at one time did not exist and that were heavily constrained to emerge in a limited number of possible orders.

## Questions
We can ask in the developement of concepts generally speaking do qualitative concepts develop first or quantitative concepts? And do they develop in this stratified manner that presupposes some necessity of the order? If there are constraints on the order of the development of our statified representations what can we learn from that fact? Does this imply anything about abstract constraints on communication or representation that exist by definition or is it entirely due to our biological constraints?

The plan is to examine some different contexts in which this developmental process is recapitulated:
- the development of language in both the evolution of humans as a species and in the language aquisition process of an individual human child borrowing in large part from Terrence Deacon's *The Symbolic Species* (1997). This also relates to the Charles Sanders Peirce's theory of signs (semiotics) and the process he terms semiosis. This theory of meaning and its developement might be a good overarching lens in which to view all of the examples described in this essay.
- the maturation of a child's perception and categorization faculties over time followed by their education in elementary mathematics
- in psychology, concepts that fall under the category "levels of measurement" (similar to what we now call datatypes in CS) developed originally in the field known as measurement theory popularized by the work of psychologist S. S. Stevens)
- the development in the history of mathematics of the differnt types of number and other related mathematical objects
- in the history of trade and money ??WTF??? (what does fungability and interchangable parts have to do with any of this??)

## Terminology
Note that the common interpretations of terms such as quantitative, qualitative, measure, discrete, and continuous are not really expressive and differentiated enough to really fully describe the proccesses we are attempting to understand.
... (more about this)

Speculative philosophers like Charles Sanders Peirce, Hegel, and Herbert Spencer extrapolate what I mention below to their cosmology and metaphysics insisting in the likeness of the evolutionary processes of the physical world and the process of the mind (a kind of theory of *almost* everything). An important more recent term that represents much of these ideas about development is self-organization. Of course they wrote about such a concept, for example a very important part of Peirce's philosophy is the concept of habit-formation but generalized beyond what we would be familiar with today which resembles what is meant by self-organization.

**Individual Perception**
When we are children we perceive continuous qualitative dimensions such as color, space, and time, ...etc. Although it makes sense to call these dimensions continuous, it is important realize that they have no notion of distance or metric. Also a vague qualitative-version of number (qualitative-amount) and a qualitative-version of size as well (qualitative-magnitude). As we learn language we being to assign names (mostly antonymous pairs) to the infinite poles of these dimensions/categories. Since these categories labeled with words they are under one interpretation discrete and under another interpretation they can be considered continuous qualitative dimensions along with a subjective and vague feeling of where one category becomes the next along that dimension (intervals?). So we have either moved from qualitative to quantitative or from qualitative to somewhat-closer-to quantitative.

In fact the words qualitative and quantitative can be misleading since different people will choose different locations along the dimension of more and more differentiated units to be the place where the labels are switched.

### Jean Piaget

### measure
But it is helpful to add a third word "measure" that describes an even more complex data structure. Why a triad here?

For example as a child learns a few words what was before perceived as the continuous qualitative dimension of qualitative-amount becomes something with more categories like "few, some, many". Then as the child how to count and about concepts like whole numbers and integers these qualitative intervals become more properly quantitative "1, 2, 3, …". (i.e., countable infinity)

Mathematics
In the development of one's education about mathematical concepts one follows a similar path.

???
As an individual learns about Euclidian synthetic geometry (thus continuity), fractions, and analytic geometry (measurement and real numbers), and chemistry and physics (physical dimensions, e.g. distance) some of these formerly qualitative dimensions become understood as more and more quantitative (qualitative sensing -> counting -> measurement). One can fill in more intermediate steps in this list.

Topology -> Projective -> Affine -> Similarity -> Euclidian Synthetic Geometry -> Euclidian Analytic Geometry -> Discrete Geometry (???is this correct???)

In college a STEM student might learn about a subject called topology. Topology is the similar to geometry but notions such as a measure of distance are abstracted away while the concept of neighbourhood (formally definined) is retained. This allows one to return to the prenumeric domain and study objects of higher generality than geometric objects with a specified notion of metric/distance.

What is interesting is how it seems that we have moved from implicit continuous to explicit discrete to explicit continuous (or vague quality to definite quantity to definite quantity).

**Signs & Meaning**
This actually seems to align with Peirce's most popular triad of icon, index, symbol. Icon's have a nature closer to the qualitative than quantitative. Icons are necessarily vague. Indexes have a singular nature (haecceity). When we use a indexical word like "this" a single object is designated in the immediate environment. Symbols are to be thought of as a virtual (somewhat disconnected from indexical grounding) network of indexes that point to each other more than they point to their grounding indexicals and icons. In the ideal limit the network mesh of symbols becomes something like a continuous real space. Of course humans can't have am infinite number of symbols in the memory, but that is what it would ideally approach in the limit.

Here is an apt quote from C.S. Peirce's father about how the network of symbols grows to model the whole universe:

“The strongest use of the symbol is to be found in its magical power of doubling the actual universe, and placing by its side an ideal universe, its exact counterpart, with which it can be compared and contrasted, and, by means of curiously connecting fibres, form with it an organic whole, from which modern analysis has developed her surpassing geometry.” —Benjamin Peirce

A more related triad is that of tone, token, and type. A tone is a continuous signal. A token is a discretization of that signal, and a type is a collection of tokens. The progression from tone to token to type is related to perception and learning. I'm think that Peirce's broader categories of 1stness, 2ndness, and 3rdness fit in with this narrative as well, but I won't go into that.

**Psychological Measurement**
Also in psychological measurement there is a tradition of categorization of levels of measurement. The categories allow them to constrain what statistical operations can be done so as to only allow meaningful operations on a data type (they predate the notion of date type, but are essentially similar). The original levels were Nominal (classification), Ordinal (comparison, level), Interval (difference, affinity), Ratio (magnitude, amount). There are quite a few other classifications of varying degrees of detail, but you should be able to see the similarities (after all these are also analogizing from physiological perception to "scientific perception".

**Further Mathematics (Complex Mathematical Objects)**
It is interesting to think once we have many types of quantitative numbers (e.g., integers, fractions, reals) we start to build abstractions on top of those quantities and those superstructures can be discrete with some continuous parts or discrete parts or just continuous with continuous values. So we can have many levels of inversion or we can have consecutive levels that are the same. For example a weighted graph (think neural network) is a essentially discrete data structure with continuous values at each vertex. Is seems to be true that continuous "structures" (so to say) require continuous parts while discrete structures do not. I would like to
think more about this.

Here is a quote from the book I just read about Peirce where the author is talking about Herbert Spencer:

Spencer also gave an alternative definition of evolution as “an integration of matter and concomitant dissipation of motion; during which the matter passes from a relatively indefinite, incoherent homogeneity to a relatively definite, coherent heterogeneity.” (*First Principles*, 367). This was subsequently lampooned by the mathematician
Kirkman, who gave the following “translation” into English: “Evolution is a change from a nohowish, untalkaboutable, all-alikeness, to a
somehowish and in-generaltalkabaoutable not-all-alikeness, by continuous somethingelseifications and sticktogetherations”

Also from Peirce's first paper on the purpose of concepts relating to perception and learning:

This paper is based upon the theory already established, that the function of conceptions is to reduce the manifold of sensuous impressions to unity, and that the validity of a conception consists in the impossibility of reducing the content of consciousness to unity without the introduction of it.

Apparently Peirce disagreed with Spencer quite largely on their respective evolutionary cosmologies.

It would be interesting to investigate whether the asymmetry of Peirce's hierarchy of genuine vs degenerate versions of 1stness, 2ndness, and 3rdness is related to the asymmetry of this discrete and continuous hierarchy. He essential says that when your recursive higher ordered descriptions of the categories (e.g, 1stness of 2ndness) are semiotically constrained (e.g., there is no 3rdness *of* 1stness). This is similar to how a continuous structure (i.e. Euclidian space) must be constructed from continuous parts (i.e., real
numbers), but a discrete space can have discrete or continuous values in its "slots".

Another way to summarize it is that there seems to be universal progression both in our minds and in the "social mind" from an undifferentiated implied continuum that differentiates into a small number of differentiated parts and then into a growing number of quantities so as to bring back in the limit a notion of continuity but now in an explicitly specified representation.

it is basically a description of the dynamic pattern of the growth of knowledge at least when applied to minds. Perhaps it would be more accurate to say the growth of complexity itself.

The question is what happens when you try to recursively build up stratified representations to higher-order representations like how is done with data structures and mathematical objects.

Of course throughout this I have been sometimes haphazardly equating discrete with quantity and continuous with quality. Here is a four-part categorization (as opposed to the triad earlier) of the same idea:

qualitative
continuous
(undifferentiated dimension)

qualitative
discrete
(differentiated dimension; few intervals)

quantitative
discrete
(countable infinity of values; the intervals have become singularities)

quantitative
continuity
(uncountable infinity of values; the singularities have become
neighbors)
NOTE: elaborate here more on properties of the continuum 

Information Theory and real numbers. Does a real number contain an infinite quantity of information?

In the context of mathematics, a very simple example of a higher-ordered structure beyond the continuum would be a complex number. It can be put in this scheme by describing it as a discrete "compound" of a quantitative ??continuities??.
But I'm not sure if it would be a
- qualitative/discrete compound of quantitative/continuities; or
- quantitative/discrete compound of quantitative/continuities

using the four-fold scheme

The two slots of a real pair are singularities of continuous numbers
not intervals.

Peirce even analogizes such mental processes to the process of an organism's metabolic breakdown of nutrients and then constructing them up again. This is similar to the breakdown of the continuous manifold of sensuous impressions (tones) and then the building back up of tokens, types and higher-order structures (type hierarchies).

I often wonder if the idea of fungibility/interchangeable parts fits somewhere in this story? Because in order to have measurement you need a *unit of measurement*, that is a standard. This presupposes that the standard can be replicated and the replicas are fungible.  You really can't progress from quality to quantity until you have such a comparison to a standard. (see Measurement Theory)

Also in the context of the the history of technology the invention of precise interchangeable parts (i.e. fungability) seem to have been an important contributing factor in the rapid growth of social and technological complexity as well.

...

[^1]: Note that although this title corresponds with the outline of the Doctrine of Being from Hegel's *Science of Logic*, I do not cover Hegel's ideas except superficially as I was unaware them at the time of writing this essay.















things to add:

- list the properties (intensional specification) of the different number sets naturals, integers, rational, real, complex

- Hegel and The Science of Logic seems to have covered very similar material...

- money??? is this applicable?

- more about the development of larger and larger sets in mathematics?

- history of the invention and emergence of data structures in computer science

## Glossary:
...

## References/Reading List:

Peter Gärdenfors - The Geometry of Meaning (2nd ESSENCE Summer School) - https://www.youtube.com/watch?v=L0X9mEe9aY0 - Professor Peter Gärdenfors is Head of Cognitive Science at Lund University, Sweden. This video shows his tutorial "The Geometry of Meaning: Semantics Based on Conceptual Spaces" from the Second ESSENCE Summer School in Edinburgh in August 2015. 

Jacob Bronowski New Concepts in the Evolution of Complexity: Stratified Stability and Unbounded Plans
Synthese
Vol. 21, No. 2 (Jun., 1970), pp. 228-246 (19 pages)
Published By: Springer
https://www.jstor.org/stable/20114723?seq=1#page_scan_tab_contents

Quite Right: The Story of Mathematics, Measurement, and Money by Norman Biggs

Stevens, Stanley Smith (June 7, 1946). "On the Theory of Scales of Measurement" (PDF). Science. 103 (2684): 677–680. Bibcode:1946Sci...103..677S. doi:10.1126/science.103.2684.677. PMID 17750512.

Wright B.D. (1999) Fundamental measurement for psychology. In S.E. Embretson & S.L. Hershberger (Eds.), The new rules of measurement: What every educator and psychologist should know. Hillsdale, NJ: Lawrence Erlbaum Associates.
(https://www.rasch.org/memo64.htm)

John Michael Linacre (YouTube channel) - Introduction to the Rasch Model. Benjamin D. Wright, 1994. All - Parts 1+2+3 - https://www.youtube.com/watch?v=K8fdBLGfhxc

Making Measures (Phaneron Press) by Benjamin D. Wright, Mark H. Stone

Patrick Suppes, R. Duncan Luce, & Amos Tversky - Foundations of Measurement (lecture course) - https://www.youtube.com/playlist?list=PLrKlhVqlZwK6UcJ7K-XpaLmWoGehnXLAX

Foundations of Measurement (Vol 1-3) - http://www.lps.uci.edu/~johnsonk/CLASSES/FoundationsOfMeasurement/FoMHome.html

A Hundred Years of Numbers. An
Historical Introduction to Measurement
Theory 1887-1990 - http://www.lps.uci.edu/~johnsonk/CLASSES/FoundationsOfMeasurement/Diez.AnHistoricalIntroductionToMeasurementTheoryPartOne.pdf

The Logical Structure of Kinds by Eric Funkhouser

Peirce bibliography from Wikipedia: https://en.wikipedia.org/wiki/Charles_Sanders_Peirce_bibliography

What is a Sign? by C S Peirce

The Continuity of Peirce's Thought (Vanderbilt Library of American Philosophy) by Kelly A. Parker

Peirce's Scientific Metaphysics: The Philosophy of Chance, Law, and Evolution (Vanderbilt Library of American Philosophy) by Andrew Reynolds

Charles S. Peirce's Phenomenology: Analysis and Consciousness by Richard Kenneth Atkins

On a New List of Categories (1867) by Charles Sanders Peirce - https://en.wikisource.org/wiki/On_a_New_List_of_Categories

A Philosophical Commentary On C. S. Peirce’s “On A New List Of Categories”: Exhibiting Logical Structure And Abiding Relevance A Dissertation in Philosophy by Masato Ishida (2009) - https://etda.libraries.psu.edu/files/final_submissions/4550

Peirce-Arg Philosophers (Arguments of the Philosophers) by Christopher Hookway

Peirce and Triadomania: A Walk in the Semiotic by C. W. Spinks

Semiotics and Significants The Correspondence between Charles S. Peirce and Victorial Lady Welby (Edited by Charles S. Hardwick)

Francesco Bellucci - *Peirce’s Speculative Grammar: Logic as Semiotics* (Routledge Studies in American Philosophy) 

Francesco Bellucci (TIDD PUC-SP, YouTube) - Peirce on Symbols - https://www.youtube.com/watch?v=YhB6pFhXOto

Gloyd Merrell - https://www.youtube.com/watch?v=CpbqzzYU_Ks

???T. L Short (Peirce's Theory of Signs)???
???Menno Hulswit (From Cause to Causation: A Peircean Perspective (Philosophical Studies Series, 90))???

Commens Digital Companion to C. S. Peirce - http://www.commens.org/

Terrence Deacon, *The Symbolic Species: The Co-evolution of Language and the Brain*. New York: W.W. Norton & Company. 1997. ISBN 978-0-393-31754-1

Terrence Deacon, *Incomplete Nature: How Mind Emerged from Matter*. New York: W.W. Norton & Company. 2011. ISBN 978-0-393-04991-6

Wikipedia summary of Incomplete Nature: https://en.wikipedia.org/wiki/Incomplete_Nature

The Great Chain of Being: A Study of the History of an Idea by Arthur O. Lovejoy

Peirce, C. S. - Upon Logical Comprehension and Extension (https://peirce.sitehost.iu.edu/writings/v2/w2/w2_06/v2_06.htm)

Rudolf Wille - Concept Lattices and Conceptual Knowledge Systems (pdf) - https://bit.ly/3ncbfXo

https://stratos.seas.harvard.edu/files/stratos/files/periodictabledatastructures.pdf

Oxford University Department for Continuing Education - Cezar Ionescu - What is a Mathematical Property (2018 Open Event) - https://www.youtube.com/watch?v=8IhuPi5SbcI

Stanford Encyclopedia of Philosophy

Internet Encylopedia of Philosophy

https://en.wikipedia.org/wiki/Unit_of_measurement

https://en.wikipedia.org/wiki/Polynomial_conjoint_measurement

https://en.wikipedia.org/wiki/Louis_Narens

How real are real numbers? - https://www.scielo.br/j/man/a/rML75qWWzpSTbkC7SfbFpPp/?lang=en

Hegel Society of Great Britian HSGB - Science of Logic lectures by Stephen Houlgate - https://www.youtube.com/playlist?list=PLBAqLRlJe9p4sSXYnSVZUyVFeRFDFB4RR
