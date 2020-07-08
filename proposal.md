# NumPy Documentation for Community Education 

_Google's Season of Docs_

# Introduction

NumPy delivers clean and fast array-based computing in a free open source software
library. It is a fundamental package in the SciPy stack for scientific computing [[1]](https://www.numpy.org). Over 370 thousand projects use  for efficient array computing
[[2]](https://github.com/numpy). NumPy users are greeted by a new website with
applications and case studies [[1]](https://www.numpy.org). When a new user finds the
documentation page, s/he is met with multiple "Start Here" links and introductory
tutorials that can be overwhelming for a beginner, such as [NumPy
Basics/byte-swapping](https://.org/doc/stable/user/basics.byteswapping.html). I began
using NumPy ten years ago in graduate school. I found myself piecing together blog posts,
lecture notes, and StackExchange answers to avoid going through the NumPy documentation.
There are currently over 360 thousand StackExchange conversations that deal with NumPy. 
I imagine other users have had similar routes to success in NumPy. 
The building blocks of educational tools
are communication and community [[4]](https://www.gutenberg.org/files/852/852-h/852-h.htm).
The documentation needs to establish a community  that reflects the desired
goals of the project. The documentation should be consistent, clear guide for a new user.
The tutorials should give new users easy-to-follow steps and build comfort with the
library [[3]](https://documentation.divio.com/).  The documentation
should welcome a new user into the NumPy community. The structure, the pace, and the
authors of the documentation all need to create a place that welcomes exploration and
communication. This proposal will organize and fill in gaps in the current NumPy
documentation so that new users are educated and welcomed into the community. 

The knowledge that users communicate is gained by testing and experimenting [[4,](https://www.gutenberg.org/files/852/852-h/852-h.htm)[5](https://books.google.com/books/about/The_Quest_for_Certainty.html?id=5VcNAAAAIAAJ)].  Knowledge depends upon the method of testing
and evaluating. Content that provides clear goals and applications in how-to's allows users to test and evaluate new ideas and methods. The community can build a
knowledge base enhance skills, facts, and applications. The how-to space provides a
two-fold benefit. First, new and experienced users have a set of clear goals to test and build
experiments. Second, potential documentation contributors have a space to communicate
their goals, methods, and solutions. The how-to space fills an immediate need to make
NumPy's documentation more accessible for new users and possible contributors. 

# Current Knowledge 

John Dewey said that the foundation of learning is a genuine  experience
[[4]](https://www.gutenberg.org/files/852/852-h/852-h.htm). The NumPy community has a
tremendous amount of genuine experience that can be shared with other users. Education is
built upon community and communication. An organized documentation page clears the way for
new users to experience NumPy. It also creates a structured template for potential
contributors to communicate expereriences in NumPy. 

There are four broadly-grouped spaces for software documentation [[3]](https://documentation.divio.com/): tutorial space, how-to space,
 explanation space, and reference space. The NumPy documentation has a number of documents
 in the tutorial space that mix explanation and how-to space content into the tutorial.
 Tutorial space should focus on user education and use easy-to-repeat steps to communicate
 ideas. The how-to space provides more goal-oriented procedures that users can apply in
 real-world applications. The explanation space provides detailed information detailed doc-strings
 in each function. The current tutorial and how-to spaces are not clearly delineated and
 sometimes enter into the explanation and reference space. There is an excellent tutorial
 for the "Absolute Beginner" and there is a great reference for Matlab users to build
 NumPy code in the "Numpy for Matlab users". Clearly delineating these four spaces make the documentation more clear. 



# Gap in the Knowledge Base/Unmet Need 

The current documentation covers many necessary topics, but lacks clear distinction
between tutorial, how-to, explanation, and reference spaces.  This results in confusion
for potential contributors. New users can be overwhelmed by explanation and reference
material in the tutorial section and potential contributors are faced with hurdles to
contribute.  I propose a more accessible layout for newcomers and possible documentation
contributors with a logical flow in documentation and managing pull requests for 
user-contributed how-to documents by new contributors.  My long term goal is to build the
documentation community so that learning from the documentation is a give-and-take
educate-and-communicate experience. This model for documentation will ground education in
actual experience for new comers and potential contributors. 




# Rationale

This Google Summer of Docs proposal is important for my pedagogical and career goals.
I use NumPy and SciPy in almost all of my courses. The current documentation is difficult for my students
to navigate. I want to use my experience teaching non-CS majors how to code to help
organize, edit, and fill in gaps in the current tutorials.  Then, I can use the
documentation as a textbook and reference material for my courses. I have created dozens
of tutorials, exercises, and examples using Python and  <github.uconn.edu/rcc02007>. I
want to convert some of this material into tutorials and how-tos. I have had over 800
students use NumPy (as part of the Scipy stack) and I have multiple students that are
interested in becoming  documentation contributors for the Fall semester. I have been
teaching at University of Connecticut Mechanical Engineering for 4 years and taught over
30 credit-hours of courses. 

#  Specific Aims 

I have three specific aims for this Google Summer of Docs proposal: 
1. Organize the
current documentation, 
2. Edit the current tutorials (Beginner's Guide, Array Creation,
Indexing, Linear Algebra, and NumPy for Matlab) to move reference information into the
Explanation Space, and  
3. Build how-to materials with students. Each specific aim has an
expected outcome for the proposal. 

These three specific aims are meant to make the documentation more welcoming for new users and provide structure for potential contributors. The aims also help to further the long term goal of continuing to grow the NumPy documentation community. 

# Expected Outcomes

I have three expected outcomes as such: 
1. A revised documentation
webpage that clearly separates the four spaces: tutorials, how-to, explanation, and
reference, 
2. new tutorials for: reading and writing arrays, array creation (np.zeros,
np.ones, np.block, etc.), and element-wise vs. linear algebra operation in NumPy, and 
3. a curated how-to space. 
 
These expected outcomes will help new users progress through
documents, provide potential documentation contributors with clear styles and formats,
make current tutorials shorter and easier to follow, move explanations to a separate
section, and new documentation contributors will be able to contribute small use cases to
the how-to section without building entire Sphinx documentation.  We want to continue to
build our teaching-and-learning community.

New documentation contributors can contribute small use cases to
millions of users without building the entire Sphinx documentation. We want to
continue to build our teaching-and-learning community. This proposed documentation will mimic current open source documentation such as Matplotlib, Divio, etc. New users and potential contributors will have an easier time learning to apply NumPy in their fields and software. 

The timeline for the project is __9/14-11/30__. The first step is to build the
documentation and separate content in the current tutorials into __Tutorial__, __How-to__, and
__Explanation__ content. This will be done in the first five weeks of the project as part
of Outcomes 1 and 2-revising the website and tutorials, respectively. The proposed
Documentation organization is shown in the Proposed Documentation below. 

## Proposed Documentation:

### i.Tutorials:

* Absolute basics for beginners (remove installation, can pandas import/export be replaced
  with numpy.loadtxt?) 
  * link to "What is numpy" 
  * link to basic installation instructions here
* Quickstart Tutorial (meant for follow-up to [Python
  tutorial](https://docs.python.org/tutorial/) )
* Working with NumPy arrays 
    * array creation (np.zeros, np.ones, np.block, etc.) (_write: med-low priority_)
    * element-wise operations (`+,-,*,/`) and linear algebra operations (`+,-,@,
      linalg.solve`) (_write:med priority_)
    * Read and write data using Numpy (_write: high priority_)
    * Indexing

### ii. How-to's:
* Linear Algebra on n-dimensional arrays (would love to edit the headings and
  descriptions and maybe change title to "Image processing with Numpy's linear algebra")
* link to [numpy-tutorials](https://github.com/numpy/numpy-tutorials) how-to content (_on-going work_)

### iii. Explanation:

* Data types
* I/O with Numpy
* Indexing
* Broadcasting
* Byte-swapping 
* Structured arrays
* Writing custom array containers
* subclassing ndarray
* Miscellaneous 

### iv. Reference Space:

* Glossary 
* Numpy API Reference 
* Numpy for Matlab users (equivalence table is a great reference table, but
  array/matrix discussion is distracting and seems deprecated)

Upon completing this Google Season of Docs I propose the following outcomes:

1. A revised  Documentation Webpage that clearly separates the four spaces:
Tutorials, How-to, Explanation, and Reference

2. New Tutorials for:  array creation (np.zeros, np.ones, np.block, etc.), element-wise
operations (`+,-,*,/`) and linear algebra operations (`+,-,@, linalg.solve`), and  Read
and write data using Numpy (high priority)

3. Advised how-to documents to increase user contributions and help further
the goals of the  community in teaching and learning

Each outcome has a number of steps
outlined below in the tables for Outcomes 1-3. While the __Proposed Documentation__ is
submitted for review, the high priority "Read/write arrays" tutorial will be written for
submission as a pull request as part of Outcome 2. During the review of the revised
website and updated "Read/Write arrays" tutorial, I will begin writing a tutorial for
creating arrays using NumPy functions e.g. `np.ones`, `np.zeros`, `np.diag`. The remaining
time will be used to respond to pull request issues and start to write the rank 3
tutorial: Element-wise and linear algebra operations in Python. 

The third outcome is to advise students at University of Connecticut to build
documentation in the [numpy-tutorials](https://github.com/numpy/numpy-tutorials)
repository. The submitted tutorials or how-to documents will be Jupyter notebooks that use
NumPy to solve engineering problems. I will use some of my course notes/examples to
submit an example notebook. I will advise students to follow the layout and structure as
we build a [template](https://github.com/numpy/numpy-tutorials/pull/11) and [framing
scheme](https://github.com/numpy/numpy-tutorials/issues/13). This outcome presents a
genuine experience for students to communicate concepts and solutions to a broader
audience. It is a great opportunity for students to get involved with the NumPy community
and learn. 

|__Outcome 1: Revise website__ | Deliverable Date|
|---| ---|
|Fork  Repository and Build Docs with Sphinx| 9/21 |
|Build Webpage with Four Spaces defined and linked| 10/1|
|Move current tutorials into appropriate spaces and Build docs | 10/10 |
|Submit PR to github with proposed changes | 11/1 |
|Respond to comments/suggestions and revise PR | _ongoing with Outcome 2_ |
|Website revised | 11/30 |

|__Outcome 2: Revise tutorials__ | Deliverable Date |
|---|---|
|Review tutorials revision ranking | 9/21 |
|Separate current tutorial content into __Tutorial__ and __Explanation__ spaces| 10/1|
|Write rank 1: Read/Write arrays| 10/10 |
|Submit PR to github for separation and revision| 10/20|
|Write the rank 2: Array Creation PR| 11/15|
|Write the rank 3: Element-wise and linear algebra operations PR| 11/30|
<!--https://.org/devdocs/user/ionumpy.html-->

Proposed ranking of tutorial revisions (subject to change according to mentors/community):

1. Read/Write  arrays __currently empty page__

2. Array creation (np.zeros, np.ones, np.block, etc.) __Does not exist: would help new users to have the
common array creation/interaction tools explained and demonstrated__

3. Element-wise and linear algebra operations (`+,-,*,/` and `+,-@,linalg.solve`) __Does
not exist: this
is especially helpful for 1. Matlab users and 2. People adopting  for linear algebra
(machine learning, linear regression, etc.)__


|__Outcome 3: Curated How-to space__|Deliverable Date|External Link(issue/example)|
|---|---|---|
|Build How-to example (candidate: [How to find natural frequencies of guitar strings](https://github.uconn.edu/rcc02007/CompMech05-BVPs/blob/master/notebooks/03_Good_Vibrations.ipynb) |10/20|
|Build How-to template for new contributors| 10/1 _in progress_|[Tutorial template PR](https://github.com/numpy/numpy-tutorials/pull/11) & [Framing possible contributions](https://github.com/numpy/numpy-tutorials/issues/13) | 
|Work with other contributors to build How-to notebooks _recruiting UConn students and other community members_ | _7/1 status: work-study approved and applications arriving_ |

# Expected Significance

This Google Summer of Docs proposal will make the NumPy documentation , fill in
missing tutorials from the website, and gain documentation contributors. As a Professor in
Mechanical Engineering, I plan to segment the documentation in a way that my students will
be able to navigate the documents and easily find introductory tutorials vs hands-on
how-to guides. The segmented documentation: tutorial, how-to, reference, and explanation
will give potential contributors structured examples to build new resources. The proposed
documentation lends itself to a give-and-take through educate-and-communicate experience for
new and experienced users. The proposed how-to document advising with University of
Connecticut students will put this educate-and-communicate idea to practice. We want all
users to find room to experiment, learn, and join the NumPy community. 

# References


1. [NumPy.org](https://www.numpy.org) website _accessed 07/2020_.
2. [NumPy GitHub repository](https://github.com/numpy). 
3. [The Documentation System](https://documentation.divio.com/). Divio.com _accessed 07/2020_.
4. Dewey, John. [Democracy and Education](https://www.gutenberg.org/files/852/852-h/852-h.htm). Project Gutenberg, Aug. 2015. 