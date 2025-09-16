## General Information
- **Term:** Spring 2025
- **Credits:** 4
- **Prerequisites:** Algorithms (CS-UH 1052) and Software Engineering (CS-UH 2012)
- **Corequisites:** None

## Course Description
This course counts toward the following NYUAD degree requirements:
- Majors > Computer Science
- Minors > Computer Science

One may ask several interesting questions about a given program, such as: 

- Does this program terminate?
- Can the pointer `p` be `null`?
- Will the value of the variable `v` be read in the future?
- Do the variables `x` and `y` point to the same location in memory?
- Could somebody steal the passwords stored in my browser?

 Answering any of these questions about a program is undecidable as stated by Rice's Theorem. However, we can use a technique called program analysis to get approximate answers to those questions by reasoning about the potential runtime behaviour of the program without necessarily executing it. This technique works well for many real-world scenarios. For example, bug finding tools (e.g., SpotBugs) use program analysis to detect, and possibly fix, bugs in a given program. Security analysis tools (e.g., SonarCube, CodeSonar) also use static analysis to detect security vulnerabilities and data leaks.

This course will introduce the main concepts behind program analysis such as intermediate representations, inter-procedural and intra-procedural analysis techniques, call graphs, pointer analysis, and analysis frameworks. The course will also include relevant research papers that introduce both classical and state-of-the-art research in the field. The course will give an overview of the program analyses that work and those that do not work in practice and how to design program analyses for modern software systems.

## Learning Outcomes

| # | Course Learning Outcome (CLO) | PLO1 | PLO2 | PLO3 | PLO4 | PLO5 | PLO6 |
|---|--------------------------------|:----:|:----:|:----:|:----:|:----:|:----:|
| 1 | Reason about the theoretical foundation of program analysis using lattice theory and fix points | Med |  |  | High |  |  |
| 2 | Evaluate the different configuration parameters that affect the performance of program analysis | Med |  |  |  |  |  |
| 3 | Apply program analysis to software security |  | Med |  |  |  |  |
| 4 | Solve a program analysis design problem given a textual description | High | Med |  | High |  |  |
| 5 | Constructively read research papers and distill their main contributions | Med |  |  |  |  | High |
| 6 | Present project proposals |  |  |  |  | High | Med |
| 7 | Report results on project progress both in presentation form and written form |  |  |  |  | High | Med |
| 8 | Use command line tools and GitHub |  | High | High |  |  | High |

## Teaching and Learning Methodologies
1. **Lectures:** In class lectures will cover the fundamental concepts. Most lectures have interactive in-class exercises and discussions and you are expected to participate.
2. **Readings:** The course schedule lists sections of the course textbook that students should read prior to class. By reading the textbook before the lecture, you can better use the lecture: you can clarify concepts you found difficult to understand and you can better participate in class discussions and exercises.
3. **Individual Assignments:** assignments will be an opportunity for students to master concepts by completing a series of problem-solving assignments.
4. **Group Research Paper Seminars:** group presentation that tackle recent and classical research papers about the topic of static analysis will provide an overview of the main challenges that research aim to tackle in the field.
5. **Group Project:** this semester-long effort enable students to embark on a research-oriented project of their choice, done in groups to mimic how realistic projects are done in the real world.
6. **Guest Lectures:** speakers from industry will come to class and provide students with a different perspective about static analysis in real-world settings.

## Graded Activities

| Activity Detail | Grade Percentage | Submission Week | Linked to CLO |
|---|:---:|:---:|:---:|
| Individual Assignments | 35% | 2, 4, 5, 6, 9, 10, 11 | 1, 2, 4, 8 |
| Group Research Paper Seminars | 20% | 10, 11, 12 | 3, 5 |
| Group Project Proposal Presentation | 5% | 9 | 3, 5, 6 |
| Group Project Proposal Document | 5% | 9 | 3, 5, 6 |
| Group Project Final Presentation | 10% | 14 | 5, 7 |
| Group Project Final Document | 20% | 14 | 5, 7 |
| Group Project GitHub Repo | 5% | 14 | 8 |

## Grade Distribution
To get a passing grade in this course, your total grade in the course should be at least 63%. To remain fair to all students who are registered in the course, we will neither curve the final grade, nor will we use historical grade distributions to assign the final letter grades. We will use the following grade cut-offs:

| A | A- | B+ | B | B- | C+ | C | C- | D+ | D | F |
|---|---|---|---|---|---|---|---|---|---|---|
| [100–95] | (95–90] | (90–87] | (87–83] | (83–80] | (80–77] | (77–73] | (73–70] | (70–67] | (67–63] | (63–0] |

## Course Materials

*Required Texts provided by the instructor or library*
- Anders Møller and Michael I. Schwartzbach. *Static Program Analysis.* [Publicly Available](https://cs.au.dk/~amoeller/spa/). (SPA)

*Optional Readings*
- Uday Khedker, Amitabha Sanyal, and Bageshri Karkare. *Data Flow Analysis: Theory and Practice.* CRC Press (Taylor and Francis Group). 2009.
- Flemming Nielson, Hanne Riis Nielson, and Chris Hankin. *Principles of Program Analysis.* 2005.

## Course Schedule

### Notes
- The distribution of lecture content in this schedule is tentative and is subject to change throughout the semester depending on how the flow of each lecture goes.
- All submissions are due at **5pm** on the deadline.

### Legend
- `A`: a course deliverable that **counts** towards your final grade.
- [B](#): a lecture topic.
- C: a text-book reading.

### Topics
- T0: Introduction
- T1: Intermediate Representations
- T2: Intra-Procedural Analysis
- T3: Call Graph Construction
- T4: Pointer Analysis
- T5: Inter-Procedural Analysis
- T6: Context Sensitivity
- T7: Inter-procedural Finite Distribute Subset Problems (IFDS)
- T8: Inter-procedural Distributed Environments (IDE)
- T9: Synchronized Pushdown Systems

### Schedule

<table border="1">
  <thead>
    <tr>
      <th style="text-align: center;">Week</th>
      <th>Monday</th>
      <th>Tuesday</th>
      <th>Wednesday</th>
      <th>Thursday</th>
      <th>Friday</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>20.01-24.01</td>
      <td></td>
      <td></td>
      <td>T0 =&gt; end</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>27.01-31.01</td>
      <td><a href="https://youtu.be/-zyMw_0RmeY" target="_blank">T1 =&gt; end</a><br>[SPA] § 2</td>
      <td></td>
      <td><a href="https://youtu.be/YCNeXeL66WU" target="_blank">T2 =&gt; Intra-procedural analysis</a></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>03.02-07.02</td>
      <td><a href="https://youtu.be/PqpN5vKvAT0" target="_blank">T2 =&gt; Lattice Theory 1</a><br>[SPA] § 4, 5</td>
      <td></td>
      <td><a href="https://youtu.be/WqEm5zn1zUM" target="_blank">T2 =&gt; end</a> + <a href="https://youtu.be/89aLM1et1ds" target="_blank">(cont'd)</a><br>[SPA] § 4, 5</td>
      <td></td>
      <td><code>A1</code></td>
    </tr>
    <tr>
      <td>10.02-14.02</td>
      <td><a href="https://youtu.be/KGNkH7eHU_Y" target="_blank">T3 =&gt; call graph construction</a></td>
      <td></td>
      <td>
        <a href="https://youtu.be/KGNkH7eHU_Y" target="_blank">T3 =&gt; end</a><br>
        <a href="https://youtu.be/8du-qmduhcQ" target="_blank">T3: hands-on</a>
      </td>
      <td></td>
      <td><code>A0.0</code></td>
    </tr>
    <tr>
      <td>17.02-21.02</td>
      <td><a href="https://youtu.be/OEFpWWnyVo4" target="_blank">T4 =&gt; end</a><br>[SPA] § 11</td>
      <td></td>
      <td><strong>No Class</strong></td>
      <td></td>
      <td><code>A2</code></td>
    </tr>
    <tr>
      <td>24.02-28.02</td>
      <td><a href="https://youtu.be/Is9yqpNFQhQ" target="_blank">T5 =&gt; end</a><br>[SPA] § 8</td>
      <td></td>
      <td><a href="https://youtu.be/wgnbTv-kNAU" target="_blank">T6 =&gt; end</a><br>[SPA] § 8</td>
      <td></td>
      <td><code>A3</code></td>
    </tr>
    <tr>
      <td>03.03-07.03</td>
      <td><a href="https://youtu.be/y7iLreS37MA" target="_blank">T7 =&gt; end</a> + <a href="https://youtu.be/lJbiwYa6mVM" target="_blank">(cont'd)</a><br>[SPA] § 9</td>
      <td></td>
      <td><a href="https://youtu.be/76x95LO-NI0" target="_blank">T8 =&gt; end</a><br>[SPA] § 9</td>
      <td></td>
      <td>
        <code>A4</code><br>
        <code>A0.1</code>
      </td>
    </tr>
    <tr>
      <td>10.03-14.03</td>
      <td>T9 =&gt; end<br>[SPA] § 9</td>
      <td colspan="4" style="text-align: center;">
        <strong>&lt;= No Classes =&gt;</strong>
      </td>
    </tr>
    <tr>
      <td>17.03-21.03</td>
      <td>T9: hands-on</td>
      <td></td>
      <td>How to Present!</td>
      <td></td>
      <td><code>A5</code></td>
    </tr>
    <tr>
      <td>24.03-28.03</td>
      <td>Office Hours (Presentations)</td>
      <td></td>
      <td><code>Proposal Presentations</code></td>
      <td></td>
      <td><code>Proposal Document</code></td>
    </tr>
    <tr>
      <td>31.03-04.04</td>
      <td colspan="5" style="text-align: center;">
        <strong>&lt;= Eid Al-Fitr Holiday =&gt;</strong>
      </td>
    </tr>
    <tr>
      <td>07.04-11.04</td>
      <td><code>Paper Seminars</code></td>
      <td></td>
      <td><code>Paper Seminars</code></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>14.04-18.04</td>
      <td><code>Paper Seminars</code></td>
      <td></td>
      <td><code>Paper Seminars</code></td>
      <td></td>
      <td><code>A6</code></td>
    </tr>
    <tr>
      <td>21.04-25.04</td>
      <td><code>Paper Seminars</code></td>
      <td></td>
      <td><code>Paper Seminars</code></td>
      <td></td>
      <td><code>A7</code></td>
    </tr>
    <tr>
      <td>28.04-02.05</td>
      <td>Guest Lecture</td>
      <td></td>
      <td>Guest Lecture</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>05.05-09.05</td>
      <td><code>Final Presentations</code></td>
      <td></td>
      <td><code>Final Presentations</code></td>
      <td></td>
      <td><code>Final Report</code></td>
    </tr>
  </tbody>
</table>

## Paper Discussions
Most in-class paper discussions suffer from the lack of attention from most students except the presenter. To provide a more interactive environment for the paper discussions in this course, student will take the following roles:

*   **Presenter** (20 mins): give a presentation about the paper.
*   **Historian** (10 mins): position the paper in the context of related work (either prior to the paper, or later work that extends/critiques the paper). You will present your findings in class.
*   **Reviewer** (10 mins): review the paper as if you are serving on the Program Committee. Tell us why the committee should accept/reject the paper. These are some useful links that contain tips on how to read and review academic papers: [link1](http://www.cgl.uwaterloo.ca/smann/Research/review-conference.txt), [link2](http://homes.cs.washington.edu/~mernst/advice/meier-paper.review.html), [link3](http://www.cl.cam.ac.uk/~ey204/teaching/ACS/R212_2015_2016/aid/stevens.pdf), [link4](http://library.queensu.ca/inforef/criticalreview.htm), [link5](http://cseweb.ucsd.edu/~wgg/CSE210/howtoread.html).
*   **Researcher** (10mins): propose one project that extends or is inspired by the work discussed in the paper, and is related to your research area (for grad students). Pitch that project idea to us in class!
*   **Validator** (20 mins): search for, download, and validate any artifacts that are published with the work (e.g., an official artifact, source code available on the internet, scripts to mine data/code, proofs, tools, survey data/methodology). If you can't find anything online, contact the authors. In class, you will walk us through your findings, and demo any tools that were published with the paper.
*   **All students**: come up with one question about the core ideas presented in the paper, and pose that question during class.

Each paper discussion will end with a 10-minute open discussion to open the floor to further questions from the audience.

*Note: this structure is inspired by the [Machine Learning for Interactive Systems and Advanced Programming Tools Seminar at ETH](https://ait.ethz.ch/teaching/courses/2016-FS-ML-IS-PL/).*
