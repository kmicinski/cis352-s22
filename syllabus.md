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
  - This will be a project-focused. Approximately 3-5 hours per week
    outside of class is expected. I recommend against taking this
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
            <th class="projdesc" colspan="1" scope="col"><strong>Projects/Exams-High</strong></th>
            <th class="examdesc" colspan="1" scope="col"><strong>Projects/Exams-Low</strong></th>
            <th scope="col">Grade</th>
          </tr>
        </thead>
        <tbody>
          <tr id="gradea">
            <td class="lggradecol" id="result-A-h">90</td>
            <td class="lggradecol" id="result-A-l">80</td>
            <th scope="row" id="result-A">A</th>
          </tr>
          <tr id="gradeam">
            <td class="lggradecol" id="result-A--h">87</td>
            <td class="lggradecol" id="result-A--l">77</td>
            <th scope="row" id="result-A-">A-</th>
          </tr>
          <tr>
            <td class="lggradecol" id="result-B+-h">85</td>
            <td class="lggradecol" id="result-B+-l">75</td>
            <th scope="row" id="result-B+">B+</th>
          </tr>
          <tr>
            <td class="lggradecol" id="result-B-h">83</td>
            <td class="lggradecol" id="result-B-l">73</td>
            <th scope="row" id="result-B">B</th>
          </tr>
          <tr>
            <td class="lggradecol" id="result-B--h">80</td>
            <td class="lggradecol" id="result-B--l">70</td>
            <th scope="row" id="result-B-">B-</th>
          </tr>
          <tr>
            <td class="lggradecol" id="result-C+-h">77</td>
            <td class="lggradecol" id="result-C+-l">67</td>
            <th scope="row" id="result-C+">C+</th>
          </tr>
          <tr>
            <td class="lggradecol" id="result-C-h">74</td>
            <td class="lggradecol" id="result-C-l">64</td>
            <th scope="row" id="result-C">C</th>
          </tr>
          <tr>
            <td class="lggradecol" id="result-C--h">70</td>
            <td class="lggradecol" id="result-C--l">60</td>
            <th scope="row" id="result-C-">C-</th>
          </tr>
          <tr>
            <td class="lggradecol" id="result-D-h">60</td>
            <td class="lggradecol" id="result-D-l">50</td>
            <th scope="row" id="result-D">D</th>
          </tr>
          <tr>
            <td class="lggradecol" id="result-F-h">&lt; 60</td>
            <td class="lggradecol" id="result-F-l">&lt; 50</td>
            <th scope="row" id="result-F">&lt;D</th>
          </tr>
        </tbody>
      </table>
    </div>
<div class="rightside">
          <table class="table table-sm table-striped grade-table participation">
            <thead>
              <tr class="gradestop">
                <th scope="col"><strong>Participation</strong></th>
                <th scope="col"><strong>GPA Δ</strong></th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="smgradecol" id="part-minus" style="background-color: white;">&lt; 20</td>
                <th scope="row">-</th>
              </tr>
              <tr>
                <td class="smgradecol" id="part-stay" style="background-color: white;">≥ 20 – &lt; 30</td>
                <th scope="row">=</th>
              </tr>
              <tr>
                <td class="smgradecol" id="part-plus" style="background-color: white;">≥ 30</td>
                <th scope="row">+</th>
              </tr>
            </tbody>
          </table>
          <div class="div_calc">
            <p style="text-align: center; font-size: 16pt; margin-bottom: 0px;">Grade calculator</p>
            <form onkeyup="calculate()">
              <div class="leftside_calc" style="width: 200px;padding-right: 10px;">
                <label for="Proj">Project:</label>
                <input type="text" id="proj_score_input" name="exam_exce" size="7" style="float:right" required="">
              </div>
              <div class="rightside_calc" style="width: 200px;padding-right: 10px;">
                <label for="Exam">Exam:</label>
                <input type="text" id="exam_score_input" name="exam_sati" size="7" style="float:right" required="">
              </div>
              <div class="rightside_calc" style="width: 200px;padding-right: 10px;">
                <label for="Part">Participation:</label>
                <input type="text" id="part_score_input" name="exam_sati" size="7" style="float:right" required="">
                <p id="calc_result_0" style="display:inline-block;">Projected grade:</p>
                <h3 id="calc_result" style="display:inline-block;">-</h3>
              </div>
            </form>
            <style>
              .table-sm td, .table-sm th {padding:0.4rem;}
            </style>
            <script>
              function place_highlights(high, low, part, result) {
                  grade_a = [90, 80]
                  grade_am = [87, 77]
                  grade_bp = [85, 75]
                  grade_b = [83, 73]
                  grade_bm = [80, 70]
                  grade_cp = [77, 67]
                  grade_c = [74, 64]
                  grade_cm = [70, 60]
                  grade_d = [60, 50]
                  grade_f = [0, 0]
                  var calibrate = [grade_a, grade_am, grade_bp, grade_b, grade_bm, grade_cp, grade_c, grade_cm, grade_d, grade_f]
                  function clear_col(base) {
                    var element = document.getElementById(base+"-l");
                    element.style.backgroundColor = 'white';
                    var element = document.getElementById(base+"-h");
                    element.style.backgroundColor = 'white';
                  }
                  function highlight(ele) {
                    // console.log("highlight "+ele)
                      document.getElementById(ele).style.backgroundColor = "#ff7f50";
                  }
                  // clear colors                
                  for (i=0; i < 10; i++) {
                          grade = ["A","A-","B+","B","B-","C+","C","C-","D","F"][i]
                          var element = document.getElementById("result-"+grade);
                          if (element!==null){
                            element.style.backgroundColor = 'white';
                          }
                          clear_col("result-"+grade);
                  }
                  // clear participation too
                  document.getElementById("part-minus").style.backgroundColor = "white";
                  document.getElementById("part-stay").style.backgroundColor = "white";
                  document.getElementById('part-plus').style.backgroundColor = "white";
                  for (i=0; i < 10; i++) {
                          grade = ["A","A-","B+","B","B-","C+","C","C-","D","F"][i]
                          var element = document.getElementById("result-"+grade);
                          if (element!==null){
                            element.style.backgroundColor = 'white';
                          }
                          clear_col("result-"+grade);
                  }
                  for (i=0; i < 10; i++) {
                    if (high>=calibrate[i][0]){
                      fst = ["A","A-","B+","B","B-","C+","C","C-","D","F"][i]
                      highlight("result-" + fst + "-h");
                      break;
                    }
                  }
                  for (i=0; i < 10; i++) {
                    if (low>=calibrate[i][1]){
                      snd = ["A","A-","B+","B","B-","C+","C","C-","D","F"][i]
                      highlight("result-" + snd + "-l");
                      break;
                    }
                  }                  
                  if (part < 20) {
                      highlight("part-minus");
                  } else if (part >= 30) {
                      highlight("part-plus");
                  } else {
                      highlight("part-stay");
                  }
                  if (["A", "A-"].includes(result)){
                    document.getElementById("result-" + result).style.backgroundColor = "#28a745";
                  }
                  if (["B", "B-", "B+"].includes(result)){
                    document.getElementById("result-" + result).style.backgroundColor = "#ffc107";
                  }
                  if (["C", "C-", "C+"].includes(result)){
                    document.getElementById("result-" + result).style.backgroundColor = "#007bff";
                  }
                  if (["D", "F"].includes(result)){
                    document.getElementById("result-" + result).style.backgroundColor = "#dc3545";
                  }
              }
              function calculate() {
                  var examscore = parseInt(document.getElementById('exam_score_input').value)
                  var projscore = parseInt(document.getElementById('proj_score_input').value)
                  var pa = parseInt(document.getElementById('part_score_input').value)
                  grade_a = [90, 80]
                  grade_am = [87, 77]
                  grade_bp = [85, 75]
                  grade_b = [83, 73]
                  grade_bm = [80, 70]
                  grade_cp = [77, 67]
                  grade_c = [74, 64]
                  grade_cm = [70, 60]
                  grade_d = [60, 50]
                  var calibrate = [grade_a, grade_am, grade_bp, grade_b, grade_bm, grade_cp, grade_c, grade_cm, grade_d]
                  var count = [0,0]
                  var validcheck = (examscore >= 0) && (examscore <= 150) && (projscore <= 100) && (projscore >=0) && (pa <= 100) && (pa>=0)
                  var complete = !isNaN(examscore) && !isNaN(pa) && !isNaN(projscore)
                  // console.log(complete)
                  var high = Math.max(examscore, projscore)
                  var low = Math.min(examscore, projscore)
                  grade = [high, low]
                  for(i=0;i<5;i++){
                      // console.log(i)
                      for(j=0;j<9;j++){
                          if(grade[i]<calibrate[j][i]){
                            count[i]++;
                          }
                      }
                  }
                  if(complete && validcheck){
                      var rowsink = Math.max.apply(null, count)
                      if(pa>=30) rowsink--;
                      else if(pa<20) rowsink++;
                      if(rowsink>9){
                          result = "F";
                      }
                      else if(rowsink<0){
                          result = "A"
                      }
                      else{
                          result = ["A","A-","B+","B","B-","C+","C","C-","D","F"][rowsink]
                      }
                      if (result) {
                          document.getElementById("calc_result_0").innerHTML = "Projected grade:";
                          document.getElementById("calc_result").innerHTML = result;
                          place_highlights(high, low, pa, result)

                      }
                  }
                  if(!complete && validcheck){
                      document.getElementById("calc_result_0").innerHTML = "Please complete form";
                      document.getElementById("calc_result").innerHTML = "";
                  }
                  if(complete && !validcheck){
                      document.getElementById("calc_result_0").innerHTML = "Invalid scores";
                      document.getElementById("calc_result").innerHTML = "";
                  }
              }
            </script>
          </div>
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

- Assignments and exams must be completed alone, without exception.

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








<!-- ## Course Overview -->

<!-- This course will introduce many of the principles of programming -->
<!-- language design and implementation. We will discuss numerous features -->
<!-- of several programming languages and the algorithms and data -->
<!-- structures that are needed to provide these features. Projects will -->
<!-- cover both the use of various features and high-level understanding -->
<!-- the algorithms and data structures involved in their -->
<!-- implementation. -->

<!-- Lectures and labs will include examples (and exercises) in Racket. No -->
<!-- prior knowledge of Racket is needed for this course, but students -->
<!-- should be familiar with the programming techniques from their -->
<!-- lower-level courses and possess fluency in basic functional -->
<!-- programming. -->

<!-- ## Grading -->

<!-- - Projects: 56% -->
<!-- - Exams: 44% -->
<!--   - Midterm: 14% -->
<!--   - Final: 20% -->
<!--   - Coding Exam 0: 5% -->
<!--   - Coding Exam 1: 5% -->

<!-- ## Grade cutoffs -->

<!-- These are rough grade cutoffs. I never fit grade distributions to a -->
<!-- normal curve (e.g., specifying that only 10% of students may earn an -->
<!-- A), however I may choose to lower the bar for some letter grades. I -->
<!-- will not curve assignments or projects. -->

<!-- - 93% -- A -->
<!-- - 89% -- A- -->
<!-- - 84% -- B+ -->
<!-- - 80% -- B -->
<!-- - 77% -- B- -->
<!-- - 74% -- C+ -->
<!-- - 70% -- C -->
<!-- - 65% -- C- -->
<!-- - 55% -- D -->
<!-- - 0%  -- F -->


<!-- ## Autograder -->

<!-- Projects in this course will be graded by an automatic grader. We may -->
<!-- adjust projects so that portions of the projects include style-based -->
<!-- grading, though we will *not* employ subjective grading. More -->
<!-- pointedly: we will *not* award partial credit for solutions that have -->
<!-- the right ideas but do not pass our tests. -->

<!-- ## Late Projects and Extensions -->

<!-- I used to extend project deadlines, but I have found that this is -->
<!-- often unfair to the students who start on time (and more students than -->
<!-- I would have thought have raised this point to me -->
<!-- privately). Therefore, project extensions will be rare--and only in -->
<!-- the event of things such as university closures. Project extensions -->
<!-- for students will not be granted except for religious observances and -->
<!-- extenuating circumstances (family illness, etc..). The late policy is -->
<!-- as follows: -->

<!-- - Projects turned in on time will earn a maximum of 100% -->

<!-- - Projects turned in up to 72 hours late will have a 15% penalty -->
<!--   applied. -->

<!-- - Projects turned in after 72 hours late (until the end of the term) -->
<!--   will have a 30% penalty applied. -->

<!-- - Your project grade always be the maximum possible. For example, -->
<!--   let's say you make an on-time project submission for 60%, but the -->
<!--   next day you turn in a project which earns an 75%. This submission -->
<!--   would earn a 63.75%. Five days after the deadline you turn in a -->
<!--   project earning 100%. Your final score is 70%, as the 70% (100% with -->
<!--   a 30% penalty) still got the maximum grade of any submission. -->

<!-- You *should* be able to earn **at least** a 70% on all of the projects -->
<!-- with enough work. -->

<!-- ## Topics -->

<!-- We will plan to cover all of the following, though some may be dropped -->
<!-- for time: -->

<!-- - Programming in Racket -->
<!-- - Higher-order functions -->
<!-- - Execution models and their impact on the stack -->
<!-- - Pattern matching -->
<!-- - Immutable data structures -->
<!-- - Okasaki-style immutable queues -->
<!-- - Immutable binary trees -->
<!-- - Quad-trees -->
<!-- - Static scope -->
<!-- - Dynamic scope -->
<!-- - Lambda calculus -->
<!-- - Textual-reduction semantics -->
<!-- - Big-step semantics (CE-style evaluators) -->
<!-- - Metacircular interpreters -->
<!-- - Church encoding -->
<!-- - Control and continuations -->
<!-- - Abstract machines -->
<!-- - The CEK machine -->
<!-- - A-Normal Form -->
<!-- - Continuation-passing style -->
<!-- - Top-down parsing -->
<!-- - State-passing style -->
<!-- - Simply-typed lambda calculus -->
<!-- - Type inference -->
<!-- - Hygienic macros -->
<!-- - Logic programming -->
<!-- - MiniKanren -->

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
