# Survey of history classes in undergraduate Computer Science

A quick hack to get a sense of how much the history of computing is taught on undergraduate CS courses (not much!).

Essentially this a collection of data and an Jupyter Notebook to grep it all, so you can search for whatever terms you like.

Data for the top 10 universities in the world has been collected, and a quick grep/pdfgrep based script in Python is provided for searching.

Contributions welcome!

### Universities:

1. MIT
2. Stanford
3. Oxford
4. Harvard
5. Carnegie Mellon
6. Cambridge
7. Berkeley
8. ETH Zurich
9. Singapore
10. Princeton

## Findings

This has since been updated with contributions, so results are not entirely from the data.

It is common for courses to provide a brief review of the field at the start and will often not be listed in the course description (although Cambridge and Oxford both advertise it in a number of courses). So this is not to say that there is *no* teaching of history within computing, but a larger context, *general* history education seems to be lacking. 


### Carnegie Mellon: *History of Computing*

[course page](http://www.cs.cmu.edu/~tcortina/15292s16/courseinfo.html)

This course traces the history of computational devices, pioneers and principles from the early ages through the present. Topics include early computational devices, mechanical computation in the 19th century, events that led to electronic computing advances in the 20th century, the advent of personal computing and the Internet, and the social, legal and ethical impact of modern computational artifacts. This course also includes a history of programming languages, operating systems, processors and computing platforms. Students should have an introductory exposure to programming prior to taking this course.

### Berkeley: *The Beauty and Joy of Computing*

[course page](http://cs10.org/su16/)

An introduction to the beauty and joy of computing. The history, social implications, great principles, and future of computing. Beautiful applications that have changed the world. How computing empowers discovery and progress in other fields. Relevance of computing to the student and society will be emphasized. Students will learn the joy of programming a computer using a friendly, graphical language, and will complete a substantial team programming project related to their interests.

### Stanford: (2010-2011) *Canon of Computer Science*

[course page](http://graphics.stanford.edu/courses/cs208-11-spring/)

Analysis and discussion of seminal works in computer science. Emphasis on works that changed the course of computing and continue to this day to provoke and stimulate. We will study foundational ideas that are at the core of personal computing, the Web, artificial intelligence, computer system design, computer networks, computer graphics, cryptography, and more.
Through immersion in original literature, we can more deeply comprehend the present state of computing, its origins, its underlying assumptions, and its major open questions. In connecting students with the ideas that shaped computer science, the course aims to instill lasting inspiration and a deep understanding of major trends in the field.

### Princeton (2009-2015) *Great Moments in Computing*

[course page](http://www.princeton.edu/~mrm/EECS583Spring2009syllabus.pdf)

This course will cover pivotal developments in computing, including hardware, software, and theory. Material will be covered by reading seminal papers, patents and descriptions of highlyinfluential architectures. Emphasis will be on developing deep understandings of the discoveries and inventions that brought computer systems to where they are today. Discussion-oriented class will focus on in-depth analysis of readings. Final project or paper required.

### U. Colorado (2000-2016) *Computer Science: The Canon*

[course page](http://www.cs.colorado.edu/~duck/canon2000/)

This will be a "great works" lecture-and-discussion course, focusing on readings that constitute the historical core of computer science. Authors will include Turing, Von Neumann, Goedel, Lovelace, Babbage, Boole, Leibniz, and Shannon; we will also look at more recent works by Karp, Wiener, Brooks, Papert, and Feynman, among others. These readings will be wide-ranging, and a high level of academic curiosity and mathematical fearlessness will be assumed. Students will also have the chance to suggest their own candidates for "classic" status. You should think of this course as an opportunity to encounter, think about, and discuss the ideas that have collectively formed the tradition in which you are working.

### Berkeley (?-2014) *Reading the Classics*

[course page](https://people.eecs.berkeley.edu/~christos/classics/cs298.html)

### Others

#### Oxford

*Intelligent systems* and *Logic and* both give a brief history of their field

#### Cambridge

*Concepts in Programming* looks to have the most in depth history review. 
*Human Computer Interaction*, *Operating Systems*, *Unix Tools*, *Natural Language Processing* all advertise brief reviews.

## Other Notable courses

These are just some of the interesting courses titles that came up while looking through the websites, no doubt others will have been missed by the blunt `grep` search.

- **Harvard:** Great Ideas in Computer Science
- **ETH Zurich:** Science in Perspective 
- **Carnegie Mellon**: Great Theoretical Ideas in Computer Science

## Dependencies

- Python 3
    - BeautifulSoup
    - requests (only for downloading data, which is already included)
- Jupyter notebook
- [pdfgrep](https://pdfgrep.org) or `brew install pdfgrep` on macOS

## Misc

I only gathered the english text I could find for ETH Zurich, they offer some electives in the final year, but the information is in German...