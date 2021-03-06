## Week 1 Quiz Questions and Answers

In order to prepare your Week 1 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-1" in your fork of this repo. Then, after all edits have been made/committed, your Week 1 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-1 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Structure Quiz, Problem 1]
- Question (ilankham−stat6250): How common it is to abbreviate the word "repository" as "repo"?

- Question (akurayev-stat6250): Where to learn more about ERROR and WARNING messages in SAS? As I just getting started with SAS programming, it is a good idea to learn how to interpret the SAS log messages.



[Course Structure Quiz, Problem 2]
- Question (ilankham−stat6250): Is the requirement to complete 8 of 10 forum posts to allow people to "slack off" at the end of the quarter, or is it to accommodate students enrolling in the course late, or both?
- Answer (ilankham−stat6250): Both; however, students are encouraged to complete all assignments as written, even if they have no impact on their course grade.



[Course Structure Quiz, Problem 3]
- Question (ilankham−stat6250): Is the requirement to complete 8 of 10 weekly quizzes to allow people to "slack off" at the end of the quarter, or is it to accommodate students enrolling in the course late, or both?

- Question (akurayev-stat6250): What does SAS stand for?
- Answer (akurayev-stat6250): Ths SAS abbreviation stand for Statistical Analysis System.



[Course Structure Quiz, Problem 4]
- Question (ilankham−stat6250): How will code reviews for projects be conducted? Will they involve comments on code in GitHub, meetings with the instructor, or both?
- Answer (ilankham−stat6250): Both; Code Reviews will involve 1:1 meetings with the instructor held through Google Hangouts, during which project code will discussed and commented.



[Course Structure Quiz, Problem 5]
- Question (ilankham−stat6250): How similar to Weekly Quiz problems will final exam problems be? In other words, if I want to best prepare for the final exam throughout the course, should I primarily focus on thoroughly understanding weekly quiz problems?
- Answer (ilankham−stat6250): The best way to prepare for the Final Exam is to work through every assigned Weekly Quiz Problem and to develop an understanding of all concepts involved to the point that the problems can be thoroughly answered without consulting reference materials.



[Course Structure Quiz, Problem 6]
- Question (ilankham−stat6250): Is the ability to earn five total achievements at all related to the common employee rating scale of 0-5, with 5 being the highest possible level of performance?

- Question (akurayev-stat6250): What sort of aptitude should someone have in order to learn SAS?
- Answer (akurayev-stat6250): The aptitude to learn. I think it wiil take some time but stay and follow the course and it will just click. Anyone can learn SAS.



[Course Structure Quiz, Problem 7]
- Question (ilankham−stat6250): What's the intention of encouraging resubmission of incomplete assignments? Is it to encourage students to focus on iteratively creating projects that can be added to work-sample portfolios?

- Question (akurayev-stat6250): If Team-Based Problem Solving should be done in team environment, why does everyone have to submit their work separately?



[Course Structure Quiz, Problem 8]
- Question (ilankham−stat6250): Why does the instructor give extra credit for catching mistakes he's made? Is it to reassure students that everyone makes mistakes, or help him proofread his course materials, or both?

- Question (akurayev-stat6250): Can you import Excel spreadsheets to SAS? If yes, what is import syntax?
- Answer (akurayev-stat6250): Yes, you can. Syntax:
proc import
datafile="filename"
out=SAS-data-set
dbms=identifier
  replace;
  sheet="sheet name";
  getnames=yes;
run;


[Course Structure Quiz, Problem 9]
- Question (ilankham−stat6250): Instead of a carrier pigeon, what about an unladen swallow?
- Answer (ilankham−stat6250): An African swallow maybe, but not a European swallow.



[Course Structure Quiz, Problem 10]
- Question (ilankham−stat6250): What does it mean to check GitHub daily? Does this mean accessing the class GitHub organization daily to check in on the status of the repos I might be asked to contribute to?

- Question (akurayev-stat6250): Whats is the default length of a numeric variable in SAS?
- Answer (akurayev-stat6250): The default length of a numeric variables is 8 bytes, which means we can store up to 16 digits for a numeric varibale in SAS.



[hello-world Week 1 SAS Recipe]
- Question (ilankham−stat6250): Is there a way of having SAS print to a different output destination than the log?
- Question (akurayev-stat6250): How to convert number formst to date format?


[fizz-buzz Week 1 SAS Recipe]
- Question (ilankham−stat6250): Is the mod function at all related to how clocks work, with hours counting from 1 to 12, and then starting back at 1 again?
- Question (akurayev-stat6250): What do we need to have spaces or special characters in a varible name?


