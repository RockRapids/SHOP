---
title: CI/CD and Git Reading List
subtitle: Mastering the distributed version control systems
date: 2021-07-14
tags: ["time management"]
---


An open source discipline is about understanding, using and contributing to a git-centric continuous integration, continuous development, continuous deployment open source workflow workflow. Ultimately, this discipline involves contributing to the development communities that build the tools used in the workflow ... one of the first, most fundamental building blocks of this workflow is Git.

## START with the [ProGit manual](https://git-scm.com/book/en/v2)

### Getting Started
#### About Version Control
As a precursor, understand the essentials of [software configuration managment](https://en.wikipedia.org/wiki/Software_configuration_management) and why the [evolution of version control systems](https://en.wikipedia.org/wiki/Comparison_of_version-control_software#History_and_adoption) evolved as it dd. Two decades ago, it was already abundantly clear that old centralized version control systems like [CVS](https://en.wikipedia.org/wiki/Concurrent_Versions_System) or even the newer open source approaches like [Apache [Collabnet] Subversion](https://en.wikipedia.org/wiki/Apache_Subversion) were going to be too fragile or dependent upon a central server and that [**DISTRIBUTED** version control systems (DVCSs)](https://stackoverflow.com/questions/tagged/dvcs) were going to absolutely REQUIRED for geographically distributed, highly decentralized developers working on free open source software in non-proprietary free open source development teams. 

In a DISTRIBUTED version control system, a client cannot just check out the latest snapshot of the files. Rather, it is necessary [for the sustainability of the project, for open source development communities to actually use a truly FREE open source development workflow] that a client fully mirrors the complete repository, including its full history. Thus, if any server dies, and these systems were collaborating via that server, any of the client repositories can be copied back up to the server to restore it. 

Every clone is really a full backup of ALL of the data ... in open source, ideally, 'all' really means ALL ... no copies of affiliated documents on someone's laptop or a message board ... that means all issues and feature requests, all requirements specifications, all design sprints, all experimentation, all test specifications, all functional requirments specifications, all CI/CD specifications and ALL discussions pertaining to these matters ... ALL repository data and all discussions about that data should be in Git ... if it matters, of it should be in Git and everyone involved should *over-communicate* [with cross-referencing, reviewing, annotating assigning appropriate parties] via Git ... keeping ALL data in one DISTRIBUTED repository [and focusing everyone's attention on that repository] is the basis of successful asynchronous communication for open source communities.

#### A Short History of Git

It was not just one killer feature, eg Git branching, but for a variety of reasons, [Git](https://en.wikipedia.org/wiki/Git) emerged as the defacto standard; that organic convergence or standardization itself is important. One should understand origins of Git and how it has been maintained, as well as the history of different [Git hosting services](https://git.wiki.kernel.org/index.php/GitHosting) [Github's history](https://en.wikipedia.org/wiki/GitHub), [Gitlab's history](https://en.wikipedia.org/wiki/GitLab) and why Gitlab's [continuous integration/development/deployment pipeline](https://docs.gitlab.com/ee/ci/introduction/index.html) is so repository-centric. The centricity of the repository and keeping information tied to the repository ushers in next phase of these community-driven and repository driven workflows are about the so-called "disposable" container-based integrated development environments such as [Gitpod](https://www.gitpod.io/docs/) or [Eclipse Theia](https://theia-ide.org/docs/) which are about shifting the focus from distributed isolation to cloud-based distributed collaboration. This would not be possible without Git or the standardization on Git. 

The different reasons for why free open source Git has such a dominant position in version control systems are not because there weren't other.notable DVCS predecessors including [BitKeeper](https://en.wikipedia.org/wiki/BitKeeper), [Mercurial](https://en.wikipedia.org/wiki/Mercurial), [GNU Bazaar](https://en.wikipedia.org/wiki/GNU_Bazaar) or [Darcs](https://en.wikipedia.org/wiki/Darcs). Since its birth in 2005, Git [continues to evolve](https://git.github.io/rev_news/archive/) but fully distributed Git has matured to be simple, easy to use, supports very large projects efficiently, has a [truly incredible "killer feature" branching system](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell#ch03-git-branching) for non-linear development with thousands of parallel branches and ... in spite of all these features and over [a decade and a half of released improvements](https://github.com/git/git/tree/master/Documentation/RelNotes), Git is still amazingly fast, still *a growing movement*.

#### What is Git?

The major difference between Git and any other version control systems is the way Git thinks about its data. **Other** systems think of the information they store as a set of files and the *changes* or *deltas* made to each file over time, ie a method which is commonly described as *delta-based version control*. Git is different and this important distinction between Git and nearly all other VCSs makes Git reconsider almost every aspect of version control that most other systems copied from the previous generation

Instead of the delta-based method, Git thinks of its data more like a series or stream of snapshots of a miniature filesystem. With Git, every time you commit, or save the state of your project, Git basically takes a picture of what all your files look like at that moment and stores a reference to that snapshot. ***To be efficient,*** if files have not changed, Git doesn’t store the file again, just a link to the previous identical file it has already stored ... this makes Git into an extremely efficient, fast file system and there are benefits which translate into direct gains in managing branching. 

1.4 The Command Line
1.5 Installing Git
1.6 First-Time Git Setup
1.7 Getting Help
1.8 Summary
1. Git Basics
2.1 Getting a Git Repository
2.2 Recording Changes to the Repository
2.3 Viewing the Commit History
2.4 Undoing Things
2.5 Working with Remotes
2.6 Tagging
2.7 Git Aliases
2.8 Summary
3. Git Branching
3.1 Branches in a Nutshell
3.2 Basic Branching and Merging
3.3 Branch Management
3.4 Branching Workflows
3.5 Remote Branches
3.6 Rebasing
3.7 Summary
4. Git on the Server
4.1 The Protocols
4.2 Getting Git on a Server
4.3 Generating Your SSH Public Key
4.4 Setting Up the Server
4.5 Git Daemon
4.6 Smart HTTP
4.7 GitWeb
4.8 GitLab
4.9 Third Party Hosted Options
4.10 Summary
5. Distributed Git
5.1 Distributed Workflows
5.2 Contributing to a Project
5.3 Maintaining a Project
5.4 Summary
6. GitHub
6.1 Account Setup and Configuration
6.2 Contributing to a Project
6.3 Maintaining a Project
6.4 Managing an organization
6.5 Scripting GitHub
6.6 Summary
7. Git Tools
7.1 Revision Selection
7.2 Interactive Staging
7.3 Stashing and Cleaning
7.4 Signing Your Work
7.5 Searching
7.6 Rewriting History
7.7 Reset Demystified
7.8 Advanced Merging
7.9 Rerere
7.10 Debugging with Git
7.11 Submodules
7.12 Bundling
7.13 Replace
7.14 Credential Storage
7.15 Summary
8. Customizing Git
8.1 Git Configuration
8.2 Git Attributes
8.3 Git Hooks
8.4 An Example Git-Enforced Policy
8.5 Summary
9. Git and Other Systems
9.1 Git as a Client
9.2 Migrating to Git
9.3 Summary
10. Git Internals
10.1 Plumbing and Porcelain
10.2 Git Objects
10.3 Git References
10.4 Packfiles
10.5 The Refspec
10.6 Transfer Protocols
10.7 Maintenance and Data Recovery
10.8 Environment Variables
10.9 Summary
A1. Appendix A: Git in Other Environments
A1.1 Graphical Interfaces
A1.2 Git in Visual Studio
A1.3 Git in Visual Studio Code
A1.4 Git in IntelliJ / PyCharm / WebStorm / PhpStorm / RubyMine
A1.5 Git in Sublime Text
A1.6 Git in Bash
A1.7 Git in Zsh
A1.8 Git in PowerShell
A1.9 Summary
A2. Appendix B: Embedding Git in your Applications
A2.1 Command-line Git
A2.2 Libgit2
A2.3 JGit
A2.4 go-git
A2.5 Dulwich
A3. Appendix C: Git Commands
A3.1 Setup and Config
A3.2 Getting and Creating Projects
A3.3 Basic Snapshotting
A3.4 Branching and Merging
A3.5 Sharing and Updating Projects
A3.6 Inspection and Comparison
A3.7 Debugging
A3.8 Patching
A3.9 Email
A3.10 External Systems
A3.11 Administration
A3.12 Plumbing Commands
