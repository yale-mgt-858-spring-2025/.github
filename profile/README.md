# MGT858 - Database Systems, Spring 2025

Hello 👋👋! This is the "about" page for [MGT858 "Database
Systems"](https://858.mba) at the Yale School of Management in Spring 2025.
This is the third time I've taught this course. Thanks for joining! 

## Overview

| Key                     | Value                                                                                                                             |
| ----------------------- |-----------------------------------------------------------------------------------------------------------------------------------|
|  🎓&nbsp;Course  number  |  MGT858  |
|  📚&nbsp;Units  |  2  units  in  Yale  College  and  equivalent  elsewhere  |
|  👥&nbsp;Enrollment  |  Open  to  any  student  at  Yale  |
|  📅&nbsp;Term  |  Spring-2  2025  (half-term)  |
|  🕓&nbsp;Meeting  Time  |  Monday  &  Wednesday  13:00-14:20  EST,  March  25  -  May  6,  2025  |
|  💀&nbsp;Final Exam | Monday, May 6th in class |
|  🏫&nbsp;Meeting  Location  |  Room  2410  in  [Evans  Hall](https://map.yale.edu/?id=1910#!m/560094)  |
|  💻&nbsp;Zoom  link  |  No  zoom  🙁  |
|  📅&nbsp;Calendar  |  [Yale  SOM  Academic  Calendar](https://som.yale.edu/programs/mba/integrated-curriculum/the-academic-calendar)  |
|  🌐&nbsp;Website  |  http://858.mba  (down  sometimes  until  class  begins;  requires  Yale  VPN)  |
|  💬&nbsp;Discussions  |  https://github.com/orgs/yale-mgt-858-spring-2025/discussions  |  
|  👨‍🏫&nbsp;Instructor  |  Kyle  Jensen  |
| 🤝&nbsp;Teaching Assistants | [Harshal Bhatia](mailto:harshal.bhatia@yale.edu) |



MGT858 introduces students to the database systems used in modern
technology companies.  You will emerge from this course an SQL ninja,
well-prepared for tech sector roles including data scientist, product manager,
and technical program manager.  The first half of the course covers relational
databases (after a brief discussion of content-addressable storage) and the
latter half covers other
kinds of systems including key-value stores, document databases (noSQL),
distributed databases, graph databases, and vector databases.  We will discuss
the business case for each of these database such that you ought to emerge from
the course able to think of a software product or service and describe what
kind of database systems ought to be used to build that product.  You will not
learn how to build such systems, though you will learn a little bit about their
internals. You will definitely learn how these systems can be used to answer to
the kinds of analytics questions you will encounter as a manager.  The
coursework includes *numerous* quizzes, homework assignments, and a final
examination, all of which require writing code and must be submitted using the
git version control system.  (Experience with git is not required; however,
some experience programming is necessary. The particular language does not
matter.) Students can expect to spend perhaps three to four hours per week on homework.

## Admission to the class

You can be admitted to the class by bidding in the Yale SOM bidding system.
I asked for a big 'ole room this year, so you should get in for "free".
Anybody at Yale can take the class. But, you have to figure out what is 
required by your program. For example, Yale College students require some
kind of form. 

## How to use this document/repo

Because our class info and policies are tracked using git, you can see if and
how they change over the course of the semester. Further, you have the ability
to make changes yourself---please send me a pull request. Similarly, if you
feel these documents are lacking, please open an
"[issue](https://github.com/yale-mgt-858-spring-2025/about)" on GitHub for this
repo and we'll address the issue. Finally, because our git repo is hosted on
GitHub, you can easily receive push notifications of changes to this repo.
(Woot!)

## Office hours

Your first stop for help should be the [classroom discussion](https://github.com/orgs/yale-mgt-858-spring-2025/discussions)
on GitHub. Please only email if you need private help. Please, check with the TAs first. (I care greatly about 
you, but my inbox is often a hot mess and I'm not always the best at responding to email. 😞)

The office hours for each of the teaching staff is shown
below. Though, if you are reading this before the start of
the semester, it is possible some staff are missing because
they did not yet determine their schedule. 

Feel free to send an email if these times do not work for you.

| Person          | Email | Hours            | Location/URL                                                                |
| --------------- | ----- | ----------- | ----------------------------------------------------------------------- |
| Kyle Jensen     | kyle.jensen@yale.edu | TBD | L400 (the Bunker) |
| Harshal Bhatia | harshal.bhatia@yale.edu | TBD | TBD |



## Development environment

You will need to write code a lot of code this semester, mostly domain-specific
query languages like [PostgreSQL-flavored SQL](https://www.postgresql.org/docs/).
Most of the homework assignments and the final exam will require using the [git
version control system](https://git-scm.com/) for submission. You'll sign up
for GitHub, join the [yale-mgt-858-spring-2025
organization](https://github.com/yale-mgt-858-spring-2025) on [GitHub](https://github.com/yale-mgt-858-spring-2025/.github/blob/main/profile/github.md) and
submit your assignments (in part) by pushing up code to GitHub. Usually I'll
give you some starter code like empty `.sql` files with examples queries.
When you complete your assignments, you'll make git commits and push those
commits up to GitHub so that I can download your answers and test them.
Obviously this requires knowing a little bit of git. I'll point you to some
git tutorials, but I'm not going to teach git in class. You are forewarned
😉. 

You can complete the homework assignments on any kind of computer: Windows,
Mac, Linux, whatever. You'll almost certainly need to install some software in
order to do so. Obviously you'll need git. You might also need _ clients_ for
different database systems. For example, you will almost certain need a
PostgreSQL client or a MongoDB client.  The `$XYZ` _client_ is a piece of
software that connects to the `$XYZ` _server_ in order to send the server
queries (or other commands) and interpret the responses. (Here, `$XYZ` is a
stand-in for PostgreSQL, Redis, MongoDB, Clickhouse, Elasticsearch, etc.) Now, it could be that you don't
want to set up the `$XYZ` client software on your computer, which would be totally reasonable: it
can be a pain in the rear-end. For this reason, you might want to use [GitHub Codespaces](https://docs.github.com/en/codespaces/overview)
for your assignments. You can find a lot of tutorials for doing that online. 


## Preparing for the course

I am receiving a few emails from students about how best to prepare for the
class. There's a few ways to think about doing so. One is to prepare narrowly
for the content you're going to encounter. For SQL, in my person opinion, the
best way to do so is going through the exercises at
[SQLBolt](https://sqlbolt.com/).  I think that website is fantastic and it's
part of the assigned reading in class. For the other database systems we'll
use, the answer is less clear.  You can read about
[ElasticSearch](https://github.com/elastic/elasticsearch) (the representative
full-text search database we might use);
[ClickHouse](https://github.com/ClickHouse/ClickHouse) or 
[DuckDB](https://duckdb.org/)
(the representative
columnar stores we might use); [Redis](https://github.com/redis/redis) (the
representative caching database we might use);
[MongoDB](https://github.com/mongodb/mongo) (the representative noSQL
database we'll likely use); and [Neo4j](https://github.com/neo4j/neo4j) (the
representative graph database we'll use).

A second way to prepare is to level-up your computer skills in general,
particularly your *nix skills. A good resource for doing so is [MIT's missing
semester course](https://missing.csail.mit.edu/).

Finally, you might think about getting your personal computer set up for
writing code. That usually starts with choosing a package manager
([homebrew](https://brew.sh/) on Mac OS and
[Chocolatey](https://chocolatey.org/) on Windows) and choosing a [good code
editor](https://github.com/collections/text-editors). I use
[VSCode](https://code.visualstudio.com/) and [NeoVim](https://neovim.io/).

Also 😜, you'll want to be familiar with [git](https://git-scm.com/). You can
find [many tutorials
online](https://medium.com/@javinpaul/top-10-free-courses-to-learn-git-and-github-best-of-lot-967aa314ea).
Your use of git this semester will be super simple because you won't generally
have collaborators. If you like, you can use a [git GUI](https://git-scm.com/downloads/guis).
I use GitHub Desktop often, mostly for line-by-line staging of changes.


## Textbook

There is no textbook for the course. Readings will be posted on the
[class website](https://858.mba).

## Diversity, equity, inclusion and their opposites

This class will be an inclusive environment. If you see behavior
that you feel is discriminatory, _particularly_ from the professor
or teaching staff, we encourage you to avail yourself of one or
more of the following resources.

- [Preventing and Responding to Sexual Misconduct at Yale Booklet](https://smr.yale.edu/sites/default/files/files/Guide-Preventing-and-Responding-to-Sexual-Misconduct.pdf)
- [Yale
  Sexual Harassment and Assault Response & Education (SHARE)](https://sharecenter.yale.edu/)
- Diane Temple in SOM Human Resources and Sheri Scully in the SOM AASL.
- [Yale Title IX Coordinators](https://provost.yale.edu/title-ix/coordinators) (SOM’s Title IX Coordinator is Rebecca Udler)
- [Yale's Live Safe App](https://your.yale.edu/community/public-safety/campus-safety-services/livesafe-app)
- [Office for Equal Opportunity Programs](https://equalopportunity.yale.edu/)

## Homework assignments

We will usually have two homework assignments per week and an on-paper quiz
at the start of every class. That's
a *lot* of work!  All of the homework assignments will be submitted to
GitHub using git. 

## Use of AI assistants, human assistants, and the honor code

You should totally be using AI assistants such at GitHub Copilot
(best for writing code) or ChatGPT/Mistral/Claude/Gemini/Llama.
I ask that you not copy from other humans in "real-time".
You are welcome to use the advice of other humans through media
such as StackOverflow or our [class
discussion/qa](https://github.com/orgs/yale-mgt-858-spring-2025/discussions)
and also to work on your homework with your colleagues. Given such
parameters, what do I think would constitute a violation of the
honor code? I can think of a few things: 1) blatant copying,
particularly in serial; 2) wide spread dissemination  of answers
to quizzes or homework assignments; 3) copying from a human in
real-time; 4) use of unauthorized resources during quizzes or exams;
5) efforts to thwart faithful grading, such as fibbing about time
of submission.  What's the bottom line? We're all adults. I want
you to learn, I want you to have fun, and I want to faithfully
report a grade that reflects your "real world" subject matter
competence at the end of the term. Don't do things that mess that
up.

## Quizzes

Most classes begin with an on-paper, ten-minute multiple choice quiz.
Alas, these are a crude and imperfect assessment of
the degree to which you understand the pre-class reading material.
The following are my reasons for giving pre-class quizzes:

1. It makes you think about the upcoming class!
2. Empirical evidence shows that the [testing effect](https://en.wikipedia.org/wiki/Testing_effect)
   increases your understanding and retention of material.
3. They give you a low-stakes, super-small reward for coming to class prepared.
4. They ensure that your classmates are better prepared for class and therefore more fun to speak with.
5. You can drop your lowest two scores, so they are not stressful.


A few notes about the quizzes...

* The quiz questions are not uniformly drawn from material in
  the pre-class reading. Some pre-class reading will be over-represented
  and some under-represented either, usually because of heterogeneous
  importance of the pre-class reading material.
* We want the quiz questions to test your conceptual understanding.
  We do not want to ask "gotcha" questions or simple recall questions.
  However, we will fall short in those aspirations often.
* Some quiz questions will have obvious answers. We do this in part
  to remind you of important concepts.
* If you feel like a quiz questions is unfair or that the answer
  is wrong, please tell Kyle. It is easy for Kyle to "fix" a bad
  question.
* Questions that have multiple correct answers are indicated as
  such.

## Grading

Grading will follow the official Yale SOM grading
policy, which is as follows.

| Grade | Description                                                                 | Reported on Transcript |
|-------|-----------------------------------------------------------------------------|------------------------|
| HH    | High Honors. Up to top 10% of class.                                        | Yes                    |
| H     | Honors. Next 25%.                                                           | Yes                    |
| PR    | Proficient. Next 55%.                                                       | No                     |
| P     | Pass. Lowest 10% in core courses; guideline of 5% in electives.             | No                     |
| F     | Fail. An absolute standard; no minimum requirement.                         | Yes                    |


In my opinion, it's a quite generous curve (though [the ethics of
grading on a curve are
dubious](https://digitalcommons.law.byu.edu/cgi/viewcontent.cgi?httpsredir=1&article=1153&context=elj)).
I will compute the grades for non-SOM students by overlaying their school's
grading scale on top of the SOM curve. There's not a 1-to-1 correspondence.
Your letter grade will be based on your sum grade and your sum grade will be
determined _roughly_ as follows (I reserve the right to make changes. The most
common change I make is dropping assignments or quizzes.)


| Component       | Percentage            | 
| --------------- | ---------------- |
| Homework     | 30% | 
| Quizzes   | 30% | 
| Final exam   | 30% | 
| Participation   | 10% | 

The ethics of counting participation in the grade are also a bit dubious 🙁.
But, I'm including it for consequentialist reasons: your participation makes
the class more fun for all of us and most importantly for me 🤣.


