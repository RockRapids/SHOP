---
layout: post
title:  "Social Coding Collaboration Under Different Culturally Influenced Workflows"
subtitle:  "GitHub Actions, GitLab CI/CD, Gerrit/OpenDev"
date:   2024-01-08 4:30:00
categories: Tools
---


*We're all in favor of social coding and collaboration ... but what does that really mean?* 

Well ... it depends ... upon the workflow ... Preparation cures al lot of ills ... it's not really possible to be over-prepared ... but sometimes it's just necessary *to just look stupid ... provoke the enlightenment to get underway ...*

It might be HARD or frustrating to understand what's going on ... but it's terribly important to FORK the repo, get familiar with code, get up to speed on the discussions, documentation, wiki, mailing lists, discord/slack channel ... in order to be taken seriously, it's really essential to really put in the work before asking too many questions ... HOWEVER ... ultimately, you'll have to pipe up and *just ask your stupid question* ... becuase *there are no stupid questions* is more than just a trite cliche ... QUESTIONS and discussions are essential for social coding ... different people approach the SOCIAL nature of coding in a different manner ... so 

**Before you submit an issue**, search the issue tracker for similar entries. Someone else might have already had the same bug or feature proposal. If you find an existing issue that is tied to the bug you've found or feature that you're proposing, show your support with a simple emoji *emotional* reaction for how you feel about the issue ... then, if needed, add your specific **technical** notes/comments/concerns/suggestions/questions to the issue discussion.

In GitHub or Gitlab, contribution typically starts by forking own personal copy of the original repository, cloning that locally and playing with a bit, and pushing one or more commits to that personal fork. Once your code seems ready to merge, you can ask the service to create a pull request in GitHub or a merge request in GitLab for your branch into the original repository. The request is reviewed, and if accepted your changes get merged into the original repository. If not, which might be more likely for your early contributions as you're still figuring out how or why things were done, you push more commits to your fork and update the request seeking more reviews ... it cannot be emphasized enough that the whole development process is really centered around the [issue-driven pull request in GitHub](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) or [issue-driven merge request creation in Gitlab](https://docs.gitlab.com/ee/user/project/merge_requests/).

OpenDev is a collaboratory for open source software development at scale. Its focus is on code review, continuous integration, and project hosting provided exclusively through open source solutions like Git, Gerrit, Zuul, and Gitea. It also provides a number of peripheral collaboration services most notably the [Mailman GNU mailing list manager](https://list.org/). OpenDev doesn't use a pull request (or merge request) workflow, like those implemented by GitHub or Gitlab. Instead it follows Gerrit's iterative change proposal workflow, which results in a slightly different experience. Contribution with Gerrit starts by cloning the original repository locally. 


