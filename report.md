# NumPy documentation for community education 

# Google's Season of Docs - Project Report

The building blocks of educational tools are communication and community
[[1]](https://www.gutenberg.org/files/852/852-h/852-h.htm).  Great
documentation needs to establish a community  that reflects the desired
goals of the project. This project accomplished three specific aims to
communicate NumPy ideas and philosophy to the community.

##  Specific aims 

I had three specific aims for this Google Season of Docs (GSoD) project: 
1. Organize the current documentation 
2. Edit the current tutorials and move reference information into the
Explanation Space 
3. Build tutorials to grow the NumPy community. 

Each specific aim has an outcome for the project.  These three
specific aims made the documentation more welcoming for new users and
provided structure for potential contributors. The aims also helped to
grow the NumPy documentation community, a longer term goal. 

## Project outcomes

I had three outcomes from this Google Season of Docs project: 
1. A revised documentation
webpage that separates the four spaces: tutorials, how-to, explanation, and
reference 
2. Write new tutorials and explanations 
3. Build a curated tutorial space for new contributors 
 
These outcomes help new users progress through documents,
provide potential documentation contributors with clear styles and
formats, built new tutorials that are easy to follow, moved
explanations to its own section, and new documentation contributors
will be able to contribute small use cases to the [NumPy
Tutorials](https://github.com/numpy/numpy-tutorials) without
building the entire Sphinx documentation. I focused on user involvement
while building the teaching-and-learning community. 

### Outcomes overview

Since the project started, I have

- participated in 8 NumPy documentation team calls [hackmd
  minutes](https://hackmd.io/@rgommers/HJfE0Sq7H)
- participated in 7 NumPy community calls [hackmd
  minutes](https://hackmd.io/76o-IxCjQX2mOXO_wwkcpg?view)
- posted over 100 messages on the NumPy Slack channel
- opened 13 PRs with 10 closed
- opened 8 issues with 4 closed
- made 7 reviews on community PRs
- mentored 3 new NumPy users developing NumPy tutorials [UConn NumPy
  Tutorials](https://github.com/cooperrc/uconn_numpy_tutorials)
- at [NumPy tutorials](https://github.com/numpy/numpy-tutorials) made 22
  commits with 3,847 lines added and 1,426 deleted 

The activities listed above demonstrates the close connection NumPy
documentation has with community involvement. Conversations in Slack led
to tutorial ideas and documentation revisions. 

### Specific outcomes - tied to specific aims

Here, I list the issues and pull requests (PRs) submitted in
connection to GSoD. I relate each issue and PR to specific aims.

The first goal was to fork the NumPy repository and build the
documentation. This was doen during the community-bonding phase of the
program. I open and closed my first NumPy issue

- [Building Documentation in a conda environment (Arch
  Linux)](https://github.com/numpy/numpy/issues/17016)



#### 1. Organize the current documentation 

Organizing the documentation was my first specific aim, but it turned
into the most difficult task. The documentation has several layers and
interrelated documents; documentation includes the numpy.org [stable
docs](numpy.org/stable/doc), the [NumPy user
guide](https://numpy.org/doc/stable/numpy-user.pdf), and the [NumPy
reference guide](https://numpy.org/doc/stable/numpy-ref.pdf). By the end
of GSoD, I had determined a reorganization and doable strategy to get
the main [stable docs](numpy.org/stable/doc) organized and reorganize
the [NumPy user guide](https://numpy.org/doc/stable/numpy-user.pdf).

I laid out my reorganization process in three steps, detailed in 

__issue__:
- [Update Landing page and table of contents -
  devdocs](https://github.com/numpy/numpy/issues/17845)

The first step is under review in the
__PR__:
- [renamed basics to fundamentals + added
  description](https://github.com/numpy/numpy/pull/17889)

I will finish responding to reviews and submit the next two steps of the
reorganization after we merge PR 17889. I am actively engaged with the
NumPy documentation team to respond to reviews and finish adding the
next two pull requests. We decided, in issue #17845, to reorganize in
stages. The PR reviews are easier with smaller changes.


##### 2. Edit the current tutorials and move reference information into the Explanation Space 

Editing current tutorials and reference material was my first goal,
after recognizing the complexity of the NumPy documentation.  I updated
two core NumPy documentation files and one NumPy tutorials file and
created two new NumPy tutorials. Building these improvements had two
crucial effects I was more engaged with the NumPy community and the
improvements guided discussions for reorganizing content in the first
specific aim. This second specific aim led to three issues and five pull
requests as such

__issues__:
- [Need to update NumPy for Matlab users
  documentation](https://github.com/numpy/numpy/issues/17094)
- [DOC: request for tutorial saving and loading NumPy
  arrays](https://github.com/numpy/numpy/issues/17266)
- [update Array creation
  document](https://github.com/numpy/numpy/issues/17710)

__PRs__:
- [DOC: Update numpy4matlab](https://github.com/numpy/numpy/pull/17159)
- [DOC: Use official MATLAB spelling in
  numpy-for-matlab-users.rst](https://github.com/numpy/numpy/pull/17215)
- [adding tutorial for creating Moore's law linear
  regression](https://github.com/numpy/numpy-tutorials/pull/31)
- [Save load arrays - Created a short tutorial to create, save, and load
  arrays using savez, savetxt, load, and
  loadtxt](https://github.com/numpy/numpy-tutorials/pull/34)
- [DOC: update arraycreation](https://github.com/numpy/numpy/pull/17887)

Ongoing work involves two open pull requests as of 12/5/2020 #17887 and #17889. I am
actively engaged with the NumPy documentation team to respond to
reviews and finish implementing the changes. 

#### 3. Build tutorials to grow the NumPy community

This specific aim was to grow the NumPy community using documentation. I
participated in NumPy community calls, NumPy documentation team  
calls, reviewed materials, reached out to other free open source
software groups, and mentored three UConn students developing
tutorials. I helped manage the [NumPy tutorials
repository](https://github.com/numpy/numpy-tutorials) and built a
[Jupyter Book
branch](https://github.com/cooperrc/numpy-tutorials/tree/numpybook) of
the repository. We wanted a space for users to share their experience
and domain expertise, without rebuilding the NumPy code and Sphinx
documentation. This space has successfully had six documents submitted
for review by the broader NumPy community. This space also created room
for @8bitmp3 to detail machine learning methods using NumPy. 

__issues__:
- [planning-onboarding-material: preparing video content for
  onboarding](https://github.com/BIDS-numpy/planning-onboarding-material/issues/4)

__PRs__:
- [Contribute Myst-NB with jupytext](https://github.com/numpy/numpy-tutorials/pull/48)

My students at UConn have developed four tutorials. They will 
submit pull requests before the winter break. We have been working
together at the [UConn NumPy
tutorials](https://github.com/cooperrc/uconn_numpy_tutorials)
repository. 

Building the Jupyter Book branch of NumPy tutorials led to bug fixes and
further documentation development with [Executable
Books](https://github.com/executablebooks)

__issues__:
- [Building launch links for binderhub and
  jupyterhub](https://github.com/executablebooks/jupyter-book/issues/1061)
- [Add details for deploying jupyterbook to binderhub and
  jupyterhub](https://github.com/executablebooks/jupyter-book/issues/1062)
__PRs__:
- [DOCS: Update gh-pages.md for
  hosting](https://github.com/executablebooks/jupyter-book/pull/1096)
- [DOCS: update instructions for using w/ jupyterhub and
binder](https://github.com/executablebooks/jupyter-book/pull/1097)


## Conclusion

In conclusion, I have successfully reorganized the NumPy documentation,
added tutorials and created explanation and reference spaces, and helped
to grow the NumPy community. This documentation needs constant
attention.  Community involvement is crucial to NumPy's documentation.
The NumPy documentation team is welcoming and supportive. There are
dozens of tasks left to build the NumPy documentation that require
communication, community, and education. This GSoD program was a great
start. The project needs further support and involvement from diverse
backgrounds. 
