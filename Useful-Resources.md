See also, [guidlines for contributing](https://github.com/KParas/MNC-Frac/wiki/Guidelines-for-Contributing)

## Technical Pre-requisites
Working with our code-base requires at least, some minimal knowledge in the following disciplines:
1. C++  abc
2. Git
3. (Nonlinear) Continuum Mechanics
4. (Nonlinear) Finite Elements
5. deal.II
6. Doxygen
7. Parallel Programming

## Useful Resources
Listed below are some resources which might be helpful in achieving the pre-requisites described above.

1. Beginners might find the [deal.II video lectures](https://www.math.colostate.edu/~bangerth/videos.html) quite useful, not just as a resource for learning deal.II but for scientific software development in general, since these cover several topic of interest including:
* Introduction to Linux   
* Visualization tools: Visit, Paraview
* IDE: Eclipse
* Version control system: git
* Parallel programming: shared memory parallel(SMP) using OpenMP, distributed memory parallel using MPI

2. **C++**: the programming language in which this framework has been written
* Before moving ahead, it be helpful to go through the slides of the C++ crash course provided as a part of exercises for the course Nonlinear Finite Elements offered by Prof. Julia Mergheim. 
* If you are complete beginner with (almost) no-experience with C++, you might find the following book helpful to start with: [Guide to Scientific Computing in C++](https://link.springer.com/book/10.1007%2F978-3-319-73132-2).
* People with some prior experience might find [the C++ Primer](https://www.oreilly.com/library/view/c-primer-fifth/9780133053043/) more useful. 
* Video lectures from the course [**Advanced Programming Techniques**](https://www.video.uni-erlangen.de/course/id/806.html) by Prof. Harald Koestler.

3. **Git**: version control system to aid in collaborative software development
* For complete beginners, the following [tutorial](https://www.atlassian.com/git/tutorials) might be a good start point. Also, lots of video tutorials can be found on Youtube.
* See also the slides from the [HPC Café–Git: Basics, common workflow, hints and tricks](https://hpc.fau.de/files/2021/02/2021_02_08-hpc-cafe-git.pdf)
* Those already familiar with **git** could have a look at this [git cheat sheet](https://github.com/KParas/MNC-Frac/wiki/Git-Cheatsheet).
* Relevant videos from the [dealii video lectures](https://www.math.colostate.edu/~bangerth/videos.html).

4. **Continuum Mechanics**
* For those with no prior knowledge of this topic will find the video lectures on [LKM](https://www.video.uni-erlangen.de/course/id/243) & [NLKM](https://www.video.uni-erlangen.de/course/id/767) by Prof. Paul Steinmann very helpful.
* [This book](https://www.wiley.com/en-us/Nonlinear+Solid+Mechanics%3A+A+Continuum+Approach+for+Engineering-p-9780471823193) by G. Holzapfel is an excellent one for recapitulating topics in nonlinear solid mechanics.

5. **Linear Finite Elements**
* The video lectures from the introductory course [IFEM](https://www.video.uni-erlangen.de/course/id/551) by Dr. Sebastian Pfaller could be helpful for those with no prior exposure to the finite element method. 
* Another resource, which I personally found very useful as I began to learn about finite elements if the course on [The Finite Element Method for Problems in Physics](https://www.coursera.org/learn/finite-element-method?). This course gives a very gentle intro to FEM and uses Deal.II for the exercises. The material is available for free to enrolled student.
* A good reference book is **The Finite Element Method: Linear Static and Dynamic Finite Element Analysis** by Thomas Hughes. 

6. **Nonlinear Finite Elements**
* The lectures notes on NLFE by Prof. Julia Mergheim should be sufficient for our purposes. 
* One might also find useful the [MIT video lectures](https://ocw.mit.edu/resources/res-2-002-finite-element-procedures-for-solids-and-structures-spring-2010/nonlinear/) on nonlinear FEM. 

7. **deal.II**: library for FE backend
* A quick intro to some of the required features of deal.II could be obtained from the exercises for the NLFE course mentioned above.
* Relevant videos from the [dealii video lectures](https://www.math.colostate.edu/~bangerth/videos.html).
* **NOTE:** One must go through The [Deal.ii Tutorials](https://www.dealii.org/9.0.0/doxygen/deal.II/Tutorial.html) 1-5 before touching the source code.
* Our source code would be helpful in learning how deal.II can be used to model problems in solid mechanics.
* Also see [here](https://github.com/KParas/MNC-Frac/wiki/Searching-deal.II) 

8. **Doxygen**: tool for generating documentation from source code.
* The best way to learn here, would be to go through our source code and also the source code of deal.II to understand how the comments need to be modified so as to turn them into doxygen documentation.

9. **Parallel Programming** (optional for beginners)
* Videos 39-41 of the [dealii video lectures](https://www.math.colostate.edu/~bangerth/videos.html).

**HINT:** If you would like to save the effort of going through each of the video lectures, the corresponding lecture materials (scripts, slides, exercises etc.) for the above mentioned courses, offered by FAU should be available through the [FSI CE Materialsammlung](https://ce.fsi.uni-erlangen.de/wp/en/studium/materialsammlung/).
