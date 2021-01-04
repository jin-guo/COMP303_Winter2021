# COMP303_Winter2021

## General Information
|   |  |
| :---: | ------------- |
| Instructor    | [Jin Guo](http://jguo-web.com/index.html)  |
| Live Lecture Date and Time    | TR 1:05 pm - 2:25 pm | 
| Lecture Link and Recordings | myCourses |
| Assignments and Forum | GitLab and Discord |

## Teaching Assistant Team

| Name | Email Address |
| :---: | :---: |
| Mathieu Nassif | mathieu.nassif@mail.mcgill.ca |
| Deeksha Arya | deeksha.arya@mail.mcgill.ca |
| Meng Cao | meng.cao@mail.mcgill.ca |
| Jazlyn Hellman | jazlyn.hellman@mail.mcgill.ca |
| Eunbee (Andrea) Jiang | eunbee.jang@mail.mcgill.ca |
| Jintao Guo | jintao.guo@mail.mcgill.ca |
| Marc-Antoine Ouimet | marc-antoine.ouimet@mail.mcgill.ca |
| Karine Song | karine.song@mail.mcgill.ca |


## TA Office Hours
TBD

## Description
This course provides an in-depth introduction to the discipline of software design for building realistic and high-quality software applications. It will focus on object-oriented programming techniques, and cover topics related to managing software complexity and verifying that they work as expected. It will use Java for all the code examples and assignments. However, the considerations during the design process apply in all languages for practical software development.

## Expected Outcome

After completing this course successful students should be able to:

- Properly explain and apply general Design Principles (separation of concerns, encapsulation, substitutability, interface segregation, etc.) and important Design patterns;
- Properly explain and apply design techniques such as UML Diagrams and Design by Contract;
- Effective use programming language mechanisms such as exception handling and reflection;
- Analyze and evaluate the quality of design solutions; correctly identify design smells and apply appropriate refactoring to eliminate them;
- Gain experience on software development tools such as modern IDEs, automatic documentation and testing tools, and version control system.

## Reference Material
- **Required Textbook**: 
  - [Introduction to Software Design with Java (referred to as SD in the schedule)](https://link.springer.com/book/10.1007/978-3-030-24094-3). The electronic version of this book is **free** for McGill users with library access. For those who optionally want a print version, the [Paragraph Bookstore](http://paragraphbooks.com/) will stock a limited number of copies;
  - [Companion Website](https://github.com/prmr/DesignBook) for source code, exercises, and solutions.
- **Other Recommended References:** 
  - [The Pragmatic Programmer (referred to as PP)](https://www.oreilly.com/library/view/the-pragmatic-programmer/9780135956977/), by David Thomas, Andrew Hunt, Addison-Wesley Professional;
  - [Effective Java (referred to as EJ)](https://www.oreilly.com/library/view/effective-java-3rd/9780134686097/), by Joshua Bloch, Addison-Wesley Professional.

- **Sample Projects:** 
  - [Inclass demos](https://github.com/jin-guo/COMP303_CodeDemos);
  - [Minesweeper](https://github.com/prmr/Minesweeper);
  - [Solitaire](https://github.com/prmr/Solitaire).

- **Diagramming Tool (and Sample Project):** 
  - [JetUML](http://cs.mcgill.ca/~martin/jetuml/)

## Prerequisites
COMP 206 and COMP 250. Please also perform the [self assessment](https://github.com/prmr/COMP303/blob/master/Assessment.md) within the first week of the class to determine if you are ready to take this course.


## Assessment and Evaluation (Updated):

|  Assessment Method | Format | Weight |
| :---: | :---: | :---: |
|  Participation | Quiz | 10% |
|  Peer Assessment | GitLab | 15% (5*3) |
|  Design Activities | GitLab and Discord (TBD) | 75% (18*3+21) |

 
- Due to the remote teaching complication, I won't require you to attend the live lectures even though it is recommended. If you are not able to attend the live lectures, please make sure to follow the recordings afterward and complete the quizzes. It will count for your participation grades.
- Our TA will try their best to support your learning. But considering this is a big class – many of you will have similar questions or concerns and many of you have will answers to other people’s questions, we encourage you to discuss your questions about the lectures and exercises online;
- Every module of the lecture will come with [exercises provided by the textbook](https://github.com/prmr/DesignBook). Those are for your practice and will not be graded. Instead, your practical skills will be evaluated through a series of design activities throughout the semester. Those design activities will be either assessed by your peers or our TAs. During the peer assessment, you will be graded by the quality of your reviews and discussions with your peers. The TA assessment will be done in an interactive manner using Discord.
- Any form of plagiarism, cheating is strictly banned during midterm or final exam. Integrity is crucial to this course and your future career. Any violation against academic integrity will be taken very seriously. For more information, please refer [here](https://www.mcgill.ca/students/srr/academicrights/integrity).

## Schedule (Tentative)
*Subject to minor adjustments*

| Lecture | Date | Content | Reading | Exercise | Others |
| :---: |:---:| :---: | :---: | :---: | :---: |
|1	|  7 Jan  | Introduction | SD: Chapter 1| [Exercise 0](https://github.com/jin-guo/COMP303_Winter2020/blob/master/M0-Exercise.md) <br>[Exercise in SD: Chapter 1](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter1.md) | |
|2	|  12 Jan | Encapsulation - 1 | SD: Chapter 2 | [Exercise 1-5 in SD: Chapter 2](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter2.md)| |
|3	|  14 Jan | Encapsulation - 2 | EJ: Item 15-17  | [Exercise 6-9 in SD: Chapter 2 <br>(omit the exercise related to Design by Contract and Assertion which will be introduced later in the course)](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter2.md) | Activity 1 Release|
|4	|  19 Jan | Types and Polymorphism - 1 | SD: Chapter 3 |  [Exercise 1-2 in SD: Chapter 3](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter3.md) | |
|5	|  21 Jan | Types and Polymorphism - 2 | EJ: Item 14 |  [Exercise 3-6 in SD: Chapter 3](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter3.md) | |
|6	|  26 Jan | Types and Polymorphism - 3 | |  [Exercise 7-12 in SD: Chapter 3](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter3.md) | Activity 2 Release|
|7	|  28 Jan | Object State - 1 | SD: Chapter 3, EJ: Item 10, 11 | [Exercise 1-5 in SD: Chapter 4](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter4.md)| |
|8	|  2 Feb | Object State - 2 | EJ: Item 1, 3 | [Exercise 6-11 in SD: Chapter 4](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter4.md)| |
|9	|  4 Feb | Design for Robustness - 1 | PP: Topic 23, 24, 25| | |
|10  |  9 Feb | Design for Robustness - 2 | EJ: Item 69 - 72 | | Activity 3 Release|
|11	|  11 Feb | Content Review (by TAs)| | |
|12	|  16 Feb | Unit Testing - 1 |  SD: Chapter 5  | [Exercise 1-3 in SD: Chapter 5](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter5.md) | |
|13	|  18 Feb | Unit Testing - 2 | | [Exercise 4-11 in SD: Chapter 5](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter5.md) | |
|14	|  23 Feb | Composition - 1 | SD: Chapter 6 | [Exercise 1-5 in SD: Chapter 6](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter6.md) | Activity 4 Release |
|15	|  25 Feb | Composition - 2| | | |
|16	|  9 Mar | Composition - 3 | SD: Chapter 6 | [Exercise 6-19 in SD: Chapter 6](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter6.md) | |
|17	|  11 Mar | Inheritance - 1 | SD: Chapter 7, EJ:Item 19,20| [Exercise 1-5 in SD: Chapter 7](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter7.md) | |
|18	|  16 Mar | Inheritance - 2 | SD: Chapter 7, EJ:Item 18| [Exercise 6-10 in SD: Chapter 7](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter7.md)|  Activity 5 Release|
|19 |  18 Mar | Content Review (by TAs) | |  | 
|20 |  23 Mar | Inversion of Control - 1 |SD: Chapter 8 (8.1-8.7)| [Exercise 1-7 in SD: Chapter 8](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter8.md) | |
|21 |  25 Mar | Inversion of Control - 2 |SD: Chapter 8 (8.1-8.7)| [Exercise 9-11 in SD: Chapter 8](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter8.md)| Activity 6 Release| 
|21 |  30 Mar | Inversion of Control - 3  | | | |
|22 |  1 Apr | TBD | | | | 
|23 |  6 Apr | TBD | | | |
|24 |  8 Apr | TBD | | | |
|25 |  13 Apr | Software Engineering Ethics and Wrap-up | | | Activity 7 Release |

## Quiz links

