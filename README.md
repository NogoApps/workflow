# Workflow

Nogo apps workflow documentation.

## Overview

We use a method similar to kanban with consists in 3 standarts:

1. Comunication.
2. Organization.
3. Version control.

# Slack(Comunication)

- brainstorm_10min: Weekly meeting with github projects, github issues and codacy in 10min.
 1. Issues with label "stuck"
 2. Sprints
 3. Next features
- change_request: If you want ask for  a change in the project about something in progress.
- general: general subjects.
- github: Integration with github.
- reviews_codacy: New reviews from codacy.
- visitors_slaask: Chat room to visitors of our website.

# Github projects(Organization)

- Cards
 1. You can use projects to create a workflow and organize the tasks and the team in notes.
 2. Every task have to be possible done in more of 2 hours and less the 6 hours if not, split or paste some tasks in one task.
 3. Can go just forward(pulled to next column) and all the columns can have just 6 tasks at once.
 4. Every card title needs to have the current date.
 5. We goal is min of 6 tasks weekly.
 6. Every friday we clean the column done.
 7. Every time i change a card of column to another column i have to change the date to the current.
- Issues
 1. Every note you create have to be convert in an issue when you put in the column "To do" and completed the data.
 2. The issue data is assign(person responsible), milestone(stage of the project), label(type) and description.
 3. Stuck label is some task is static more than 3 days in the same column or something was not approved in the review, what gets priority and the team discuss in slack. When you solve the issue stucked change label stuck to priority.
 4. New, replace, bug and priority are the others types.
 5. Every issue have to become a commit in your branch.
 6. We can see in pulse and graphs informations about our issues and pulls.
 7. When you make a review in an issue you can use the emoji "like" or "dislike"(this needs a comment) to symbolize what you think and can comment along the updates of the issue.
 8. When we delete issues on friday from the column "done", we need to close them.

## Columns

- Backlog: Here we discussed our ideas, difficulties and plans. One times a week we make the brainstorm meeting.
- To do: Here we have all the approved tasks(issues) to do with descriptions, labels, assigns and milestone.
- Doing(testing): Here shows what is in progress.
- Done: The task is finished and now can wait for review.
- Review(testing): Here analyze the code when receive a pull request and make coments at lines, create a review and discuss about changes, request changes or approve with a like icon. When the review is complete close the issue and erase the issue of the column.


# Version control

Work in your branch and just when your work is done try a pull request, every pull request needs a description explain whats change and why.

Ex: 

- What is changed?

Text example, text example, Text example, text example, Text example, text example, Text example, text example, Text example, text example.

- Why?

Text example, text example, Text example, text example, Text example, text example, Text example, text example, Text example, text example.

## Code Review Checklist

The review needs to be done at 3 levels:

1. Receive a pull request.
2. Codacy test.
3. Build test and UI test.
4. Comparation test with git or github.
5. To approve(change to column done) or disapprove(add label "stuck").

More details:

- Column "doing" and "review" need make these tests.
- The person who make the review can't be the same who did the code.

## General

- The code works?
- The code is clean?
- The the code is encapsuled and OO?
- The code respect design patterns, material design and android conventions?
- There is something redundant or unnecessary?
- The project is modulate with loose coupling?
- All the methods and variables are commented or with explicit scope.
- Some log or debug is unnecessary?
- If the project needs some import in gradle, virtual machine and etc... the whole team needs be informed and create a documentation.
- The code comented was removed?
- The build works?
- The UI is working in all devices that should?
- The codacy see some problem in your code that needs to be fixed?

## Codacy

The codacy make some automatic reviews and give us a better look in the code.

# Git

You can to analyze in local git the diferences with the cheats below this topic and on github when create a pull request.

On github you can make comments at lines of the code, only use git if you need an analyzes deeper.

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

## PS: Our project page(with download and overview) will be available with github pages and our blog is in medium.


