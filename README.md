## Course Information

Section A:

- Class Time: 2:00pm-3:15pm Tue Thu
- Location: Green Center Petroleum (PET) Hall

Section B:

- Class Time: 3:30pm-4:45pm Tue Thu
- Location: Green Center Petroleum (PAT) Hall


## Instructors

Section A: Tolga Can, Teaching Professor of CS

- Contact: tolgacan (at) mines (dot) edu
- Office Hours: Wednesdays @12-1pm, Thursdays and Fridays @10:30-11:30am

Section B: Greg Davoll, Adjunct Instructor

- Contact: greg.davoll (at) gmail (dot) com 
- Office Hours: TBD

## Teaching Assistants (TA)

Alexander Chenot

- Contact: achenot (dot) mines (dot) edu

Nora Kelly

- Contact: cameronkelly (at) mines (dot) edu

Ronan Rael

- Contact: rtrael (at) mines (dot) edu

Sabestian Willowhawk

- Contact: swillowhawk (at) mines (dot) edu

TA office hours will be posted.

## Course Overview

In previous courses, you have examined how to write programs in individual languages such as Java or C.
In this class, we will take a broader view of programming languages, and study the key
concepts and techniques that allow developers to *implement* languages such as Java or C.
This will be a project-based course, and we will develop significant experience in this area,
by learning how to use *functional programming* (specifically the OCaml language) to build
(over the course of the semester) a working interpreter for a non-trivial subset of JavaScript.
Ultimately, the course will improve your skill as a programmer, and will deepen your understanding
of how programming languages are designed and implemented.

That understanding will enable you to make better choices as a computer scientist, whether you are programming or designing systems or languages.

## Course Outcomes

Upon completion of this course, it is expected that you would be able to:

* explain programming language theory terms including lexical closure, lexing, parsing, big-step semantics, small-step semantics.
* develop functional programs using the map-reduce idiom.
* implement the expression evaluation core of a programming language.
* evaluate the suitability of mutable and immutable programming approaches for new problems.
* prove the amortized running time for a data structure or algorithm.

## Prerequisites

The prerequisites are [CSCI-306 Software Engineering](http://cs-courses.mines.edu/csci306/index.html) and [CSCI-358 Discrete Math](http://cs-courses.mines.edu/csci358/index.html). As long as you have some programming experience and basic mathematical knowledge, and are comfortable with GitHub, that should be sufficient. If you are in this class and have not completed both classes with a C or better, please contact your instructor immediately.

## Be Prepared...

This is a **difficult** class, for several reasons:
1. We will take a **formal** approach to the topics, i.e., we will carefully develop the mathematical/logical underpinnings of programming languages design and implementation. You may not have seen this level of formality in any other CS class so far.
2. The class is **project-based**, meaning you should expect to devote a significant portion of your effort for this class towards writing code.
3. Virtually all of the code you write will be in the **functional programming language** OCaml. This may be your first exposure to functional programming.
4. Programming languages textbooks are often highly technical. We have tried to collect some of the most easily-digestible materials for your reference, but you may find it difficult to master the material without being actively engaged in the class. Class **attendance and participation are essential**.

## Online Community and Communication

We use [Ed Discussion](https://edstem.org/us/courses/41943/discussion/) as the class online discussion forum for student questions and class communications.
This is a great way to ask questions and communicate with the instructors, teaching assistants,
and your classmates. Participation in online discussions will factor into the Participation component of your grade. Dive in and answer a peer's questions - explaining to others is a great way to deepen your own understanding!

The instructors will use Ed Discussion to communicate with the class. If you have
questions about the course, you should first do a quick search of this syllabus and the class online discussion forum,
to make sure your question has not already been answered. If not, please
go ahead and post your question on the class online discussion forum so that the instructors, the TAs, or another student
can answer it publicly. This will help to streamline communication.

NOTE #1: **neither the instructors nor the TAs will debug your code for you!** If you are
having difficulty with a certain piece of code, take the time to identify what specific
operation(s) is causing unexpected behavior, and ask for help about that. In other words,
posting/emailing your source code is not allowed, but asking questions about language
features or generic code snippets is welcomed. See the CS@Mines Collaboration Policy for further information.

NOTE #2: if you have a question you do not wish to publicize (e.g., about your
grades, etc.), please create a "private post" on the class online discussion forum. This can be directed at just your instructor, or at all instructors and TAs. **Email should only
be used in rare instances where use of the class online discussion forum would not be feasible.**

All grade information will be on [Canvas](https://elearning.mines.edu/)  under our course Gradebook.

Project code distribution will be on Github in our [CSCI 400 Organization](https://github.com/mines-csci400).

isengard, a campus Linux server, can be used for code development (or you can run your own Ubuntu VM on your own device); note you will need to be on campus or using [ITS Remote Access](https://helpcenter.mines.edu/) to access isengard.

## Textbook and Other Reading Materials

NOTE: the following resources are *recommended*, but **NOT REQUIRED**. I will assign
readings from these sources to supplement the lectures, but you are only responsible
for the information presented in lecture.

- [*Functional Programming in OCaml* by Clarkson et al.](https://www.cs.cornell.edu/courses/cs3110/2019fa/textbook/)

Supplemental references (these delve deeper into some topics and provide alternate descriptions of the topics covered in class and the Clarkson text):

- Chris Okasaki. Purely Functional Data Structures. Cambridge University Press. 1998. ISBN-13: 978-0521663502.
- Chris Okasaki. Purely Functional Data Structures. Ph.D. Thesis. CMU-CS-96-177. Carnegie Mellon University. 1996. (A “draft” version of the above book)
- Erik Meijer and Peter Drayton. Static Typing Where Possible, Dynamic Typing When Needed: The End of the Cold War Between Programming Languages
- Robert Trajan. Amortized Computational Complexity. SIAM J. on Algebraic Discrete Methods. Vol 6, No 2, April 1985.
- Benjamin Pierce. Types and Programming Languages. 2002. ISBN-13: 978-0262162098 
- *The Semantics of Programming Languages* by Matthew Hennessy
- Alfred V. Aho, Monica S. Lam, Ravi Sethi, Jeffrey D. Ullman. Compilers: Principles, Techniques & Tools. ISBN-13: 978-0321486813.

Programming References:

- [OCaml Tutorial](https://ocaml.org/learn/tutorials)
- [OCaml Manual](https://v2.ocaml.org/manual/index.html)
- [JavaScript Specification](https://262.ecma-international.org/12.0/)
- [Mozilla Developer Network: JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript)


## Technology Requirements

This course assumes you ar able to access a Linux system (Debian or Ubuntu). isengard is available if your own system is not Linux or if you do not install a virtual machine. Note that Microsoft's WSL should not be used - past students have not had success, and that platform will not be supported by the instructors or TAs.
Use of a non-Linux platform is also not supported.

You are recommended to bring a device to class for coding, note-taking, and electronic communications. This device should be able to access a Linux system for coding and have a web browser for electronic communications. Please contact the instructor if bringing a device to class would present difficulty for you.

## Class Notes

Class notes will be posted 1-2 days after the lecture.
**Posted notes are not guaranteed to provide all information discussed in lecture**
(class attendance is required for this class - see the Warning).

There is a Github organization for the class:
[https://github.com/mines-csci400](https://github.com/mines-csci400)
All of your individual/team repositories will show up there.


## Grading and Evaluation

The course score (percentage) will be computed as a weighted average of scores (points received over points possible) as follows:

| item             | percentage    |
| -----------------|---------------|
| Participation    | 10%           |
| Labs             | 50%           |
| Homeworks        | 10%           |
| Midterm Exam     | 15%           |
| Final Exam       | 15%           |

### Participation 

Participation is a *qualitative* score based on your exhibited effort across worksheets, the class online discussion forum, and in class.

During most lectures, you will have a worksheet to practice the material. After the lecture is complete (i.e., we finish the set of slides corresponding to the worksheet), your worksheet will be submitted at the start of the next class. Late worksheets will not be accepted, electronic submissions will not be accepted, and office hours cannot be used to submit worksheets - class attendance is expected.

### Exams 

There will be a midterm exam around the middle of the semester and a cumulative exam during finals week. The exams are an evaluation tool whose purpose is to produce a distribution of scores across all students that best distinguishes the extent of learning. Thus, please expect the exams to be very challenging.

### Homeworks 

There are 7 homeworks, which will be completed individually.
These are designed to help encourage you to keep up-to-date on the course material.
You will have approximately **1-2 weeks** to work on each homework.

- [Homework 1: Github username](http://github.com/mines-csci400/f23-syllabus)
- [Homework 2: OCaml preliminaries](http://github.com/mines-csci400/f23-syllabus)
- [Homework 3: Lexing & Parsing](http://github.com/mines-csci400/f23-syllabus)
- [Homework 4: Structural induction](http://github.com/mines-csci400/f23-syllabus)
- [Homework 5: Big-step semantics](http://github.com/mines-csci400/f23-syllabus)
- [Homework 6: Recursive functions](http://github.com/mines-csci400/f23-syllabus)
- [Homework 7: Type inference](http://github.com/mines-csci400/f23-syllabus)

### Labs

There will be six labs, programming in OCaml. Lab 1 is completed individually, and Labs 2-6 are completed in groups of 2-3 students. These are worked on in groups to facilitate supporting one another, but each group member will want to understand the full project for the best results on exams.

You will have approximately **1-2 weeks** to work on each lab. This time overlaps with homeworks, be sure to plan accordingly.
The labs increase in difficulty and build upon prior labs, and lab solutions will NOT be provided, meaning you will need to pay
special attention to building a collection of **test cases**, to ensure that bugs in
earlier lab submissions do not propagate into later labs.

You will be given several test cases to check basic code functionality, but **you are responsible
for adding sufficient test cases to ensure that all corner cases have been covered**.
In most cases, you will also be able to use a "black-box" implementation such as the Node.js JavaScript
interpreter to compare with your implementation's behavior.
Buggy behavior will be identified by our own comprehensive set of test cases, and will result in lost points.
Programs which fail to compile will result in a 0 (zero) for the assignment -- no exceptions!
**You are responsible for ensuring that your code is properly submitted and properly compiling
using the toolchain discussed in class**.

- [Lab 1: Learning OCaml](http://github.com/mines-csci400/f23-syllabus)
- [Lab 2: Expression evaluation](http://github.com/mines-csci400/f23-syllabus)
- [Lab 3: Basic JavaScript interpreter](http://github.com/mines-csci400/f23-syllabus)
- [Lab 4: Implementing recursive higher-order functions](http://github.com/mines-csci400/f23-syllabus)
- [Lab 5: Closures, type checking](http://github.com/mines-csci400/f23-syllabus)
- [Lab 6: Objects, mutable variables](http://github.com/mines-csci400/f23-syllabus)

## Letter Grades 

Letter grades will initially be calculated based on the following intervals:

| range    | grade |
|----------|--------------|
| [93,100] | A |
| [90,93)  | A- |
| [87,90)  | B+ |
| [83,87)  | B |
| [80,83)  | B- |
| [77,80)  | C+ |
| [73,77)  | C |
| [70,73)  | C- |
| [67,70)  | D+ |
| [63,67)  | D |
| [60,63)  | D- |
| [0,60)   | F            |

We will *not* perform any rounding on the scores (e.g., a score of 92.999 will not be rounded up to 93).
If warranted, the scale may be expanded or normalized to correspond to university and department norms.
However, skewed student effort may result in correspondingly skewed letter distributions.


## Late Policy 

Late policy: except for worksheets, late submissions are accepted up to 5 days after the deadline, with a penalty of -20% per day applied. Worksheets are not accepted late.

Please take care to manage your time so that you are able to submit your best work by the deadline.
It is import to evaluate all students as evenly as possible. While we will attempt to accommodate disabilities and extenuating circumstances (physical/mental health, school-related travel, and similar) to the greatest possible extend, it would be unfair to offer any further special treatment.

To have late lab code accepted, notify your instructor concerning which GitHub commit is to be graded.

For all items, resubmissions will not be accepted once the due date has passed or a grade has been assigned.

## Grading Corrections 

Grading changes will only be made for grading errors. It is not possible to change grades in response to disagreements about point allocation, partial credit, letter grade cutoffs, etc., because such changes would be unfair to the rest of the class. Grading corrections will only be made for the following errors:

1. _Arithmetic_: The grader incorrectly summed your points. 
2. _Code_: An error in the grading environment or scripts incorrectly tested your code. 
3. _Written_: The grader incorrectly understood your answer.

## Lab Expectations and Grading 

* Labs will include a coding portion and a report portion.
* Code will be graded objectively. Code must produce the correct output to receive credit. Incorrect output, no output, compilation errors, or runtime errors will not receive credit. 
* **Please double-check your submitted code to ensure that minor errors will not result in major test failures.** resubmissions will not be accepted once due dates have passed.
* Code tests will include edge cases. You are responsible for testing your code; we will not supply all the test cases used to grade your code. Think through all possible conditions for your program. 
* Report grading will evaluate your overall understanding for the project area.


## Written Work 

Format and submit your written work as follows. Improper submission or formatting may result in a penalty on assignments.

* For FERPA compliance, all graded work submitted on physical paper must include a cover sheet
on all written work that contains only your name and no answers or other work. Electronic submissions do not need a cover sheet.
* Write your name on every page of all written work. If the work cannot be matched to you, you cannot receive credit for it.
* Include page numbers and total page count in written reports to ensure pages are properly ordered and no pages are overlooked.
* Handwritten work must be _clearly legible_ to receive credit.
* Submit electronic written work in PDF format. Do not submit word processor files because these are inconsistently formatted by different software.
* Lab code will be submitted as code in GitHub. We will not look at work submitted after the cut-off unless a late submission is explicitly requested (see the Late Policy) and the commit to grade identified.
* Work must be readable when printed in black and white. 


## Collaboration

We will use GitHub for submitting code. We will use private individual and team-specific
repositories to submit assignments. Your repositories will show up here:
[https://github.com/mines-csci400](https://github.com/mines-csci400)

The following collaboration guidelines are provided:

* Worksheets may be discussed with others in the class, and work compared. Worksheets allow open collaboration.
* Homeworks are individual - you may not copy or share any part of a solution. However, per the CS collaboration policy, you may consult others under the "empty hands" requirement.
* Labs are a group effort within your group and expect active collaboration within the group. Per the CS collaboration policy, you may consult others under the "empty hands" requirement. Copying any amount of code is considered academic misconduct, as is intentionally modifying copied code.
* Exams are an individual effort. Copying any part of a solution or consulting classmates on an exam is considered academic misconduct.

Please review the full text of the CS@Mines Collaboration Policy for citation requirements when collaboration is used in an assignment (including "empty hands" collaboration).

## Respectfulness and Academic Honesty

Every student is expected to show respect to the instructors and the rest of the class. This course is preparation
for your future career, so make sure you are behaving with the same level of professionalism that
would be expected at a future full-time position. The general rule of thumb is:
**_informal_ is okay, but _disrespectful_ is not**.

- The instructors prefers to be addressed by "Prof. Read"/"Amelia" and "Sumner".
- It is vital that you do your best to participate in the class, and communicate with the instructor(s) about any course-related difficulties you are facing.

Plagiarism/cheating is NOT acceptable, and will be met with the maximum available penalty.
Sophisticated plagiarism-detection software may be used on every submitted assignment, and
all confirmed instances of cheating will be immediately reported to the Computer Science department.
Please ensure that you do not engage in or facilitate academic dishonesty in this class!

Please see the CS@Mines Collaboration Policy concerning what is considered plagiarism in code development work - be sure to use the empty hands policy on any discussion held with others concerning CSCI 400 assignments to avoid any plagiarism issues.

## Accommodation

The Colorado School of Mines is committed to ensuring the full participation of all students in its programs, including students with disabilities. If you anticipate or experience any barriers to learning in this course, please feel welcome to discuss your concerns with me. Students with disabilities may also wish to contact Disability Support Services (DSS) to discuss options to removing barriers in this course, including how to register and request official accommodations. Please visit their website at [https://disabilities.mines.edu](https://disabilities.mines.edu) for contact and additional information.  If you have already been approved for accommodations through DSS, please meet with me at your earliest convenience so we can discuss your needs in this course.

## Schedule

The course schedule is maintained on Canvas and is subject to change.  There will be 6 labs and 7 homeworks, as well as a midterm and a final exam. Lab and Homework due dates are interspersed through the course; pay attention to due dates to ensure you do not miss submitting a lab or a homework on time.


## Acknowledgements

This course is inspired by [Bor-Yuh Evan Chang](http://www.cs.colorado.edu/~bec/)'s fantastic Programming Languages course.
Special thanks to Evan for his advice and assistance. It is heavily based on Jed McClurgh's offering from Fall 2021 (thanks, Jed!)
