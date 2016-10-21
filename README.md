# Workflow

Nogo apps workflow documentation.

## Overview

We use a method agil similar to kanban with consists in 3 standarts:

1. Comunication.
2. Organization.
3. Version control.

# Slack(Comunication)

- brainstorm: Weekly meeting.
- change_request: If you want ask for  a change in the project about something in progress.
- general: general subjects.
- github: Integration with github.
- reviews_codacy: New reviews from codacy.
- visitors_slaask: Chat room to visitors of our website.

# Trello(Organization)

1. You can use Trello to create a workflow and organize the tasks and the time. 
2. Every task have to be possible done in more of 2 hours and less the 6 hours if not, split or paste some tasks in one task.
3. Can go just forward and all the columns can have just 6 tasks at once.
4. We goal is min of 6 tasks weekly.
5. If some task is static more than 2 days it became a priority and go to discuss on brainstorm weekly.

## Columns:

- Backlog: Here we discussed our ideas, difficulties and plans. One times a week we make the brainstorm meeting.
- To do: Here we have all the approved tasks to do with descriptions.
- Doing(testing): Here shows what is in progress.
- Review(testing): Here we analyze the code and 
- Done: The task is finished.

# Version control

Work in your branch and just when your work is done try a pull request.

# Code Review Checklist(Version control)

The review needs to be done at 3 levels:

1. Codacy test.
2. Build test and UI test.
3. Comparation test with git or github.
4. Column "doing" and "review" need make these tests.

## General

- The code works?
- The code is clean?
- The the code is encapsuled and OO?
- The code respect design patterns, material design and android conventions?
- There is something redundant or unnecessary?
- The project is modulate with loose coupling?
- Some log or debug is unnecessary?
- If the project needs some import on gradle, virtual machine and etc... the whole team needs be informed.
- The code comented was removed?
- The build works?
- The codacy see some problem in your code that needs to be fixed?

## Codacy

The codacy make some automatic reviews and give us a better look in the code.

# Git

You can to analyze in local git the diferences with the cheats below this topic and on github when create a pull request.

## Cheats to compare and logs

- git diff (show the changes)
- git diff HEAD
- git diff --word-diff(show just the changes and not the all line)
- git diff --staged(show the changes in stage area)
- git --stat(show just the files changed)
- git checkout(change branchs)
- git log(show commits from autors with dates)
- git log --oneline(show just the descriptions of commits)
- git log --stat(see the files that changes too)

## Possible mistakes

1. If you have a repository inside your repository.
2. If you don't have access to the key of the repository.
3. If the remote repository have changes to pull.
4. If you are try to push to master instead your branch.

## More git cheats:![alt tag](http://i.imgur.com/Ia1S7R8.png)


