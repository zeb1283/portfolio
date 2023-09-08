---
layout: essay
type: essay
title: "AmIUgly: Question Edition"
# All dates must be YYYY-MM-DD format!
date: 2023-09-07
published: true
labels:
  - Questions
  - Opinion
---

## Introduction
When asking a question in real life, it is generally fine to ask questions the so-called "not smart way." This would be the way that doesn't follow the guidelines that Eric Raymond sets in his webpage that discusses asking questions the smart way. Rather than start with the smart, or "beautiful" way, I think that it would be much more interesting and fun to discuss the "ugly" way first.

## The Ugly
[This is the not so smart way to ask a question.](https://stackoverflow.com/questions/77064929/trouble-with-importing-python-modules-in-vscode) For those who do not want to visit the other page, it says, "Trouble with importing python modules in vscode" in the title. No description of any specific errors, not even formatted as a question! Well, whatever, let's just move on to the content of the forum post. A general summary is that the developer is attempting to download a module from Git, and is getting a ModuleNotFound error when attempting to use it. When they use pip.list, it shows the module is available.

## Why it's Ugly
Firstly, I know that this is a not-so-smart question because I have had this exact issue before. I looked up the error and found that the solution is as simple as restarting the IDE and making sure that the module is actually stored within the right Python interpreter. So, this question violates Raymond's principles simply by being asked. The answer is out there, waiting to be found.

The other issue is the way that it is asked. There is no real context, no sample code that they tried it with, no explanation of where the error is being thrown from. The title does not say anything about the specific error, just that they are "experiencing trouble." This likely stops many who would know the answer from actually clicking on the thread. Even the ones who did just referred this kind developer to StackOverflow's guide to asking questions.

## The Beautiful
[This is an excellent way to ask a similar question.](https://stackoverflow.com/questions/54598292/modulenotfounderror-when-trying-to-import-module-from-imported-package) The title is already a significant improvement. "'ModuleNotFoundError' when trying to import module from imported package." It says the exact error and the exact reason it had for happening. When you go into the post, there is an immediate sharing of the directory structure, and the file names and import code that is written within them.

## Why it's Beautiful
This question follows most, if not all, of Raymond's guidelines to asking a question. It explains everything, from the file structure to exact errors, and does so in a polite and grammatically accurate manner. It is detailed without being overly long. This developer got rewarded for it, with an incredibly detailed answer and a boatload of upvotes to boot. They even responded nicely!

## The Importance of Asking Beautiful Questions
As developers, we generally don't have all day to entertain questions that are too general, or require us to ask question back to understand what the problem is exactly. Even in the examples above, which discuss something as simple as a module not being properly installed, there is still a lot of context needed to discern the exact issue. Asking smart questions is not only for your benefit, but for those who are attempting to help you. Also, asking smart questions will make you look smarter too! Providing helpful context and using correct language when asking a question will help to show your understanding of the topic at hand.

Most importantly, the faster the helper can get to the root of the problem, the faster the inquirer will receive a helpful response. Although it would be better if we could deal with the more ugly questions with grace and patience, it is not a realistic expectation to have. There will be snark, and there will be some not-so-helpful remarks.

All in all, this was hopefully a helpful exploration of a smart (and beautiful) question and one that is maybe slightly less pleasing. If there are any questions, please make them smart. I am prone to using a fair bit of sarcasm.
