# Google's Season of Docs  Documentation

# Introduction

NumPy delivers clean and fast array-based computing in a free open source software
library. It is a fundamental package in the SciPy stack for scientific computing [[1]](www..org). Over 370 thousand projects use  for efficient array computing
[[2]](github.com//numpy). New NumPy users are are greeted by a new website with
applications and case studies [[1]](www..org). When the new user finds the
documentation page, s/he is met with multiple "Start Here" links and introductory
tutorials that can be overwhelming for a beginner, such as [NumPy
Basics/byte-swapping](https://.org/doc/stable/user/basics.byteswapping.html). I began
using NumPy ten years ago in graduate school. I found myself piecing together blog posts,
lecture notes, and StackExchange answers to avoid going through the NumPy documentation.
There are currently over 360 thousand StackExchange conversations that deal with NumPy, so
I imagine other users have had similar routes to success in NumPy. 

It is important to establish a community in the documentation that reflects
 the desired goals of the project. The documentation needs a consistent, clear guide for a new user. The tutorials should
give new users easy-to-follow steps and build comfort with the library
[[3]](https://documentation.divio.com/). The building blocks of educational tools are
communication and community [[4 Dewey, John. Democracy and
 Education]](https://www.gutenberg.org/files/852/852-h/852-h.htm). The documentation education is meant to
 welcome a new user into the NumPy community. When new users enter
 the website, they are entering the NumPy community. The structure, the pace, and the
 authors of the documentation all need to create a place that welcomes exploration and
 communication. This proposal is meant to organize and fill in gaps in the current NumPy
 documentation so that new users are educated and welcomed into the community. 

The knowledge that users communicate is gained by testing and experimenting [[4 /5]](Quest
for Certainty + Democracy and Education).  Knowledge depends upon the method of testing
and evaluating. Content that provides clear goals and applications in how-to's provides
new and experienced users guides to approaching new problems. The community can build a
knowledge base enhance skills, facts, and applications. These "how-to" guides provide a
two-fold benefit. First, new and experienced users have a set of clear goals to test and
experiment on. Second, potential documentation contributors have a space to communicate
their goals, methods, and solutions. The how-to space fills an immediate need to make
NumPy's documentation more accessible for new users and possible contributors. 

# Current Knowledge 

* Software documentation is broadly grouped into four spaces [[Divio's
 Documentation System]](https://documentation.divio.com/): 
  * tutorial space
  * how-to space
  * explanation space
  * reference space
* 's explanation and reference space is generated from detailed doc-strings
 in each function
* the tutorial and how-to spaces are not clearly delineated and sometimes enter into the explanation and reference space
* There are excellent tutorials for the "Absolute Beginner" and newcomers with
 Matlab experience


# Gap in the Knowledge Base/Unmet Need 

* The current documentation covers many necessary topics, but lacks clear distinction between tutorial, how-to, explanation, and reference space

* New documentation contributors are faced with hurdles to contribute 

* My goal is to make 's documentation more accessible for newcomers and possible documentation contributors with a logical flow in documentation and building templates for user-contributed How-to's

* My long term goal is to build the documentation community so that learning from the documentation is a give-and-take that experienced users will point new-comers to the .org documentation for help




# Rationale

* I use  in almost all of my courses
* The current documentation is off-putting for new users e.g. my students
* I want to use my experience teaching non-CS majors how to code to help organize, edit, and fill in gaps in the current tutorials
* Then, I can use the  documentation as a textbook for courses
* I have created dozens of tutorials, exercises, and examples using Python and  <github.uconn.edu/rcc02007>. I want to convert some of this material
into Tutorials and How-Tos 
* I have had over 800 students use  (as part of the Scipy stack)
* I have multiple students that are interested in becoming  documentation
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

e.  for Matlab
  
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

## 2. Edit the current tutorials (Beginner's Guide, Array Creation, Indexing, Linear Algebra, and  for Matlab) to move reference information into the Explanation Space. 

_The current tutorials will be shorter and easier to follow. New users will not
be faced with extra information that doesn't directly lead to applying  to
their use cases._

## 3. Build a "How-to" template with one or two examples

  a. Define a problem, create an approach with , and present the solution
  
  b. These will be user-contributed and present use cases that working students
  and professionals can follow
  
  c. The How-to's will be curated with links or tags to functions, classes, etc. 

_New documentation contributors will be able to contribute small use cases to
millions of users without building entire Sphinx documentation. We want to
continue to build our teaching-and-learning community. For essential
how-to's, the content can be added to the core documentation._


* This proposed documentation will mimic current open source documentation such as Matplotlib, Divio, etc. New users and potential contributors will have an easier time learning to apply  in their fields and software. 

# Expected Outcomes

Upon completing this Google Season of Docs I propose the following outcomes:

1. A revised  Documentation Webpage that clearly separates the four spaces:
Tutorials, How-to, Explanation, and Reference

2. Revised Tutorials for: Quickstart Tutorial, Lists from arrays, array
creation, and linear algebra

3. The curated How to space will increase user contributions and help further
the goals of the  community in teaching and learning

The timeline for the project is __9/14-11/30__. Each outcome has a number of steps outlined below in the tables for Outcomes 1-3. The first steps are to build the documentation and separate content in the current tutorials into __Tutorial__ and __Explanation__ content. This will be done in the first three weeks of the project as part of Outcomes 1 and 2-revising the website and tutorials, respectively. 

|__Outcome 1: Revise website__ | Deliverable Date|
|---| ---|
|Fork  Repository and Build Docs with Sphinx| 9/21 |
|Build Webpage with Four Spaces defined and linked| 10/1|
|Move current tutorials into appropriate spaces and Build docs | 10/10 |
|Submit PR to github with proposed changes | 10/20 |
|Respond to comments/suggestions and revise PR | _ongoing with Outcome 2_ |
|Website revised | 11/30 |

|__Outcome 2: Revise tutorials__ | Deliverable Date |
|---|---|
|Rank the tutorials in order of need of revision | 9/21 |
|Separate current tutorial content into __Tutorial__ and __Explanation__ spaces| 10/1|
|Revise rank 1 Tutorial content| 10/10 |
|Submit PR to github for separation and revision| 10/20|
|Revise the rank 2 tutorial submit PR| 11/1|
|Revise the rank 3 tutorial submit PR| 11/15|
|Revise the rank 4 tutorial submit PR| 11/30|
<!--https://.org/devdocs/user/ionumpy.html-->

Proposed ranking of tutorial revisions:

1. Read/Write  arrays __currently empty page__

2. array creation (np.zeros, np.ones, np.block, etc.) __Does not exist: would help new users to have the
common array creation/interaction tools explained and demonstrated__

3. Element-wise and linear algebra operations (`+,-,*,/` and `+,-@,linalg.solve`) __Does
not exist: this
is especially helpful for 1. Matlab users and 2. People adopting  for linear algebra
(machine learning, linear regression, etc.)__

4. TBD

|__Outcome 3: Curated How-to space__| Deliverable Date|
|---|---|
|Build How-to example (either "Transform Vectors with " or "Saving and loading NumPy arrays")|10/20|
|Build How-to template for new contributors| 11/1| 
|Work with other contributors to build How-to notebooks _recruiting UConn students and other community members_ | _7/1 status: work-study approved and applications arriving_ |

# Expected Significance

* New users will stay in the  documentation ecosystem
* Learning   community-driven and 
* Potential documentation contributors will be part of the  community and help build consistent documentation
