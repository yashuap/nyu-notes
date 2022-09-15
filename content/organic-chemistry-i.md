---
title: "Organic Chemistry I"
date: 2022-09-14T15:51:07-04:00
katex: true
mol: true
---

# Organic Chemistry I
## Resources

[Syllabus](/organic-chemistry/i-syllabus.pdf)  
[Textbook](/organic-chemistry/textbook.pdf)  
[Study Guide/Solution Manual](/organic-chemistry/solution-manual.pdf)  

## Course Information
### Grading
| Graded Item                        | % of Final Grade |
| ---                                | ---              |
| Quizzes                            | 10%              |
| Midterm Exams (2 highest out of 3) | 40%              |
| Final Exam                         | 25%              |
| Laboratory Grade                   | 25%              |

{{<hint info>}}Homework is not graded.{{</hint>}}
{{<hint warning>}}Quizzes are not given every week, but rather on random weeks (dependant on the TA).{{</hint>}}

## Electrons
### Quantum Numbers

Each electron in an atom is fundamentally unique. But in order for them to be 'unique,' they need to have some sort of identity to discern them from other electrons. For electrons, this 'ID' is their quantum numbers.

{{<details "What principle asserts that electrons are unique in an atom?">}}
**Pauli Exclusion Principle.**
{{</details>}}

{{<details "Make a chart that states the four quantum numbers, what they physically represent, and their range of possible values.">}}
| Quantum Number      | Physical Representation | Possible Values              |
| ---                 | ---                     | ---                          |
| Principle ($n$)     | energy shell            | $1 \rightarrow \infty$       |
| Azimuthal ($\ell$)  | shape/orbital           | $0 (s), 1 (p), 2 (d), ... n$ |
| Magnetic ($m_\ell$) | orientation             | $-\ell, ... 0, ... \ell$     |
| Spin ($m_s$)        | spin                    | $-\frac{1}{2}, \frac{1}{2}$  |

{{<hint info>}}$\ell$ represents the type of orbital ($s, p, d, f$).{{</hint>}}
{{</details>}}

### Orbitals

The traditional ball model of the atom depicts electrons as particles in space, contained in a discrete sphere. In reality, however, electrons exhibit wave-like behaviours, meaning that they are *continuous* entities that take up space. There is no hard line that divides electrons and not-electrons. These volumes of space are called 'orbitals.'

{{<hint danger>}}That's not to say there all areas of space has a chance to have an electron, since there can be areas of space with the probability equal to 0. See [nodes](#nodes).{{</hint>}}

{{<details "Being continuous, the probability distribution is not uniform. What is being varied in these orbitals?">}}
**Electron density.**

These orbitals/electron density clouds model the probability of an electron occupying a point of space, and their infinitesimal small areas in space come together and form a continuous distribution of volume. 

{{<figure src="https://tracingcurves.files.wordpress.com/2019/07/46a9d-bohrvs.electroncloud.jpg" caption="https://tracingcurves.files.wordpress.com/2019/07/46a9d-bohrvs.electroncloud.jpg">}}
{{</details>}}

{{<details "How many electrons can reside in an orbital? Does it depend on $\ell$?">}}
Two.

Remember, $\ell$ only represents the *type* of orbital. Yes, we write the maximum number of electrons in an $s$ orbital as $s^2$, and we write the maximum number of electrons in a $p$ orbital as $p^6$, but *only when we write the electron configuration*. Really, this is just a shorthand, because a $p$ 'orbital' is actually three orbitals in disguise, each with their own orientations (those orbitals being $p_x, p_y,$ and $p_z$). Each of these $p_n$ orbitals can hold two electrons.

{{<hint info>}}For a quick formula to get the maximum number of electrons in a *type* of orbital, you can use the equation $2+4\ell$.{{</hint>}}

{{<details "Why can orbitals only have two electrons?">}}
Because of the Pauli Exclusion Principle.

Remember, the PEP states that no two electrons can have the same four quantum numbers. Electrons reside in the same orbital if their $n, \ell,$ and $m_\ell$ are the same as each other. That leaves only the fourth quantum number, $m_s$, which only has two possible values ($-\frac{1}{2}, \frac{1}{2}$). If there were more than two electrons in an orbital, then it's guaranteed that there will duplicates, violating the PEP (see the [pidgeonhole principle](https://en.wikipedia.org/wiki/Pigeonhole_principle)).

{{<hint warning>}}
Some of you may be disappointed with this explanation, since I don't really explain *why* there are only two spin values. Frankly, I do not know, nor do I think it's something that we're gonna be expected to know. Though if you can find a reasonably understandable explanation and send it to me, then I'm happy to add it here.
{{</hint>}}
{{</details>}}
{{</details>}}

Each orbital has its own distinct shape. A $s$ orbitals are ball-like, while $p$ orbitals are dumbbell-shaped.

{{<expand "Figure of orbital shapes">}}
{{<figure src="https://energywavetheory.com/wp-content/uploads/2018/05/K5EcA.jpg" caption="https://energywavetheory.com/wp-content/uploads/2018/05/K5EcA.jpg">}}
{{</expand>}}

### Electron Configuration

To represent the amount of electrons in an atom, chemists use electron configurations. We start from a $n$ of 1 and an $\ell$ of 0 ($s$), meaning that hydrogen's neutral electron configuration is represented as $1s^1$. 

{{<hint info>}}The superscripts represent the number of electrons in an orbital. If you add all of them up, you get the number of electrons in the entire atom/ion.{{</hint>}}

{{<details "What order do electrons fill orbitals?">}}
They adhere to the **aufbau principle**, meaning they fill the orbitals with the lowest orbital energy.

{{<figure src="https://image.shutterstock.com/image-illustration/chart-electron-configuration-each-energy-260nw-1552589996.jpg" caption="A helpful chart showing the optimal orbital energy path.(https://www.shutterstock.com/image-illustration/chart-electron-configuration-each-energy-level-1552589996)">}}

{{<hint danger>}}
This diagram is not without its faults. It is generally accurate for the ground states of lower energy atoms, however many exceptions exist with atoms and ions of higher energy.
{{</hint>}}
{{</details>}}

{{<details "What is the electron configuration of $\ce{_{6}C}$?">}}
$1s^22s^22p^2$
{{</details>}}

For longer electron configurations, you can use a shorthand by replacing part of the configuration with the symbol of the noble gas in the previous period. For example, $\ce{_{16}S}$ can be represented as $[\ce{Ne}]3s^23p^4$

{{<details "What is the electron configuration of $\ce{_{87}Fr}$?">}}
Long form: $1s^22s^22p^63s^23p^64s^23d^{10}4p^65s^24d^{10}5p^66s^24f^{14}5d^{10}6p^67s^1$

Shorthand: $[\ce{Rn}] 7s^1$

{{<hint info>}}The in shorthand form, the $n$ of the $s$ orbital is equal to the period number.{{</hint>}}

{{</details>}}

