# Programmer Pro Skills Bootcamp!

Welcome to the Programmer Pro Skills Bootcamp! Through guided learnings, we will help build your skills that will help
you get to the next step in your career! Actually, maybe not a guarantee bump on the career ladder just because you completed this course. But I'm sure you'll learn something that will help you! Anyways no idea what to really say here but - all the best!

# How This Works

Each lesson is sectioned by a branch. Lesson branches are named `lesson-NNN` where `NNN` is number in ascending order. eg: `lesson-001`.

Each branch would have its own markdown file denoted by `lesson-NNN.md` (same as its branch) in the `lessons` folder.

The lesson will contain the goal, some steps and some hints.

See [How To Begin And Complete A Lesson](#how-to-begin-and-complete-a-lesson) for futher instructions.

# Getting Started

1. `Fork` the project to your own repo.
   * _all you work will be in your own fork and any assessment/review will be in your own repo._
2. `git clone` your forked repo.
3. in your repo, add a remote link to the main project. Let's call the main project: `teacher`.
    * ` git remote add teacher git@ssh.dev.azure.com:v3/ctmaus/CTM/programmer-pro-skills-bootcamp`
4. `git checkout main`


## How To Begin And Complete A Lesson

1. `git checkout main`
2. `git fetch teacher`
3. Merge the lesson you need to progress to
   * `git merge teacher/lesson-NNN`
4. `git checkout -b <branch-name-base-on-what-you-want-to-focus-on>`
5. `git push -u origin <branch-name-base-on-what-you-want-to-focus-on>`
6. Create a PullRequest on that branch and get your mentor to review.
7. Merge the PR back into `main`
8. take a breather and repeat.

# What we want to focus on

Through this course we want to focus on skills or disciplines that we believe will make you a better programmer in the real world.
Programming tricks and technical skills can always be learnt while doing the work. But there are implicit skills that
aren't usually proactively practiced; yet they carry a big impact working in a team and in a system that needs to scale and
be maintained.

Have a read of [Learning Disciplines](./LEARNING-DISCIPLINES.md) to know what we want to focus on.

These Disciplines should be carried out in your job as well.
