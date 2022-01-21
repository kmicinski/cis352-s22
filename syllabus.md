---
title: Syllabus
layout: default
---

## Programming Languages: Theory and Practice
(*CIS 352* at Syracuse U)

**Note**: parts of this syllabus are subject to change with adequate
notice to students.

An introduction to the design and implementation of programming
languages, focused on operational semantics and interpreters. This
course is heavily project-focused, and a specific emphasis will be
placed upon training in algorithmic thinking and programming strategy.

**Workload**:
  - Asynchronous video lecture units (at most ~80min per week)
    - We assume you have watched the videos before class
  - Participation points:
    - Quiz before each lecture (closes as lecture begins)
    - See other sources of participation below
  - 5 projects
  - 4 in-person quizzes (80 minutes, on paper) and a final (120 minutes, on paper)
  - This will be a project-focused course. Approximately 3-5 hours per
    week outside of class is expected. I recommend against taking this
    course concurrent with other project-heavy courses.

**No Monday Labs**:
 - As a 3-credit course, Monday labs are not required as part of the
   curriculum. Instead, the professor and TAs will likely plan to hold
   some Monday office hours instead.

## Grading

Grading has been simplified compared to previous offerings of
CIS352. For Spring 2022, there are only two major components to the
grade: exams and projects, which are both grade on a percent
scale. Participation possibly adds a "plus" (i.e., A- to A), a
"minus," (A to A-) or no change at all (B remains B) to the grade
based how much participation is done.

There is a detailed chart below explaining the grading policy, but it
is roughly this: (a) there are exams and projects, (b) if you get at
least an 80% in one category and at least a 90% in the other, you will
get an A (and so on), (c) if you get fewer than 20 participation
points, you will get a "minus" taken from your grade in (b), [20-30)
participation points will cause no change, and >=30 participation
points will add a "plus" to the grade. Note that there is no A+,
however, the professor will track this information for recommendation
letters and references.

### Informal Grading Rules for CIS352

- Your grade consists of participation, projects, and quiz / exam
  questions.
- The bulk of this is projects and exams, and most of your time will
  be spent on projects.

Project Grading:
- Projects are graded on a percentage basis, based on the number of
  passing tests (including some hidden tests).
- Projects are graded via the autograder. You may submit as many times
  as you like up until 11:59PM on the day of the project's
  deadline. However, the autograder will rate-limit you by providing
  you with a set number of tokens per day.

Exam Grading:
- There are 12 exam questions, and *every* quiz/exam is
  cumulative. Each of the twelve questions will cover the same rough
  topics (learning objectives), and you will always get the *maximum*
  grade throughout the entire course on a project.
  - As an example, if you get 4/5 points on question 1 on quiz 1, and
    5/5 points on question 1 (different question, same topic) on quiz
    2, you will have achieved the max score on question 1 and need not
    reattempt it in the rest of the course.
- There will be 4 in-person "quizzes" that take the whole class
  period. They will be in class roughly every few weeks.
  - You may submit up to *six* answers per quiz.
- There will be a cumulative final where you will see (again) all 12
  exam questions. You may submit up to *eight* answers on the final
  (to raise your previous grade on each of eight questions, possibly
  to 100% for that question)

Participation:
- There are many opportunities for participation points, outlined
  below. You need at least 20 in the course, otherwise you will get a
  "minus" (e.g., A to A-). If you get more than 30 participation
  points, you get a "plus" (e.g., A- to A).

Final Grading:
- Finally, your grade is given using the table below based on the
  higher and lower of your exam / project grades. Roughly: you will
  get an A with 80% in one category (exams/projects) and 90% in the
  other (and so on at 2-3-point intervals), and then a
  plus/minus/no-change will be taken based on participation.

Example:
- Janice gets an average of 85% on the projects, as reported by the
  Autograder. Janice gets a 87% on the exams, as reported by
  BlackBoard. Janice would get an A-, but also has 31 participation
  points, so gets an A.

<div class="container">
  <div class="row">
    <div class="leftside">
      <table class="table table-sm table-striped grade-table table-hover">
        <thead>
          <tr class="gradestop">
            <th class="projdesc" colspan="1" scope="col"><strong>Projects/Exams (Higher)</strong></th>
            <th class="examdesc" colspan="1" scope="col"><strong>Projects/Exams (Lower)</strong></th>
            <th scope="col">Grade</th>
          </tr>
        </thead>
        <tbody>
          <tr id="gradea">
            <td class="lggradecol">90</td>
            <td class="lggradecol">80</td>
            <th scope="row">A</th>
          </tr>
          <tr id="gradeam">
            <td class="lggradecol">87</td>
            <td class="lggradecol">77</td>
            <th scope="row">A-</th>
          </tr>
          <tr>
            <td class="lggradecol">85</td>
            <td class="lggradecol">75</td>
            <th scope="row">B+</th>
          </tr>
          <tr>
            <td class="lggradecol">83</td>
            <td class="lggradecol">73</td>
            <th scope="row">B</th>
          </tr>
          <tr>
            <td class="lggradecol">80</td>
            <td class="lggradecol">70</td>
            <th scope="row">B-</th>
          </tr>
          <tr>
            <td class="lggradecol">77</td>
            <td class="lggradecol">67</td>
            <th scope="row">C+</th>
          </tr>
          <tr>
            <td class="lggradecol">74</td>
            <td class="lggradecol">64</td>
            <th scope="row">C</th>
          </tr>
          <tr>
            <td class="lggradecol">70</td>
            <td class="lggradecol">60</td>
            <th scope="row">C-</th>
          </tr>
          <tr>
            <td class="lggradecol">60</td>
            <td class="lggradecol">50</td>
            <th scope="row">D</th>
          </tr>
          <tr>
            <td class="lggradecol">&lt; 60</td>
            <td class="lggradecol">&lt; 50</td>
            <th scope="row">&lt;D</th>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="rightside">
      <!-- <div id="projectquestions"> -->
      <!--   <h5 class="pcardtitle">Projects</h5> -->
      <!--   <div id="projects" class="egrade" grade="A"> -->
      <!--     <svg width="100" height="100" viewPort="0 0 100 100" version="1.1" xmlns="http://www.w3.org/2000/svg"> -->
      <!--       <circle class="pfail" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--       <circle class="pminimal" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--       <circle class="psat" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--       <circle class="pex" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--     </svg> -->
      <!--   </div> -->
      <!--   <p class="points"> -->
      <!--     3 <strong class="ex">Excellent</strong> -->
      <!--     &nbsp;5 <strong class="sat">Satisfactory</strong> -->
      <!--   </p> -->
      <!--   <p class="points" id="min">6 <strong class="min">Minimal</strong></p> -->
      <!-- </div> -->
      <!-- <div> -->
      <!--   <div id="examquestions"> -->
      <!--     <h5 class="pcardtitle">Exam Questions</h5> -->
      <!--     <div id="exams" class="egrade" grade="A"> -->
      <!--       <svg grade="A" class="gpa" width="100" height="100" viewPort="0 0 100 100" version="1.1" xmlns="http://www.w3.org/2000/svg"> -->
      <!--         <circle class="efail" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--         <circle class="esat" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--         <circle class="eex" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--       </svg> -->
      <!--     </div> -->
      <!--     <p class="points"> -->
      <!--       6 <strong class="ex">Excellent</strong> -->
      <!--       &nbsp;12 <strong class="sat">Satisfactory</strong> -->
      <!--     </p> -->
      <!--   </div> -->
      <!-- </div> -->

      <table class="table table-sm table-striped grade-table participation">
        <thead>
          <tr class="gradestop">
            <th scope="col"><strong>Participation</strong></th>
            <th scope="col"><strong>GPA Δ</strong></th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="smgradecol">&lt; 20</td>
            <th scope="row">-</th>
          </tr>
          <tr>
            <td class="smgradecol">&geq; 20 &ndash; &lt; 30</td>
            <th scope="row">=</th>
          </tr>
          <tr>
            <td class="smgradecol">&geq; 30</td>
            <th scope="row">+</th>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>


#### Projects

There are *five programming projects* in the Racket programming
language. Projects will generally have deadlines of roughly 12
calendar days from their assignment (though this may be adjusted at
times). Projects will be graded using an *autograder* whose URL is
[https://autograder.org](https://autograder.org). You will receive
credentials for the autograder--if you have not received these by the
first day of class, let Chang (TA) know. You are expected to learn how
to use the Git interface to the autograder--the autograder will
technically accept archives, but the instructors strongly prefer
students (and will exclusively help support) using Git.

##### Project Late Policy

- Projects turned in within 72 hours of the deadline will receive a 15
  percent penalty. Projects turned in after 72 hours and until the end
  of the course will receive a 25 percent penalty.

#### Exams

Exams explicitly measure your ability to materialize solutions to
questions regarding relevant course content in an open-ended
fashion. There will be four "quizzes" through the semester, each of
which will have up to 12 questions, based on the number of topics
presented so far in the course. Each exam will be cumulative, and for
each question number N (between 1 and 12) the content will be roughly
the same with a different question. These questions correspond to the
learning objectives (see top of page).

You will always get your *maximum* grade on any one problem. You can
keep submitting (say) problem 5 until you either run out of chances
(the final) or achieve full marks on that question.

We see in-person exams as a crucial counterpart to coding projects in
determining the course grade. We recognize exams can be stressful. It
is our intention that our grading scheme (frequent quizzes that allow
you to raise your score after several attempts at the same material,
along with the fact that a lower score in exams may be offset by
project grades) will help assuage exam-related stress. However, the
instructors strongly encourage students to look into the resources
provided by the Barnes Center (such as extended exam time) if a
student thinks their academic performance is impeded by exam-related
stress.

#### Participation Credit (at least 30+ available)

Lots of participation credit will be available. Last year, the
most-participating student accrued 43 participation points. You get
participation in several ways:
  - &gt;50% participation quiz (on Blackboard) before each class gives
    1 point, closes when class begins. (I.e., there is a quiz for
    *each class* that goes along with the videos.)
  - Volunteering to livecode in class gives 2 points. Students are
    encouraged to present, and we will work to establish a positive
    environment where all students can make progress even if they
    don't at first succeed. However, if you feel you simply cannot
    livecode in class you may ask me about doing some individualized
    programming instruction with the TAs / instructor instead.
  - "Introduce yourself" to class (1 minute answer to question) gives 1 point.
  - "Meet your professor" to discuss career goals gives 1 point.
  - Groups that present answers to in-class questions will receive 1 point.

#### Collaboration and the Honor Code

- Projects and exams must be completed alone, without exception.
- Specifically, you must never send your code to anyone or allow
  anyone to watch you code, obtain your code, study your code, copy
  your code, etc... We expect you will take reasonable precautious to
  ensure the secrecy of your solutions (e.g., closing your laptop
  before leaving your apartment, if living with other students).
- The autograder employs elaborate cheat-detection techniques. These
  techniques will compare your code to other students' submissions,
  along with students from previous years. The TAs will be using these
  features to periodically scan for students who are cheating. Past
  experience shows us that this system is very robust, and has allowed
  us to detect several large clusters of collaborating students.
- All apparent cases (with credible evidence, as determined by lead
  instructor) of academic dishonesty will be reported, even if the
  student believes they made an honest mistake, or no mistake at
  all. We understand honor violations are stressful processes, and
  thus we strive to only submit honor code cases when we believe there
  is clear evidence that the honor board should review our findings
  independently.
- You may collaborate, to any degree you want, with anyone (even
  outside of your group) on participation coding exercises. These will
  be clearly labeled, and are specifically not the course projects
  (which explicitly disallow any form of collaboration).
- While we recommend you discuss the project specification with your
  peers, you should basically never be getting help from peers about
  your code. In particular, you should never be showing another
  student your project code. If you do discuss coding about the
  project with another student, it should only be in the abstract
  (e.g., "can you use operator overloading to implement that?" or "do
  you think it would be sensible to implement this with `map`?") and
  not particularized to your codebase. We understand that this can be
  a challenging line to walk, and thus, we recommend the following
  heuristic: when talking to other students about code, discuss mostly
  the in-class exercises and participation coding exercises.
- Cite all help other than the professor, T.A., and
  required/recommended text (you are allowed to cite those if you
  wish, but it is not required unless you are specifically told
  otherwise); note that proper citation is sufficient to avoid any
  charge of academic dishonesty, and we will not be particularly
  focused on copyright law during lab work.
**Again**: You should **never** share code with another student. This
  includes both sending a file to another student and "over the
  shoulder" copying (even when, e.g., variable names are changed,
  etc..). In the eyes of the instructor, these are both equally
  bad. You should never be sitting and helping another along by
  writing their code. By doing so you are both violating the honor
  policy and disadvanting the student you are helping (as they may not
  then properly learn the material).
- If a student is found (by the university academic integrity council)
  to have violated the academic integrity policy, the instructor
  reserves the right to impose any grade sanction they see fit, up to
  and including course failure.

## Student Support

Syracuse University values diversity and inclusion; we are committed
to a climate of mutual respect and full participation. There may be
aspects of the instruction or design of this course that result in
barriers to your inclusion and full participation in this course. I
invite any student to meet with me to discuss strategies and/or
accommodations (academic adjustments) that may be essential to your
success and to collaborate with the Office of Disability Services
(ODS) in this process.

If you would like to discuss disability-accommodations or register
with ODS, please visit their website at
http://disabilityservices.syr.edu. Please call (315) 443-4498 or email
disabilityservices@syr.edu for more detailed information.

ODS is responsible for coordinating disability-related academic
accommodations and will work with the student to develop an access
plan. Since academic accommodations may require early planning and
generally are not provided retroactively, please contact ODS as soon
as possible to begin this process.

## Accreditation

As part of the regular ABET accreditation process for the
undergraduate program in computer science, we may be collecting
samples of students' work in each of our undergraduate classes.  As a
result, some of your labs/homeworks/exams may be photocopied/scanned
(or electronically copied) to be presented for accreditation at some
later point.

## Student Mental Health

Mental health and overall well-being are significant predictors of
academic success. As such it is essential that during your college
experience you develop the skills and resources effectively to
navigate stress, anxiety, depression and other mental health
concerns. Please familiarize yourself with the range of resources the
Barnes Center provides (https://ese.syr.edu/bewell) and seek out
support for mental health concerns as needed. Counseling services are
available 24/7, 365 days a year, at 315.443.8000.

## Discrimination and Harassment

The University does not discriminate and prohibits harassment or
discrimination related to any protected category including creed,
ethnicity, citizenship, sexual orientation, national origin, sex,
gender, pregnancy, disability, marital status, age, race, color,
veteran status, military status, religion, sexual orientation,
domestic violence status, genetic information, gender identity, gender
expression or perceived gender.

Any complaint of discrimination or harassment related to any of these
protected bases should be reported to Sheila Johnson-Willis, the
Universitys Chief Equal Opportunity & Title IX Officer. She is
responsible for coordinating compliance efforts under various laws
including Titles VI, VII, IX and Section 504 of the Rehabilitation
Act. She can be contacted at Equal Opportunity, Inclusion, and
Resolution Services, 005 Steele Hall, Syracuse University, Syracuse,
NY 13244-1120; by email: titleix@syr.edu; or by telephone:
315-443-0211.

If you notice any incidents of harassment or discrimination, however
minor, please email me. You may wish to use an anonymous email service
such as https://anonymousemail.me/. Please feel free to tell me as
much as you feel comfortable.  I am a mandatory Title IX reporter and
must report incidents such as sexual harassment, relationship
violence, stalking, etc...

## Slack

Slack is an instant messaging app for teams. We'll be using it for
most course management. This is the best place to get in touch with me
for one-off questions, ask for an appointment for office hours,
etc.. Email me if you have not been invited to the course Slack.
