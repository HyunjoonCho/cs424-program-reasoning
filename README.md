# CS424: Program Reasoning (프로그램 논증)

## Logistics
- Instructor: [Kihong Heo](https://kihongheo.kaist.ac.kr) (허기홍, kihong.heo@prosys.kaist.ac.kr)
- TAs (mailing list: cs424.ta@prosys.kaist.ac.kr)
  - [Sujin Jang](https://sujin0529.github.io) (장수진)
  - Changgong Lee (이창공)
- Time: Mon/Wed 09:00 - 10:15
- Office hours (by appointment):
  - Instructor: Mon 10:15 - 11:00
  - TAs: Mon 10:15 - 11:00
- Location: N1 102

## Course Description
The main theme of this course is __"the relationship between specification and implementation"__ for safe and reliable software.
This course will cover two topics under the theme:
1. **program verification**: how to automatically _prove_ whether a given implementation satisfies the specification,
2. **program synthesis**: how to automatically _generate_ an implementation that satisfies the specification.

Students will learn theories and practices of program verification and synthesis through lectures, and assignments.

## Grading
- Homework: 50%
- Final Exam: 40%
- Participation: 10%

## Note
- This course DO NOT allow for P/NR grading.
- Freshmen can enroll in this course only if they have prior approval by the instructor. Send an email to the instructor for the approval.

## Textbook
- Lecture slides will be provided
- [Program Synthesis](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/10/program_synthesis_now.pdf) (PS)
- [Introduction to Program Synthesis](https://people.csail.mit.edu/asolar/SynthesisCourse/index.htm) (IPS)
- [The Calculus of Computation](https://www.amazon.com/Calculus-Computation-Procedures-Applications-Verification/dp/3540741127) (COC)

## Homework
This course includes programming assignments through which students will learn how to design
and implement program synthesizers and program verifiers.
Students will use a few tools which are described [here](TOOL.md).

All submissions will be managed using Github.
For each assignment, a unique invitation URL for GitHub Classroom will be posted in the [discussion board](../../discussion).
Once you accept the invitation, a private repository for your assignment will be created.
You can push as many commits as you want before the deadline. We will grade the final commit of your `master` branch.

The late homework policy is as follows:
- 80% credit for one day late
- 50% credit for two days late
- NO credit given after two days late

## Academic Integrity Violation
Students who violate academic integrity will get an F.
See [the KAIST CS honor code](https://docs.google.com/forms/d/e/1FAIpQLSdSn63tEvq6R0G6n3Cz7jKX16RWvDy2giBKm8EVJtQHUBJoDA/viewform).

## Schedule
|Week|Topics|Reading|Homework|
|-|------|-------|--------|
|0|[Functional Programming in OCaml](slides/lecture0.pdf)||<img src="icons/github-classroom.png" width="16" />HW0: Hello-world, OCaml Programming|
|1|[Introduction](slides/lecture1.pdf)|<img src="icons/youtube.png" width="16" /> Undecidability [<img src="icons/kor.png" width="16" />](https://youtu.be/oippSXvxUlw) [<img src="icons/eng.png" width="16" />](https://www.youtube.com/watch?v=HeQX2HjkcNo&t=2)|||
|2|[Operational Semantics](slides/lecture2.pdf)||<img src="icons/github-classroom.png" width="16" />HW1: SmaLLVM Interpreter|
|3|[Concepts in Program Verification](slides/lecture3.pdf)|||
|4|[Propositional Logic](slides/lecture4.pdf)|COC Ch1, <img src="icons/youtube.png" width="16" /> [Curry-Howard Correspondence](https://cs3110.github.io/textbook/chapters/adv/curry-howard.html)|
|5|[First-order Logic](slides/lecture5.pdf)|COC Ch2|
|6|[First-order Theory](slides/lecture6.pdf)|COC Ch3|<img src="icons/github-classroom.png" width="16" />HW2: Automated Theorem Proving|
|7|[Hoare Logic](slides/lecture7.pdf)|COC Ch5, [CACM'21](https://cacm.acm.org/magazines/2021/7/253452-formal-software-verification-measures-up/fulltext)||
|8|[Automated Program Verification](slides/lecture8.pdf)||<img src="icons/github-classroom.png" width="16" />HW3: SmaLLVM Verifier|
|9|[Overview of Program Synthesis](slides/lecture9.pdf)|PS Ch1-2, IPS Lec1, [Wired](https://www.wired.com/story/ai-write-code-like-humans-bugs/), [IEEE Spectrum](https://spectrum.ieee.org/ai-code-generation-language-models), [CACM](https://cacm.acm.org/magazines/2022/10/264844-neurosymbolic-ai/fulltext)||
|10|[Inductive Synthesis and Enumerative Search](slides/lecture10.pdf)|PS Ch4.1, IPS Lec2-4|<img src="icons/github-classroom.png" width="16" />HW4: LIA Synthesizer|
|11|[Search Space Pruning](slides/lecture11.pdf)|||
|12|[Search Space Prioritization](slides/lecture12.pdf)|[CACM'18](https://cacm.acm.org/magazines/2018/12/232879-search-based-program-synthesis/fulltext)||
|13|[Representation-based Search](slides/lecture13.pdf)||<img src="icons/github-classroom.png" width="16" />HW5: SLIA Synthesizer|
|14|[Constraint-based Search](slides/lecture14.pdf)|||
|15|[Functional Synthesis](slides/lecture15.pdf)||<img src="icons/github-classroom.png" width="16" />HW6: CEGIS|
|16|[Program Synthesis as AI](slides/lecture16.pdf)|[Trustworthy AI](https://prosys.kaist.ac.kr/trustworthy/)||
|-|Final Exam|||
## Hall of Fame
Have fun with student artifacts from previous semesters [here](hof.md) (distinguished essays, drawings, etc).

## Related & Advanced Course
- [CS402: Introduction to Logic for Computer Science](https://github.com/hongseok-yang/logic23), KAIST
- [CS524: Program Analysis](https://github.com/prosyslab-classroom/cs524-program-analysis), KAIST

## Acknowlegement
A large part of the slides is based on the lecture notes of similar courses:
- [CS389: Automated Logical Reasoning](https://www.cs.utexas.edu/~isil/cs389L/), Univ. of Texas at Austin
- [AAA528: Computational Logic](http://prl.korea.ac.kr/~pronto/home/courses/aaa528/2018/), Korea Univ.
- [CSE291: Program Synthesis](https://github.com/nadia-polikarpova/cse291-program-synthesis), UCSD
- [CSE9116: Program Synthesis](http://psl.hanyang.ac.kr/courses/cse9116_2022s/), Hanyang Univ.

## References
- [PL Wiki](https://github.com/prosyslab/pl-wiki/wiki)
- [Search-based Program Synthesis](https://cacm.acm.org/magazines/2018/12/232879-search-based-program-synthesis/fulltext), CACM 2018
- [AI Can Write Code Like Humans—Bugs and All](https://www.wired.com/story/ai-write-code-like-humans-bugs/). Wired 2021
- [Coding Made AI—Now, How Will AI Unmake Coding?](https://spectrum.ieee.org/ai-code-generation-language-models), IEEE Spectrum 2022
- [Neurosymbolic AI](https://cacm.acm.org/magazines/2022/10/264844-neurosymbolic-ai/fulltext), CACM 2022
- [Formal Software Verification Measures Up](https://dl.acm.org/doi/10.1145/3464933), CACM 2021
- [Autocorrect Errors in Excel](https://www.nature.com/articles/d41586-021-02211-4), Nature 2021
- [Trustworthy AI](https://prosys.kaist.ac.kr/trustworthy/)
- [Automated Reasoning @ Amazon](https://www.amazon.science/blog/?q=&f0=0000017d-6ba3-ddaa-a97d-efa3e2ed0000&s=0&expandedFilters=Research%2520area%2CTag%2CConference%2CAuthor%2CDate%2C)
