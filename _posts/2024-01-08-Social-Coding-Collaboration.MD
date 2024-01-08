---
layout: post
title:  "Social Coding Collaboration Under Different Culturally Influenced Workflows"
subtitle:  "GitHub Actions, GitLab CI/CD, Gerrit/OpenDev"
date:   2024-01-08 4:30:00
categories: Tools
---


# BEFORE your even get started ...

You should be quite familiar with the [architecture of open source applications](https://aosabook.org/en/index.html) ... and you should understand something about how/why things developed as the did. As you go forward, you will run into completely dysfunctional communities and software development organizations. 

***[Development communities or organizations [including business organizations] which design systems are NECESSARILY constrained to produce designs which are copies of the communication structures and workflows of these communities or organizations.](https://en.wikipedia.org/wiki/Conway's_law).*** 

This does not ***just*** mean that if your organization has four separate groups working on a compiler, that organization structure will tend to produce something compiles in some sort of 4-pass strategy ... although that's one way to think about it.

The inescapable nature of human organizations drives natural human thinking tendency to structure thought according to an [inner platform effect](https://en.wikipedia.org/wiki/Inner-platform_effect) ... so humans NECESSARILY cannot escape designing systems which are templated layers or copies of the communication structures and foundational workflows used in the communities or organizations which design things ... people don't perform *Vulcan mind melds* ... they have to express ideas semiotically, semantically, linguistically with one another ... so that social coding collaboration workflow will become the inner skeletal foundation of everything that your community builds.

**It's worth spending a LOT of time getting this right.**

*We're all in favor of social coding and collaboration ... it's like how everyone thinks standards and standardization are a great idea ... we're all in favor of standardization as long everyone standardizes on doing it our way.*  Social coding is beyond being just HARD or frustrating ... troubleshooting something ON OUR OWN is a little bit hard or a little bit frustrating in comparison to how MASSIVELY HARD or MASSIVELY FRUSTRATING something is in a group of strong-minded, creative developers.  Collaboration on something that ***really*** matters, ie where the output will be greater than the sum of the parts, is much more than intensely frustrating that dev'ing something alone.

**It's worth spending a LOT of time getting this right ...** so go back and spend some more time getting familiar with what has worked in the [architecture of open source applications](https://aosabook.org/en/index.html). It's safe to say you probably should find yourself wanting to USE the fundamentals that your find those open source applications as part of the architecture of your own development workflow ... instead of just mere gists of ideas, you might even use something like [Git](https://aosabook.org/en/v2/git.html) or the [Bourne-Again SHell](https://aosabook.org/en/v1/bash.html), more or less in its full entirety.

# To START OFF ...
 
It's terribly important to get really, really familiar with the lay of the land first ... FORK the repo and install it so that it works, get familiar with code by tweaking a few things, get up to speed on the discussions, read the documentation, go over the wiki, follow the threads on mailing lists, discord/slack channel ... in order to be taken anywhere close to seriously, it's really essential to really put in the work before asking too many questions ... HOWEVER ... ultimately, you will have to pipe up and *just expose yourself as an idiot with a stupid question.* 

And that's when the fun starts ... becuase *there are no stupid questions* is more than just a trite cliche ... QUESTIONS and discussions are absolutely essential for social coding ... if you really tried to prepare and then were abused because of your dumb question -- then maybe the group is not for you.

It is painfully humiliating to THINK that you understood what's going on ... and then you find out that you THOUGHT you understood, and told people that you thought you understood ... but you actually understood something ever so ***slightly*** different than Reality as Reality REALLY was.

This happens. This is why we never judge others ... we USUALLY do not have a clue about how other people think ... but we often really believe that other people see things just like we do ... different people approach things like the SOCIAL nature of coding in a different manner ... and if you were not welcomed for honestly trying to contribute, then maybe the group is not for you. There are plenty of other fish in the sea. 

In GitHub or Gitlab, contribution typically starts by forking own personal copy of the original repository, then taking that fork and cloning it locally to your own machine ... and playing with a bit, and pushing one or more commits back to that personal fork BUT BY THEN YOUR FORK IS NOT EQUAL TO THE ORIGINAL FORK IN THE ORIGINAL REPOSITORY.  To be successful with this approach, your really have to WORK AT STAYING IN SYCNCH, really understanding the CURRENT mindset of the people who are developing the code today FROM THEIR POINT OF VIEW ... you have to SYNCH YOUR MIND to the community's mind ... once your little improvement to the code seems ready to merge, you can ask the service to create a pull request in GitHub or a merge request in GitLab for your branch into the original repository. The request will be reviewed, and since it's difficult to stay in synch, there will need to be lots of back-and-forth to make really sure all of the people are on the same page ... if everything appears to be in synch and if accepted your changes get merged into the original repository, then the real fun starts. 

In contrast to Github or Gitlab, OpenDev is a collaboratory for open source software development at scale. Its focus is more heavily on on the code review side ... it's more about larger team continuous **integration** ... not just integration of the code or git data, but INTEGRATION of the minds working on the project. The project hosting for OpenDev projects will provided exclusively through open source solutions like Git, Gerrit, Zuul, and Gitea. OpenDev also provides a number of peripheral collaboration services most notably the [Mailman GNU mailing list manager](https://list.org/). OpenDev doesn't use a pull request (or merge request) workflow, like those implemented by GitHub or Gitlab. Instead it follows Gerrit's iterative change proposal workflow, which results in a slightly different experience, since contribution with Gerrit starts by cloning the original repository locally and then always working together on the a similar clone of the same ORIGINAL reference repository, rather than a forking and work on forks. 

It cannot be emphasized enough that the whole development process is usually centered around the [issue-driven pull request in GitHub](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) or [issue-driven merge request creation in Gitlab](https://docs.gitlab.com/ee/user/project/merge_requests/) ... and your best chance of making contribution and earning some cred is to really, Really, REALLY understand the issues in issue tracker and the pull/merge request process and, ideally, to WORK ON SOMEBODY ELSE'S ISSUE.

# Before you submit your first issue

**Really, really, REALLY search the issue tracker for similar entries*** ... maybe under a different title or with different wording. Someone else might have already had the same bug or feature proposal. If you find an existing issue that is tied to the bug you've found or feature that you're proposing, show your support with a simple emoji *emotional* reaction for how you feel about the issue ... then, if needed, add your specific **technical** notes/comments/concerns/suggestions/questions to the issue discussion.


If not, ***which might be more likely for your early contributions*** since you're still figuring out how or why things were done, you push more commits to your fork and update the request seeking more reviews ... there's nothing wrong with just working on your own fork and using it as a way to really learn the code base and the community's mindset IN A WAY THAT DOESN'T BOTHER ANYONE ... but if you want to get your changes merged into the original repository, you'll need to get the community to review your changes and to agree with your thinking and accept it.  Do not underestimate how difficult and HUMBLING this can be ... it's not just about the code, it's about the people and the essence of what it means to really BELONG inside a development community.

