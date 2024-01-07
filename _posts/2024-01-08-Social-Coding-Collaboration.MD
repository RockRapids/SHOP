---
layout: post
title:  "Social Coding Collaboration Under Different Culturally Influenced Workflows"
subtitle:  "GitHub Actions, GitLab CI/CD, Gerrit/OpenDev"
date:   2024-01-08 4:30:00
categories: Tools
---


*We're all in favor of social coding and collaboration ... it's like standardization ... we're all in favot of standardization as long everyone standardizes on doing it our way.* 

It might be beyond just HARD or more than intensely frustrating to THINK that you understand what's going on ... and then you find out that you THOUGHT you understood, and told people that you understood ... but you understood that things worked ***slightly*** differently.

It's terribly important to get really, really familiar with the lay of the land first ... FORK the repo and install it so that it works, get familiar with code by tweaking a few things, get up to speed on the discussions, read the documentation, go over the wiki, follow the threads on mailing lists, discord/slack channel ... in order to be taken anywhere close to seriously, it's really essential to really put in the work before asking too many questions ... HOWEVER ... ultimately, you will have to pipe up and *just expose yourself as an idiot with a stupid question.* 

And that's when the fun starts ... becuase *there are no stupid questions* is more than just a trite cliche ... QUESTIONS and discussions are absolutely essential for social coding ... if you really tried to prepare and then were abused because of your dumb question -- then maybe the group is not for you.

Do not judge others ... different people approach things like the SOCIAL nature of coding in a different manner ... and if you were not welcomed for honestly trying to contribute, then maybe the group is not for you. There are plenty of other fish in the sea. 

**Before you submit your first issue**, REALLY search the issue tracker for similar entries ... maybe under a different title or with different wording. Someone else might have already had the same bug or feature proposal. If you find an existing issue that is tied to the bug you've found or feature that you're proposing, show your support with a simple emoji *emotional* reaction for how you feel about the issue ... then, if needed, add your specific **technical** notes/comments/concerns/suggestions/questions to the issue discussion.

In GitHub or Gitlab, contribution typically starts by forking own personal copy of the original repository, cloning that locally and playing with a bit, and pushing one or more commits to that personal fork ... but you really have to understand the mindset of the people who have been developing the code FROM THEIR POINT OF VIEW. Once your little improvement to the code seems ready to merge, you can ask the service to create a pull request in GitHub or a merge request in GitLab for your branch into the original repository. The request will be reviewed, and if accepted your changes get merged into the original repository. 

If not, ***which might be more likely for your early contributions*** since you're still figuring out how or why things were done, you push more commits to your fork and update the request seeking more reviews ... it cannot be emphasized enough that the whole development process is really centered around the [issue-driven pull request in GitHub](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) or [issue-driven merge request creation in Gitlab](https://docs.gitlab.com/ee/user/project/merge_requests/) ... and your best chance of making contribution and earning some cred is to really understand the issues in issue tracker and the pull/merge request process and to WORK ON SOMEBODY ELSE'S ISSUE.

In contrast to Github or Gitlab, OpenDev is a collaboratory for open source software development at scale. Its focus is more heavily on on the code review side ... it's more about larger team continuous integration. The project hosting for OpenDev projects will provided exclusively through open source solutions like Git, Gerrit, Zuul, and Gitea. OpenDev also provides a number of peripheral collaboration services most notably the [Mailman GNU mailing list manager](https://list.org/). OpenDev doesn't use a pull request (or merge request) workflow, like those implemented by GitHub or Gitlab. Instead it follows Gerrit's iterative change proposal workflow, which results in a slightly different experience, since contribution with Gerrit starts by cloning the original repository locally and then always working together on the a similar clone of the same ORIGINAL reference repository, rather than a forking and work on forks. 


