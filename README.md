# Survey of history classes in undergraduate Computer Science

A quick hack to get a sense of how much the history of computing is taught on undergraduate CS courses (not much!).

Essentially this a collection of data and an Jupyter Notebook to grep it all, so you can search for whatever terms you like.

Data for the top 10 universities in the world has been collected, and a quick grep/pdfgrep based script in Python is provided for searching.

Very welcome to be proved wrong!

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

Of the top 10 universities in the world, I only found two that had classes dedicated to understanding computing in a wider historical context:

It is common for courses to provide a brief review of the field at the start and will often not be listed in the course description (although Cambridge and Oxford both advertise it in a number of courses). So this is not to say that there is *no* teaching of history within computing, but a larger context, *general* history education seems to be lacking. 


### Carnegie Mellon: *History of Computing*

This course traces the history of computational devices, pioneers and principles from the early ages through the present. Topics include early computational devices, mechanical computation in the 19th century, events that led to electronic computing advances in the 20th century, the advent of personal computing and the Internet, and the social, legal and ethical impact of modern computational artifacts. This course also includes a history of programming languages, operating systems, processors and computing platforms. Students should have an introductory exposure to programming prior to taking this course.

### Berkeley: *The Beauty and Joy of Computing*

An introduction to the beauty and joy of computing. The history, social implications, great principles, and future of computing. Beautiful applications that have changed the world. How computing empowers discovery and progress in other fields. Relevance of computing to the student and society will be emphasized. Students will learn the joy of programming a computer using a friendly, graphical language, and will complete a substantial team programming project related to their interests.

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