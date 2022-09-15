---
title: "Organic Chemistry I OLD"
date: 2022-09-08T10:57:12-04:00
katex: true
---

# Organic Chemistry I

## Resources
[Syllabus](/organic-chemistry/i-syllabus.pdf)  
[Textbook](/organic-chemistry/textbook.pdf)  
[Study Guide/Solution Manual](/organic-chemistry/solution-manual.pdf)  

## Class Info
### Grading
| Graded Item                        | % of Final Grade |
| ---                                | ---              |
| Quizzes                            | 10%              |
| Midterm Exams (2 highest out of 3) | 40%              |
| Final Exam                         | 25%              |
| Laboratory Grade                   | 25%              |

### Homeworks and Quizzes
There is homework for the class in the form of practice problems, however **they are not graded**. As for quizzes, we *may* get one during recitation covering the week's content, and those will be graded (10%).

### Misc
The professor advised us to get a molecular modeling kit. The one we had to get for General Chemistry should suffice.

## Atoms and Atomic Structure

An atom, as you probably know, is composed of a nucleus (which is made of protons and neutrons) and electrons. Atoms have an equal number of protons and electrons, while ions have an unbalanced amount, hence their charge. 

### Where are electrons?

What are electrons? Naive models often represent them as balls orbiting a central nucleus, however that is not really accurate to reality. Instead, electrons occupy **electron density clouds** that model the *probability* of an electron occupying a given location. 

{{<hint danger>}} Electrons (and many subatomic 'particles') are not just particles, nor are they just waves. Rather, they exhibit properties of both particles *and* waves.{{</hint>}}

The thing about probability is that, at least in this context, it's not discrete; rather it's a continuous property. What this means is that these clouds are quite 'blurry.' If we're talking about a simple ball-shaped density cloud (such as the $1s$ orbital), that means that the closer we are to the nucleus, the more likely we'll 'find' an electron there, and the probability distribution will be denser there. The further away we go, the probability of finding an electron decreases. 

Note, however, that the probability for a $1s$ orbital *approaches* 0 the further out we go; It never is 0. Even if we are 100,000 miles away from the nucleus of an atom, there is *technically* still a chance that we'll find an electron from that atom there.

That's not to say that there aren't regions of space with 0 electron dinsity. Only the $1s$ orbital has such omnipresent distribution. Orbitals with a higher energy shell (we'll get to what that means later) have regions of space, called **nodes**, with 0 probability of finding an electron there. The figure below shows the electron density clouds of $1s$, $2s$, and $3s$ orbitals, along with their nodes.

{{<figure src="https://upload.wikimedia.org/wikipedia/commons/5/5c/S_orbitals.png">}}

$2s$ orbitals have one node, and $3s$ orbitals have 2 nodes. How many nodes does a $4s$ orbital have? How about a $2p$ orbital? Well, if you noticed the pattern emerging from the figure, you'd know the answer is 3 and 1 respectively. The number of nodes is one less than the principle quantum number ($n$).

{{<hint info>}}
$$
	\text{\\# of nodes} = n - 1
$$
{{</hint>}}

{{<expand "Test">}}
{{</expand>}}

### You lost me at $1s$

Okay, I may have went ahead a little bit. I can't just throw terms like $1s$, 'energy shells,' and 'principle quantum number' around without explaining what they mean. Electrons are like snowflakes in the sense that no two electrons are alike. Unlike snowflakes, however, where it's technically possible yet virtually impossible to have two of the same snowflakes, electrons in an atom are *fundamentally* unique, as discovered by Wolfgang Pauli. 

{{<hint info>}}The **Pauli Exclusion Principle** states that no two electrons *in the same atom* can have the same four quantum numbers.{{</hint>}}

These four quantum numbers are as follows: the principle quantum number ($n$), the azimuthal(wtf?) quantum number ($\ell$), the magnetic quantum number ($m_\ell$), and the spin quantum number ($m_s$). 

{{<hint info>}}
| Quantum Number      | Physical Representation                   | Possible Values              |
| ---                 | ---                                       | ---                          |
| Principle ($n$)     | energy shell                              | $1 \rightarrow \infty$       |
| Azimuthal ($\ell$)  | shape/orbital                             | $0 (s), 1 (p), 2 (d), ... n$ |
| Magnetic ($m_\ell$) | orientation                               | $-\ell, ... 0, ... \ell$     |
| Spin ($m_s$)        | spin                                      | $-\frac{1}{2}, \frac{1}{2}$  |
{{</hint>}} 


