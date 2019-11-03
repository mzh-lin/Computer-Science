# Computer-Science

It is a complete education in computer science using online materials

# To-Do List

**Curriculum version**:`8.0.0`\(see[CHANGELOG](https://github.com/ossu/computer-science/blob/dev/CHANGELOG.md)\)

* [Intro CS](#1)
  * [Introduction to Programming](#1.1)
  * [Introduction to Computer Science](#1.2)
* [Core CS](#2)
  * [Core programming](#2.1)
  * [Core math](#2.2)
  * [Core systems](#2.3)
  * [Core theory](#2.4)
  * [Core applications](#2.5)
* [Advanced CS](#3)
  * [Advanced programming](#3.1)
  * [Advanced math](#3.2)
  * [Advanced systems](#3.3)
  * [Advanced theory](#3.4)
  * [Advanced applications](#3.5)
* [Final project](#4)
* [Pro CS](#5)


<h2 id="1">Intro CS</h2>
<h3 id="1.1">Introduction to Programming</h3>

**Topics covered**:`simple programs` `simple data structures`

| Courses | Effort | Prerequisites |
| :--- | :--- | :--- |
| [Python for Everyone](https://www.coursera.org/specializations/python) | 58 hours | none |
| [Fundamentals of Computing](https://www.coursera.org/specializations/computer-fundamentals) | 138 hours | high school mathematics |

<h3 id="1.2">Introduction to Computer Science</h3>

**Topics covered**: `computation` `imperative programming` `basic data structures and algorithms` `and more` 

| Courses | Duration | Effort | Prerequisites |
| :--- | :--- | :--- | :--- |
| [Introduction to Computer Science and Programming using Python](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-10)\([alt](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/)\) | 9 weeks | 15 hours/week | high school algebra |

<h2 id="2">Core CS</h2>
<h3 id="2.1">Core programming</h3>

| Courses                                                      | Duration | Effort          | Prerequisites                            |
| ------------------------------------------------------------ | -------- | --------------- | ---------------------------------------- |
| [How to Code - Simple Data](https://www.edx.org/course/how-code-simple-data-ubcx-htc1x) | 7 weeks  | 8-10 hours/week | none                                     |
| [How to Code - Complex Data](https://www.edx.org/course/how-code-complex-data-ubcx-htc2x) | 6 weeks  | 8-10 hours/week | How to Code: Simple Data                 |
| [Software Construction - Data Abstraction](https://www.edx.org/course/software-construction-data-abstraction-ubcx-softconst1x) | 6 weeks  | 8-10 hours/week | How to Code - Complex Data               |
| [Software Construction - Object-Oriented Design](https://www.edx.org/course/software-construction-object-oriented-ubcx-softconst2x) | 6 weeks  | 8-10 hours/week | Software Construction - Data Abstraction |
| [Programming Languages, Part A](https://www.coursera.org/learn/programming-languages) | 4 weeks  | 8-16 hours/week | recommended: Java, C                     |
| [Programming Languages, Part B](https://www.coursera.org/learn/programming-languages-part-b) | 3 weeks  | 8-16 hours/week | Programming Languages, Part A            |
| [Programming Languages, Part C](https://www.coursera.org/learn/programming-languages-part-c) | 3 weeks  | 8-16 hours/week | Programming Languages, Part B            |

#### Readings

- **Required** to learn about monads, laziness, purity: [Learn You a Haskell for a Great Good!](http://learnyouahaskell.com/) 
  - **Note**: probably the best resource to learn Haskell: [Haskell Programming from First Principles](http://haskellbook.com/) `paid` 
- **Required**, to learn about logic programming, backtracking, unification: [Learn Prolog Now!](http://lpn.swi-prolog.org/lpnpage.php?pageid=top) 

<h3 id="2.2">Core math</h3>

**Topics covered**: `linear transformations` `matrices` `vectors` `mathematical proofs` `number theory` `differential calculus` `integral calculus` `sequences and series` `discrete mathematics` `basic statistics` `O-notation` `graph theory` `vector calculus` `discrete probability` `and more`

| Courses                                                      | Duration | Effort          | Prerequisites             |
| ------------------------------------------------------------ | -------- | --------------- | ------------------------- |
| [Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | -        | -               | pre-calculus              |
| [Linear Algebra - Foundations to Frontiers](https://www.edx.org/course/linear-algebra-foundations-to-frontiers-0) ([alt](http://ulaff.net/)) | 15 weeks | 8 hours/week    | Essence of Linear Algebra |
| [Calculus 1A: Differentiation](https://www.edx.org/course/calculus-1a-differentiation) | 13 weeks | 6-10 hours/week | pre-calculus              |
| [Calculus 1B: Integration](https://www.edx.org/course/calculus-1b-integration) | 13 weeks | 5-10 hours/week | Calculus 1A               |
| [Calculus 1C: Coordinate Systems & Infinite Series](https://www.edx.org/course/calculus-1c-coordinate-systems-infinite-series) | 13 weeks | 5-10 hours/week | Calculus 1B               |
| [Mathematics for Computer Science](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/index.htm)<!--1--> | 13 weeks | 5 hours/week    | Calculus 1C               |

[^1]:  Students struggling with MIT Math for CS can consider taking the Discrete Mathematics Specialization first. It is more interactive but less comprehensive, and it costs money to unlock full interactivity.

<h3 id="2.3">Core Sysytems</h3>

**Topics covered**: `procedural programming` `manual memory management` `boolean algebra` `gate logic` `memory` `computer architecture` `assembly` `machine language` `virtual machines` `high-level languages` `compilers` `operating systems` `network protocols` `and more`

| Courses                                                      | Duration | Effort           | Additional Text / Assignments                                | Prerequisites                                                |
| ------------------------------------------------------------ | -------- | ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Introduction to Computer Science - CS50](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x#!) ([alt](https://cs50.harvard.edu/)) | 12 weeks | 10-20 hours/week | After the sections on C, skip to the next course. [Why?](https://github.com/ossu/computer-science/blob/dev/FAQ.md#why-do-you-recommend-skipping-the-second-half-of-cs50) | introductory programming                                     |
| [Build a Modern Computer from First Principles: From Nand to Tetris](https://www.coursera.org/learn/build-a-computer) ([alt](http://www.nand2tetris.org/)) | 6 weeks  | 7-13 hours/week  | -                                                            | C-like programming language                                  |
| [Build a Modern Computer from First Principles: Nand to Tetris Part II](https://www.coursera.org/learn/nand2tetris2) | 6 weeks  | 12-18 hours/week | -                                                            | one of [these programming languages](https://user-images.githubusercontent.com/2046800/35426340-f6ce6358-026a-11e8-8bbb-4e95ac36b1d7.png), From Nand to Tetris Part I |
| [Introduction to Computer Networking](https://lagunita.stanford.edu/courses/Engineering/Networking-SP/SelfPaced/about) | 8 weeks  | 4–12 hours/week  | [Assignment 1](https://github.com/PrincetonUniversity/COS461-Public/tree/master/assignments/assignment1) [Assignment 2](https://www.scs.stanford.edu/10au-cs144/lab/reliable/reliable.html) [Assignment 3](https://nptel.ac.in/content/storage2/courses/106105080/pdf/M2L7.pdf) [Assignment 4](http://www-net.cs.umass.edu/wireshark-labs/Wireshark_TCP_v7.0.pdf) | algebra, probability, basic CS                               |
| [ops-class.org - Hack the Kernel](https://www.ops-class.org/) | 15 weeks | 6 hours/week     | Replace course textbook with [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) | algorithms                                                   |

<h3 id="2.4">Core theory</h3>

**Topics covered**: `divide and conquer` `sorting and searching` `randomized algorithms` `graph search` `shortest paths` `data structures` `greedy algorithms` `minimum spanning trees` `dynamic programming` `NP-completeness` `and more`

| Courses                                                      | Duration | Effort         | Prerequisites                                              |
| ------------------------------------------------------------ | -------- | -------------- | ---------------------------------------------------------- |
| [Algorithms: Design and Analysis, Part I](https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms1+SelfPaced/about) | 8 weeks  | 4-8 hours/week | any programming language, Mathematics for Computer Science |
| [Algorithms: Design and Analysis, Part II](https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms2+SelfPaced/about) | 8 weeks  | 4-8 hours/week | Part I                                                     |

<h3 id="2.5">Core applications</h3>


**Topics covered**: `Agile methodology` `REST` `software specifications` `refactoring` `relational databases` `transaction processing` `data modeling` `neural networks` `supervised learning` `unsupervised learning` `OpenGL` `raytracing` `block ciphers` `authentication` `public key encryption` `and more`

| Courses                                                      | Duration  | Effort          | Prerequisites                                  |
| ------------------------------------------------------------ | --------- | --------------- | ---------------------------------------------- |
| [Databases](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about) | 12 weeks  | 8-12 hours/week | some programming, basic CS                     |
| [Machine Learning](https://www.coursera.org/learn/machine-learning) | 11 weeks  | 4-6 hours/week  | linear algebra                                 |
| [Computer Graphics](https://www.edx.org/course/computer-graphics-uc-san-diegox-cse167x) | 6 weeks   | 12 hours/week   | C++ or Java, linear algebra                    |
| [Cryptography I](https://www.coursera.org/course/crypto)     | 6 weeks   | 5-7 hours/week  | linear algebra, probability                    |
| [Software Engineering: Introduction](https://www.edx.org/course/software-engineering-introduction-ubcx-softeng1x) | 6 weeks   | 8-10 hours/week | Software Construction - Object-Oriented Design |
| [Software Development Capstone Project](https://www.edx.org/course/software-development-capstone-project-ubcx-softengprjx) | 6-7 weeks | 8-10 hours/week | Software Engineering: Introduction             |

## Advanced CS

After completing **every required course** in Core CS, students should choose a subset of courses from Advanced CS based on interest. Not every course from a subcategory needs to be taken. But students should take *every* course that is relevant to the field they intend to go into.

The Advanced CS study should then end with one of the Specializations under [Advanced applications](https://github.com/ossu/computer-science#advanced-applications). A Specialization's Capstone, if taken, may act as the [Final project](https://github.com/ossu/computer-science#final-project), if permitted by the Honor Code of the course. If not, or if a student chooses not to take the Capstone, then a separate Final project will need to be done to complete this curriculum.

<h3 id="3.1">Advanced programming</h3>


**Topics covered**: `debugging theory and practice` `goal-oriented programming` `GPU programming` `CUDA` `parallel computing` `object-oriented analysis and design` `UML` `large-scale software architecture and design` `and more`

| Courses                                                      | Duration | Effort         | Prerequisites                       |
| ------------------------------------------------------------ | -------- | -------------- | ----------------------------------- |
| [Compilers](https://lagunita.stanford.edu/courses/Engineering/Compilers/Fall2014/about) | 9 weeks  | 6-8 hours/week | none                                |
| [Software Debugging](https://www.udacity.com/course/software-debugging--cs259) | 8 weeks  | 6 hours/week   | Python, object-oriented programming |
| [Software Testing](https://www.udacity.com/course/software-testing--cs258) | 4 weeks  | 6 hours/week   | Python, programming experience      |
| [LAFF - On Programming for Correctness](https://www.edx.org/course/laff-on-programming-for-correctness) | 7 weeks  | 6 hours/week   | linear algebra                      |
| [Introduction to Parallel Programming](https://classroom.udacity.com/courses/cs344) ([alt](https://www.youtube.com/playlist?list=PLGvfHSgImk4aweyWlhBXNF6XISY3um82_)) | 12 weeks | -              | C, algorithms                       |
| [Software Architecture & Design](https://www.udacity.com/course/software-architecture-design--ud821) | 8 weeks  | 6 hours/week   | software engineering in Java        |

<h3 id="3.2">Advanced math</h3>

**Topics covered**: `parametric equations` `polar coordinate systems` `multivariable integrals` `multivariable differentials` `probability theory` `and more`

| Courses                                                      | Duration | Effort        | Prerequisites          |
| ------------------------------------------------------------ | -------- | ------------- | ---------------------- |
| [Multivariable Calculus](https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/index.htm) | 13 weeks | 12 hours/week | MIT Calculus 1C        |
| [Introduction to Probability - The Science of Uncertainty](https://www.edx.org/course/introduction-probability-science-mitx-6-041x-2) | 18 weeks | 12 hours/week | Multivariable Calculus |

<h3 id="3.3">Advanced systems</h3>


**Topics covered**: `digital signaling` `combinational logic` `CMOS technologies` `sequential logic` `finite state machines` `processor instruction sets` `caches` `pipelining` `virtualization` `parallel processing` `virtual memory` `synchronization primitives` `system call interface` `and more`

| Courses                                                      | Duration | Effort          | Prerequisites                     |
| ------------------------------------------------------------ | -------- | --------------- | --------------------------------- |
| [Reliable Distributed Systems, Part 1](https://www.edx.org/course/reliable-distributed-algorithms-part-1-kthx-id2203-1x) | 5 weeks  | 5 hours/week    | Scala, intermediate CS            |
| [Reliable Distributed Systems, Part 2](https://www.edx.org/course/reliable-distributed-algorithms-part-2-kthx-id2203-2x) | 5 weeks  | 5 hours/week    | Part 1                            |
| [Electricity and Magnetism, Part 1](https://www.edx.org/course/electricity-magnetism-part-1-ricex-phys102-1x-0)1 | 7 weeks  | 8-10 hours/week | calculus, basic mechanics         |
| [Electricity and Magnetism, Part 2](https://www.edx.org/course/electricity-magnetism-part-2-ricex-phys102-2x-0) | 7 weeks  | 8-10 hours/week | Electricity and Magnetism, Part 1 |
| [Computation Structures 1: Digital Circuits](https://www.edx.org/course/computation-structures-part-1-digital-mitx-6-004-1x-0) | 10 weeks | 6 hours/week    | electricity, magnetism            |
| [Computation Structures 2: Computer Architecture](https://www.edx.org/course/computation-structures-2-computer-mitx-6-004-2x) | 10 weeks | 6 hours/week    | Computation Structures 1          |
| [Computation Structures 3: Computer Organization](https://www.edx.org/course/computation-structures-3-computer-mitx-6-004-3x-0) | 10 weeks | 6 hours/week    | Computation Structures 2          |

**1 Note**: These courses assume knowledge of basic physics. ([Why?](https://github.com/ossu/computer-science/blob/dev/FAQ.md#why-is-the-curriculum-missing-some-pre-requisites)) If you are struggling, you can find a physics MOOC or utilize the materials from Khan Academy: [Khan Academy - Physics](https://www.khanacademy.org/science/physics)

<h3 id="3.4">Advanced theory</h3>

**Topics covered**: `formal languages` `Turing machines` `computability` `event-driven concurrency` `automata` `distributed shared memory` `consensus algorithms` `state machine replication` `computational geometry theory` `propositional logic` `relational logic` `Herbrand logic` `concept lattices` `game trees` `and more`

| Courses                                                      | Duration | Effort         | Prerequisites                                |
| ------------------------------------------------------------ | -------- | -------------- | -------------------------------------------- |
| [Introduction to Logic](https://www.coursera.org/learn/logic-introduction) | 10 weeks | 4-8 hours/week | set theory                                   |
| [Automata Theory](https://lagunita.stanford.edu/courses/course-v1:ComputerScience+Automata+SelfPaced/about) | 7 weeks  | 10 hours/week  | discrete mathematics, logic, algorithms      |
| [Computational Geometry](https://www.edx.org/course/computational-geometry-tsinghuax-70240183x) | 16 weeks | 8 hours/week   | algorithms, C++                              |
| [Introduction to Formal Concept Analysis](https://www.coursera.org/learn/formal-concept-analysis) | 6 weeks  | 4-6 hours/week | logic, probability                           |
| [Game Theory](https://www.coursera.org/learn/game-theory-1)  | 8 weeks  | x hours/week   | mathematical thinking, probability, calculus |
<h3 id="3.5">Advanced applications</h3>

These Coursera Specializations all end with a Capstone project. Depending on the course, you may be able to utilize the Capstone as your Final Project for this Computer Science curriculum. Note that doing a Specialization with the Capstone at the end always costs money. So if you don't wish to spend money or use the Capstone as your Final, it may be possible to take the courses in the Specialization for free by manually searching for them, but not all allow this.

| Courses                                                      | Duration | Effort         | Prerequisites                                      |
| ------------------------------------------------------------ | -------- | -------------- | -------------------------------------------------- |
| [Robotics (Specialization)](https://www.coursera.org/specializations/robotics) | 26 weeks | 2-5 hours/week | linear algebra, calculus, programming, probability |
| [Data Mining (Specialization)](https://www.coursera.org/specializations/data-mining) | 30 weeks | 2-5 hours/week | machine learning                                   |
| [Big Data (Specialization)](https://www.coursera.org/specializations/big-data) | 30 weeks | 3-5 hours/week | none                                               |
| [Internet of Things (Specialization)](https://www.coursera.org/specializations/internet-of-things) | 30 weeks | 1-5 hours/week | strong programming                                 |
| [Cloud Computing (Specialization)](https://www.coursera.org/specializations/cloud-computing) | 30 weeks | 2-6 hours/week | C++ programming                                    |
| [Full Stack Web Development (Specialization)](https://www.coursera.org/specializations/full-stack) | 27 weeks | 2-6 hours/week | programming, databases                             |
| [Data Science (Specialization)](https://www.coursera.org/specializations/jhu-data-science) | 43 weeks | 1-6 hours/week | none                                               |
| [Functional Programming in Scala (Specialization)](https://www.coursera.org/specializations/scala) | 29 weeks | 4-5 hours/week | One year programming experience                    |

<h2 id="4">Final project</h2>\
After you've gotten through all of Core CS and the parts of Advanced CS relevant to you, you should think about a problem that you can solve using the knowledge you've acquired. Not only does real project work look great on a resume, but the project will also *validate* and *consolidate* your knowledge. You can create something entirely new, or you can find an existing project that needs help via websites like [CodeTriage](https://www.codetriage.com/) or [First Timers Only](http://www.firsttimersonly.com/).

Another option is using the Capstone project from taking one of the Specializations in [Advanced applications](https://github.com/ossu/computer-science#advanced-applications); whether or not this makes sense depends on the course, the project, and whether or not the course's Honor Code permits you to display your work publicly. In some cases, it may not be permitted; do **not** violate your course's Honor Code!

<h2 id="5">Pro CS
</h2>

After completing the requirements of the curriculum above, you will have completed the equivalent of a full bachelor's degree in Computer Science, or quite close to one. You can stop in the Advanced CS section, but the next step to completing your studies is to develop skills and knowledge in a specific domain. Many of these courses are graduate-level.

Choose one or more of the following **specializations**:

- [Mastering Software Development in R Specialization](https://www.coursera.org/specializations/r) by Johns Hopkins University
- [Artificial Intelligence Engineer Nanodegree](https://www.udacity.com/ai) by IBM, Amazon, and Didi
- [Machine Learning Engineer Nanodegree](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009) by Kaggle
- [Cybersecurity MicroMasters](https://www.edx.org/micromasters/ritx-cybersecurity) by the Rochester Institute of Technology
- [Android Developer Nanodegree](https://www.udacity.com/course/android-developer-nanodegree-by-google--nd801) by Google

These aren't the only specializations you can choose. Check the following websites for **more options**:

- edX: [xSeries](https://www.edx.org/xseries)
- Coursera: [Specializations](https://www.coursera.org/specializations)
- Udacity: [Nanodegree](https://www.udacity.com/nanodegree)

# References

[https://github.com/ossu/computer-science\#pro-cs](https://github.com/ossu/computer-science#pro-cs)

