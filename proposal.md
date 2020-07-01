# Google's Season of Docs Numpy Documentation

# Introduction

* Numpy = great free open source software
* Numpy is a fundamental Python package for scientific computing [[1]](www.numpy.org). Over 370 thousand projects use Numpy for efficient array computing
[[2]](github.com/numpy/numpy).
* Documentation is spread throughout multiple resources (Numpy, Scipy, blogs,
 stack exchange, textbooks, etc.)
* Needs a consistent, clear guide for a new user
* Education is accomplished through community [[Dewey, John. Democracy and
 Education]](https://www.gutenberg.org/files/852/852-h/852-h.htm)
* We build knowledge and skills by testing and experimenting [Dewey]
* It is important to establish a community in the documentation that reflects
 the desired goals of the project
* This consistent, clear guide will help potential contributors add documentation and advise new users

There is an immediate need to make Numpy's documentation more accessible for
new users and possible contributors. 

# Current Knowledge 

* Software documentation is broadly grouped into four spaces [[Divio's
 Documentation System]](https://documentation.divio.com/): 
  * tutorial space
  * how-to space
  * explanation space
  * reference space
* Numpy's explanation and reference space is generated from detailed doc-strings
 in each function
* the tutorial and how-to spaces are not clearly delineated and sometimes enter into the explanation and reference space
* There are excellent tutorials for the "Absolute Beginner" and newcomers with
 Matlab experience


# Gap in the Knowledge Base/Unmet Need 

* The current documentation covers many necessary topics, but lacks clear distinction between tutorial, how-to, explanation, and reference space

* New documentation contributors are faced with hurdles to contribute 

* My goal is to make Numpy's documentation more accessible for newcomers and possible documentation contributors with a logical flow in documentation and building templates for user-contributed How-to's

* My long term goal is to build the documentation community so that learning from the documentation is a give-and-take that experienced users will point new-comers to the numpy.org documentation for help




# Rationale

* I use Numpy in almost all of my courses
* The current documentation is off-putting for new users e.g. my students
* I want to use my experience teaching non-CS majors how to code to help organize, edit, and fill in gaps in the current tutorials
* Then, I can use the Numpy documentation as a textbook for courses
* I have created dozens of tutorials, exercises, and examples using Python and Numpy <github.uconn.edu/rcc02007>. I want to convert some of this material
into Tutorials and How-Tos 
* I have had over 800 students use Numpy (as part of the Scipy stack)
* I have multiple students that are interested in becoming Numpy documentation
 contributors for the Fall semester
* I have been teaching at University of Connecticut Mechanical Engineering for 4
 years and taught over 30 credit-hours of courses

#  Three Specific Aims 


## 1. Organize the current documentation into:

### i. Tutorial Space

a. Absolute Beginner's Guide (move the lists to arrays here)

b. Array Creation (built-in functions, read from csv's, saving-loading
arrays)

c. Indexing

d. Linear Algebra

e. Numpy for Matlab
  
### ii. How-to Space: A curated selection of notebooks or websites that demonstrate
  how to define a problem, how to approach the problem, and the final results

### iii. Explanation Space

a. Broadcasting

b. Byte-swapping

c. Array creation (raw bytes, library functions, read from disk)

### iv. Reference Space: leave in the current function help documentation and API's

_This organization will help new users progress through documents and potential
documentation contributors will have clear styles and formats to base future
work_

## 2. Edit the current tutorials (Beginner's Guide, Array Creation, Indexing, Linear Algebra, and Numpy for Matlab) to move reference information into the Explanation Space. 

_The current tutorials will be shorter and easier to follow. New users will not
be faced with extra information that doesn't directly lead to applying Numpy to
their use cases._

## 3. Build a "How-to" template with one or two examples

  a. Define a problem, create an approach with Numpy, and present the solution
  
  b. These will be user-contributed and present use cases that working students
  and professionals can follow
  
  c. The How-to's will be curated with links or tags to functions, classes, etc. 

_New documentation contributors will be able to contribute small use cases to
millions of users without building entire Sphinx documentation. We want to
continue to build our teaching-and-learning community. For essential
how-to's, the content can be added to the core documentation._


* This proposed documentation will mimic current open source documentation such as Matplotlib, Divio, etc. New users and potential contributors will have an easier time learning to apply Numpy in their fields and software. 

# Expected Outcomes

Upon completing this Google Season of Docs I propose the following outcomes:

1. A revised Numpy Documentation Webpage that clearly separates the four spaces:
Tutorials, How-to, Explanation, and Reference

2. Revised Tutorials for: Quickstart Tutorial, Lists from arrays, array
creation, and linear algebra

3. The curated How to space will increase user contributions and help further
the goals of the Numpy community in teaching and learning

The timeline for the project is __9/14-11/30__. Each outcome has a number of steps outlined below in the tables for Outcomes 1-3. The first steps are to build the documentation and separate content in the current tutorials into __Tutorial__ and __Explanation__ content. This will be done in the first three weeks of the project as part of Outcomes 1 and 2-revising the website and tutorials, respectively. 

|__Outcome 1: Revise website__ | Deliverable Date|
|---| ---|
|Fork Numpy Repository and Build Docs with Sphinx| 9/21 |
|Build Webpage with Four Spaces defined and linked| 10/1|
|Move current tutorials into appropriate spaces and Build docs | 10/10 |
|Submit PR to github with proposed changes | 10/20 |
|Respond to comments/suggestions and revise PR | _ongoing with Outcome 2_ |
|Website revised | 11/30 |

|__Outcome 2: Revise tutorials__ | Deliverable Date |
|---|---|
|Rank the tutorials in order of need of revision | 9/21 |
|Separate current tutorial content into __Tutorial__ and __Explanation__ spaces| 10/1|
|Revise top-ranked Tutorial content| 10/10 |
|Submit PR to github for separation and revision| 10/20|
|Revise the rank 2 tutorial submit PR| 11/1|
|Revise the rank 3 tutorial submit PR| 11/15|
|Revise the rank 4 tutorial submit PR| 11/30|
<!--https://numpy.org/devdocs/user/ionumpy.html-->


|__Outcome 3: Curated How-to space__| Deliverable Date|
|---|---|
|Build How-to example (either "Transform Vectors with Numpy" or "Saving and loading Numpy arrays")|10/20|
|Build How-to template for new contributors| 11/1| 
|Work with other contributors to build How-to notebooks _recruiting UConn students and other community members_ | _ongoing_ |

# Expected Significance

* New users will stay in the Numpy documentation ecosystem
* Potential documentation contributors will be part of the Numpy community and help build consistent documentation
