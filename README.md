# Julia: Solving Real-World Problems with Computation, Fall 2023 (under construction)

## Announcement
Office Hours are Wednesdays 4:30pm-5:30pm in 2-135.

## Logistics

**MIT's numbering scheme gone nuts:** (1.C25/6.C25/12.C25/16.C25/18.C25/22.C25)  
This course is part of the [Common Ground](https://computing.mit.edu/cross-cutting/common-ground-for-computing-education/common-ground-subjects/).  

**Lectures:** Tuesdays & Thursdays 1-2:30 PM in room 2-142 

**Prerequisites:** 6.100A, 18.03, 18.06 or equivalents (meaning some programming, dif eqs, and lin alg) 

**Instructors:** A. Edelman, R. Ferrari, Y. Marzouk, P. Persson (UCB), S. Silvestri, J. Urschel, [G. Dalle](https://gdalle.github.io/)

**Teaching Assistants:** Jacob Hansen (jahansen@mit.edu), Nicholas Klugman (nklugman@mit.edu)

**Office Hours:** Wednesdays 4:30pm-5:30pm in 2-135

**Grading:** Homeworks that may be spaced one or two weeks, to be submitted on canvas. No exams.  
**Lecture Recordings:** Available on Canvas under the Panopto Video tab. Should be published the evening after each lecture.  
**Links:** Worth bookmarking.  

| [Piazza](https://piazza.com/class/lm7pcjq3cbq2fm) | [Canvas](https://canvas.mit.edu/courses/21713) | [Julia](https://julialang.org/) | [JuliaHub](https://juliahub.com/ui/Home) |
| ------------------------------------------------- | ---------------------------------------------- | ------------------------------- | ---------------------------------------- |
| Discussion                                        | HW submission                                  | Language                        | GPUs                                     |

## Description

Focuses on algorithms and techniques for writing and using modern technical software in a job, lab, or research group environment that may consist of interdisciplinary teams, where performance may be critical, and where the software needs to be flexible and adaptable. Topics include automatic differentiation, matrix calculus, scientific machine learning, parallel and GPU computing, and performance optimization with introductory applications to climate science, economics, agent-based modeling, and other areas. Labs and projects focus on performant, readable, composable algorithms and software. Programming will be in Julia. Expects students have some familiarity with Python, Matlab, or R. No Julia experience necessary.

Counts as an elective for CEE students, an advanced subject (18.100 and higher) for Math students, an advanced elective for EECS students, and a computation restricted elective for NSE students. AeroAstro students can petition department to count this class as a professional subject in the computing area.
(Professors may be open to petitioning for counting for other programs.)

Class is appropriate for those who enjoy math and wish to see math being used in modern contexts.

While not exactly the same as our past [Computational Thinking Class](https://computationalthinking.mit.edu/)... not entirely different either.

## Course Objectives

1. Making mathematics your playground: By the end of the course, students will be able to write interactive Julia code that aids in their understanding of new mathematical systems or concepts.
2. Abstractions: By the end of the course students will be able to use the unique abstractions that exist in the Julia language to write code that can be part of a huge ecosystem.  (By contrast many  "one-off"  homeworks in traditional courses are not able, by their very nature, to reveal the value of abstraction.)
3. Open Source and group collaborations: By the end of the course students will be able to participate in a larger open source project and also will have experienced how programming language can help break down barriers between areas making real the dream of scientific bilinguals that has been promoted at MIT. (See for example [former MIT President Reif in the NYT back in 2018](https://www.nytimes.com/2018/10/15/technology/mit-college-artificial-intelligence.html).)
   

## Homeworks at a glance

| Homework                                                | Assigned | Due    | Topic                     |
| ------------------------------------------------------- | -------- | ------ | ------------------------- |
| [HW0](https://mit-c25-fall23.netlify.app/homeworks/hw0) | Sep 7    | Sep 14 | Getting Started           |
| [HW1](https://mit-c25-fall23.netlify.app/homeworks/hw1) | Sep 14   | Sep 21 | Automatic Differentiation |
| [HW2](https://mit-c25-fall23.netlify.app/homeworks/hw2) | Sep 21   | Sep 28 | Matrix Calculus           |
| [HW2](https://mit-c25-fall23.netlify.app/homeworks/hw3) | Sep 28   | Oct 12 | Matrix Calculus           |

Each student gets to turn in one homework late without justification.
Further late turn ins must be justified.
Remember: just because the automated tests succeed doesn't mean your code is 100% correct.
It is a necessary, but not sufficient condition.

Homework solutions will be put online after each deadline.

## Lectures at a glance   (future based on the 2022 class, will be modified based on students' interest this year)

| #   | Day | Date  | Lecturer          | Topic                                                | Slides / Notes                                                                                                                                    | Notebooks                                                                                                                                                                                                                                                                                                                                                           |
| --- | --- | ----- | ----------------- | ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 0   |     |       |                   | Julia tutorial                                       | [Cheat Sheets](https://computationalthinking.mit.edu/Fall23/cheatsheets/)                                                                         |                                                                                                                                                                                                                                                                                                                                                                     |
| 1   | R   | 9/7   | Edelman           | Intro to Julia                                       |                                                                                                                                                   | [Intro to Julia](https://gdalle.github.io/IntroJulia/), [Tutorial](https://mit-c25-fall23.netlify.app/notebooks/0_julia_tutorial), [Hyperbolic Corgi](https://mit-c25-fall23.netlify.app/notebooks/1_hyperbolic_corgi), [Images](https://mit-c25-fall23.netlify.app/notebooks/1_images), [Abstraction](https://mit-c25-fall23.netlify.app/notebooks/1_abstraction), |
| 2   | T   | 9/12  | Edelman           | Automatic Differentiation                            | [autodiff handwritten notes](https://github.com/mitmath/JuliaComputation/blob/ec6861bc9396d2b577f1bbc8136683d4298d7dc8/slides/ad_handwritten.pdf) | [[AutoDiff jupyter notebook]](https://github.com/mitmath/18337/blob/master/lecture1/AutoDiff.ipynb), [[autodiff video]](https://www.youtube.com/watch?v=vAp6nUMrKYg)                                                                                                                                                                                                |
| 3   | R   | 9/14  | Edelman           | Automatic Differentiation                            |                                                                                                                                                   | [Reverse Mode AutoDiff Demo](https://simeonschaub.github.io/ReverseModePluto/notebook.html)                                                                                                                                                                                                                                                                         |
| 4   | T   | 9/19  | Edelman           | Matrix Calculus                                      | [Matrix Calc 1](https://docs.google.com/presentation/d/1TGZ5I3ZP907-itZrslKF4miReNzV1dAOXNU4QMCHkd8/edit#slide=id.p)                              | [Matrix Jacobians](<https://mit-c25-fall22.netlify.app/notebooks/2_matrix_jacobians>), [Finite Differences](<https://mit-c25-fall22.netlify.app/notebooks/2_finite_differences>)                                                                                                                                                                                    |
| 5   | R   | 9/21  | Edelman           | Matrix Calculus                                      | [Matrix Calc 2](https://docs.google.com/presentation/d/1IuwijmdWCes1Quh1gJxbHoMbA50Tk0xxXnaPvu3tQjQ/edit#slide=id.g15504621cdd_0_0)               | [Linear Transformations](https://mit-c25-fall22.netlify.app/notebooks/3_linear_transformations), [Symmetric Eigenproblems](https://mit-c25-fall22.netlify.app/notebooks/3_symmetric_eigenvalue_derivatives)                                                                                                                                                         |
| 6   | T   | 9/26  | Edelman           | Differential Equations Lec 1                                    |                                                                                                                                                   |    [Time Stepping (background)](https://computationalthinking.mit.edu/Fall23/climate_science/time_stepping), [ODEs and parameterized types (main topic)](https://mit-c25-fall22.netlify.app/notebooks/3_symmetric_eigenvalue_derivatives), [Resistors and Stencils (touched on this)](https://computationalthinking.mit.edu/Fall23/climate_science/resistors_and_stencils/)                                                                                                                                                                                                                                                                            |
| 7   | R   | 9/28  | Edelman           | Differential Equations Lec 2        |                                                                                                                                                   |                                                                                                                                                                                                                                                                       |
| 8   | T   | 10/3  | Silvestri         | Climate Science                                      |                                                                                                                                                   | [Solving the climate system](https://mit-c25-fall22.netlify.app/notebooks/10_climate_science)                                                                                                                                                                                                                                                                       |
| 9   | R   | 10/5  | Silvestri         | Climate Science                                      |                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                     |
|     | T   | 10/10 | *Student Holiday* |                                                      |
| 10  | R   | 10/12 | Edelman           | Economic Model of Climate                            |                                                                                                                                                   | [Economic Model](https://computationalthinking.mit.edu/Fall23/climate_science/inverse_climate_model/), [Optimization with JUMP](https://computationalthinking.mit.edu/Fall23/climate_science/optimization_with_JuMP/)                                                                                                                                               |
| 11  | T   | 10/17 | Dalle             |                                                      |
| 12  | R   | 10/19 | Dalle             |                                                      |
| 13  | T   | 10/24 | Dalle             |                                                      |
| 14  | R   | 10/26 | Dalle             |                                                      |
| 15  | T   | 10/31 | Edelman           | Imaging and Convolutions                             |                                                                                                                                                   |
| 16  | R   | 11/2  | Edelman           | Convolutions and PDEs                                |                                                                                                                                                   |
| 17  | T   | 11/7 | Drake             | (HPC and GPUs    )                                     | [HPC and GPU Slides](https://docs.google.com/presentation/d/1i6w4p26r_9lu_reHYZDIVnzh-4SdERVAoSI5i42lBU8/edit?usp=sharing)                        | [N-body with FLoops](https://mit-c25-fall22.netlify.app/notebooks/floop_nbody), [JuliaHub demo](https://mit-c25-fall22.netlify.app/notebooks/juliahub_in_class_110122)                                                                                                                                                                                              |
| 18  | R   | 11/9 | Edelman           | HPC and GPUs                                         |
| 19  | T   | 11/14 | Persson           | Mesh Generation                                      | [Mesh generation](slides/mesh_generation.pdf)                                                                                                     | [Computational Geometry](https://mit-c25-fall22.netlify.app/notebooks/4_computational_geometry)                                                                                                                                                                                                                                                                     |
| 20  | R   | 11/16 | Persson           | Mesh Generation                                      |                                                                                                                                                   |
| 21  | T   | 11/21 |                   |                                                      |                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                     |
|     | R   | 11/23 | *Thanksgiving*    |                                                      |
| 22  | T   | 11/28 |                   |                                                      |                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                     |  |
| 23  | R   | 11/30 | Urschel           | Computational sports mathematics                     |
| 24  | T   | 12/5  | Urschel           | Computational sports mathematics                     |
| 25  | R   | 12/7  | Edelman           | Discrete and Continuous, are they so very different? |                                                                                                                                                   |
| 26  | T   | 12/12 | Class Party       |                                                      |


