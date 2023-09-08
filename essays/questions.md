---
layout: essay
type: essay
title: "Avoiding the heat when asking questions"
# All dates must be YYYY-MM-DD format!
date: 2023-08-30
published: true
labels:
  - Questions, Opinion
---

## Introduction
When asking a question in real life, it is generally fine to ask questions the so-called "not smart way." This would be the way that doesn't follow the guidelines that Eric Raymond sets in his guidelines for asking questions the smart way. Rather than start with the smart way, I think that it would be much more interesting and fun to discuss the "bad" way first.

## The Ugly
[This is the not so smart way to ask a question.](https://stackoverflow.com/questions/77064929/trouble-with-importing-python-modules-in-vscode) For those who do not want to visit the other page, it says, "Trouble with importing python modules in vscode" in the title. No description of any specific errors, not even formatted as a question! Well, whatever, let's just move on to the content of the forum post. A general summary is that the developer is attempting to download a module from Git, and is getting a ModuleNotFound error when attempting to use it. When they use pip.list, it shows the module is available.

## Why it's Ugly
Firstly, I know that this is a not-so-smart question because I have had this exact issue before. I looked up the error and found that the solution is as simple as restarting the IDE and making sure that the module is actually stored within the right Python interpreter. So, this question violates Raymond's principles simply by being asked. The answer is out there, waiting to be found.

The other issue is the way that it is asked. There is no real context, no sample code that they tried it with, no explanation of where the error is being thrown from. The title does not say anything about the specific error, just that they are "experiencing trouble." This likely stops many who would know the answer from actually clicking on the thread. And even the ones who did referred this kind developer to StackOverflow's guide to asking questions.

## The Beautiful
[This is an excellent way to ask the exact same question.](https://stackoverflow.com/questions/54598292/modulenotfounderror-when-trying-to-import-module-from-imported-package) The title is already a significant improvement. "'ModuleNotFoundError' when trying to import module from imported package." It says the exact error and the exact reason it had for happening. When you go into the post, there is an immediate sharing of the directory structure, and the file names and import code that is written within them.
