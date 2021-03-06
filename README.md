# CSCI551 Inquiry Based Group Project

## Goals
This project has the following goals:

* Students work in a team
* Team sets out to answer a question per student about a topic related to numerical methods or parallel programming. 
* Students find a survey of research work as the starting point of their project
* Students devise a way to test and/or gain understanding about the question they are trying to ask through a hands on implementation of the concept.
	* Should come up with a procedure or method for testing the effectiveness of known solutions or their solutions.
* Students present their findings to the class
* Students write up a document with their findings


## Examples
Examples might be:

* How does the performance of a modern parallel programming language, like [Chapel](https://chapel-lang.org/), [Charm++](http://charmplusplus.org/) or [UPC](https://upc.lbl.gov/) compare to solving the same problem in C++/Python/Rust w/ OpenMPI?
* What alternatives to Apache Spark are there? How does the performance/ease of implementation compare to Apache Spark for a significantly complex problem?
* What is the performance cost of solving the same problem in MPI with Python vs C++?
	* How about with GPUs?
	* How about Python w/ [Numba JIT compilation](https://numba.pydata.org/numba-doc/latest/index.html)?
	* Compiled Python?
	* Rust w/ MPI?
* How might containers like Docker, LXC, rkt, etc impact running MPI, Spark, or other parallel programming approach's performance vs native deployments? 


## Evaluation

Your project will be graded based on the following components.

* Proposal - You need to submit a proposal with the following:
	* Question or topic you want to know more about
	* How you will answer the question/test your understanding
* Papers - You will need to find a minimum of 4 papers that relate to your topic or try to solve the question you are wanting to answer. These cannot all come from the same research group/team.
* Presentation - You will need to give a short 5-10 minute presentation to the class on what you were trying to answer, how you tested, and what findings you discovered
* Lab Check in - There will be a few weeks of class where we'll have open time for you to work with your teams and check in with me about any issues you're running into and so I can see progress is being made. 
* Paper - You will submit a short paper describing what you were trying to answer, how you tested it, the testing results, and what you learned from these results.
* Code - You must submit the code for your project along with the paper submission. 

## Project Submission

At least one member of every team should submit a tar.gz to Tyson's Turnin system, the tar.gz should have the following:

* PDF of your paper that discusses your results, analysis, motivation, conclusions, etc. 
* All of the code for you used for your project. 
	* Alternatively you can add me to a repository with all your code for the project, and just put a README in the tar.gz with the link to this repository. 
